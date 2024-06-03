# Agricultural-Autonomous-Land-Vehicle-Teknofest

This project was developed by the AGRO-DEV TEAM during our participation in the Teknofest Agricultural Unmanned Ground Vehicles Competition, where we reached the semi-finals. The project involves creating an image processing-based wild herb detection and destruction tool using autonomous ground vehicle technology.

# Overview
The Agricultural Autonomous Ground Vehicle project aims to develop an autonomous robot capable of detecting and removing wild herbs from agricultural fields. Using advanced image processing techniques and artificial intelligence, the vehicle can navigate fields, identify unwanted plants, and take action to remove them efficiently.

# Features
Wild Herb Detection: Utilizes a deep learning model based on the Yolov5 Darknet Neural Network to accurately identify wild herbs among crops.

Autonomous Navigation: The vehicle can navigate autonomously through agricultural fields using a combination of sensors and AI algorithms.

Mechanical Herb Removal: Equipped with a mechanism to remove wild herbs from the soil, ensuring they do not compete with crops for nutrients.

Real-Time Monitoring: Includes various sensors to monitor and control the vehicle's operations, ensuring optimal performance and safety.

# Technical Details
# Vehicle Components
Microcontrollers: Jetson Nano and Raspberry Pi for handling AI computations and system controls.

Sensors: Includes Lidar for obstacle detection, LM35 for temperature monitoring, and ultrasonic sensors for proximity sensing.

Motors: Geared DC motors for wheel movement and mechanical operations.

Camera: High-resolution cameras for image acquisition and processing.

# Software Architecture
Image Processing: Utilizes the Yolov5 Darknet model for real-time wild herb detection. The model is trained on a custom dataset labeled using the MakeSense application.

Autonomous Driving Algorithms: Implemented using the MAVLINK protocol to communicate between Jetson Nano and Pixhawk for navigation.

Mechanical Design: Robust chassis and wheel system designed to navigate through rugged agricultural terrains.

Power Management: Powered by a 22.2V 5200mAh Li-Po battery ensuring long-lasting operations.

# Running the Application
Start the Application:

Deploy the application on the Jetson Nano. Ensure all components are connected and powered.

Launch the control software to start the autonomous operations.

# Simulation and Testing
Simulation Environment: Gazebo and Rviz are used for simulating the vehicle's operations in a controlled environment.

Testing: Comprehensive tests are conducted to ensure the integration of AI, mechanical, and electronic components.

# Conclusion
The Agricultural Autonomous Ground Vehicle project is an innovative solution for modern agriculture, addressing the challenge of wild herb management using cutting-edge technology. Our team's dedication and collaborative efforts have resulted in a functional prototype that demonstrates the potential of autonomous systems in enhancing agricultural productivity.
