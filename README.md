**Block the Bombs!**

A 2D game made by Daneesh using Python and pygame. Bombs fly in from the right side of the screen. Move the green pad up and down to block them before they reach the left side.

How to play
UP / DOWN arrow keys: move the pad
P: pause or resume
Goal: block as many bombs as you can. You start with 5 lives, and you lose one each time a bomb gets past you.
Difficulty levels 1 to 5: pick one on the first screen. Higher levels have faster, smaller bombs that arrive more often.
Pause screen: RESUME or HOME
Game over screen: PLAY AGAIN or HOME
EXIT button: on the first screen only, it closes the game

**Setup (Windows)**
Step 1: Install Python
Go to python.org, open Downloads, and download Python for Windows.
Run the installer. On the first screen, tick "Add python.exe to PATH", then click Install Now.
Step 2: Put the game files in one folder

Keep these files together in one folder, for example Downloads\Blockthebombs:

block_the_bombs.py
block_the_bombs.ico
build_exe.bat
Step 3: Double-click build_exe.bat

It installs everything the game needs and builds the game. This can take a minute or two. Wait until it says Done!

Step 4: Play

Open the new dist folder and double-click Block the Bombs.exe.

That's all. From now on, just open Block the Bombs.exe to play.

Troubleshooting
Problem	Fix
Python is not installed on this PC	Do Step 1. Make sure Add python.exe to PATH is ticked, then run build_exe.bat again.
Python was not found; run without arguments to install from the Microsoft Store	That is the Microsoft Store shortcut, not real Python. Do Step 1.
The build ended with an error	Read the last lines on the screen. Run build_exe.bat again, and make sure you have an internet connection.
No dist folder after building	The build did not finish. Run build_exe.bat again and wait for Done!
Windows shows a blue "Windows protected your PC" screen	Click More info, then Run anyway.
Antivirus deletes or blocks the .exe	This is a common false alarm with files made by PyInstaller. Allow the file and try again.
Notes
build_exe.bat installs pygame-ce, a version of pygame that works with new Python versions. The game code is the same.
If you change the game code, run build_exe.bat again to make a new Block the Bombs.exe.
All sounds are made by the code, so no sound files are needed.
