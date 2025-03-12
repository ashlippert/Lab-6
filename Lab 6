# Lab 6: Moving With Purpose - Sensing and Mobility

**Authors:**

Ashlyn Lippert and Seth Daniel

**Date:**

March 12th, 2025

## Introduction
   This lab explores the use of ultrasonic sensors for object detection and distance measurement, along with motor control for robotic mobility. Ultrasonic sensors operate using echolocation, similar to bats and dolphins, to determine proximity. By integrating these sensors with an H-Bridge motor driver and Arduino microcontroller, we can develop a system that responds dynamically to obstacles.

  The lab focuses on programming an ultrasonic sensor to measure distances, controlling motor speed and direction using Pulse Width Modulation (PWM), and implementing a collision avoidance system. Through this process, we gain hands-on experience with sensor-actuator integration and real-time decision-making for robotic applications.

## Materials
1. Computer running Arduino IDE
2. Additional wires
3. A motor driver
4. Two motors
5. RedBoard
6. HC-SR04 Ultrasonic Sensor

## Assembly Methods
**Objective 1: Learn to Listen**

**Ultrasonic Sensor Setup**

   To begin, the HC-SR04 ultrasonic sensor is connected to the RedBoard to measure distances. The sensor’s VCC and GND pins are wired to the appropriate power and ground terminals on the RedBoard. The Trigger (Trig) pin is connected to Digital Pin 7, and the Echo pin is connected to Digital Pin 6. Proper wiring ensures accurate distance measurement. Once connected, the RedBoard is linked to a computer via USB, and the Arduino IDE is opened. The correct board and port settings must be selected, and a simple distance measurement program is uploaded to verify functionality. The schematic describing the circuit used for this part of the lab is provided in Figure 1.

<div align= "center">
<img src="" alt "Schematic 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 1: Ultrasonic sensor circuit schematic. </figcaption>
</div>

<br>

   Once assembled, the RedBoard circuit created using schematic 1 should resemble what is shown in Figure 2 below.

<div align= "center">
<img src="https://github.com/user-attachments/assets/d035d937-2607-494d-9e97-8ce2f591d9b5" alt "Circuit 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 2: Constructed ultrasonic sensor circuit from Schematic 1. </figcaption>
</div>
<br>

**Objective 2: Move It**

**Motor and H-Bridge Setup**

  The TB6612FNG motor driver is connected to the RedBoard to control motor movement. The motor power connections (VM, VCC, GND) are properly wired to provide sufficient voltage. The motor control inputs (AIN1, AIN2, BIN1, BIN2) are connected to the designated Arduino pins to allow direction control. The PWM inputs (PWMA, PWMB) are wired to PWM-enabled pins to regulate speed. The motors are then connected to the A01, A02, B01, and B02 output terminals of the motor driver, ensuring they receive movement commands. Finally, the Arduino IDE is used to upload a basic motor control program to confirm proper motor function. Figure 3 below shows the schematic for constructing this circuit.


<div align="center">
<img src="https://github.com/user-attachments/assets/4cec5b73-a503-4f8a-9187-81eadedb0bf6" alt="Schematic 2" width="400">
<br/>
<figcaption style="font-size: 16px; text-align: center;"> Figure 3: Motor and H-Bridge controlled circuit schematic. </figcaption>
</div>   

<br/>

  Once assembled, the circuit should look resemble Figure 5 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/23505952-297d-40d4-9144-ae91f7526852" alt="Assembled potentiometer controlled LED circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 5: Constructed Motor and H-Bridge circuit from Figure 3. </figcaption>
</div>
<br>

## Test Equipment

1. Computer with Arduino IDE


## Test Procedures

**Part 1: Learn to Listen**
   
   To verify the ultrasonic sensor’s performance, a basic distance measurement program is uploaded to the RedBoard. The Serial Monitor is used to observe real-time distance readings. An object is placed at different known distances, and the sensor’s output is compared to actual measurements. If discrepancies are found, wiring and code adjustments may be necessary. Additionally, the resolution and precision of the system are evaluated by moving an object in small increments and observing the sensor's response.

   The code used for this portion of the lab is provided in Figure 5 below:

<div align="center">
  <img src="" alt="Assembled potentiometer controlled LED circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 5: Constructed Motor and H-Bridge circuit from Figure 3. </figcaption>
</div>
<br>


**Part 2: Move It**

  Motor control is tested by uploading a program that sends movement commands to the motors. The Serial Monitor is used to adjust PWM values and verify speed changes at different levels. The motors should move forward, reverse, turn left, and turn right as programmed. Once basic motor functionality is confirmed, the ultrasonic sensor is integrated into the program to implement collision avoidance. The system is tested by placing an object in front of the robot; when the distance is less than 10 cm, the motors should stop. If the robot does not respond correctly, adjustments are made to the algorithm to improve accuracy and responsiveness.

  The code used for this portion of the lab is provided in Figure 6-10 below:

 <div align="center">
  <img src="" alt="MotorMovement 1" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 6: MotorMovement_Lab6 Code 1/5. </figcaption>
</div>
<br>
 
<div align="center">
  <img src="" alt="MotorMovement 2" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 7: MotorMovement_Lab6 Code 2/5. </figcaption>
</div>
<br>

<div align="center">
  <img src="" alt="MotorMovement 3" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 8: MotorMovement_Lab6 Code 3/5. </figcaption>
</div>
<br>

<div align="center">
  <img src="" alt="MotorMovement 4" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 9: MotorMovement_Lab6 Code 4/5. </figcaption>
</div>
<br>

<div align="center">
  <img src="" alt="Assembled potentiometer controlled LED circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 10: MotorMovement_Lab6 Code 5/5. </figcaption>
</div>
<br/>

## Test Results:

**Table 1: Resistor Values**



**Table 2: LED Blinking Delay**



## Discussion:


## Conclusion:
