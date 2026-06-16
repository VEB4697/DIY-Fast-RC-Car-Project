# 🖨️ 3D Printing Files

This directory contains all the 3D printable STL and 3MF models required for the DIY Fast RC Car. The files are divided into two subdirectories based on their mechanical subsystem:

## 📁 Subdirectories

1. **[Gear Box/](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/)**
   * Contains transmission components including pinion gears, spur gears, and axle housings.
   * **Requires**: High durability materials (Nylon/PETG), 100% infill, and fine layer heights (0.1mm - 0.12mm).

2. **[Steering/](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/)**
   * Contains steering brackets, knuckles, suspension wings, spacers, and servo mounts.
   * **Requires**: High impact-resistant materials (PETG/ABS/ASA), 40-50% infill, and standard layer heights (0.2mm).

---

## 💡 Recommended Print Settings

| Component Type | Recommended Material | Infill Density | Infill Pattern | Layer Height | Shells/Perimeters | Supports Needed? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Gears** | Nylon (PA), PETG, or Delrin | 100% | Concentric / Solid | 0.10 - 0.12 mm | 5+ | No |
| **Axle Housings** | PETG, ABS, PLA+ | 50% | Gyroid | 0.20 mm | 4 | Yes (for axle cavities) |
| **Steering Wings/Knuckles** | PETG, ABS, ASA | 50% | Gyroid | 0.20 mm | 5 | Yes (for overhangs) |
| **Mounts & Spacers** | PLA+, PETG | 40% | Grid | 0.20 mm | 3 | No |

### 🛠️ Printing Tips:
* **Gears**: Do not use standard PLA for the drivetrain gears; they will melt/strip quickly due to frictional heat at high RPM. Nylon is the gold standard for printed gears.
* **Orientation**: Orient steering wings flat on the print bed to maximize strength along the layer lines. Avoid placing shear stress perpendicular to layer lines.
* **Tolerances**: Print a small test piece first to check screw-hole sizing. Holes are sized for M3 and M4 screws, which can be tapped directly or secured with heat-set threaded inserts.
