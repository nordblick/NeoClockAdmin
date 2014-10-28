NeoPixelClock
=============


NeoPixelClock Firmware
----------------------
NeoPixelClock (npa) is just a simple a clock using adafruits neopixel ring and a bunch of additional parts like a DS1307 RTC-Chip, a light sensor for adaptive brightness and -of course - an arduino. A plain AVR would be fine as well, if you use an FTDI-interface for serial communication.


NeoPixelClockAdmin
------------------
NeoClockAdmin (npca) is a lightweight tool to administrate neopixel-based clock, connected via serial port. ; You can manage time and events onwhich the clock should recognice 

Command line options for npca.
	-p  Path to serial device
	-b <1-15> Set clock brighness 
	-s Sync clock time with current time of operation system
	-d Display current clock settings (time, events, brighness) 
	-a <id> <datetime> <action>
	-r <id> 

Source npca is developed on a MAC for BSD-based system, but could easiliy adapted to any other OS.

