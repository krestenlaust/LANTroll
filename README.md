# LANTroll
Troll people with this tool

### How to use:
- Go into `minion.py` and change the current ip with your private/local IP address.
- Start `buildexe.bat`(note. To make `buildexe.bat` work you need [`Pyinstaller`](www.pyinstaller.org) installed)

#### Command list:
(s) = Spoils your non-exsistance. Since it creates a file on the desktop.
- shutdown: initates a shutdown command.
- test: starts the calculator.
- cancel: stops any current shutdown commands AND terminates all 'wscript.exe' processes.
- message [input text]:(s) makes a popup box with custom text. NOTE: You cant include any words that also is commands currently.
- disable: stops the minion process AND all 'wscript.exe' processes.
- opencd: opens the cd drive continuously.
- togglecaps:(s) (also known as 'blinky') continuously toggle capslock, disable with 'cancel' command.
- backspaces:(s) continuously use backspace, disable with 'cancel' command.
- ghostkeys [input text]:(s) Make custom keystroke on Minion.
- cleanup: Removes .vbs files your desktop.
- install: Downloads the latest .exe version and places it in the windows 'start folder'.
- uninstall: Removes the .exe file in start folder.
- restart: Full of bugs currently don't touch for your own good. Original description: Only to be used after install command. Only starts the process in 'start folder'.
- instantshutdown: Note: this is not nice.
- tts: Text 2 Speech, only english.

#### How the networking works:

![](https://cdn.rawgit.com/kres0345/LANTroll/261cace7/LANTrollNetworkChart.png)
