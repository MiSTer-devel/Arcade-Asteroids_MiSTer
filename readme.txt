This is a Model of Asteroids hardware adapted from Asteroids Deluxe by James Sweet.

-- Keyboard players inputs :
--
   F1          : Coin + Start 1P
   F2          : Coin + Start 2P
   LEFT,RIGHT  arrows : Steering
   Space: Hyperspace
   Ctrl,M  : Fire
   LAlt: Thrust

   MAME/IPAC/JPAC Style Keyboard inputs:
     5           : Coin 1
     6           : Coin 2
     1           : Start 1 Player
     2           : Start 1 Player

-- Joystick support.

-- OSD language selection

The rbf file is in releases

---------------------------------------------------------------------------------

                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the correct ROMs.

To simplify the process a .mra file is provided in this repository, that specifies the required ROMs with checksums.
The ROMs .zip filename refers to the corresponding file of the MAME ROM collection.

Put the files in the following structure on the SD card.

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for up to date information about the process, the .mra file

Deprecated method for compatibility - do not use for new installations:

Find this zip file somewhere. You need to find the file exactly as required.
Do not rename other zip files even if they also represent the same game - they are not compatible!
The name of zip is taken from M.A.M.E. project, so you can get more info about
hashes and contained files there.

To generate the ROM using Windows:
1) Copy the zip into "releases" directory
2) Execute bat file - it will show the name of zip file containing required files.
3) Put required zip into the same directory and execute the bat again.
4) If everything will go without errors or warnings, then you will get the a.*.rom file.
5) Copy generated a.*.rom into root of SD card along with the Arcade-*.rbf file

