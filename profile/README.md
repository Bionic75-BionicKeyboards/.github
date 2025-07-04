# Bionic75

The _Bionic75_ is a 75% multi-layout, rapid disassembly, ultra-low latency wireless, ultra-low power, RGB keyboard.
It has a compact 83 key ISO layout and 82 key ANSI layout.

It has a magnetic daughterboard connector and is designed with a CNC machined aluminum case that uses a ball catch system. 

The _Bionic75_ supports QMK firmware.

![Bionic75_ISO_Layout](https://github.com/user-attachments/assets/0fedb576-de96-4a30-a345-d2d17c7a4963)

Required tools: none or a screw driver if PCB mouted stabilizers are used
Optional tools: lube for the stabilizers

## Features
- 75% form factor (82 keys ISO/ 81 keys ANSI)
- Hot swappable
- RGB backlight (south facing) using SK68MINI-E LED family
- Full ISO and ANSI support (for this you need to pick the ISO or ANSI plate or both)
- Support for QMK
- Support for custum keyboard layouts using VIA
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
- 1000 Hz (1kHz) polling rate for gaming.  
  **Note:** faster polling rates _will not_ provide any advantage as the polling rate is not the bottle necck in the system's latency. Debouncing and especially the input latency (human reaction time, especially descision making) make higher pollig rates absolute pointless (except for marketing) and will only waste energy/shorten battery life for no gains. As a matter of fact, studies have prooved that less than 5% were able to notice the difference between 400 Hz and 1000 Hz. It's not relevant except to add marketing bubbles to the product (because higher numbers make people believe that something is better - that's why you see _1000 Hz_ instead of _1 kHz_ in the specs). 
- Support for 1 LiPo battery cell of any capacity (batteries are optional, >= 4 Ah recommended)
  - single battery enhances battery longevity
  - the higher the capacity, the faster the possible charging
  - by default, the Bionic75 comes with a 10,000 mAh battery (10 Ah)
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
  

**Note:** If the keyboard will be used wired only you don't have to connect batteries. 
You also don't have to connect two battreries if you prefer a single LiPo cell.
At te bottom of the page you will find a list of products and manuifacturers so that you can jump start your keyboard without having to worry about selecting materials and foaming or switches and key caps - basically a prebuild kit.
This list will also contain a price table to give you an idea about the costs of the prebuild kit (note: the prices are not maintained and could have changed in either direction).
However, you can customize _every_ component individually if desired.
There will also be a list that contains all the used parts along with their datasheets.

You will find gidance for the simple assembly and flashing in the [instruction manual]() (assembly will take minutes).
