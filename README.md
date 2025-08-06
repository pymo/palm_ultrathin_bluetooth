# Palm Ultra-thin Keyboard (P10900U) Bluetooth Mod

![Demo of Palm Ultra-thin keyboard](/images/manual.jpg)

This project modifies the Palm Ultra-thin Keyboard into a Bluetooth keyboard. The conversion kit includes a custom PCB that replaces the original one, a li-po battery, and a 3D printed cover with power switch. The Bluetooth PCB supports BLE 5.3, can pair up to 4 hosts simultaneously, and supports wired USB Type-C connection.


Where to buy
-----------

You can buy the kit from my [Tindie store](https://www.tindie.com/products/39633/). You can also make the PCB by yourself if you are familiar with PCB making and SMT. The PCB files are in the `/pcb` folder.

Keyboard Matrix
-----------

[Keyboard Matrix analysis](keyboard_matrix.md)

Instruction to install the PCB
-----------

[Tutorial for installing the PCB into the keyboard](install.md)

PCB design and firmware
-----------
The PCB uses a WCH CH582F chip, a RISC-V based Bluetooth controller. It is low cost, power efficient and easy enough to use, which is why I chose it. The PCB files are at the /pcb folder.

The firmware is in the release page. Follow [this tutorial](https://github.com/pymo/wch_micro_kbd/blob/main/doc/wch_isp_tool.md) to flash the firmware. The source code is in a [separate repo](https://github.com/pymo/wch_micro_kbd/). 
