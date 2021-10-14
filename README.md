# Driver Drowsiness Detector using Count of Yawns
This program helps in detecting if the driver of a vehicle is drowsy, using the number of counts of yawns. If the number passes a specified threshold value, the beeper starts to ring and the driver is alerted. <br>

It uses Computer Vision to detect facial points, and yawn is calculated using the distance between upper and lower lip facial point distance. <br>

Novelty:
1. Majority of road accidents all over the world are caused due to the driver feeling sleepy and drowsy. This program will alert the driver that he/she needs to stop the vehicle and get some rest before driving again, thus reducing the number of road accidents.
2. This program maps facial points very accurately and hence, can be used for multiple different projects. 

Methodology:
1. Facial Mappings are mapped with facial boundaries.  
2. Distance between upper and lower lip is measures.
3. If the distance is more than specified threshold value, output ('Yawn Detected') is printed.
4. Yawn Counter is incremented.
5. If the counter is higher than the threshold, driver is alerted.

Input/Output Screenshots: <br><br>
![alt text](https://github.com/shreyagupta4/Driver-Yawn-Detection/blob/main/YC.png) <br>
![alt text](https://github.com/shreyagupta4/Driver-Yawn-Detection/blob/main/YC5.png) <br>
![alt text](https://github.com/shreyagupta4/Driver-Yawn-Detection/blob/main/YC7.png)
