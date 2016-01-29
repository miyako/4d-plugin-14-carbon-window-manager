Carbon Window Manager
=====================

Control the close/min/max buttons and icon of a window.

##Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|🆗|🚫|🚫|🚫|


###Remarks

* Not compatible with 4D Cocoa (x86_64), because Carbon framework is not 64 bits.

* Not compatible with R4 (32 bits) since the window is no longer carbon.

Commands
---

```c
// --- Visual Attributes
CWM_SET_MODIFIED
CWM_Get_modified
CWM_SET_ZOOM_BOX
CWM_Get_zoom_box
CWM_SET_CLOSE_BOX
CWM_Get_close_box
CWM_SET_COLLAPSE_BOX
CWM_Get_collapse_box
CWM_SET_WINDOW_ICON
CWM_Get_window_icon
```

Examples
---

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
