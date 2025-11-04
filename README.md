# Cognitive Radar for Target Tracking

<img width="900" height="520" alt="image" src="https://github.com/user-attachments/assets/2c25e827-d6a4-4b59-b219-f377abe57a64" />


**M.Tech Thesis | Defence Institute of Advanced Technology, Department of Electronics & Communication Engineering (Radar and Communication)**  
*Year: 2023 | Tools: MATLAB, Python*  

---

## Overview
This thesis explores the concept of **Cognitive Radar**, an intelligent radar system inspired by the echolocation mechanism used by bats and dolphins. The work focuses on how cognitive systems can dynamically adapt transmission and reception strategies for improved target tracking accuracy in complex environments. The study emphasizes **Kalman Filtering techniques** and their application in radar perception, modeling, and real-time tracking.

---

## Methodology
- Implemented **Kalman Filter (KF)** and compared performance across variants: **Extended KF, Unscented KF, and Cubature KF (CKF)**.  
- Conducted over **1000 recursive prediction–correction cycles** to evaluate convergence and minimize estimation error.  
- Simulated the **tracking of a two-link robotic arm** using CKF in MATLAB.  
- Applied **dynamic programming** at the transmitter for waveform optimization.  

<img width="720" height="361" alt="image" src="https://github.com/user-attachments/assets/f714146e-996a-422e-8172-b148f8b1a871" />

---

## Key Findings
- **CKF achieved the lowest RMSE** and exhibited superior stability under non-linear dynamic conditions.  
- Cognitive feedback between radar transmitter and receiver improved **tracking accuracy and response adaptiveness**.  
- Demonstrated feasibility of CKF-based perception for **real-world target tracking** and defense radar systems.  

---

## Algorithms & Tools
- **Kalman Filtering Family:** KF, EKF, UKF, CKF  
- **Programming Tools:** MATLAB, Python  
- **Core Concepts:** Cognitive Radar, Dynamic Programming, Nonlinear Estimation, Adaptive Signal Processing  

---

## Repository Contents
├── Thesis_Report.pdf
├── README.md


---

## Related Publication
**Cognitive Radar for Target Tracking**  
*Author*  
IEEE TQCEBT 2022 | October 2022  
[DOI: 10.1109/TQCEBT54229.2022.10041644](https://doi.org/10.1109/TQCEBT54229.2022.10041644)

---

## Future Scope
- Integration of **deep learning** for adaptive waveform prediction.  
- Extension of CKF-based tracking models for **multi-target and swarm UAV detection**.  
- Real-time hardware implementation for defense and autonomous navigation systems.  

---

## Author
**Kanika Singh Rajpoot**  
*M.Tech, Defence Institute of Advanced Technology (2023)*  


