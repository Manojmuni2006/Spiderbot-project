AUTONOMOUS SPIDER ROBOT Hexapod Locomotion with Servo Control & Obstacle
Avoidance

Project Overview The Autonomous Spider Robot is a quadruped walking
robot inspired by spider locomotion. It uses 8 servo motors, Arduino
Nano, and ultrasonic sensing for autonomous movement and obstacle
avoidance.

Features - 4-leg spider style locomotion - 8 SG90 servo motor control -
Ultrasonic obstacle detection - Multi-directional movement - Battery
powered - Future AI navigation ready

System Architecture HC-SR04 Ultrasonic Sensor | v Arduino Nano V3 | v
PCA9685 Servo Driver | v 8 SG90 Servos | v Spider Robot Legs

Power Supply → Li-Po Battery Pack

Hardware Components - Arduino Nano V3 - PCA9685 Servo Driver - 8x SG90
Servo Motors - HC-SR04 Ultrasonic Sensor - Li-Po Battery Pack - Spider
Robot Frame

Leg Mechanism Each leg has 2 Degrees of Freedom Coxa Servo → Forward &
backward motion Femur Servo → Up & down motion

Obstacle Avoidance Logic
1. Ultrasonic sensor sends pulse
2. Echo return time measured 
3. Distance calculated 
4. If obstacle detected → STOP 
5.Robot turns left/right
6. Resume forward movement

Specifications Legs: 4 Servo Motors: 8 DOF per leg: 2 Controller:
Arduino Nano Communication: I2C Sensor Range: 2cm – 400cm Servo Driver:
PCA9685 Power: Li-Po Battery

Future Scope Phase 1: - Arduino Nano control - Basic obstacle avoidance

Phase 2: - Raspberry Pi 4 - Camera module - Python navigation

Phase 3: - NVIDIA Jetson Nano - Computer Vision - SLAM mapping - AI path
planning

Team Electronauts:
Ranjan Babu R — Team Lead,Assembly,debug
Prabakaran M — Hardware design
 Kannan R — Programming
 Manoj M — Circuit Design,Assembly
