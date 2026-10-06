# Ahmed Ghfiri – Élève ingénieur mécatronique (dernière année, ESPRIT Tunis)

Systèmes embarqués, drones, robotique : de la conception mécanique et des cartes électroniques au firmware temps réel et à la perception embarquée.

## Recherche

Stage de fin d'études (PFE) de 6 mois en France, à partir de décembre 2026 / janvier 2027, idéalement en laboratoire, avec pour objectif de poursuivre en doctorat.

## Projets phares

**[AquaWing](https://github.com/Ahmedmecatronique/AquaWing)** – drone VTOL autonome de sauvetage en mer (projet CDIO d'un an)

Firmware de vol temps réel STM32 (C/C++), protocole UART custom vers Raspberry Pi, navigation GPS par waypoints, largage automatique de bouée, détection de victimes par IA (YOLO, OpenCV, fusion RGB et thermique), station sol FastAPI/WebSocket.

**[Bras manipulateur 6 axes](https://github.com/Ahmedmecatronique/robot-6-axe-ros)** – projet personnel

Pile ROS 2 Humble (10 nœuds), IK analytique à 8 configurations avec repli Levenberg-Marquardt, trajectoires quintiques 100 Hz, firmware STM32 FreeRTOS + micro-ROS (PID 1 kHz, génération de pas 20 kHz), IHM jumeau numérique 3D PySide6/OpenGL, calibration main-œil, 54 tests unitaires.

**[Contrôleur de vol quadricoptère STM32F103](https://github.com/Ahmedmecatronique/firmware_drone_manuel_stm32f103c8t6)** – firmware en C, entièrement en virgule fixe (Cortex-M3 sans FPU)

Boucles de contrôle à 3 kHz, PID en cascade angle → vitesse, filtre de Mahony en quaternion (Q2.30), MPU-9250 par DMA, ESC OneShot125 / PWM, autotests au démarrage, télécommande ESP32 (NRF24L01), tableau de bord web temps réel (Python, WebSocket). Firmware vérifié en émulateur Cortex-M3 ; essais sur carte et en vol à venir.

## Expérience récente

Stagiaire R&D drones chez TECHNOZOR (2026) – conception d'une carte de contrôle de vol STM32 custom, validée en vol.

## Compétences

- **Embarqué** : C, C++, STM32, ARM Cortex-M, FreeRTOS, micro-ROS, bare metal / HAL
- **Robotique** : ROS 2, PID, cinématique, fusion de capteurs, PixHawk
- **Électronique** : Altium Designer, KiCad, conception de PCB, VHDL / FPGA
- **IA & vision** : Python, OpenCV, YOLO
- **CAO & simulation** : SolidWorks (niveau avancé, certifié CSWA), CATIA V5, ANSYS, Abaqus, MATLAB/Simulink
- **Outils** : Linux, Git, Docker, FastAPI

## Contact

ahmedghfiri1@gmail.com · [LinkedIn](https://www.linkedin.com/in/ahmed-ghfiri-63baa0298/)

<details>
<summary>English version</summary>

### Ahmed Ghfiri – Final-year Mechatronics Engineering student (ESPRIT, Tunis)

Embedded systems, drones, robotics: from mechanical design and electronic boards to real-time firmware and embedded perception.

**Looking for:** a 6-month final-year internship (PFE) in France starting December 2026 / January 2027, ideally in a research laboratory, with the goal of pursuing a PhD.

**Featured projects**

- **[AquaWing](https://github.com/Ahmedmecatronique/AquaWing)** – autonomous VTOL sea-rescue drone (one-year CDIO project). Real-time STM32 flight firmware (C/C++), custom UART protocol to a Raspberry Pi, GPS waypoint navigation, automatic buoy drop, AI victim detection (YOLO, OpenCV, RGB + thermal fusion), FastAPI/WebSocket ground station.
- **[6-DOF robotic arm](https://github.com/Ahmedmecatronique/robot-6-axe-ros)** – personal project. ROS 2 Humble stack (10 nodes), analytical IK with 8 configurations and Levenberg-Marquardt fallback, 100 Hz quintic trajectories, STM32 FreeRTOS + micro-ROS firmware (1 kHz PID, 20 kHz step generation), 3D digital-twin HMI (PySide6/OpenGL), hand-eye calibration, 54 unit tests.
- **[STM32F103 quadcopter flight controller](https://github.com/Ahmedmecatronique/firmware_drone_manuel_stm32f103c8t6)** – C firmware, fully fixed-point (Cortex-M3, no FPU). 3 kHz control loops, cascaded angle → rate PID, quaternion Mahony filter (Q2.30), MPU-9250 over DMA, OneShot125 / PWM ESC output, power-on self-tests, ESP32 remote (NRF24L01), real-time web dashboard (Python, WebSocket). Verified in a Cortex-M3 emulator; board and flight tests still to come.

**Recent experience:** Drone R&D intern at TECHNOZOR (2026) – designed a custom STM32 flight-controller board, flight-validated.

**Skills:** Embedded (C, C++, STM32, ARM Cortex-M, FreeRTOS, micro-ROS, bare metal / HAL) · Robotics (ROS 2, PID, kinematics, sensor fusion, PixHawk) · Electronics (Altium Designer, KiCad, PCB design, VHDL / FPGA) · AI & vision (Python, OpenCV, YOLO) · CAD & simulation (SolidWorks – advanced level, CSWA certified; CATIA V5, ANSYS, Abaqus, MATLAB/Simulink) · Tools (Linux, Git, Docker, FastAPI)

**Contact:** ahmedghfiri1@gmail.com · [LinkedIn](https://www.linkedin.com/in/ahmed-ghfiri-63baa0298/)

</details>
