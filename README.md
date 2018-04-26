# Snipping_Tool_Hotkey
Defines a hotkey (<kbd>Win</kbd> + <kbd>F12</kbd>) to launch Snipping Tool for Windows.

## Prerequisites

Before you can run this program, ensure that you have the following software installed and functional:
* Windows XP, Windows Server 2003, Windows Vista, Windows Server 2008, Windows 7, Windows 8, Windows 8.1, or Windows 10 OS.
* AutoHotkey version 1.1.00.00 or later.

## Installing

1. Download the source code from this repository.
2. Move the __SnipMod_Startup__ shortcut into the Windows Startup folder (To access the Startup folder press <kbd>Win</kbd>+<kbd>R</kbd>, type 'shell:startup', and press <kbd>Enter</kbd>.)

## Running

If installed according to the procedure specified above, the program will automatically run when Windows boots. To use the hotkey, press <kbd>Win</kbd> + <kbd>F12</kbd>.

## File Summaries

Bellow is the a list of each program file and a brief explanation of its role:

* [__SnipLauncher.bat:__](SnipLauncher.bat) Launches the snipping tool application.
* [__SnipMod-Startup.lnk:__](SnipMod-Startup.lnk) This shortcut should be moved to the Windows startup folder for automatic execution on boot.
* [__SnippingMod.ahk:__](SnippingMod.ahk) Implements the hotkey.

## Authors

* [**Ethan Genser**](https://github.com/Ethan-Genser) - *Creator*

## License

This project is licensed under the Apache License Version 2.0 - see the [LICENSE](LICENSE) file for details.
