# Project-AnitaMk-0
Project Anita Mk 0 is my first fully functional robot! It allows a user to have control over a robot over a Wi-Fi connection. The robot can move forward, backward, left, and right, as well as stream a live video feed to the user! 

projectanitaESPCAM.ino is what you upload to the ESP32 cam board! This ESP 32 cam board connects directly to the Arduino UNO that is inside the robot. This board is responsible for connecting to the Wi-Fi network and managing all of the video streaming.

project_anita_uno.ino is what you upload to the Arduino Uno board. This recieved instructions from the ESP32 cam board to move or change the colors of the lights!

Here is the Youtube video: https://youtu.be/wANwJkVwjgc
