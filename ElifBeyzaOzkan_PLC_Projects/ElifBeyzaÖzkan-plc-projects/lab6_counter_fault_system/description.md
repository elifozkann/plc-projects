# Counter Fault System

## 🧩 Overview
This project implements a production control system that uses a **CTU counter** to track product counts and integrates alarm, reset, and timing functions for fault handling.  
The system simulates a simplified manufacturing line using a Siemens S7-1200 PLC programmed in TIA Portal.

## ⚙️ System Description
- The system starts with a **Start** button and can be stopped or reset at any time.  
- A **CTU (Count Up)** block tracks the number of products processed.  
- When the counter reaches a predefined value, an indicator LED or buzzer signals that the production limit has been reached.  
- A **Reset** button clears the counter and resets the system state.  
- A **TON timer** is integrated for time-based operations (such as alarm delays or system reset conditions).  
- The **HMI interface** displays live counter values, system status, and alarm indicators.

## 💻 Technical Components
- **PLC:** Siemens S7-1200  
- **Programming Environment:** TIA Portal  
- **Programming Language:** Ladder Diagram (LD)  
- **HMI:** Siemens SIMATIC Panel  
- **Inputs:** Start, Stop, Reset  
- **Outputs:** Counter Display, LEDs, Buzzer, Lamp

## 🧠 Key Learning Outcomes
- Understanding of **counter-based automation control (CTU)**  
- Integration of **timers (TON)** with counting logic  
- Implementation of **fault detection and reset mechanisms**  
- Visualization of system states through **HMI integration**

### HMI Interface
![alt text](image.png)