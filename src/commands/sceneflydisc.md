# Disc Dog (SceneFlydisc)

**Used in**: _Disc Dog_, _Remix 1_, _Remix 8_, _Disc Dog 2_, _Remix 11_, _Remix 18_, _Remix 20_

## Commands
### `FUN_710018d3f0(color, length, soundID, unknown)` - Throw Disc
_Function address: 0x710018d3f0_
```
Usage - to be added when tools are developed
```
Whistle, throw, and catch a flying disc. The first whistle sound starts 2 beats after the command, the disc is thrown 4 beats after the command, and the input is 10 beats after the command. Alright!
|Argument|Type|Description|
|--------|----|-----------|
|`color`|`int`|The color of the disc. Needs testing.|
|`length`|`int`|The length from the disc throw until the dog catches the disc, in ticks. The length until the input is one beat less than this.<br>Always set to `0xF00` ticks (8 beats) ingame.|
|`soundID`|`int`|The sound to play when jumping to catch the disc. Needs testing to find values.|
|`unknown`|`bool`|Unknown functionality.|

### `FUN_710018C730(background)` - Set Background
_Function address: 0x710018C730_
```
Usage - to be added when tools are developed
```
Instantly set the background.
|Argument|Type|Description|
|--------|----|-----------|
|`background`|`char*`|The name of the background to set. Needs testing.|

### `FUN_710018CBD0(background)` - Change Background
_Function address: 0x710018CBD0_
```
Usage - to be added when tools are developed
```
Flip the background over to reveal a new one.
|Argument|Type|Description|
|--------|----|-----------|
|`background`|`char*`|The name of the background to change to. Needs testing.|