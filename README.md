DFRobot Gravity: I2C 4-20mA DAC Module with Arduino

This project demonstrates the setup and control of the DFRobot Gravity I2C 4-20mA DAC Module using an Arduino. The module is powered using a 24V DC power supply and communicates with Arduino via the I2C protocol to produce an analog current output in the range of 4-20mA, controlled by a 12-bit digital signal.

DFRobot Gravity: I2C 4-20mA DAC Module (GP8302 chip)

Input Signal Range: 12-bit (0x000-0xFFF), controlling 0-25mA current.
Power Input: 18-24V DC
Current Output: 4-20mA analog
Interface: I2C (Vcc, GND, SDA, SCL)

Wiring Diagram
Connections:
Power Supply:

VIN: 24V DC from external power supply.
GND: Ground of power supply.
DAC Module to Arduino:

VCC -> 5V (Arduino)
GND -> GND (Arduino)
SDA -> Pin A4 (Arduino)
SCL -> Pin A5 (Arduino)


after running Arduino I2C scaner you will find similar result in serial monitor
Scanning...
I2C device found at address 0x58 !
done
