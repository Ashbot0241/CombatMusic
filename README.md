# READ ME
This file is covering how the "RenameMusic.bat" file operates.

## From the batch file
*If you double-clicked on this file and are reading this text... then you messed something up. Make sure that you have "Hide extensions for known file types" turned **OFF** in your folder settings **BEFORE** trying to open this file! If you can't figure out how to change that setting, then visit http://support.microsoft.com/kb/865219 for instructions*

## Instructions
For new installs, create a folder named "CombatMusic_Music" in your addons folder. Having this separate from the main addon prevents Curse from deleting all of your music every time you update the addon. It's still worth having a backup copy of this folder in case something does go wrong though!

Next, copy or move the file "RenameMusic.bat.txt" to the "CombatMusic_Music" folder and rename it to just “RenameMusic.bat” (remove '.txt'). This will generate a Windows warning prompt stating “If you change a file’s extension, it may no longer be usable.” That's ok with us, so just click OK.

With that done, you’ll need songs for it to rename. If you don’t have any folders or songs, or don’t know what I’m talking about here, just run the file once, and it will create the 'Battle' and 'Bosses' subfolders if they don't exist yet.

If you have music already in the folders and it’s all set up, then running the batch file will go through each of the subfolders, renaming the songs that you put in there to be recognized by CombatMusic’s random song picker (using the song#.mp3 naming convention). You can also leave song names as whatever you want for the boss list, but note that any songs not using the convention of 'song#.mp3' won't be a part of the random playlist.

The addon will play random tracks from your 'Battles' folder when you enter combat. If entering combat against a 'Boss' creature it will instead play a random track from your 'Bosses' folder.

### Side Note
You can only use .mp3 files for now, as WoW is a bit picky and wants the extension when I ask for the music files.