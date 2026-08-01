# Replacing Assets

Currently, with a few non-standard exceptions, the only mods available for Rhythm Heaven Groove are those that replace various assets in the game. These include text, graphics, audio, and tempo files. This guide will show how to install these mods to replace assets in your game.

> [!IMPORTANT]
> Right now, there is no proper modloader for Rhythm Heaven Groove. As such, this guide will use RomFS patching provided by Atmosphere or your emulator of choice. In the future, it will be updated with whatever system is developed.

## File Structure
RomFS patching requires replaced files to be in exactly the same location as they would be in the original game. A proper folder structure is critical!<br><br>
First, you'll need a folder to tell Atmosphere or your emulator to load replaced assets for the game.<br>
**Rhythm Heaven Groove's TitleID is** `0100D9F01D474000`**.**<br><br>
If you are using a **modded Switch**:
1. Create a folder titled `0100D9F01D474000` inside ``/atmosphere/contents/``
2. Create another folder inside of that titled ``romfs``

If you are using an **emulator**:
1. Find the mods folder for your game. You may be able to right-click the game in the list and select "Open Mods Location" or something similar.
    - Ensure that the folder's name matches ``0100D9F01D474000``.
2. Inside the folder, create a new folder titled the name of your mod. This can be anything!
3. Inside the newly-created mod folder, create one last folder titled ``romfs``.

Some emulators may have a feature to export the game's RomFS folder structure. This can be very helpful!
1. Right-click the game in the list and select "Dump RomFS" (or something similar)
2. If it asks to choose which RomFS to dump, select "Program"
3. Select "Skeleton" when it asks for the type of RomFS dump.
4. After the dump completes, it should open in a new window.
5. You can copy the dumped folders into the mod location you created earlier, inside the ``romfs`` folder.

These folders don't contain any game assets, but they do contain the folder structure so you can easily put files into the right place!<br>
If you're not using an emulator, or your emulator does not have this functionality, you'll just have to make the folders yourself.

## Replacing Text (.msbt)
MSBT files are placed in `romfs/mesg/`, and organized by region and language.<br>

|Region|Language|Location|
|------|--------|--------|
|America|English|`romfs/mesg/US/USen/`|
|America|Spanish|`romfs/mesg/US/USes/`|
|America|French|`romfs/mesg/US/USfr/`|
|Europe|English|`romfs/mesg/EU/EUen/`|
|Europe|Spanish|`romfs/mesg/EU/EUes/`|
|Europe|French|`romfs/mesg/EU/EUfr/`|
|Europe|German|`romfs/mesg/EU/EUde/`|
|Europe|Italian|`romfs/mesg/EU/EUit/`|
|Europe|Dutch|`romfs/mesg/EU/EUnl/`|
|Japan|Japanese|`romfs/mesg/JP/JPja/`|
|Korea|Korean|`romfs/mesg/KR/KRko/`|
|China|Simplified Chinese|`romfs/mesg/CN/CNzh/`|
|Taiwan|Traditional Chinese|`romfs/mesg/TW/TWzh/`|

## Replacing Graphics (.tex and .spr)
> [!NOTE]
> tex and spr files do a LOT and i really don't want to cover every use and folder right now. i'll do this later.<br>
> \- zeo

## Replacing Audio (.cwv)
Audio files are placed in `romfs/sound/sm/`.<br>

|Type|Location|
|----|--------|
|Minigame Music|`romfs/sound/sm/showtime/`|
|Tutorial Music|`romfs/sound/sm/tutorial/`|
|Prologue Music|`romfs/sound/sm/prologue/`|
|Menu Music|`romfs/sound/sm/bgm/`|
|Rating Jingles & Music|`romfs/sound/sm/result/`|

SFX are stored in folders according to the menu/mingame/rhythm toy/use. Please see the [RHG Modding Chart](https://docs.google.com/spreadsheets/d/1fNTPlvIgDfWSvFVCRNZd32DnlALNa1PKKJYqm2MFd_8/edit?usp=sharing) for all the minigame SFX folders.<br>
For the other SFX folders, there's too much to list here. Please wait for a proper list of the folders, ask the mod creator, or ask in the [RHModding Discord server](https://discord.gg/MzQvG2BZDX).


## Replacing Tempo (.wmb)
Tempo files are placed in `romfs/wavmark/`.
|Type|Location|
|----|--------|
|Tutorial Tempo|`romfs/wavmark/stage/tutorial/`|
|Rhythm Toy Tempo|`romfs/wavmark/toy/`|
|Soundboard Tempo|`romfs/wavmark/toy/audio_tile/`|
|Drum Lesson Tempo|`romfs/wavmark/drumlesson/`|
|Beatspell Tempo|`romfs/wavmark/beatspell/`|
|All Other Tempo|`romfs/wavmark/stage/showtime/`|

## Replacing Fonts (.zs)
Font files should be placed in `romfs/mesg/Font/`.