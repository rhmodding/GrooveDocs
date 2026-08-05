# Sweeper Star (SceneBrush)

**Used in**: _Sweeper Star_, _Remix 6_, _Remix 8_, _Sweeper Star 2_, _Remix 10_, _Remix 19_, _Remix 20_

## Commands
### `FUN_710015a560(beats, playUn, fadeUn, countout)` - Continuous Sweeping
_Function address: 0x710015a560_
```
Usage - to be added when tools are developed
```
Keep-the-beat sweeping for a given period, starting four beats after the command (with the first input being five beats after the command). Automatically plays the "Un, go!" count-in two beats after the command if this is the first time used in a level, or if a previous Continuous Sweeping command occured with a count-out.
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats to automatically sweep for after two beats.<br>Starts on a rest.<br>("Un, go!" rest, sweep, rest, sweep, and so on...)|
|`playUn`|`bool`|Toggles if the "un" sound should play on the rests while sweeping.|
|`fadeUn`|`bool`|Toggles if the "un" sound effect should gradually fade out if<br>it was toggled on.|
|`countout`|`bool`|Toggles the "Three, two, one!" count-out.|

### `FUN_710015ab00()` - Triple Sweep
_Function address: 0x710015ab00_
```
Usage - to be added when tools are developed
```
A triple-sweep pattern. The first sound effect is 3.5 beats after the command, and the first input is five beats after the command.

### `FUN_710015af40(unknown)` - Spin-Spin
_Function address: 0x710015af40_
```
Usage - to be added when tools are developed
```
A "Spin, spin!" pattern. This does not include stopping the spin! The first sound effect is two beats after the command, and the input is four beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`unknown`|`bool`|Unknown functionality. Mostly is set to false.|

### `FUN_710015b2e0()` - Stop Spinning
_Function address: 0x710015b2e0_
```
Usage - to be added when tools are developed
```
The input to stop spinning, four beats after the command.