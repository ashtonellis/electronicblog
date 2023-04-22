# Final Project Updates

## March 20th

### Final Project Ideas

Create jellyfish (crochet) and either suspend from ceiling or create some sort of stand  
have varying levels of movement based on inputs (buttons, switches, dials, rfid)  
movements: move faster, change direction  

![Idea 1](images/idea1.jpg)  

Create a solar system (also crochet?)  
inputs (rfid, button, dial, switch) spawn both movement and audio output that bring attention to and facts about different planets  
maybe moves on track?  

![Idea 2](images/idea2.jpg)  

## April 5th

![Sketch 1](images/finalsketch.jpg)

What if....?  

* able to change speed
* able to set off movement of specific ones (color sets?)
* change direction of movement (noticable?)

6 jellyfish in 3 colors  
3 motors - each connect to 2 jellyfish  
each motor moves for 30 seconds per trigger  
etcentric cams ? pear shaped ?  

![Sketch 2](images/finalsketch2.jpg)  

![Sketch 3](images/finalsketch3.jpg)  

need layers of interaction -

* toy ?
* unpredictability

buttons start movement of each set

* single button sets off movement of each, almost randomly ?
  * each press turns on/off each movement (variables?)
* knob ? allows control of speed

maybe need another axis of movement (idk how to do that)  

possibly use light switches  
different combinations of switches create different motion (speed, which move, etc)  

## April 19th update

created mostly working prototype that works without power  
still need to cut gears to attach to motors/dowels  
the arduino can power 20mA per pin and 100mA for the whole board  
if adding capacitors, use .01-.1 uf capacitors  
seperate power supply for motors (3-6V) making sure to connect grounds  
ordered all parts, waiting on motors to arrive  

## April 21st update

recieved L293D motor driver shield

Information on shield:

* Motor Power Connections
  * shield supports motor voltage range of 4.5-25V
  * can be shared with arduino or powered seperately
  * remove pwr jumper to seperate power
  * only share power when the motor supply voltage is less than 12V
* DC Motor Connections
  * each channel can supply up to 600mA current to each motor
* Arduino Shield to Pin Connections
  * for DC and stepper - shield uses pins D3-D8, D11-D12
  * for servo - shield uses pins D9-D10
  * shield does not use pins D2 or D13
