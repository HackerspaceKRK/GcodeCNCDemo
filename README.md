#HSKRK Low Budget CNC (LBCNC)

Simplest firmware for bipolar 4-wire stepper motors powered CNC machines on g-code diet.
!["a lot of hot glue in there"](http://hackerspacekrk.github.io/LBCNC/images/photo1.jpg)
Test run of our construction: http://www.youtube.com/watch?v=VrmuOFds8pg  

Makes use Arduino Mega due to 4 pins per motor required.
* X axis is connected to pins 30-33
* Y axis is connected to pins 34-37
* Z axis is connected to pins 38-42  
!["by Arduino.cc"](http://arduino.cc/en/uploads/Reference/bipolar_stepper_four_pins.jpg)  
image from Arduino.cc



##Which files should I use?

* If you are testing out X-Y table then use 2axis.ino .
* If you already made some wood works and have also Z axis, then use 4axis.ino .

##Prerequisites

* Arduino: http://arduino.cc/
* A lot of hot glue
* Some more hot glue

##More

For the latest version please visit https://github.com/HackerspaceKRK/LBCNC

##Authors

http://hackerspace-krk.pl  
Jakub Kramarz  
2013-11-09 

http://marginallyclever.com  
Dan Royer  
2013-08-30
