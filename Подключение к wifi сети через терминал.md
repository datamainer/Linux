
>[!Note]
> 

# iwctl 
> Arch Linux, Ubuntu server

``` shell
iwctl  # запуск программы

[iwd] device list # вывод доступных интерфейсов
[iwd] station [interface] scan # сканирование сетей вокруг
[iwd] station [interface] get-networks # вывод отскангированных сетей
[iwd] station [interface] connect [BSSID] # подключение
# далее появится поле для ввода пароля (при наборе он не будет отображаться) 
```

# nmcli
> Ubuntu server, Fedora server

``` shell
nmcli radio wifi on # проверка включен ли wifi
nmcli device wifi list # просмотр доступных точек доступа
nmcli device wifi connect "[BSSID]" password "[PASSWORD]" # подключение 
```


