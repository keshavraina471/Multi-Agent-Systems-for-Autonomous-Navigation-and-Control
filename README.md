# Multi-Agent-Systems-for-Autonomous-Navigation-and-Control<br>
**Overview:**<br>
This project focuses on the development and implementation of multi-agent systems for autonomous navigation and control. The system involves the use of ESP8266 microcontrollers to control multiple motors with closed-loop feedback using PID control and Kalman filtering. The goal is to achieve precise control of motor speeds and position realization for autonomous agents, which can be applied in robotics, drones, and other multi-agent systems.<br>

The project is part of my research internship at IIT Mandi under the guidance of Dr. Tushar Jain. The work involves both theoretical and practical implementation of control algorithms for multi-agent systems.<br>

**Key Features:**<br>

**1. Closed-Loop Control:**<br>
 i) Implementation of PID control for precise motor speed regulation.<br>
ii) Use of Kalman filtering to reduce noise and improve the accuracy of RPM measurements.<br>

**2. Position Realization:**<br>
i) Calculation of linear and angular velocities from motor RPMs.<br>
ii) Real-time position estimation (x, y, theta) using kinematic equations.<br>

**3. WiFi Communication:**<br>
i) Use of ESP8266 for WiFi communication, enabling remote monitoring and control.<br>
ii) Setup of a local WiFi access point for real-time data transmission.<br>

**Repository Structure:**<br>
The repository contains the following Arduino sketches (.ino files) for different aspects of the project:<br>

**1. Closed_loop_xy.ino:**<br>
i) Implements closed-loop control for two motors to achieve desired linear and angular velocities.<br>
ii) Calculates the position (x, y) and orientation (theta) of the agent in real-time.<br>
iii) Uses PID control and Kalman filtering for motor speed regulation.<br>

**2. Desired_RPM_Both_motors.ino:**<br>
i) Focuses on controlling two motors to achieve desired RPMs using PID control.<br>
ii) Implements Kalman filtering to reduce noise in RPM measurements.<br>

**3. Position_realisation_from_RPM.ino:**<br>
i) Converts motor RPMs into linear and angular velocities.<br>
ii) Estimates the position (x, y) and orientation (theta) of the agent using kinematic equations.<br>

**4. Single_motor_closedLoopcontrol.ino:**<br>

i) Implements closed-loop control for a single motor using PID control.<br>
ii) Uses Kalman filtering to improve RPM measurement accuracy.<br>

**Technologies and Tools Used:**<br>

**Hardware:**<br>
i) ESP8266 microcontroller<br>
ii) DC motors with encoders<br>
iii) Motor drivers<br>

**Software:**<br>

i) Arduino IDE<br>
ii) PID control algorithm.<br>
iii) Kalman filter for noise reduction.<br>
iv) WiFi communication using ESP8266<.br>

**Mathematical Models:**<br>

i) Kinematic equations for position realization.<br>
ii) Control theory for PID tuning.<br>

**Applications:**<br>

**Autonomous Robotics:**<br>
 Precise control of robotic agents for navigation and task execution.<br>

**Industrial Automation:**<br>
Coordination of multiple agents in manufacturing and logistics.<br>

**Future Work:**<br>
i) Integration of more agents for complex multi-agent systems.<br>
ii) Implementation of advanced control algorithms like MPC (Model Predictive Control).<br>
iii) Development of a user interface for real-time monitoring and control.<br>

**Acknowledgments:**<br>
i) **Dr. Tushar Jain**, IIT Mandi, for his guidance and supervision.<br>
ii) **Akumalla Ravi Kiran**, PhD Scholar, IIT Mandi, for his continuous support and mentorship throughout the project.<br>
iii) IIT Mandi for providing the resources and infrastructure for this research.<br>



