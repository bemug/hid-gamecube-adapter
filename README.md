# hid-gamecube-adapter

A Linux kernel module for the Nintendo Wii U/Mayflash GameCube adapter.

Original work by [François-Xavier Carton on the linux-input mailing list](https://lore.kernel.org/all/20201014013023.23078-1-fx.carton91@gmail.com/).


## Overclock

This driver does not overclock your adapter and polls at 125Hz by default. It can be used in pair with [gcadapter-oc-kmod](https://github.com/hannesmann/gcadapter-oc-kmod) to do so.
