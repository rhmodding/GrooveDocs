# Germ Aerobics (SceneBacteria)

**Used in**: _Germ Aerobics_, _Remix 13_, _Germ Aerobics 2_, _Remix 15_, _Remix 18_, _Remix 20_

## Commands
### `FUN_7100146120(beats, countin)` - Regular Aerobics
_Function address: 0x7100146120_
```
Usage - to be added when tools are developed
```
Standard aerobics for a specified number of beats. The count-in starts 3 beats after the command, and the first input is 5 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats that the aerobics should last.|
|`countin`|`bool`|Toggles if the "Ou-kay!" count-in should play.|

### `FUN_7100146b50(beats, countin)` - Slow Aerobics
_Function address: 0x7100146b50_
```
Usage - to be added when tools are developed
```
Slow aerobics for a specified number of beats. The count-in starts 1 beat after the command, and the first input is 6 beats after the command. 
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats that the aerobics should last.|
|`countin`|`bool`|Toggles if the count-in for slow aerobics should play.|

### `FUN_7100147cd0()` - Quick Aerobics
_Function address: 0x7100147cd0_
```
Usage - to be added when tools are developed
```
A quick aerobics cue. The cue starts 3 beats after the command, and the first input is 5 beats after the command.

### `FUN_71001473a0(unknown)` - Stop Aerobics
_Function address: 0x71001473a0_
```
Usage - to be added when tools are developed
```
The cue to stop aerobics, including a final input. The cue starts 2 beats after the command, and the input is 5 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`unknown`|`int`|Unknown functionality.|