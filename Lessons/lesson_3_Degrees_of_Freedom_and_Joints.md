# 🦿 Lesson 3: How Robots Move – Degrees of Freedom (DoF) & Joints

Now that you know what robots are made of, let’s understand **how they move**. Just like your arm bends at the elbow or rotates at the shoulder, robots move using joints and limbs.

---

## 🧠 Core Idea

Robots move through a combination of **joints** and **links**, and their range of movement is defined by **Degrees of Freedom (DoF)**.

> Every independent way a robot can move is a "degree of freedom".

---

## 🧍 Analogy: "Your Arm as a Robot Arm"

* **Shoulder**: Rotates → 3 DoF (up/down, front/back, rotate)
* **Elbow**: Bends → 1 DoF (flex/extend)
* **Wrist**: Twists and tilts → 2-3 DoF

So your full arm has **6-7 DoF** total. That’s why it's so flexible!

---

## 🔩 What Are Joints?

Joints connect robot parts (called **links**) and let them move relative to each other.

### Types of Joints:

| Joint Type | Symbol | Motion Type    | Example           | DoF |
| ---------- | ------ | -------------- | ----------------- | --- |
| Revolute   | R      | Rotational     | Elbow, wheel axis | 1   |
| Prismatic  | P      | Linear         | Sliding drawer    | 1   |
| Spherical  | S      | Multi-axis rot | Human shoulder    | 3   |
| Fixed/None | -      | No motion      | Welded joint      | 0   |

---

## 🎯 Degrees of Freedom (DoF)

A robot's total DoF = sum of all joint DoFs.

* A **2-joint robot arm** with 2 revolute joints → 2 DoF
* A **mobile robot** with wheels → usually 3 DoF (x, y, rotation)
* A **humanoid arm** → \~6 DoF for free movement in space

> Rule of Thumb: The more DoF, the more flexible the robot—but also harder to control!

---

## 📐 Simple DoF Examples

* **Door hinge**: 1 DoF (rotates open/close)
* **Car seat slider**: 1 DoF (moves forward/backward)
* **Drone**: 6 DoF (moves in 3D + rotates pitch/yaw/roll)

---

## 🧪 Exercise 3: Build a Paper Arm

Take paper, straws, or cardboard and create a **2-joint arm**:

* Add a hinge (revolute joint) at elbow and shoulder
* See how many positions it can reach
* Try sketching its **workspace** (the area it can reach)

Document your project in `/exercises/robotic_arm_models.md`

---

## ✅ Mini Quiz

1. What is a joint in robotics?
2. What’s the difference between revolute and prismatic joints?
3. How many DoF does a drone typically have?

---

## 🏁 Summary

* **Joints = Movement points**
* **DoF = Number of independent movements**
* More DoF = More flexibility, but more complexity

➡️ Up next in Lesson 4: "Robot Types & Kinematic Structures – Serial vs Parallel"
