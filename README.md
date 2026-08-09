# 555-Timer-PWM-DC-Motor-Speed-Controller
**555 timer-based PWM DC motor speed controller designed and developed in KiCAD for practical motor speed control.
# DC Motor Speed Controller ⚙️

A PCB design project for controlling the speed of a DC motor using a **555 timer-based PWM circuit**. The schematic and PCB were designed in **KiCad**, with the goal of creating a compact and practical motor speed controller.

## 🔧 Project Overview

The controller uses an **NE555P timer** to generate a PWM signal. A potentiometer is used to adjust the PWM duty cycle, which controls the power delivered to the motor and therefore allows its speed to be varied.

The output stage uses a **TIP122 Darlington transistor** to drive the motor, while a **1N4007 diode** provides protection against the motor's inductive voltage spikes.

## 🧩 Main Components

| Component        | Value / Part          |
| ---------------- | --------------------- |
| Timer IC         | NE555P                |
| Power Transistor | TIP122                |
| Potentiometer    | 100kΩ                 |
| Diodes           | 1N4007                |
| Capacitors       | 100nF, 1000µF         |
| Resistors        | 1kΩ, 2.2kΩ            |
| Indicators       | LED                   |
| Connectors       | 2-pin screw terminals |

## 🛠️ Tools Used

* **KiCad 10**
* Schematic Editor
* PCB Editor
* PCB Layout & Routing
* Gerber Generation

## 📂 Repository Contents

```text
DC-Motor-Speed-Controller/
│
├── DC Motor Speed Controller.kicad_sch
├── DC Motor Speed Controller.kicad_pcb
│
├── Gerbers/
│   └── PCB manufacturing files
│
├── Images/
│   ├── PCB_Front.png
│   └── PCB_Back.png
│
└── README.md
```

## 📚 What I Learned

This project helped me gain practical experience with:

* 555 timer circuits
* PWM-based motor speed control
* Transistor-based motor driving
* Flyback protection for inductive loads
* Schematic design in KiCad
* PCB component placement
* PCB routing
* Generating Gerber files
* Preparing a PCB design for manufacturing

## 🚀 Future Improvements

Possible improvements for a future version include:

* Adding better motor current protection
* Adding a fuse or dedicated protection stage
* Improving thermal management of the power transistor
* Adding reverse-polarity protection
* Testing and documenting the actual motor voltage, current and speed range

## ⚠️ Safety

This controller is intended for suitable **low-voltage DC motor applications**. Use an appropriate DC power supply and ensure that the motor current does not exceed the capabilities of the switching and PCB components.

Do not connect this circuit directly to AC mains.

---

## 👨‍💻 Author

**Aditya Joshi**

B.Tech ECE (Semiconductor)

Interested in **PCB Design, Electronics, VLSI and Embedded Systems**.
