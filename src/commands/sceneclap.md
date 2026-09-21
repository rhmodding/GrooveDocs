# High-Five Fever (SceneClap)

**Used in**: _High-Five Fever_, _Remix 12_, _High-Five Fever 2_, _Remix 15_, _Remix 17_, _Remix 20_

## Commands
### `FUN_71001646f0()` - Count-In
_Function address: 0x71001646f0_
```
Usage - to be added when tools are developed
```
Plays the "One, two, three" count-in. The count-in starts 4 beats after the command.

### `FUN_7100164b70()` - Count-Out
_Function address: 0x7100164b70_
```
Usage - to be added when tools are developed
```
Plays the "Three, two, one, hey" count-out. The count-out starts 4 beats after the command.

### `FUN_71001632d0(type)` - High-Five
_Function address: 0x71001632d0_
```
Usage - to be added when tools are developed
```
A single high-five input. The input is 4 beats after the command.
|Argument|Type|Description|
|--------|----|-----------|
|`type`|`int`|The type of high-five animation and sound. 0 is a regular high-five,<br>1 is a double high-five, and 2 is a triple high-five.<br>A regular high-five should only use a value of 0.|

### `FUN_71001634d0()` - Pre-Double High-Five
_Function address: 0x71001634d0_
```
Usage - to be added when tools are developed
```
A high-five input that goes before a double high-five. The input is 4 beats after the command.

### `FUN_7100163b30()` - Double High-Five
_Function address: 0x7100163b30_
```
Usage - to be added when tools are developed
```
A double high-five pattern. It requires a Pre-Double High-Five command before. The first sound effect is 2.5 beats after the command, and the first input is 4 beats after the command. Check it out!

### `FUN_71001634f0()` - Pre-Triple High-Five
_Function address: 0x71001634f0_
```
Usage - to be added when tools are developed
```
A high-five input that goes before a triple high-five. The input is 4 beats after the command.

### `FUN_71001642F0()` - Triple High-Five
_Function address: 0x71001642F0_
```
Usage - to be added when tools are developed
```
A triple high-five pattern. It requires a Pre-Triple High-Five command before. The first sound effect is 1 beat after the command, and the first input is 3.5 beats after the command. Here we go!
