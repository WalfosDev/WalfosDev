## Bonjour! 👋
I'm Merrick, an Electrical Engineering Co-op student at Concordia building across the full hardware stack, from schematics in KiCad to cloud-connected software.
I love competitions, check out my [LinkedIn](mailto:merrick.marshall.innovates@gmail.com) to see what I am up to! Here you'll find my projects across the stack.

ENG (fluent) · FR (fluent) · 日本語 (beginner)

---
### 🔭 My Projects
#### 1) **Haichi (配置) : Browser-based distributed display controller** `active`
  - Managing content across multiple displays is painful; proprietary software, manual sync, fiddly OS utilities.
  - Haichi (Japanese for *arrangement*) solves this with a zero-install web app, it allows the user to controll the content on the other displays: sign in, drag, done.
  - It's built as a **React (Typescript)** SPA (single-page application) talking to a **Django REST** backend. State is managed client-side, metadata lives in **PostgreSQL**, and **media** is offloaded to object storage (**S3 / MinIO** locally) to keep the database lean.

#### 2) **Robowars : IEEE Concordia 2026 Competition** `active`
  - A competition where 20cm × 20cm robots fight to push each other off a circular platform with white edges. Rounds typically last under 10 seconds, which makes real-time performance the central engineering challenge. 
  - Designed in **KiCad**. The robot runs on an **ESP32-S3** using **ESP-IDF** directly (**no Arduino** abstraction) with task scheduling handled by **FreeRTOS** for strict timing guarantees.
  - Opponets are detected using an IR array driven by a 2-to-4 multiplexed GPIO controller, sampled at fixed intervals via the **GPTimer** peripheral with an ISR updating shared state. 

#### 3) **ChessRobot : ROS2 Motion Controller** `active`
  - Building the middleware layer between a chess-playing ML model and physical hardware for an autonomous chess robot.
  - The system uses `ROS2` with `URDF`, `RViz`, and `Gazebo` for simulation of a `LeRobot` arm, with `MoveIt` handling motion planning.
  - Current focus is configuring the hardware controller for physical arm deployment.

#### 4) **Nauti Metrics : QGIS Bathymetric Data Pipeline** `2025`
  - Built a geospatial data pipeline for Nauti Metrics, a marine survey startup. Raw NMEA sonar logs from an EdgeTech EU D052 echosounder are parsed and cleaned in Python.
  - Outliers are removed via  filtering and clustering then exported to CSV and visualized as bathymetric maps in QGIS using spatial interpolation techniques.

---
### 🏅 Awards
Competitions
- **AquaAction Great Lakes Challenge — 3rd Place** · Traverse City, MI · May 2024
- **Best Technical Innovation** — Shrekathon Hackathon · Concordia University · Mar 2026
- **1st Place** — IISE Industrial Engineering Case Competition · Mar 2026
- **2nd Place** — Product Management Hackathon · Led team and final pitch · Feb 2026
- **3rd Place** — CSME Robotics Competition · Feb 2026
- **IEEE's Choice Award** — Formula WIEEE RC Robot Car Competition · IEEE Concordia · Nov 2025
- **3rd Place** — Concordia Englympics Consulting Case Competition · Oct 2025
- **Cardinal Roy Trophy** — Academic excellence and leadership · Cégep Champlain St. Lawrence · Jun 2025
- **Lieutenant Governor's Medal** (Youth/Bronze Category) · Province of Québec · Jan 2025 

--- 
### 📫 How to reach me

[![LinkedIn](https://img.shields.io/badge/🔗%20LinkedIn-Merrick%20Marshall-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/merrick-marshall-innovates/)
<br>
[![Email](https://img.shields.io/badge/📧%20merrick.marshall.innovates@gmail.com-FF4C4C?style=for-the-badge)](mailto:merrick.marshall.innovates@gmail.com)
---
