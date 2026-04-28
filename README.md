# 6 Degrees of Freedom (6DoF)
---

### Student Information
* **Name:** Muhammad Muzammil Hussain
* **Seat No:** B23110006108
* **Section:** A

---

## 1. Concept
**6 Degrees of Freedom (6DoF)** allows a rigid body to move freely in 3D space using three translational and three rotational axes.

### Movement Breakdown:
* **Translation (Linear):** Sway (X), Heave (Y), and Surge (Z).
* **Rotation (Angular):** Pitch (X), Yaw (Y), and Roll (Z).

---

## 2. HCI Principles
* **Direct Manipulation:** Real-time object control via keyboard inputs.
* **Visibility:** Immediate visual updates of the cube's position and orientation.
* **Mapping:** Logical key assignments (Arrows/XYZ) for intuitive navigation.

---

## 3. Technical Details
* **Renderer:** Three.js (WebGL) for 3D environment rendering.
* **Material:** `MeshStandardMaterial` in **Deep Purple (#4B0082)**.
* **Logic:** `keydown` listeners update `position` and `rotation` vectors instantly.
