# Accu-Chek-Performa-Nano-Code-Chip
Performa nano code chip dump and a little reverse engineering

I have found this device and it looks like code chip is expired. When I teared it down there is only a sot23-5 package eeprom. Most probably it is 24c16.
I have dumped the contents and table is attached. I don't know the logic level but 3.3v is looks ok.

My friend said he has the new code chip (black), we also dumped that. 

I don't plan wasting much time on it, just going to write black chip contents in to white one.

Pinout
(Place the chip pins are on the right hand side)

Upper 1: VCC
2: Write Protect
3: SCL
4: SDA
5: GND
6: Not connected
