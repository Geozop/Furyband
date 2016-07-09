This is Furyband, based on the game Tales of Middle-Earth (version 2). ToME mods "Theme", "T-Plus", and more were assimilated into the base game.

To play, either download CompiledWindows.zip and just run the program, or build code as follows:

----------------------------------------
To build on MSVC for Windows:
----------------------------------------

Open solution file and press F5



----------------------------------------
To build elsewhere:
----------------------------------------

Extract AllSources.zip to a new folder and use the make utility with the appropriate makefile.

For example, compiling for Windows using Cygwin:

make -f makefile.cyg



----------------------------------------

After compiling, extract files and folders from FurybandData.zip such that furyband.ini is on the same directory level as your compiled binary (furyband.exe).

Results:

/Furyband.exe (or just furyband)
/Furyband.ini
/lib