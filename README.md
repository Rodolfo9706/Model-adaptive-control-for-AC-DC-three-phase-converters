# Model Adaptive Control for Three-Phase AC/DC Converters

This repository contains the implementation of a **Lyapunov-based nonlinear adaptive controller** for three-phase **AC/DC converters** under **exogenous disturbances** and **load variations**. The control strategy ensures **output voltage regulation** and addresses the challenges of bilinear and underactuated system dynamics.

## 🚀 Key Features
✅ **Nonlinear Adaptive Control:** Enhances system stability and robustness against disturbances.  
✅ **Almost Global Asymptotic Stability:** Achieved through Lyapunov-based techniques.  
✅ **Space Vector PWM (SVPWM):** Efficient control input distribution.  
✅ **Comparison with PI Controllers:** Demonstrates superior performance.  
✅ **Software-in-the-Loop (SITL) Simulations:** Validated in PSpice under realistic conditions.  

## 📂 Repository Contents
- 📌 **Mathematical Model:** Equations governing the converter dynamics.  
- 📌 **Control Algorithm Implementation:** Nonlinear adaptive control logic.  
- 📌 **SVPWM Modulation Code:** Pulse width modulation for control input distribution.  
- 📌 **Simulation Scripts:** SITL validation using PSpice.  
- 📌 **Performance Analysis:** Comparisons with PI controllers under various scenarios.  

## 🔧 Getting Started
Clone the repository and follow the setup instructions to reproduce the results presented in the study. Contributions and discussions are welcome!  

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
