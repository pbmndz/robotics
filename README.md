
# **Robotics Project: Autonomous and RC Sumobot controlled by PS4 with PSBT Library**

Welcome to the Robotics Project, featuring an autonomous and remote-controlled (RC) sumobot that is designed to battle with its opponents. The autonomous mode is programmed to detect the white lines on the border of the ring, locate the enemy sumobot, and attack it using its sensors and motors. The RC mode is controlled using a PS4 controller with the PSBT (PlayStation Bluetooth) library.The RC sumobot can be controlled by a human operator using the PS4 controller, whereas the autonomous sumobot is programmed to make its own decisions and movements using a variety of sensors. In a sumobot competition, each sumobot is made to push its competitor out of a circular ring.




# Features
The project includes the following features:

### Autonomous Mode
an autonomous sumobot that makes use of sensors and programmable logic to recognize and react to its surroundings.
- The sumobot's autonomous mode is made to detect white lines on the ring's edge and engage the enemy sumobot in combat.
- The sumobot's movements are controlled by decision-making logic and sensor readings combined in the autonomous mode, which is programmed using Arduino code.

### Remote-Controlled Mode
- A remote-controlled sumobot that can be controlled using a PS4 controller, with the help of the PSBT library.
- The sumobot can move in different directions, rotate, and push other sumobots out of the ring.
- The remote-controlled mode demonstrates the use of a wireless controller to operate machines.

## The autonomous mode was built using the following components:

- Arduino Uno microcontroller board
- Pololu wheels for the sumobot's locomotion
- N20 micro gear DC motor 500rpm for the wheels
- L293D motor driver for driving the motors
- Two Sharp 2Y0A21 F92 infrared distance sensors for obstacle detection
- A laser-cut acrylic base for the sumobot
- Two 2S batteries with a voltage of 3.7 volts each, for a total voltage of 7.4V
- Two ultrasonic sensors on each side of the sumobot, for obstacle detection and avoidance
- Four line tracing sensors on the bottom of the sumobot, for border detection and line following

## The remote-controlled mode was built using the following components:

- Arduino Uno microcontroller board
- Pololu wheels for the sumobot's locomotion
- N20 micro gear DC motor 500rpm for the wheels
- L293D motor driver for driving the motors
- USB Host Shield for communication with the Bluetooth dongle
- Bluetooth dongle for communication with the PS4 controller
- PS4 controller
- PSBT library
- A laser-cut acrylic base for the sumobot
- Two 2S batteries with a voltage of 3.7 volts each, for a total voltage of 7.4V

# Requirements
### To build and run the autonomous mode, you will need the following:

- A board with a microcontroller, like an Arduino or Raspberry Pi
- A sumobot chassis equipped with wheels and motors
- Sensors for line following and obstacle detection, such as ultrasonic sensors, line sensors, or infrared sensors.
- Remote-Controlled Mode; Batteries or other power source for the microcontroller and sumobot
 
### To build and run the remote-controlled mode, you will need the following:

- A microcontroller board such as Arduino or Raspberry Pi
- A sumobot chassis with motors and wheels
- A PS4 controller
- The PSBT library
- Batteries or power source for the sumobot and microcontroller
- A Bluetooth dongle
- A USB host shield

## Installation
To install and run this project, follow these steps:

- Clone the repository to a machine on your network.
- Using the Arduino IDE or another program that is compatible, upload the code to your microcontroller board.
- If you're building an autonomous mode, attach the sensors and motors to your microcontroller board according to the provided instructions.
- Using the PSBT library, connect your microcontroller board and PS4 controller.
- Start the sumobot up and use your PS4 controller to control it.

# Credits
 This robotics project was created by Paulo Benedict D. Mendoza, a student at City of Bacoor NHS Springville - Bacoor City, under the guidance of Sir Michael Angelo Cipat, as part of a robotics.
