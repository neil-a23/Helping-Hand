#  Helping Hand

Helping-Hand is a device that works to minimze the hand tremors that people with Parkinson's Disease have. In this proof-of-concept prototype, an acceleromter and gyrocscope contained in the MPU6050 chip tracks linear and rotational acceleration. From these values, the angles of the person's hands in real time is calculated. The servo motors move the device directly in the opposite direction of the hand. 

# Main Components 

Arduino Nano, MPU 6050, 2 Servo Motors, Jumper Wires, Breadboard

# Acknowledgments

A big thanks to Jeff Rowberg's i2cdevlib library, which helped us correctly calculate the yaw, pitch, and roll angles. It allowed us to access the DMP on the MPU 6050, which helped minimize drift. 

