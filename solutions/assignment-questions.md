# 📝 Assignment Solutions: Quadruped Robot Dog Mechanical Design

This document covers the primary mechanical design specifications and engineering solutions for the quadruped robot dog project.

---

## ⚙️ Technical Questions & Solutions

### 1. Body Shape and Structure
> **Answer:** > The robot features a rectangular and hollow chassis design constructed from lightweight polymers to protect internal electronics while maintaining structural rigidity.

### 2. Leg Design
> **Answer:** > The legs are designed using a segmented, multi-link bio-inspired structure that replicates canine anatomy to ensure efficient load distribution during locomotion.

### 3. Number of Joints and Degrees of Freedom (DoF)
> **Answer:** > The robot utilizes a total of 8 Degrees of Freedom ($8\text{ DoF}$), allocating 2 active revolute joints per leg (hip and knee) to allow smooth forward and lateral movement.

### 4. Motor Selection
> **Answer:** > High-torque, metal-gear digital servo motors were selected for the joints due to their precise position feedback, high holding torque, and compact form factor.

### 5. Preliminary Torque Calculation for a Joint
> **Answer:** > The required joint torque ($\tau$) was calculated using the static hold formula $\tau = F \cdot r$, where $F$ is the peak ground reaction force ($m \cdot g$) and $r$ is the maximum linkage moment arm length.

### 6. Stability and Center of Gravity (CoG)
> **Answer:** > Stability is achieved by placing heavy components like the battery pack at the lowest physical point within the chassis, keeping the Center of Gravity (CoG) strictly inside the support polygon formed by the feet.

### 7. Proposed Gait/Walking Method
> **Answer:** > A static crawl gait sequence (lifting one leg at a time while keeping three feet on the ground) was adopted to ensure a safe, continuously stable margin during locomotion.

### 8. Anticipated Mechanical Issues
> **Answer:** > Anticipated mechanical challenges include joint backlash, high structural friction at linkage friction points, and potential dynamic instability due to structural vibrations during faster gait transitions.

---

## 🔍 Structural Reference Matrix

| Design Parameter | Engineering Approach | Implementation Metric |
| :--- | :--- | :--- |
| **Total System DoF** | Quadruped configuration | $8\text{ Degrees of Freedom}$ total |
| **Symmetry Axis** | Central longitudinal plane | Mirrored components via Tinkercad Orthographic alignment |
| **Gait Type** | Static Crawl Sequence | $3\text{-leg}$ support polygon maintenance |
