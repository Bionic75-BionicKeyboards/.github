# Bionic75

The _Bionic75_ is a 75% multi-layout, rapid disassembly, ultra-low latency wireless, ultra-low power, RGB keyboard.
It has a compact 83 key ISO layout and 82 key ANSI layout.

It has a magnetic daughterboard connector and is designed with a CNC machined CNC aluminum case that uses a ball catch system. 

The _Bionic75_ supports ZMK and QMK firmware.

![Bionic75_ISO_Layout](https://github.com/user-attachments/assets/0fedb576-de96-4a30-a345-d2d17c7a4963)

Required tools: none or a screw driver if PCB mouted stabilizers are used
Optional tools: lube for the stabilizers

## Features
- 75% form factor (82 keys ISO/ 81 keys ANSI)
- Hot swappable
- RGB backlight (south facing) using WS2812 LED family
- Full ISO and ANSI support (for this you need to pick the ISO or ANSI plate or both)
- Support for QMK and ZMK
- Support for custum keyboard layouts using VIA (If QMK is used) or ZMK Studio (if ZMK is used)
- Aluminum case (you decide color and finish). If you are keen with designig you can even modify the design files to add your custom logo or signature
- Extra weight (you decide material e.g. brass or steel and finish e.g. matt or mirrored)
- Rapid disassembly system
  - ball catch case lock
  - magnetic daughterboard connector
- Gasket mount
- USB-C connectivity
- Wireless Bluetooth 5.4 connectivity operating in 2 selectable modes:
  - ultra-low latency mode with a latency @1 ms using LLPM technology to rival USB and propriettary 2.4 GHz connections
  - low energy mode with a common BLE latency @8 ms in favor of longer battery life
- Support for 2 LiPo batteries of any capacity (batteries are optional)
- Real battery management with battery maintenance to extend the battery life and improve safety (this is not a dumb charger like in commercial products)
- fully customizable foaming (you decide number of layers and material)
- Plate for ISO or ANSI or both (you decide material and thickness)
- support for PCB and plate mounted stabilizers
- ESD protection to protect against electrostatic induced damage by touching the metal case (most commercial keyboards miss that important feature)
- 1.6 mm, 4 layer PCB
- 1.6 mm, 4 layer daughterboard
- MCU: [NRF52840](https://www.nordicsemi.com/Products/nRF52840) to support both QMK and ZMK. Features 1 Mb flash memory for tons of layers and custom fucntionalities
- debugging interface (SWD, JTAG)
- power switch under ball catch case (because this keyboard has proper battery maintenace implemented, you will _never_ have to turn it off (except for long term storage)
- anti-ghosting
- fast charging (?)

## Design Components and Sources for Manufacturing
- PCB: [Bionic75-PCB](https://github.com/BionicKeyboards/bridge75-pcb)
- 

**Note:** If the keyboard will be used wired only you don't have to connect batteries. 
You also don't have to connect two battreries if you prefer a single LiPo cell.
At te bottom of the page you will find a list of products and manuifacturers so that you can jump start your keyboard without having to worry about selecting materials and foaming or switches and key caps - basically a prebuild kit.
This list will also contain a price table to give you an idea about the costs of the prebuild kit (note: the prices are not maintained and could have changed in either direction).
However, you can customize _every_ component individually if desired.
There will also be a list that contains all the used parts along with their datasheets.

You will find gidance for the simple assembly and flashing in the [instruction manual]() (assembly will take minutes).
