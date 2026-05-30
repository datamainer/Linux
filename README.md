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
