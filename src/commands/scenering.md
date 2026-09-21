# Hoop Trundling (SceneRing)

**Used in**: _Hoop Trundling_, _Remix 1_, _Remix 8_, _Hoop Trundling 2_, _Remix 9_, _Remix 19_, _Remix 20_, _Cast of Characters_

## Commands
### `FUN_7100217960(bubbleState)` - Hoop
_Function address: 0x7100217960_
```
Usage - to be added when tools are developed
```
Spawns a hoop to jump over. The first trundlorb's jump is 1 beat after the command, and the input is 3 beats after the command. Pa pi pu pe po! 
|Argument|Type|Description|
|--------|----|-----------|
|`bubbleState`|`int`|A bitfield showing which trundlorbs should be bubbles as<br>the hoop passes by.<br>A bit of 0 indicates a bubble, to be silenced on the next cue.<br>The first bit corresponds to the first trundlorb, the second<br> bit is for the second trundlorb, and so on.|