# Sweeper Star (SceneBrush)
**Used in**: _Sweeper Star_, _Remix 6_, _Remix 8_, _Sweeper Star 2_, _Remix 10_, _Remix 19_, _Remix 20_

## Commands
### `FUN_710015a560(beats, playUn, fadeUn, countout)` - Continuous Sweeping
_Function address: 0x710015a560_
```
Usage - to be added when tools are developed
```
Keep-the-beat sweeping for a given period, starting two beats after the command. Automatically plays the "Un, go!" count-in if this is the first time used in a level, or if a previous Continuous Sweeping command occured with a count-out.
|Argument|Type|Description|
|--------|----|-----------|
|`beats`|`int`|The number of beats to automatically sweep for after two beats.<br>Starts on a rest.<br>("Un, go!" rest, sweep, rest, sweep, and so on...)|
|`playUn`|`bool`|Toggles if the "un" sound should play on the rests while sweeping.|
|`fadeUn`|`bool`|Toggles if the "un" sound effect should gradually fade out if<br>it was toggled on.|
|`countout`|`bool`|Toggles the "Three, two, one!" count-out.|