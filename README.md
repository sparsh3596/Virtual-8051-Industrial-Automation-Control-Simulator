# Virtual 8051 Industrial Automation & Control Simulator

A web-based software simulator that demonstrates **8051-inspired industrial automation and DC motor speed control** using PI/PID controllers, PWM, virtual ADC, sensor feedback, and load disturbances.

## 🚀 Features

* ⚙️ DC motor speed simulation
* 🎛️ PI and PID controller implementation
* 📊 Real-time-style performance graphs
* 🔌 Virtual 10-bit ADC
* ⚡ PWM-based motor control
* 📡 Virtual sensor and signal filtering
* 🔄 Load disturbance simulation
* 📈 Speed, current, PWM, and error monitoring
* 📋 Performance analysis:

  * Steady-state error
  * Overshoot
  * Rise time
  * Settling time
* 💾 CSV data export
* 🌐 Runs directly in a web browser
* 💻 No physical hardware required

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Chart.js**
* Control-system and DC motor mathematical modeling

## 🔬 System Overview

The simulator represents a simplified industrial control loop:

```text
Setpoint
   ↓
PI / PID Controller
   ↓
PWM Control
   ↓
DC Motor Model
   ↓
Speed
   ↓
Virtual Sensor
   ↓
Signal Filtering
   ↓
Virtual ADC
   ↓
Feedback
   └──────────────→ Controller
```

A load disturbance can be introduced during the simulation to observe how the controller responds and restores the motor speed.

## 📊 PI vs PID

The simulator allows PI and PID controllers to be tested under the **same motor and load conditions**. This makes it possible to observe differences in transient response, error correction, and disturbance recovery.

## 🎯 Purpose

The main objective of this project is to provide a **hardware-free learning environment** for understanding the relationship between:

* Embedded systems
* 8051 microcontroller concepts
* Analog sensing
* ADC
* PWM
* DC motor control
* Feedback systems
* PI/PID control
* Industrial automation

## ▶️ How to Run

1. Download or clone this repository.
2. Open the project folder in **VS Code**.
3. Open `index.html`.
4. Run it using a browser or **Live Server**.
5. Configure the controller and motor parameters.
6. Click **Start Simulation**.

No MATLAB, Keil, Proteus, or physical hardware is required.

## 📁 Project Structure

```text
Virtual8051-Industrial-Automation/
│
├── index.html
├── README.md
└── assets/
    └── screenshots/
```

## 🔮 Future Improvements

* Add more 8051 peripheral simulations
* Add temperature and pressure sensor models
* Add automatic controller tuning
* Add additional motor models
* Add data logging and report generation
* Improve real-time simulation visualization

## 👨‍💻 Author

**Sparsh Rastogi**
Electrical & Electronics Engineering | VIT Chennai

---

> **Note:** This is a software simulation project created for educational purposes and does not represent a physical 8051 industrial control system.
