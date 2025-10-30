##2025_Hanium_ROSproject

2025 한이음 드림업 ICT 공모전 장려상 (Honorable Mention, KAIT)

A real-time disaster rescue robot for GPS-denied environments using multi-sensor data fusion (LiDAR, IMU, Wheel Encoder, Camera, Temperature/Humidity).

🔗 Links

🎥 Demo Video → YouTube Link

📄 Paper → “Real-Time Disaster Rescue Robot for GPS-Denied Environments Using Multi-Sensor Data Fusion,”
Korea Information Technology Society, Nov. 2025

🧠 Team → Hanium Dream-Up 2025 Project Page
 (optional)

🧩 Background

Modern disaster environments often block GPS signals (e.g., tunnels, basements, or dense urban areas).
This project proposes a multi-sensor fusion robot system capable of real-time localization, mapping, and autonomous navigation in such GPS-denied environments.

Key Objectives:

Replace unreliable GPS data with LiDAR–IMU–Odometry fusion (LIO).

Perform real-time SLAM and path planning on a Linux-based ROS2 system.

Provide cloud-based monitoring through MongoDB Atlas and Node-RED.

Detect environmental hazards with YOLOv5 and onboard cameras.

⚙️ Environment Setup
Category	Details
OS	Ubuntu 20.04 LTS
Framework	ROS2 Foxy, Navigation2, Cartographer
Programming	Python 3, C++
Hardware	Raspberry Pi 4, Stella N2 Robot
Sensors	LiDAR (YDLidar X4PRO), IMU (MW-AHRSv2U), Wheel Encoder, GPS (EZ-0048), Temp/Humidity Sensor
Database / Monitoring	MongoDB Atlas, Node-RED
AI Model	YOLOv5 (custom trained for obstacle detection)

#System architecture
<img width="972" height="625" alt="image" src="https://github.com/user-attachments/assets/5227d894-40b7-4a96-a4eb-fbb972524345" />
System

<img width="959" height="642" alt="image" src="https://github.com/user-attachments/assets/eaf8da6a-4658-474c-819f-b097c7bb600d" />
Hardware

<img width="1337" height="620" alt="image" src="https://github.com/user-attachments/assets/82e0d6e4-ddb8-4f9d-bc54-49870729c32b" />
Software

<img width="1893" height="1155" alt="image" src="https://github.com/user-attachments/assets/62a25a0c-25c0-43c5-ba43-f65bd10baf42" />
Node-RED diagram

🧠 Built With

ROS2 (Foxy) – SLAM, Navigation, and real-time sensor fusion

Cartographer – LiDAR-Inertial SLAM implementation

YOLOv5 – Real-time object detection for hazard identification

MongoDB Atlas – Cloud data storage for live sensor updates

Node-RED Dashboard – Web-based real-time monitoring

Raspberry Pi 4 + Stella N2 – Embedded control and execution platform

📊 Results

Stable autonomous navigation in GPS-denied indoor environments

<img width="1694" height="812" alt="image" src="https://github.com/user-attachments/assets/0c4860cf-5545-40ec-9fa9-354de3e2eee7" />
Web Dashboard
description
- Real-time SLAM mapping and object detection
- End-to-end monitoring pipeline from robot → cloud → web

Result Youtube
https://youtu.be/2Iq2_ShP6eY?si=E3-j7cPRBcZmXgdn

🏅 Honorable Mention (KAIT Hanium Dream-Up ICT Competition 2025)
