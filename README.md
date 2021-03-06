# JMP ArduinoProMini Multisensor Board
Arduino Pro Mini board for MySensors,the board is designed for multiple sensors.

**Supply**

1. LiOn battery
2. 5V
3. 2xAA battery

**Boards features:**
1. LiOn battery support
2. NRF24L01+ support
3. RFM69 support
4. ATSHA204A signing chip
5. AT25DF512C EEPROM chip
6. designed for multiple sensors (multiple I2C sensors, analog and digital sensors)
7. Accept Arduino Pro Mini 3.3V and 5V

------------------------------------------------
**LiOn Battery --> 3.3V** - Arduino Pro Mini 8Mhz and 3.3V
1. Weld the  regulator (IC1) and the other capacitor (Cin,Cout, C-NRF, etc)
2. short-circuit the 3.3v jumper
3. weld the C1, R1, R2 parts (voltage divider circuit)
4. use a TP4056 module and attach the LiOn battery on X1 input

**5V** - Arduino Pro Mini 16Mhz and 5V
1. Weld the  regulator (IC1) and the other capacitor (Cin,Cout, C-NRF, etc)
2. short-circuit the 5v jumper and J2 pad
3. attach the the 5V supply on X3 input
4. the regulator gives 3.3v only to antenna

**AA Battery --> 3V** - Arduino Pro Mini 8Mhz and 3.3V
1. **DON'T weld** the  regulator (IC1) 
2. Weld the C-NRF capacitor 
3. short-circuit the 3.3v and 5V jumper, J2 pad
4. weld the C1, R1, R2 parts (voltage divider circuit)
5. attach the 2xAA battery on X3 input
------------------------------------------------



**Please note: the sensor images refer to previous version of the board**

**Disclaimer**
If you order or use this you agree to and understand that the author is not liable for any injury or damage howsoever caused and that you use this PCB at your own risk. This is DIY and the author has not made any professional test. This product has not been marked with any certification marks and can't be guaranteed to comply with any standards.
