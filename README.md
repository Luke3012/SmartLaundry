# 🧺 SmartLaundry

SmartLaundry is an **IoT-enabled laundry management system** designed to automate and optimize washing and drying cycles, manage schedules, and provide real-time monitoring via a connected controller.

Developed as part of a university **Software Engineering** course, the system follows structured **requirements analysis** and **architectural design** methodologies.

---

## 📋 Overview

### 🎯 Purpose
The system aims to:
- Automate the scheduling of washing and drying cycles.
- Allow users to remotely monitor and control laundry operations.
- Optimize resource usage (energy, water, time).
- Provide error detection and notifications.

### 👥 Target Users
- **End-users** operating washing/drying machines.
- **System administrators** configuring and maintaining the SmartLaundry network.

---

## 🔧 Functional Requirements (FR)
- **FR1:** Schedule washing/drying cycles.
- **FR2:** Start, pause, or stop cycles remotely.
- **FR3:** Monitor machine status in real time.
- **FR4:** Receive alerts for cycle completion or errors.
- **FR5:** Manage multiple machines from a single controller.
- **FR6:** Provide energy and water consumption statistics.

---

## 🛠 System Architecture

The system is divided into:
- **Smart Controller Subsystem** – Central unit managing communication and schedules.
- **Washer/Dryer Subsystem** – Machines equipped with IoT modules.
- **User Interface Subsystem** – Mobile or web-based control interface.
- **Scheduler** – Optimizes cycle execution according to user preferences and constraints.

**Design Patterns & Concepts:**
- **MVC (Model-View-Controller)** for UI and control separation.
- **Observer** for real-time updates between subsystems.
- **Modular design** for scalability and maintainability.

---

## 📐 Design Model Highlights

- **Subsystem Diagram:** Shows high-level architecture and communication flow.
- **Class Diagram:** Defines key entities like `Scheduler`, `Cycle`, `Machine`, `Controller`.
- **Activity Diagrams:** Describe the workflows for scheduling, washing/drying, and control logic.
- **Sequence Diagrams:** Illustrate interactions between user, controller, and machines.

---

## 📸 Diagrams

### Use Case Diagram
![Use Case Diagram](Diagramma%20casi%20uso/CasiUso.jpeg)

### Class Diagram (Simplified)
![Class Diagram](Diagramma%20delle%20classi/SmartLaundryTest.jpeg)

### Subsystem Diagram
![Subsystem Diagram](Diagramma%20sottosistema/Diagrammasottosistema.jpeg)

### Activity Diagram – Scheduler
![Scheduler Activity Diagram](Diagrammi%20delle%20attività/DiagrammadelleattivitaScheduler.jpeg)

### Activity Diagram – Washing/Drying
![Washing/Drying Activity](Diagrammi%20delle%20attività/DiagrammadelleattivitàAsciugatura_Lavaggio.jpeg)

### Sequence Diagram – Example
![Sequence Diagram 1](Diagrammi%20delle%20sequenze/Diagrammasequenza1.jpeg)
![Sequence Diagram 2](Diagrammi%20delle%20sequenze/Diagrammasequenza2.jpeg)

---

## 🚀 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SmartLaundry.git
