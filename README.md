# Arduino Matlab Instantaneous Radar Project
This project is modified in a way that it enables HCSR-04 ultrasonic sensor to rotate 180 degree around its axis to **instantenously** create a polar plot, use color coding for showing the rotation around positive/negative axis, and create a plot of theta(rad) vs. distance(cm) at the end of sweeping the entire are twice and taking the average of both movements to increase the accuracy of the results.
Also the project published by MathWorks in 2016 on https://www.mathworks.com/matlabcentral/fileexchange/58434-mapping-your-surroundings-using-matlab-and-arduino has been 
modified to a new model where the library for the HCSR-04 sensor has been changed from JRodrigoTech/HCSR04 to `Ultrasonic`, which is an Add-On directly from MatLab's Arduino
Hardware Package.
## Setup
Please do not forget to change `COM6` in line 7 to your own COM port by checking it on Arduino IDE.

