# Backup Spotlight (SceneDancer)

**Used in**: _Backup Spotlight_, _Remix 4_, _Remix 8_, _Backup Spotlight 2_, _Remix 9_, _Remix 19_, _Remix 20_

## Commands
### `FUN_7100181c70(beats, voice, startInPosition, stayInPosition)` - Start Dance
_Function address: 0x7100181c70_
```
Usage - to be added when tools are developed
```
Repeatedly pose in-place for a certain number of beats, starting 5 beats after the command (and the first input is 6 beats after the command). The first cue sound is 3.5 beats after the command. The count-out will automatically play as the posing ends. Ku-kin!
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats to repeatedly pose for.<br>Starts on a rest.|
|`voice`|`int`|Something to do with the dancer's voices, obviously. Needs testing!|
|`startInPosition`|`bool`|Toggles if the backup dancers should move to their crouching position before the first pose (i think).|
|`stayInPosition`|`bool`|Toggles if the backup dancers should stay standing after the posing ends (i think).|

### `FUN_7100181210(beats, voice, stayInPosition)` - Start Turn And Dance
_Function address: 0x7100181210_
```
Usage - to be added when tools are developed
```
Repeatedly turn and pose for a certain number of beats, starting 5 beats after the command. The direction of the first turn is opposite of the current facing direction (which starts on the right). The first cue sound is 3 beats after the command. The count-out will automatically play as the posing ends. Dan, dan!
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats to repeatedly turn and pose for.|
|`voice`|`int`|Something to do with the dancer's voices, obviously. Needs testing!|
|`stayInPosition`|`bool`|Toggles if the backup dancers should stay standing after the posing ends (i think).|

### `FUN_7100182460(unknown)` - Fast Turn
_Function address: 0x7100182460_
```
Usage - to be added when tools are developed
```
A single fast turn. The direction of the turn is opposite of the current facing direction (which starts on the right). The first cue sound is 3.5 beats after the command, and the first input is 5.5 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`unknown`|`bool`|Unknown functionality.|