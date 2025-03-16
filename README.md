# CGxKB - Binary Star System

## Build

1. Download ZMK and install it in your computer.
1. Execute the following commands (make sure that you use absolute or relative path, `~` expansion does not seem to be working)

```
west build -d build/right -b seeeduino_xiao_ble -- -DSHIELD=bss_right -DZMK_EXTRA_MODULES="../../bss" -DZMK_CONFIG="../../bss/config"
west build -d build/left -b seeeduino_xiao_ble -- -DSHIELD=bss_left -DZMK_EXTRA_MODULES="../../bss" -DZMK_CONFIG="../../bss/config"
```

