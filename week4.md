# Week 4 Notes

## February 2nd Class Notes

How to get what you want

* website to create DIY components
* [kobakant.at/diy/](https://www.kobakant.at/DIY/)

UUID - long enough number that it won't be reproduced
NFC - near field communication, stores data

### In Visual Studio Code

* right click -> go to definition
  * explains a line of code and what is needed
* liquidcrystal is an object variable
  * has properties and methods
  * properties are attributes
  * methods are what it can do

OOP/OOM - object oriented programming/method

dht11 - our humidity/temperature sensor

* has power, group and signal pins

ultrasonic sensor - has power, ground, signal and echo pins

SPI - serial periferal interface

* sck - clock
* miso - input
* mosi - output

i2c

* scl - clock
* sda - data

### Buying Components

* qwiic - sparkfun connector, allows i2c connection to sparkfun arduino
* seeed studio - similar to qwiic, but exclusive to grove
* mouser.com or digikey - where to buy components
* our chip - atmega328p
* if sorting by price, all add quanitiy
* every component has a data sheet

#### What is in a data sheet

* absolute maximum voltage - not what we want to use all the time, max without shorting
* typical voltage
* order code table
* mechanical diagrams/dimensions - picture used may not be what shows up, make sure this is what you want
* part number breakdown - lists what each letter/number in part number means

### Programs for Modeling Circut Boards

* Fusion 360 (eagle)
* Diptrace
* KiCAD
* Exeda

* need gerber files to create board
* our machines need g-code files to mill boards (CnC machines)

a joystick is essentially 2 potentiameters and a button
limit switch indicated location 0 on both ends of a moving track
