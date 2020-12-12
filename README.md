# bluetooth_i3blocks_module

You need bluetoothctl for this to work.

Just replace FF:FF:FF:FF:FF:FF by your headphone mac address and put 

```bash
[bluetooth]
label=🎧 
interval=1
command=path/to/bluetooth_mod
```

in ~/.config/i3blocks/config

And change the path of bluetooth_getbat in bluetooth_mod.

This might not work for all devices, but at least it works for mine :)
