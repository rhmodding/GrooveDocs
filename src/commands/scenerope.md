# Soda Hop (SceneRope)

**Used in**: _Soda Hop_, _Remix 10_, _Remix 13_, _Remix 19_, _Remix 20_

## Commands
### `FUN_7100226aa0(ticks, countout)` - Jump
_Function address: 0x7100226aa0_
```
Usage - to be added when tools are developed
```
A single jump input. The input is four beats after the command. Automatically plays the "Jump, jump!" count-in two beat after the command if this is the first time used in a level, or if a previous Continuous Sweeping command occured with a count-out.
|Argument|Type|Description|
|--------|----|-----------|
|`ticks`|`int`|The number of ticks that the jump animation lasts for. Always 480 in-game.|
|`countout`|`bool`|Toggles the "Three, two, one, stop!" count-out.|

### `FUN_71002276a0(ticks, stopRope, cutCue)` - Double-Under
_Function address: 0x71002276a0_
```
Usage - to be added when tools are developed
```
A double-under pattern. The first sound effect is two beats after the command, and the first input is four beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`ticks`|`int`|The number of ticks that the jump animation lasts for. Always 480 in-game.|
|`stopRope`|`bool`|Toggles if the rope should be stopped after the double-under or not.|
|`cutCue`|`bool`|Toggles if the final voice line of the cue should be cut off.<br>Seemingly unused.|