# KayproKeyboard
Linux serial keyboard driver that supports the Kaypro keyboard and other custom key mappings

Utilizes the [uinput kernel module](https://kernel.org/doc/html/v4.12/input/uinput.html) and [tio serial I/O device tool application](https://github.com/tio/tio) to implement a user mode driver for the Kaypro keyboard. This has only been tested on Raspberry PI OS.
