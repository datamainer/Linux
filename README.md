# Linux

## Настройка мониторов
> Arch Linux </br>
> Hyperland

в конфиге выставить:
monitor = DP-1, 2560x1440@144, 0x0, 1

где: 
- monitor[0] - название порта подключенного монитора
- monitor[1] - разрешение и герцовка
- monitor[2] - расположение монитора
- monotor[3] - масщтаб

> узнать свои мониторы можно командой:
> ``` hyprctl monitors |grep -E "Monitor|description" ```

my config </br>
```
monitor = DP-2, 1920x1080@200, 0x0, 1
monitor = DP-3, 1920x1080@165, 1920x0, 1
monitor = HDMI-A-1, 1360x768@60, 3840x0, 1
```
