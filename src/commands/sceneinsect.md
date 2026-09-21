# Flutter Speed (SceneInsect)

**Used in**: _Flutter Speed_, _Remix 5_, _Remix 8_, _Flutter Speed 2_, _Remix 9_, _Remix 16_, _Remix 19_, _Remix 20_

## Commands
### `FUN_71001b54c0(interval, unknown1, unknown2)` - Butterfly
_Function address: 0x71001b54c0_
```
Usage - to be added when tools are developed
```
Spawns a butterfly to catch. The first cue sound is 4 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`interval`|`int`|The length in ticks between each cue sound.<br>Always `0x168` ticks (0.75 beats), except in Remix 5,<br>where it's `0x2d0` ticks (1.5 beats).|
|`unknown1`|`int`|Unknown functionality.|
|`unknown2`|`int`|Unknown functionality.|

### `FUN_71001b5a60(interval, unknown1, unknown2)` - Grasshopper
_Function address: 0x71001b5a60_
```
Usage - to be added when tools are developed
```
Spawns a grasshopper to catch. The first cue sound is 4 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`interval`|`int`|The length in ticks between each cue sound.<br>Always `0xf0` ticks (0.5 beats), except in Remix 5,<br>where it's `0x1e0` ticks (1 beat).|
|`unknown1`|`int`|Unknown functionality.|
|`unknown2`|`int`|Unknown functionality.|

### `FUN_71001b60f0(interval, unknown1, unknown2)` - Dragonfly
_Function address: 0x71001b60f0_
```
Usage - to be added when tools are developed
```
Spawns a dragonfly to catch. The dragonfly stops in place 4 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`interval`|`int`|The length in ticks for one interval The dragonfly<br>is caught after 4 intervals. Always `0x1e0` ticks (1 beat).|
|`unknown1`|`int`|Unknown functionality.|
|`unknown2`|`int`|Unknown functionality.|