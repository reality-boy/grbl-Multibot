# grbl-Multibot
Port of grbl for the Multibot

This is a port of grbl 1.1h configured to run on a cnc shield and my Multibot machine.
https://github.com/gnea/grbl

Only one file is currently modified, config.h. I have the origional config_org.h file
as well so you can easily see the changes I have made.  This assumes you have an official
Pronter CNC shield and not a chineese clone.  That allows us to use the laser and auto 
squaring of the y axis at the same time.
https://blog.protoneer.co.nz/arduino-cnc-shield/

This is setup to work with the Multibot CNC project. You can find the 3D print files on 
https://www.thingiverse.com/thing:4645791 and you can read up more on the project at 
https://hackaday.io/project/176110-multibot-cnc-v2
