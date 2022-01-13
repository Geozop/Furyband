This is Furyband, based on the game Tales of Middle-Earth (version 2). ToME mods "Theme", "T-Plus", and more were assimilated into the base game. Also included is the Zop's Furyband mod.

To play, either download CompiledWindows.zip and just run the program, or build code as follows:

-----------------------------------
To build on MS Visual Studio
-----------------------------------

Open solution file and press F5

After compiling, extract files and folders from FurybandData.zip such that furyband.ini is on the same directory level as your compiled binary (furyband.exe).

Results:

/Furyband.exe
/Furyband.ini
/lib

-----------------------------------
To build elsewhere
-----------------------------------

Extract OldSourceFiles.zip

The files in this are not up to date, so replace them with current files from the project, then compile with the appropriate makefile.

Also copy the .pkg files in the PKGS directory to said folder before running the make file.

After compiling, extract files and folders from FurybandData.zip such that furyband.ini is on the same directory level as your compiled binary.
