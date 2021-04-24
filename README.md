# Automatic-Water-System-Using-Aurdino
## Description:
The Automatic Plant watering system I made needed a Soil Moisture Sensor, a Relay Module, an Arduino Uno, a Water Pump. I write code on Arduino IDE, to establish a communication between Soil moisture sensor and relay module using Arduino.  The soil moisture sensor is based on a principle of measuring dielectric permittivity of surrounding medium. In soil, dielectric permittivity is a function of the water content. The sensor creates a voltage proportional to the water content of the soil.

## Objectives:
  * Monitor the moisture content of the soil using a soil moisture sensor and the water level of the tank using a float switch.
  * Turn the motor ON when the soil moisture falls below a certain reference value and if there is enough water in the tank.
  * Display the status of the soil and the tank using a 16×2 LCD.


## Components Used:
Hardware Descriptions-
  * ATmega 328 microcontroller 
  * Moisture sensor 
  * 12V DC motor  
  * Relay module 
  * Jump wire 
  * Power supply  
  * 1 Relay
  * 1 DC pump
  * PVC tubes

Software Description-
  * Arduino IDE
  
![image](https://user-images.githubusercontent.com/79711020/115949143-795a4f00-a4f0-11eb-8b61-fef90b5377ec.png)

 ## Procedure
   * Reading the moisture sensor:
   The first step is to set up the moisture sensor and get a reading off of it. In the tests directory, there is a file which can be used to run the test: MoistureSensorTest.ino

Place the moisture sensor carefully in the potted plant, leaving the wire section exposed. Notice that on the sensor there is a horizontal white line: do not submerge the sensor beyond this line, as it is possible to damage the sensor if the top gets wet. Ideally place the sensor such that the dirt level is approximately 1 inch below this.

Take three jumper wires (1 red, 1 black, 1 blue). Match them to the same colors coming off of the sensor. Run the red wire into the 5v pin on the Arduino: this will provide power to the sensor. Next run the blue wire to the Analog 0 pin, and the black wire to the ground pin (GND).
   * Testing the moisture sensor
   * Turning the Solenoid Valve
   * Setting up the power to the solenoid valve
   * Setting up the Diode
   * Setting up the Transistor
   * Setting up the ground
   * Running the tests
   * Putting it all together: Upload the completed file to the Arduino and open the Serial Monitor. Immediately you should see a reading from the moisture sensor. If that reading is too low and DEBUG < 2, AutoWater will water your plant! 

