# Advanced-Actuation-and-Holonomic-Drive-Design-Robocon-2023-
Mechanical design and analysis of Rabbit Robot (RR) and Elephant Robot (ER) developed for ROBOCON 2023, featuring holonomic drives, pneumatic and electromechanical mechanisms, and analytically validated actuation systems.
# ROBOCON 2023 – Robot Design & Mechanical Analysis
📌 Overview
This repository documents the mechanical design, working principles, and engineering calculations of two competition robots developed for ROBOCON 2023:

- Rabbit Robot (RR) – high-speed ring picking and throwing robot
- Elephant Robot (ER) – heavy-duty robot for ring lifting, stacking, and long-range throwing

The project focuses on mechanism design, actuation selection, force & torque analysis, and system-level justification, following competition constraints.
🐇 Robot 1: Rabbit Robot (RR)
Key Specifications
- Drive System: 4-Wheel Holonomic Mecanum Drive
- Weight: ~14 kg
- Controllers: Raspberry Pi 4, Arduino Mega
- Sensors: MPU6050 IMU, Camera, Laser Sensor, Limit Switches
- Actuators:
  - Linear Actuator
  - Planetary Geared Motors
  - Servo Motors
Mechanisms
- Ring Picking Mechanism
  - Dual-arm claw actuated using spur gears
  - Planetary motor rotates claw by 180°
- Ring Throwing Mechanism
  - Counter-rotating cylinders driven via chain–sprocket
   -  Linear actuator adjusts angle of projection
     
Engineering Analysis
- Friction force estimation during ring gripping
- Center of Mass (COM) calculation
- Torque calculations for claw actuation and rotation
- Projectile motion analysis for ring throwing
- Motor selection justified analytically
  
CAD & Design
- Complete CAD models created using SolidWorks
- Isometric views and mechanism-level assemblies
- CAD models available via external link (refer report)
  
🏫 Institute & Team Details
- Institute: Shri Guru Gobind Singhji Institute of Engineering and Technology, Nanded
- Team Name: RNXG – Robotics for Next Generation
- Competition: ROBOCON 2023
