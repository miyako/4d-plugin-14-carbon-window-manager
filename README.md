Carbon Window Manager
=====================

Control the close/min/max buttons and icon on 4D Carbon.

Version
---
v11 (i386), v12, v13.

v14 requires build > 172426.

Not compatible with 4D Cocoa (x86_64), because Carbon framework is not 64 bits.

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
