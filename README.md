# 🤖 RR Manipulator - Advanced Robotic Arm Design

An advanced **Revolute-Revolute (RR) Manipulator** built for precision drawing and robotic motion planning. This project integrates advanced mechanical design with control theory to push the boundaries of intelligent, compact, and efficient robotic arms.

---

## 🏫 Project Background

Developed as part of a **Robotics Lab Course**, this project addresses key gaps in robotic manipulator design:

- ✅ Limited exploration of non-conventional inverse kinematics methods in RR arms  
- ✅ Need for unified integration of **motion control**, **path planning**, and **self-collision avoidance**

> 📄 See course objectives and details in the [project documentation](./The_RR_manipuIator.pdf)

---

## 💡 Project Objectives

- Develop a fully functional RR manipulator using advanced CAD techniques  
- Address precision motion challenges using a planetary gear base system  
- Design an end-effector suited for real-time drawing applications

---

## 🧠 My Contribution: Complete CAD Design

I was responsible for **mechanical design and 3D modeling**, including:

- 🔧 Full Mechanical Architecture: From concept to CAD  
- 🧩 Component Integration: Optimal placement for function and stability  
- 🌍 Planetary Gear System: Designed for torque and precision at the base  
- ✍️ Drawing End-Effector: Rack-pinion + servo system for line control  
- 🧱 Assembly Planning: Complete exploded view and fits  
- 📐 Manufacturing Drawings: With tolerances and dimensions

---

## 🧱 Design Architecture

### 🔩 Mechanical Design Overview

| Component           | Description                                                             |
|---------------------|--------------------------------------------------------------------------|
| **Bot Base**         | Planetary gear system for high-torque & precise control                 |
| **Spur Gear Stage**  | Intermediate transmission to the arm                                    |
| **Rack-Pinion**      | Converts rotation to linear motion at the end-effector                  |
| **Drawing Mechanism**| Servo-based pen lift for drawing on flat surfaces                       |

---

## 📷 CAD Model Structure

> ![1. Planetary Gear Animation](images/animation_planetary_gear.gif)

> ![2. End Effector](images/end_effector.png)

> ![3. Full Bot Main](images/full_bot_main.png)

> ![4. Full Bot](images/full_bot.png)

> ![5. Last Arm](images/last_arm.png)

> ![6. Middle Arm](images/middle_arm.png)

> ![7. Planetary Gear - Section View](images/planetary_gear_b.png)

---

## ⚙️ Hardware Components

| SN | Item                | Description                            | Qty | Unit Price (INR) | Total (INR) |
|----|---------------------|----------------------------------------|-----|------------------|-------------|
| 1  | Raspberry Pi 5 (4GB)| Main processing unit                   | 1   | 5799.00          | 5799.00     |
| 2  | 27W USB-C Charger   | Pi power supply                        | 1   | 1094.00          | 1094.00     |
| 3  | 64GB SD Card        | OS & program storage                   | 1   | 599.00           | 599.00      |
| 4  | M995 Servo          | High-torque motors                     | 3   | 298.54           | 895.62      |
| 5  | MG90S Servo         | Precision servo for pen-lift           | 2   | 120.36           | 240.72      |
| 6  | GT2 Belt - 610mm    | Power transmission belt                | 4   | 114.00           | 456.00      |
| 7  | GT2 Belt - 400mm    | Smaller belt for joint movement        | 4   | 86.00            | 344.00      |
| 8  | KFL002 Bearings     | 15mm ID pillow block for support       | 2   | 126.00           | 252.00      |

**Total Cost**: ₹9,680.34

---

## ✨ Design Highlights

### 🌀 Planetary Gear Base

> ![Planetary Gear Close-up](images/planetary_gear_b.png)

- Higher Torque Density  
- Minimal Backlash  
- Compact & Precise  
- Smooth Operation for Heavy Loads

### ✍️ Drawing Mechanism

- Rack-Pinion based precision movement  
- Servo-controlled pen lift  
- Horizontal plane drawing setup  

---

## 🎨 Drawing Application

The RR manipulator was specifically developed for **2D sketching and line-art generation**.  

- 🎯 Precise pen-up/pen-down control  
- 🧾 Consistent stroke quality on flat surfaces  
- 📏 Fine-resolution position tracking

---

## 🗺️ Workspace Coverage

- ✔️ 360° Full Radius Coverage (except base diameter)  
- ✔️ Accurate positioning using high-torque gear systems  
- ✔️ Ideal for complete circular and linear drawing paths

---

## 📋 Design Specifications

### 🔩 Mechanical

- **Base Type**: Planetary Gear  
- **Joint Config**: RR (Revolute-Revolute)  
- **End Effector**: Rack-pinion + Servo  
- **Belts**: GT2 Timing Belt  
- **Drawing Tool**: Pen/Pencil  
- **Workspace**: Circular area minus base footprint  

### ⚙️ Performance

- High-precision motion control  
- Low backlash with planetary gearing  
- Modular and compact mechanical structure  
- Full range movement with end-effector stability

---

## 🔄 Motion Control Flow

```mermaid
graph LR
A[Planetary Gear Base] --> B[Spur Gear System]
B --> C[Rack-Pinion Mechanism]
C --> D[Servo-controlled Pen Lift]
