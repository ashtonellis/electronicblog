# Week 11 Notes

## March 20th Class Notes

Discussed Final Exam Ideas

[Final Exam Notes](final.md)  

## March 22nd Class Notes

PCB Design Programs

* DipTrace
* EasyEDA
* Fusion360
* KiCAD

Main difference is how easy it is to make your own component  
Spacing of holes on breadboard and circut board is .1 in or 2.54 mm - same as pitch (space between) of pins on components  

Carbide Motion Steps

* Turn on
* Connect to cutter
* Initialize Machine
* Put tool in with bowl of wax underneath and tighten (not too tight)
* define xyz position
  * be careful not to damage bolt
  * leave space around board, don't place at very corner
  * z- get close, lower bit, load new tool
* load job and start

in GCode- add M03 S10000 after each tool change

* starts spindle and sets speed
