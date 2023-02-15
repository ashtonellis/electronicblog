# Week 6 Notes

## February 13th Class Notes

TCI - multifunction tester

* tests components and tells what it is
* tells with leg is positive or negative

Flipper Zero - multitool for hackers

### Lab Questions

* arduino can send information faster than the computer can recieve
  * can lead to lag from buildup of input
  * change code in p5 to have it ask for information instead of arduino contstantly sending
* When code is not working....
  * add console.log to see where the problem could be
  * check serial monitor to see if data is being sent

### Arduino Code

* const int - variable that will never change
* serial.begin(bod rate) - sets up serial communication
* pinmode(pin#,mode) - sets input or output mode of a pin
* while - keep doing code until criteria is not met
  * while (|) or while(TRUE) - loop forever
* serial.available - something was sent to arduino
* serial.print(" ") - print value
* serial.println(" ") -print value with the return after

Github Copilot - not useful for us right now, you write a comment of what you want the code to do and it will write the code for you
Arduino is not capable of concurrency

### P5JS Code

IncomingSerialData[#] - reads data after it has been converted to a list, # is the place in list starting at 0, you need to know which value corresponds to which input

* example: joystick - x = 0 / y = 1 / button = 2

### Adding other Languages to Markdown

use
    ''' language
        code
        '''

mermaid language allows creation of diagrams and charts

* [mermaind notation](https://mermaid.js.org/)

will need a mermaid preview extension --> Markdown Preview Mermaid Support

### Multimeter Functions

* continuity test - sees if two points are electronically connected
* diode - can work continuity test
* check voltage
* check ohms
* check current
  * need current to flow through multimeter
  * ![meter current check](images/multimetercurrent.png)

7805 - voltage regulator, has a limit to how much it can disipate

* ![voltage regulator](images/7805.png)

benchtop power supply - can change voltage and current, tells current on screen

inductive load - electromagnet, motor, speaker

* dont want direct communication to arduino, draws too much power

LM386 - low voltage audio power amplifier
HiLetGo - amazon components

## February 15th Class Notes

ultrasonic sensor tip - to avoid outlier outputs, can tell to ingore outputs that are drastically different than previous output

for electronic parts:

* [allelectronics](https://www.allelectronics.com/)
* [American Science and Surplus](https://www.sciplus.com/)

DIP - dual inline pin
the chips on our boards are in a socket, not soldered directly to the board

Soldering Tips:

* do not use acid core solder
* ~325 degrees - suggested start temperature
* use leaded solder
  * leadfree solder is used for machine soldering, not hand soldering and requires a higher temperature (~400-450 degrees)
  * when using leaded solder, use a fan with a charcoal filter
  * throughhole components should be soldered from the back of the board
  * reflow - reheating solder on the board to get it to flow again to clean up and stabilize connections

Tin Whiskers
Rory Sparks

### Midterm Notes

particle systems - maybe smoke or sparks ?
api - application programming interface, systems talking to eachother
