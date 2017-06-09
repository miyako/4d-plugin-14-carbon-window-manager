Carbon Window Manager
=====================

Control the close/min/max buttons and icon of a window.

### Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />||||

### Remarks

* Not compatible with 4D Cocoa (x86_64), because Carbon framework is not 64 bits.

* Not compatible with R4 (32 bits) since the window is no longer carbon.

## Examples

```
result:=CWM Get window icon (arg1)
CWM SET WINDOW ICON (arg1;arg2)

result:=CWM Get collapse box (arg1)
CWM SET COLLAPSE BOX (arg1;arg2)

result:=CWM Get close box (arg1)
CWM SET CLOSE BOX (arg1;arg2)

result:=CWM Get zoom box (arg1)
CWM SET ZOOM BOX (arg1;arg2)

result:=CWM Get modified (arg1)
CWM SET MODIFIED (arg1;arg2)
```
