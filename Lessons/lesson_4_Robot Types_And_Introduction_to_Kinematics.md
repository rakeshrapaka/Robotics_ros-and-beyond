 # 🤖 Day 4: Robot Types & Introduction to Kinematics

This lesson lays the groundwork for understanding how different robots move and how we mathematically describe and control that motion (kinematics).

---

## 🧠 1. Robot Classification by Configuration

Understanding robot types is important because the mechanical design influences the motion capabilities and use cases.

| **Robot Type**         | **Example**             | **Motion Type**   | **Common Use**                    |
| ---------------------- | ----------------------- | ----------------- | --------------------------------- |
| Cartesian              | Linear XYZ rails        | Prismatic joints  | CNC machines, pick-and-place      |
| Cylindrical            | Rotational + linear     | R + P + P         | Assembly, painting                |
| Spherical (Polar)      | Rotating base + arms    | R + R + P         | Manipulation, lab robots          |
| SCARA                  | Horizontal rotary arms  | R + R + P + R     | Assembly (fast horizontal motion) |
| Articulated (Revolute) | Industrial robot arms   | R + R + R + ...   | Welding, painting, humanoids      |
| Delta / Parallel       | Triangular linkage arms | Complex combo     | High-speed pick-and-place         |
| Mobile Robots          | Wheeled or legged bases | Platform mobility | AGVs, drones, rovers              |

> 🔧 **R = Revolute (rotational joint), P = Prismatic (sliding joint)**

---

## 🧠 2. Kinematics Basics

* **Kinematics** = Study of motion **without considering forces**.
* Two major parts:

  * **Forward Kinematics (FK):** Given joint parameters, find end-effector position.
  * **Inverse Kinematics (IK):** Given end-effector position, find joint parameters.

We'll dive into FK and IK in upcoming sessions, but today's focus is to connect robot **type** with **degrees of freedom and motion style**.

---

## 🎓 Why This Matters

* The type of robot defines how we model and control it.
* Kinematic models change depending on configuration (e.g., SCARA vs Articulated).

---

## 📌 Exercise: Identify Robot Types

Try identifying the robot type for:

* A 3D printer
* A UR5 robot arm
* A CNC milling machine
* A drone

---

## 🎯 Day 4 Learning Goals

* Classify robots based on their structure.
* Understand revolute vs prismatic joints in real systems.
* Introduce the purpose of kinematics in robotics.

---
