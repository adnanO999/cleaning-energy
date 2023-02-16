# cleaning-energy
Solar panel cleaning rover
This project aims to clean solar panels in more efficient and safe way. The design process followed several iterations and endedup using caterpillar model.
The rover is designed to handle differnt slopes varying from 0 to 30 degree. 
A modular tensioner is mounted on both sides to enable smooth transition from on panel to the other and accomodate with height difference when moving across the panels.
The Robot weight approximately 10 Kg however this weight can be reduced by removing the water tank and battery from the rover and mount them externally.
S shape algorithm was used based on accelerometer and gyroscope data (pitch roll yaw angles) and projected on the panels surface. 
the microncontroller used was arduino mega thus processing was limited therefore I used serial communication to build python program to handle computer vision.
Matlab and python codes were built using existing examples however with more modification to match our goal. These codes were used to collect data from accelerometer/gyroscope transform them to csv file and plot them to analyze the movement of the robot.

overall the main focus was on the mechanical side to build a rover capable of climbing slopes. 
The project is under work to refine the software and change the microcontroller for more processing power. In addition a solidworks model is under design thus I will be able to test and simulate the rover motion.
