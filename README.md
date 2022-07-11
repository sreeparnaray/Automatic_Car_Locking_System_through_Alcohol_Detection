# Automatic Car Locking System through Alcohol Detection --> Sreeparna Ray
![automatic engine locking system through alcohol detection](https://user-images.githubusercontent.com/67807475/178297289-99313c23-48e6-42e3-ad64-592790c3d1e4.jpg)

### Abstract:
This project presents the design and implementation of an Alcohol Detection and Engine Locking System for cars and other vehicles using an Arduino Nano as the MCU (Master Control Unit) and a MQ3 Sensor as the detection device for alcohol. The system continuously monitors the alcohol level in its affinity using the MQ3 sensor, and as soon as the concentration of alcohol goes beyond the threshold level, the engine gets locked and a buzzer starts to beep/buzz to give indication to the nearby vehicles that the particular vehicle’s driver is drunk and it is not safe to drive nearby the vehicle, and is a threat to other people on the road. 
    The MQ3 Sensor senses alcohol and sends a signal to the Arduino. On receiving the signal from the sensor, the Arduino send a signal to the Buzzer and the Relay, which cuts the power supply to the motor, making the car STOP and preventing any mishap.
    
### Introduction:
The project “Automatic Engine Locking System through Alcohol Detection” aims at preventing accidents that occur due to drunk drivers. Drunk driving is the leading cause of road accidents not only in India but all over the world. Alcohol Detection using breath analyser requires the stopping of vehicles and manual scanning of the driver. Also many people are made to blow into the same breath analyser, which is also not safe as it can be a medium for disease transmission. 
In this project, we will go over how to build an alcohol sensor with an Arduino. The alcohol sensor we will use is the MQ-3 sensor. This is a sensor that is very sensitive to alcohol, particularly ethanol, which is the type of alcohol which is found in wine, beer, and liquor.
This type of sensor circuit can be used as a Breathalyzer to check a person’s blood alcohol level. Just as we exhale carbon dioxide when we breathe out, we also will breathe out some alcohol if we have alcohol in our blood. Any Alco-meter device can measure this alcohol content. The more ethanol in your blood, the more it is in the air on exhalation. This alcohol content gives a good indication for whether a person is drunk and how drunk they are. 

### Block Diagram:
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/67807475/178300742-de2d6706-a476-4351-a3b3-2ac4b549c304.jpg)

### Components Required:
1.	Arduino Nano and cable
2.	MQ-3 Alcohol Sensor
3.	Breadboard / Blank PCB
4.	P-N Diode 1N4007
5.	Transistor BC547
6.	5V relay
7.	Spst switch
8.	Gear motor & wheel
9.	9v battery and connector / Power Bank
10.	Buzzer 5V
11.	Resistor 220ohm 
12.	LED
13.	Wires

### Circuit Diagram: 
![CIRCUIT DIAGRAM JPG](https://user-images.githubusercontent.com/67807475/178301152-a52fc2c8-6333-4716-9b06-0c245c11b8ca.jpg)

### Model Image:
![automatic engine locking system through alcohol detection](https://user-images.githubusercontent.com/67807475/178301362-828b28aa-8c92-4df0-8d95-c4e1cdbdeb84.jpg)

### Result: 
After completing the connections of the circuit and uploading the code, it is ready for use. To mimic the presence of a drunk person, we have used alcohol based sanitizer as an alternative of alcohol. Both alcohol and sanitizer being volatile in nature, tends to evaporate with time. This increases the alcohol concentration in the surrounding, and this increase in concentration is sensed by the sensor. 
When a drunk person comes near to the sensor (in our case, when the sanitizer is brought near the sensor), it reads the increase in the alcohol concentration in the surrounding of the person, and the sensor sends a signal to the Arduino about the reading. If the value of reading is higher than the threshold value (800 in our case) then the Arduino sends a signal to the buzzer, LED and relay. The buzzer starts to beep, the LED glows, and the relay stops the power supply to the motor, thus stopping it, eventually stopping the vehicle. The Arduino will continue to send the signal to the relay and buzzer as long as it is receiving a value higher than the threshold value, from the MQ-3 sensor.
When the reading value of the sensor drops below the threshold value, the buzzer stops beeping, the LED stops glowing and the relay no longer stops the motor power supply, so now the vehicle can again run.
We can avoided any kind of loss of life by using this system. All equipment are totally tested and connected as required thereby giving us the much needed result.

### Discussion:
•	The system can be implemented on any 4-wheeler.
•	It can help in preventing accidents that take place due to drink-and-drive.
•	It can be used as a monitoring device by Law Enforcement Agencies.
•	It can be attached with more advanced system to provide automatic safety system for vehicles. 

### Conclusion
We have given an incredibly capable way to deal and to develop a smart system for vehicles to diminish number of disasters caused in light of alcoholic driving. As the creating insight among people is that vehicle security is dynamically critical. Future degree of this structure is to control the setbacks caused due to alcohol use. This system improves the security of individual and in this manner giving the convincing progression in the vehicle business regarding decrease setbacks caused in light of driving.
