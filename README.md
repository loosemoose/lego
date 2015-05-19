# lego
Lego Mindstorms LabVIEW sample project. 

This sample is for a sumo wrestling robot using a typical drive base with an ultrasonic sensor for finding the other bot to push.

This was made using the EV3 software and should work on both the newer EV3 mindstorms kits and the older NXT kits. 
I was using an older NXT kit so I used an ultrasonic sensor to measure distance of objects as opposed to the infrared sensor in the EV3 kits. You can swap it out if using the newer kits. You may have to download and install the ultrasonic sensor block as it is not part of the standard EV3 install. You can find it here: http://cache.lego.com/r/www/r/mindstorms/-/media/franchises/mindstorms%202014/downloads/firmware%20and%20software/ultrasonic.ev3b?l.r=-781618883  Other sensor blocks along with the EV3 software can be found on the download page here: http://www.lego.com/en-us/mindstorms/downloads

The 'code' makes use of a statemachine and uses the sensors and timer events to transition between states. This code is not advanced by any means and I encourage you to use it as a sample and modify it to your liking.

Have fun!
