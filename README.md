# 🚀 Smart Elevator Control System – ER Diagram (Assignment 5 – Final)

## 📌 Project Overview

This assignment presents the database design (ER Diagram) for a smart elevator control system used in large commercial buildings such as corporate towers, malls, airports, hospitals, and high-rise residential complexes.

The system is designed to efficiently manage multiple elevators operating across multiple buildings, handling real-time floor requests, ride assignments, and operational tracking.

🔗 **ER Diagram Link:**
[https://app.eraser.io/workspace/ulnYvb7yGOJ0q3xz8fQO?origin=share](https://app.eraser.io/workspace/ulnYvb7yGOJ0q3xz8fQO?origin=share)

---

## 🏢 Key Features

* Multi-building support
* Multiple elevators per building
* Floor-level request tracking
* Intelligent ride assignment
* Elevator status monitoring
* Maintenance tracking
* Ride history logging
* Alert and fault management

---

## 🧱 Entities Included

* Users
* Buildings
* Floors
* Elevator Shafts
* Elevators
* Floor Requests
* Ride Assignments
* Ride Logs
* Elevator Status Logs
* Maintenance Records
* Elevator Alerts

---

## 🔗 Core Relationships

* One building contains multiple floors, shafts, and elevators
* One elevator serves multiple requests and rides
* One user can generate multiple floor requests
* Each request is assigned to one elevator
* Each elevator performs multiple rides
* Floors are connected to ride logs as start and end points
* Maintenance and alerts are tracked per elevator

---

## 📊 Design Highlights

* Separation of static data (buildings, elevators) and dynamic data (requests, rides)
* Proper use of primary keys and foreign keys
* Support for real-time operations and historical analytics
* Scalable structure suitable for large infrastructure systems

---

## 📁 Files Included

* ER Diagram image (PNG/PDF)
* Source diagram file (Draw.io / Excalidraw / etc.)

---

## 🎯 Use Cases Supported

* Track elevator usage and performance
* Monitor pending and completed requests
* Identify busiest elevators
* Analyze ride history
* Manage maintenance and alerts

---

## 🛠️ Tools Used

* Draw.io / Excalidraw (for diagram design)

---

## 📌 Note

This assignment focuses only on database design (ERD).
No backend APIs or SQL queries are included.

---

## 👨‍💻 Author

Sudhanshu Mundhe
