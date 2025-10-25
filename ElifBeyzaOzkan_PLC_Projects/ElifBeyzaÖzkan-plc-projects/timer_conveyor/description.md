# Timer Conveyor

## 🧩 Overview
This project focuses on developing a conveyor belt system controlled by a PLC using time-based logic.  
The system utilizes TON timers and safety mechanisms such as an emergency stop button to manage and monitor the conveyor’s motion.

## ⚙️ System Description
- The conveyor starts when the **Start** button is pressed.  
- The **Emergency Stop** button immediately halts the system at any time.  
- A **TON timer** is used to control the belt’s operation duration (e.g., 15 seconds per cycle).  
- The belt motor runs for a specific time interval and automatically stops when the timer expires.  
- System status (belt running, stopped, or emergency) is displayed on an **HMI interface**.

## 💻 Technical Components
- **PLC:** Siemens S7-1200  
- **Programming Environment:** TIA Portal  
- **Programming Language:** Ladder Diagram (LD)  
- **HMI:** Siemens SIMATIC Panel  
- **Inputs:** Start, Stop, Emergency Stop  
- **Outputs:** Conveyor Motor, Timer Lamp, Indicator LEDs

## 🧠 Key Learning Outcomes
- Implementation of **time-based process control** using TON timers  
- Integration of **emergency stop safety logic**  
- Design of an **HMI interface** for real-time process monitoring  
- Testing and validation through **PLCSIM simulation**

## 🖼️ Project Images

## 🧩 Overview
This project focuses on developing a conveyor belt system controlled by a PLC using time-based logic.  
The system utilizes TON timers and safety mechanisms such as an emergency stop button to manage and monitor the conveyor’s motion.

## ⚙️ System Description
- The conveyor starts when the **Start** button is pressed.  
- The **Emergency Stop** button immediately halts the system at any time.  
- A **TON timer** is used to control the belt’s operation duration (e.g., 15 seconds per cycle).  
- The belt motor runs for a specific time interval and automatically stops when the timer expires.  
- System status (belt running, stopped, or emergency) is displayed on an **HMI interface**.

## 💻 Technical Components
- **PLC:** Siemens S7-1200  
- **Programming Environment:** TIA Portal  
- **Programming Language:** Ladder Diagram (LD)  
- **HMI:** Siemens SIMATIC Panel  
- **Inputs:** Start, Stop, Emergency Stop  
- **Outputs:** Conveyor Motor, Timer Lamp, Indicator LEDs

## 🧠 Key Learning Outcomes
- Implementation of **time-based process control** using TON timers  
- Integration of **emergency stop safety logic**  
- Design of an **HMI interface** for real-time process monitoring  
- Testing and validation through **PLCSIM simulation**

### HMI Interface
![alt text](image.png)