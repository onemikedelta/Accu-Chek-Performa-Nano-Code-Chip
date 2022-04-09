# Accu-Chek-Performa-Nano-Code-Chip
Performa nano code chip dump and a little reverse engineering

I have found this device and it looks like code chip is expired. When I teared it down there is only a sot23-5 package eeprom. Most probably it is 24c16, at least i2c address and libraries are suitable.
I don't know the logic level but 3.3v is looks ok.

My friend said he has the new code chip (black), we also dumped that. 

I didn't waste much time on it, I just wrote black chip contents into the white one and it worked.

Note: If you insert black chip once, your device is not going to work with white chips anymore.

Pinout
(Place the chip pins on the right hand side)

Upper 1: VCC  
2: Write Protect (VCC = protected, GND = Not Protected)  
3: SCL  
4: SDA  
5: GND  
6: Not connected  


!! BE CAREFULL !!

I don't have detailed information about these devices and this is not a medical advise. Do everything on your own reponsibility.  
I don't care if you get injured or die because of this experiments.


You may use arduino code for reading and generating black chips.  
I used this eeprom library, https://github.com/yazug/EEPROM24C04_16
