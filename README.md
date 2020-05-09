# SmartDustbin
In this project, we will make a Smart Dustbin using Arduino, where the lid of the dustbin will automatically open when you approach with trash. The other important components used to make this Smart Dustbin are an HC-04 Ultrasonic Sensor and an SG90 TowerPro Servo Motor.

# Getting Started
Download the Git repository as a ZIP ("Download ZIP" button)
Unzip
Copy the entire myCode code.
Open the Arduino program.
Paste the code into a program of arduino.
Plug in your Arduino with the following connections. (refer Connection.doc)

# Component Required
a. Components Required
b. Arduino UNO
c. HC-SR04 Ultrasonic Sensor Module  
d. TowerPro SG90 Servo Motor  
e. Connecting Wires 
f. 5V Power Supply  
g. A small dustbin with hinged lid  
h. Miscellaneous (glue, plastic tube, etc.)

# Working
After setting up the Smart Dustbin and making all the necessary connections, upload the code to Arduino and provide 5V power supply to the circuit. Once the system is powered ON, Arduino keeps monitoring for any object near the Ultrasonic Sensor.

If the Ultrasonic Sensor detects any object like a hand for example, Arduino calculates its distance and if it less than a certain predefined value, Arduino will activate the Servo Motor and with the support of the extended arm, it will list the lid open.

After certain time, the lid is automatically closed.
