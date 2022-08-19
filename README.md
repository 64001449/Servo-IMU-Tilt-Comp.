# Servo-IMU-Tilt-Comp.

Overview: This is the code for the tilt feature of an anti-rotation device made by the MnSGC Ballooning Team.

Instructions for use: First, download the zip file for the code, and then open it up in Arduino or Teensyduino. Then, connect the servo and IMU to the Arduino Uno. (The servo's brown pin goes to GND, the orange pin to 5V, and the yellow pin to D9. The IMU's GND goes to GND, the VDD goes to 3.3V, the SDA to A4, and the SCL to A5). Then, tape the IMU to one of the wide sides of the servo to simulate the in-flight movement. Now, run the code, and turn the servo so that the arm is pointing at you. You should see that the arm compensates for any angular movement from the servo.
