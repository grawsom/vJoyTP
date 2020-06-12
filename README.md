# vJoyTP
vJoy for Touch Portal

Wanted to find an easy way to use vJoy in Touch Portal and it seems like pyvjoy can do the stuff. 

reference - pyvjoy https://github.com/tidzo/pyvjoy
pyvjoy is a set of Python bindings for vJoy (vjoystick.sourceforge.net)  

I have localy made a py script with 3 parameters (vjoy Device ID, vJoy Button number, vJoy Button state on/off) and have turned all that into a exe package that can be used as a plugin in Touch Portal

NOTE:
(the dll library used in this package only works with x86!)

**Download and install the vJoyTP.tpp file**
https://github.com/grawsom/vJoyTP/blob/master/vJoyTP.tpp

TESTTOOL:
"Pointy's Joystick Test App" is very useful when testing vJoy and this library: http://www.planetpointy.co.uk/joystick-test-application/

## Requirements

At least one configured virtual Joystick with at least one Button and its ID.

- vJoy - tested with version v2.1.9.1  
https://github.com/jshafer817/vJoy/releases/tag/v2.1.9.1

TODO:
Support for Axis
and other stuff
