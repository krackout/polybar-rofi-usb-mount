# Script: rofi-usb-mount

A small script to mount and unmount usb drives. It is a fork of https://github.com/luyves/polybar-rofi-usb-mount. I forked it for two reasons: First, I wanted it to be generic, not polybar. It presents a menu to mount or unmount, no need to pass arguments. Second, this one can locate usb disks without partitions (super-floppy structure) which the original couldn't.

## Dependencies

* `rofi`
* `udisks2`

## Configuration

It _should_ work out of the box. However, feel free to change the rofi options to whatever style you want.
