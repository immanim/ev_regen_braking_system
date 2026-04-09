🚗 EV Regenerative Braking System using MATLAB Simulink

📖 Project Overview

This project presents the modeling and simulation of a Regenerative Braking System (RBS) for an electric vehicle using MATLAB Simulink and Simscape Electrical.

Regenerative braking improves energy efficiency by converting the vehicle’s kinetic energy into electrical energy during braking and feeding it back toward the energy source.

---

🎯 Objectives

- Model an electric vehicle drivetrain using a DC motor
- Simulate acceleration and braking conditions
- Demonstrate regenerative braking behavior
- Analyze current and speed characteristics during operation

---

⚙️ System Architecture

The model consists of the following key components:

- 🔋 Battery (DC Power Source)
- ⚡ DC Motor (Drive + Generator mode)
- 🔄 Current Sensor (Electrical analysis)
- 🌀 Rotational Motion Sensor (Speed measurement)
- ⚙️ Inertia (Vehicle load representation)
- 🛑 Rotational Damper (Friction effects)
- 🔁 Simulink-PS & PS-Simulink Converters

---

🔄 Working Principle

🚀 Acceleration Mode

- Battery supplies electrical energy to the DC motor
- Motor converts electrical energy into mechanical rotation
- Vehicle speed increases

🛑 Braking Mode (Regenerative)

- Motor operates as a generator
- Mechanical energy is converted back into electrical energy
- Current direction reverses (negative current observed)
- Energy is recovered instead of being wasted

---

📊 Simulation Results

The following observations confirm system behavior:

- ✔ Motor speed varies according to input signals
- ✔ Current becomes negative during braking, indicating regenerative action
- ✔ Smooth transition between motoring and generating modes

---

🧪 Key Insights

- Regenerative braking significantly improves system efficiency
- Inertia plays a crucial role in energy recovery
- Proper control of braking input is required for stable operation

---

🚀 Future Enhancements

- Implement State of Charge (SOC) estimation
- Add bidirectional DC-DC converter / H-Bridge
- Integrate real-world EV drive cycles (UDDS, WLTP)
- Extend model to BLDC or PMSM motor

---

🛠️ Tools & Technologies

- MATLAB Simulink
- Simscape Electrical
- Control System Modeling

---

👨‍💻 Author

IMMANUVEL M
Engineering Student | EV & Simulation Enthusiast

---

⭐ Acknowledgment

This project was developed as part of academic learning in electric vehicle systems and simulation techniques.

---
