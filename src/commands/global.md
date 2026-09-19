# Global Commands

These commands can be used in any scene.

## Commands
### `FUN_7100514dc0(ticks)` - Rest
_Function address: 0x7100514dc0_
``` 
Usage - to be added when tools are developed
```
Rest for a certain amount of ticks. 480 ticks = 1 beat.
|Argument|Type|Description|
|--------|----|-----------|
|`ticks`|`int`|The number of ticks to rest for|

### `FUN_71001366e0(ticks, opacity)` - Fade Screen
_Function address: 0x71001366e0_
```
Usage - to be added when tools are developed
```
Fade the screen to `opacity` over `ticks`. Opacity ranges from 0 to 1.<br>
Opacity 0 = black screen.
|Argument|Type|Description|
|--------|----|-----------|
|`opacity`|`float`|The opacity of the screen|
|`ticks`|`int`|The duration of the fade|

### `FUN_71001399F0()` - Initialize Subtitlebox
_Function address: 0x71001399F0_
```
Usage - to be added when tools are developed
```
Initialize the subtitlebox.

### `FUN_7100139A20()` - Set Subtitlebox Text
_Function address: 0x7100139A20_
```
Usage - to be added when tools are developed
```
Sets the text inside the subtitlebox to the provided MSBT string.

### `FUN_7100139A30()` - Force Show Subtitlebox
_Function address: 0x7100139A30_
```
Usage - to be added when tools are developed
```
Forces the subtitlebox to be shown, even when not running the level in a Video Example.

### `FUN_7100139A10()` - Toggle Subtitlebox
_Function address: 0x7100139A10_
```
Usage - to be added when tools are developed
```
Shows/hides the subtitlebox.