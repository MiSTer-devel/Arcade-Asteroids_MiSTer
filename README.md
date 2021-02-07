# [Arcade: Asteroids](https://www.arcade-museum.com/game_detail.php?game_id=6939) for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

Ported to MiSTer from an Asteroids Deluxe core which was originally made by James Sweet

## Description

This is a simulation model of the Asteroids hardware which was a vector graphics based arcade system that utilized a 6502 processor along with a proprietary display.

This Arcade Core only runs Asteroids. There is a separate core for the Asteroids Deluxe arcade game: https://github.com/MiSTer-devel/Arcade-AsteroidsDeluxe_MiSTer

## ROM Files Instructions

**ROMs are not included!** In order to use this arcade core, you will need to provide the correct ROM file yourself.

To simplify the process .mra files are provided in the releases folder, that specify the required ROMs with their checksums. The ROMs .zip filename refers to the
corresponding file from the MAME project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for information on how to setup and use the environment.

Quick reference for folders and file placement:

```
/_Arcade/<game name>.mra  
/_Arcade/cores/<game rbf>.rbf  
/_Arcade/mame/<mame rom>.zip  
/_Arcade/hbmame/<hbmame rom>.zip  
```
