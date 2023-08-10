# Smart-Parking-System
IOT-based car packing management system help in efficient parking space utilization only Arduino code and components used.


![car parking](https://github.com/ritvikdwivedi19/Smart-Parking-System/assets/131281117/61c1b270-a4c6-4750-90c0-e6366b03c921)


**Problem Statement**

As the population has been increasing tremendously, vehicular traffic and its parking has become an issue of great concern. In public places where there are many visitors, a lot of time is wasted for searching parking slots. Also, a lot of manual labour is required to look after the existing parking arrangement. Moreover, there is no way of knowing whether a vacant parking space is available or not. The smart parking system is going to be implemented in several countries. In India, this type of parking system is most likely to be implemented in Bangalore in the near future.

**Proposed Solution**

The given automatic parking system which is safe, speedy, user-friendly and cost-effective includes the following features:

Automated parking system without any manual labour
Simultaneous operations on different floors for car parking
Multiple entry and exit points
Pre-booking of parking slots through a mobile App
Categorization of vehicles by size and weight based on which the driver will be given a place to park the car. In this way, heavy and larger vehicles can be given a parking space on the Ground floor for convenience.

**Basic Components and Softwares used**

STM32103C to be used as the microcontroller

Ultrasonic Sensors to detect the presence of a vehicle near entry or exit

IR Sensors to detect occupancy in each parking space

Servo motors to be used as shafts

Arduino IDE for firmware development

Thunkable Classic for Android App development
Anaconda-OpenCV Python for Image Processing and weight detection
LCD Nokia 5110

**Working**

When a vehicle arrives in front of UV sensor it sends a signal to servo motor which rotates 90 degrees up and allows the car to enter inside. Once the capacity of the system is full no more vehicle is allowed inside.The exit and entry system work simultaneously with the help of a counter which increments or decrements as a vehicle enters or leaves the parking slot. The IR sensors help to identify filled and empty spaces.

![flow diagram smart](https://github.com/ritvikdwivedi19/Smart-Parking-System/assets/131281117/f83d436a-360c-43d4-865a-cbdeb3d3aad7)
