# Basic Floor Cleaner Robot

This project demonstrates a simple, low-cost floor-cleaning robot using Arduino and a rotating brush mechanism and automatic water sprinkling mechanism to drive it is a manual you can do it by adding obstacle avoiding using the ultrasonic sensors

## Features

- Moves forward while cleaning the floor with a rotating brush
- Powered by DC motors and controlled by an Arduino UNO
- Rechargeable battery for portable use
- basic manual control by using the Bluetooth communication 

## components Used

 
- ARDUNIO NANO
- 12V BATTERY
- 16/2 LCD DISPLAY
- WATER PUMP
- 5V REGULATOR L7805IC
- 16x2 LCD DISPLAY 
- HC-05 BLUETOOTH MODULE
- REALY MODULE
- L293 DC MOTOR DRIVER, DRIYER FAN
- 100RPM DC GEAR MOTORS, VIBRATION MOTOR
- WHEEL
- MOP BASE



## 🧠 Working Principle

We have to setup the equipment i.e power the Arduino nano and giving connections, and connect Bluetooth module with mobile to operate

When we connect our mobile with Bluetooth module with an application, we can operate it and give the commands to it.


We can give the commands to Arduino board or to robot using the terminal provided in the application, we can give the commands like Left – so that robot turns to left side, by stopping the rotation of left wheel so that it drifts left side
Right- same happens like in left,but it rotates to right. Front-moves forward
Back-moves backward Stop- stops


## Folder Structure

floor-cleaner-robot/
├── code/                 # Arduino code (e.g., floor_cleaner.ino)
├── images/               # Any photos or diagrams
├── docs/                 # Your .docx file and any additional reports
├── README.md             # To be created (see below)

## Future Improvements

- Add sensors for obstacle or edge detection
- Vacuum module for dry dust
- Remote or app control
- floor mapping or outlining the house or space 

