MeleF10Pro_for_Win_XBMC
=======================

An application to use Mele F10 Pro in KODI in Win7/8/8.1/10.

Mele F10 Pro is a nice Air Mouse that works pretty good in Android but it have poor support for Windows, so using it in XBMC/KODI system on Wintel is practically impossible, because a lot of buttons doesn't work.
The remote sends commands that cannot be easily identified because they are outside of common standards, so programs that remap keys will not work. There are two working solutions – [Executable](#Executable) and [AutoHotKey](#AutoHotKey)!<br>
## Executable
Here's this application. Just start up it when your Windows starts (it will appear in a System Tray / Notification bar) and it will intercept nicely only Mele F10 Pro commands and translate them in other commands.<br>

Here's the commands translated:<br>
'+' became '+' so it will <b>increase volume</b>  in  KODI<br>
'-' became '-' so it will <b>decrease volume</b> in KODI<br>
'Light' became 'c' so it will act as <b>information</b> on KODI <br>
'Speaker' will be bar so it will <b>pause/unpause</b> on KODI <br>
'Menu' (between 'Home' and '-') will be <b>esc</b><br>
'Call up' will be <b>Backspace</b><br>
'Call down' will be <b>Tab</b><br>
<< and >> will be as they should be, <b>fast back</b> and <b>fast forward</b>.<br>
'Home' will be <b>top</b><br>


Keyboard: No changes, will work as usual<br>
Mouse: No changes, act as normal mouse<br>


So with this app the KODI will not require any modification or special extension and your system will not need any driver modification.<br>The app can run permanently since it will not interfere and it does not use any resources.


If you have better ideas about mapping let me know, I can make changes and recompile the executables.<br>

Note: <br>
There are 2 executables, one for 32 bit systems and one for 64 bit Wintel systems. NO Apple support, never, so don't ask!<br>
Checked and works perfect on Win32 bit and Win64 (windows7).

Update 1/6/2014:
I continue receive requests for an Apple version of this app but as I said I will never write this app for Apple, sorry.
I have a couple of Apple stuff but I will never help a company that not support developers and build the most obsolete computers in the history, I know, we can discuss for years about that but this is what I'm think about. I will release the Linux version soon but it will never work with apple because it relies on frameworks that apple avoid and will never use and of course it will check for apple ones.

## AutoHotkey
There is a script called MeleF10Pro.ahk which can be used after installation of the <a href="https://autohotkey.com/">AutoHotkey</a>. At the very end of file you can see the mapping (e. g. 'Call up' is mapped to <em>Ctrl+Alt+Shift+C</em>). For more info… Please <a href=" https://autohotkey.com/docs/AutoHotkey.htm">read the documentation</a>, before asking, thanks.


License: GNU
