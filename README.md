# Motorized Roller Blind
This project is a combination of several other projects.
It consists mainly of:
* [Code](http://kookye.com/2016/12/13/use-nodemcu-to-control-step-motor-through-mqtt-iot-protocol/)
* [Parts](http://www.instructables.com/id/Motorized-WiFi-IKEA-Roller-Blind/)

Huge thanks to the two above!

![overview](https://github.com/petrepa/rollerblind/blob/master/Photos/overview.jpg)

## Build
I originally started this project by following the Instructable linked above, but never got quite comfortable using lua and I think the motor shield I had was broken when it arrived. Still the parts designed in that Instructable was perfect as I already had the [IKEA Tupplur](https://www.ikea.com/no/no/catalog/products/70349134/) roller blinds.

![mount](https://github.com/petrepa/rollerblind/blob/master/Photos/mount.jpg)

I still had to design a [new case for the controller](https://www.thingiverse.com/thing:2872783), since I ended up with making my own development circuit.

![circuit](https://github.com/petrepa/rollerblind/blob/master/Photos/circuit.jpg)

Parts used:
* NodeMCU V3
* 12V to 5V converter - Did not realize untill after the project was finished that the NodeMCU did not need the converter as it could handle the 12V
* ULN2003 stepper motor driver
* 12V power supply
* Power plug

![closed](https://github.com/petrepa/rollerblind/blob/master/Photos/case_closed.jpg)
![open](https://github.com/petrepa/rollerblind/blob/master/Photos/case_open.jpg)

## Code
As I mentioned I did not end up with using the code in the Instructable. I therefore searched around the web and found the code linked above. It worked perfect!
