# Hi there, I'm Martín Felipe Gil Quemba 👋

**Electronic Engineering Student (9th Semester)** at *Universidad Distrital Francisco José de Caldas* (Bogotá, Colombia) & Active Researcher at **SEROB (Robotics Research Group)**.

🔬 **Focus Areas:** Industrial Automation • Automatic Control • Mobile & Manipulator Robotics • Computational Intelligence & Bio-Signal Processing • Machine Learning • Embedded Systems & PCB Prototyping.

---

### 🛠️ Technical Toolbox

- **Languages & Scientific Computing:** `Python` `MATLAB` `Simulink` `C` `C++` `Structured Text (ST)` `Ladder` `SFC (Grafcet)` `LaTeX` `ROS 2`
- **AI, Data Science & DSP:** `Multilayer Perceptrons (MLP)` `RBF` `CNN` `LSTM` `SOM` `Welch PSD` `Wavelet DWT` `OBS`
- **Control & Robotics:** `Discrete PID` `Extended Kalman Filter (EKF)` `Fuzzy Logic` `System Identification` `Denavit-Hartenberg Kinematics` 
- **Hardware, Embedded & Automation:** `ESP32 (WROOM / S3 / C3)` `Altium Designer` `KiCad` `Autodesk Fusion 360` `Schneider EcoStruxure (Unity Pro XL)` `Factory I/O` `Blynk IoT` `Linux (Ubuntu)`

---

### 🚀 Featured Engineering Projects

1. 🧠 **[BCI-EEG-Thought-Digits-Decoding](#)** *(In Progress — Stage 1 Completed / Stage 2 Active)*
   - **Stage 1 (Completed — EDA, Spectral Pipeline & MLP Baseline):** Multiclass decoding of 10 imagined MNIST digits from massive EEG recordings ($N=18,000$ trials, 2.55 GB, Muse 2 headband). Features a Python streaming pipeline, zero-phase Butterworth filter (0.5–45 Hz) + adaptive MAD Winsorizing, coherent ERP averaging ($K=8$, $+9.03\text{ dB}$ SNR gain), and 50D spectral-spatial extraction (Welch PSD, Hjorth parameters, DASM) vs. 66D Wavelet DWT (`db4`). Optimized `patternnet` MLP (`[32]`, SCG, $L_2$ $\lambda=0.010$) achieving **100.0% accuracy in 5-Fold CV** ($N=1,184$) and **53.03% on the blind massive test set** ($N=3,600$, Macro $\text{AUC}=0.8785$, $8.23\text{ }\mu\text{s}$ latency).
   - **Stage 2 (In Progress — Deep Learning & Conference Paper):** End-to-end training and rigorous benchmarking of **Convolutional Neural Networks (1D/2D CNNs on STFT spectrograms)** and **Recurrent Networks (LSTM / BiLSTM)** against the MLP/RBF baselines (Accuracy, Macro F1-Score, Cohen's $\kappa$, and computational cost) for final scientific publication.

2. 🚜 **[ROS2-Tracked-Agricultural-Robot-Fuzzy-Control](#)** *(Research Paper & Field Evaluation)*
   - **Distributed ROS 2 & Embedded Architecture:** Field-validated tracked mobile robot for autonomous crop-row following in bell pepper greenhouses (Viracachá, Boyacá). Integrates a **Raspberry Pi 5 running ROS 2** (`lidar_node`, `wall_follower`, `esp32_bridge`, `experiment_logger`) and an **ESP32 pseudo-node** via high-speed UART (921,600 baud).
   - **Perception & Hierarchical Control:** Combines a **yaw-compensated $90^\circ$ LiDAR sectorestimator** (YDLIDAR X2 + BNO055 IMU heading compensation) with a high-level **15-rule Mamdani Fuzzy-PD controller** and low-level **200 Hz Feedforward + PI + Lead wheel-speed loops** (with dead-zone compensation and anti-windup) validated through multi-terrain step-response system identification.

3. 🤖 **[Differential-Robot-EKF-Navigation](#):** 2D stochastic pose estimation fusing quadrature encoders and MPU6050 IMU via Extended Kalman Filter (EKF) on ESP32, featuring potential-field obstacle avoidance ($180^\circ$ ultrasonic array), vector wall-following with cornering state machine, and a real-time MATLAB telemetry GUI.

4. 🛸 **[Autonomous-Blimp-SystemID-PID](#):** Experimental parametric identification via Wi-Fi/UDP telemetry and discrete-time pole-placement PID control (difference equations with anti-windup) for altitude and yaw regulation on an ESP32-S3 micro-blimp with a 3D-printed gondola.

5. 🦾 **[OpenBotv2-6DOF-Kinematics-Workspace](#):** Analytical and numerical forward/inverse kinematics (Denavit-Hartenberg & spherical wrist decoupling with $10^{-16}\text{ m}$ accuracy) and 3D Monte Carlo Alpha-Shape workspace mapping in MATLAB.

6. 🔌 **[ESP32-Multipurpose-PCB-Embedded-Suite](#):** Dual-layer development PCB designed in Altium Designer supporting a coaxial 3D-printed ultrasonic radar (AS5600 12-bit I2C encoder + flicker-free TFT), a Blynk IoT 2-DOF closed-loop turret vehicle, and a hardware-timer RTTTL synthesizer.

---

📫 **Reach out:** [LinkedIn](https://www.linkedin.com/in/martin-gil-quemba/) | [Email](mailto:martingilquemba@gmail.com)
