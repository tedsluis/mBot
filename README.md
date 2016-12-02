[TOC]   
  
# mBot
    
## mCore and sensors mBot  
<a href="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_and_sensors_mbot.png"
 target="_blank"><img src="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_and_sensors_mbot.png"
alt="mCore and sensors mBot" width="600" height="477" border="10"/></a>  
  
## Part list  
  
Component             | Description       |
--------------------- | ----------------- |
mCore                 | mBot main board   | https://github.com/tedsluis/mBot/raw/master/pictures/mcore_mbot.jpg
me Line follower      | Line follower     | https://github.com/tedsluis/mBot/raw/master/pictures/me_line_follower.jpg
me Ultrasonic sensor  | Ultrasonic sensor | https://github.com/tedsluis/mBot/raw/master/pictures/me_ultrasonic_sensor.jpg
me Bluetooth          | Bluetooth sensor  | https://github.com/tedsluis/mBot/raw/master/pictures/bluetooth_for_mbot.html.jpg
  
## mCore board mBot  
<a href="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_main_board_mbot.png"
 target="_blank"><img src="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_main_board_mbot.png"
alt="mCore board mBot" width="600" height="398" border="10"/></a>  
  
## mCore ports, pins settings and components  
<a href="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_ports_and_components.png"
 target="_blank"><img src="https://raw.githubusercontent.com/tedsluis/mBot/master/pictures/mcore_ports_and_components.png"
alt="mCore ports, pins settings and components" width="572" height="612" border="10"/></a>  
  
# Getting ready for the challenge 

* Clone this Git Repository to a local folder
* Create a branch with your team name: team/***teamName***
* Download and install the latest stable version of the Arduino IDE for your platform from: https://www.arduino.cc/en/Main/Software
* Start the Arduino IDE
* File -> Open -> [mBot-default-program/mBot-default-program.ino](https://github.com/JDriven/mBot/blob/master/mBot-default-program/mBot-default-program.ino) : Import the Example Sketch
* Sketch -> Verify / Compile : Check that this does not generate any errors
* Attach the mBot to your laptop using USB
* Turn on the mBot
* Verify the following Arduino IDE settings
 * Tools -> Board : Arduino/Genuino Uno
 * Tools -> Port : Select the USB/Serial port for your mBot 
  * If the mBot does not show up please install the required drivers and reboot: https://github.com/Makeblock-official/Makeblock-USB-Driver
 * Tools -> Programmer : Arduino as ISP
 * Tools -> Serial Monitor : Both NL & CR
 * Tools -> Serial Monitor : 115200 Baud
* Sketch -> Upload : Check that you can upload the firmware without any errors and verify this by looking at the output using the Serial Monitor

