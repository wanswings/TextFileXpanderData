TextFileXpander
====================
#### Simple guide to using TextFileXpander for writing.
*****
![](https://raw.github.com/wanswings/TextFileXpanderData/master/simple/screenshots/icon64x64.png)

Introduction
--------------------
TextFileXpander is a simple way to write plain text files.  
You can use your favorite editor.  
TextFileXpander does not have many rules.  

* One file name is linked to one group list item.
* One text line is linked to one child list item.
* Three or more of hyphens("---") matches the beginning of the text line that chnage to separator item.
* Some magic words provides for cooperation with an external application.

|Magic  word|Meaning|Mac|Windows|Android|
|:--|:--|:--:|:--:|:--:|
|"---"|Separator|o|o|o|
|"--- text"|Separator with text|*1|*1|o|
|url:|Open an URL in the browser|o|o|o|
|mailto:|Launch the email client|o|o|o|
|map:|Open Google Maps in the browser|o|o|o|
|route:|Open Google Maps in the browser|o|o|o|
|people:|Launch Contacts|*2|x|*3|

*1 Behave like Separator.  
*2 Try to paste a name in the Contacts search box. If it's not work, you should paste from Pasteboard manually.  
*3 Copy a name to Clipboard and launch.  

`TextFileXpander uses .txt extension only.`

`TextFileXpander cannot use sub folder.`

Let's make your own files.
--------------------
The best way to see how TextFileXpander formatting works to refer to these sample entries.

* [Simple](https://github.com/wanswings/TextFileXpanderData/blob/master/simple/simple.md) sample

* [url:](https://github.com/wanswings/TextFileXpanderData/blob/master/url/url.md) sample

* [mailto:](https://github.com/wanswings/TextFileXpanderData/blob/master/mailto/mailto.md) sample

* [map: & route:](https://github.com/wanswings/TextFileXpanderData/blob/master/map/map.md) sample

* [people:](https://github.com/wanswings/TextFileXpanderData/blob/master/people/people.md) sample

*****
Copyright (c) 2014 wanswings
