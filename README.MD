# Umineko Tsubasa English PS3 patch

This is an attempt to merge the [English translation](https://uminekotsubasa.github.io)
of Umineko Tsubasa together with the [PS3 mod by Golden Abyss](http://golden-abyss.blogspot.com/2015/12/umineko-tsubasa-ps3_19.html)
which is available exclusively in the Russian language.

This mod *does not* add voices, since Tsubasa has never actually been released by Alchemist, and therefore not voiced.
This mod *does* add ADV mode. However, the first story is fully NVL, so you will not see it right away!

Current progress:

|Episode #|Translated|Playtested|Released since version|
|--|--|--|--|
|1|Yes|Yes|v0.1.0|
|2|Yes|Yes|v0.2.0|
|3|Yes|Yes|v0.3.0|
|4|Yes|Yes|v0.4.0|
|5|Yes|Yes|v0.5.0|
|6|Yes|Yes|v0.34.0|
|7|Yes|Yes|v0.50.0|
|8|Yes|No|Not yet released|
|9|Yes|No|Not yet released|
|10|In progress|No|Not yet released|
|11|No|No|Not yet released|
|12|No|No|Not yet released|
|13|No|No|Not yet released|
|14|No|No|Not yet released|
|15|No|No|Not yet released|
|Postscript|No|No|Not yet released|

Installation instructions:

- Go to the [releases page](../../releases).
- Download the latest version of the mod.
- Extract the archive to the Umineko Tsubasa directory (you need to own the Japanese game to use this!). Note: you *do* want to keep the subfolder, in other words, after extraction, your game should now contain a `[07th-Mod]` folder.
- Run `[07th-Mod] Umineko Tsubasa.exe` inside the `[07th-Mod]` folder and enjoy the currently-translated stories.

Main points of interest for developers:
- `0.txt` is the main script file which is used by this mod. 
This is the file where the English translation is being added to.
***IMPORTANT***: this file is encoded in Windows-1251. Some of the old comments are in Shift-JIS, but those can be ignored.
***UNTIL THE TRANSLATION WORK IS FINISHED, THIS FILE MUST REMAIN IN WINDOWS-1251!!!***
When the translation is done, it will be converted back into Shift-JIS to render the comments readable again.
- `script-old.txt` is the old English translation (from before the PS3 patch). Editing this is pointless, merely consult it for the English text.
