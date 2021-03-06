# CodeMyRobot
RHOK 2019 CodeMyRobot

## Getting Started

The following instructions will get you a copy of the project up and running on your local machine for develop and test your robot.

## Prerequisites

You will need a computer with a USB port, and a Carl 7 Robot. 

### Install the Arduino IDE
https://www.arduino.cc/en/Main/Software


### ESP32 Arduino Install
https://github.com/espressif/arduino-esp32/blob/master/docs/arduino-ide/boards_manager.md


### Library and tools
You will need Library and tool files copied to your Arduino IDE library and tool folders before your project can be compiled.

Copy the folders inside library and tool to the following folders. 

On Windows the default folder is: 
- C:\Users\yourUsername\Documents\Arduino\libraries
- C:\Users\yourUsername\Documents\Arduino\tools

On Mac and Linux the default folder is:
- /home/yourUsername/Arduino/libraries
- /home/yourUsername/Arduino/tools

You will also need to unzip the Adafruit-GFX-Library-master.zip file and add this folder to your Arduino/libraries folder if that folder is not already there.

If you find your project will not compile and the error is returning a missing library file check and make sure your libraries are in the correct place. 


### CH341 Driver

Windows 
You can install the driver with CH341SER.EXE found in this git repository. 

MacOS 
You can find the latest MacOS driver here: 
https://sparks.gogo.co.nz/ch340.html

Linux
The driver should already be included in your Linux kernel, however, if your running a much older version you may need to install and compile it.

It is recommended to update your kernel but if you don't want to do that the linux CH341 Driver can be found here: 
http://www.wch.cn/download/CH341SER_LINUX_ZIP.html


