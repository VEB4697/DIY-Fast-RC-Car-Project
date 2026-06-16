# ⚙️ Gear Box & Drivetrain Components

This folder contains the 3D files for the power transmission system. It houses the motor mount, axle structures, and mechanical gears that translate motor rotation into high-speed wheel rotation.

## 📂 File Directory

* **[Left AxlePart.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Left%20AxlePart.stl)**:
  * Left-side mounting housing for the rear drivetrain axle.
* **[Right Axle Part.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Right%20Axle%20Part.stl)** / **[Right Axle Part.3mf](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Right%20Axle%20Part.3mf)**:
  * Right-side mounting housing. Provided in both standard STL format and 3MF format (which preserves orientation, scale, and multi-part data).
* **[pinion gear_100%_Infill_fine_layer.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/pinion%20gear_100%_Infill_fine_layer.stl)**:
  * The pinion gear that mounts directly to the motor shaft. Features a small tooth profile designed to mesh perfectly with the spur gear.
* **[spur gear_100%_Infill_fine_layer.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/spur%20gear_100%_Infill_fine_layer.stl)**:
  * The main drive spur gear. Transmits power from the pinion gear to the drive shaft/axle.

---

## ⚙️ Printing & Assembly Specifications

### 1. Gear Mesh & Printing
* **Print Resolution**: Set to **0.1mm** or **0.12mm** layer height. The teeth on these gears are small; printing with standard 0.2mm layers will result in rough mesh profiles that lead to rapid wear and noise.
* **Infill**: Set to **100%** (Solid) for both gears. This ensures that the teeth do not shear off under high motor torque.
* **Material**: 
  * **Best**: Nylon (PA12 or PA6-CF).
  * **Alternative**: PETG (use low print speeds for optimal layer adhesion).
  * **Prototyping**: PLA/PLA+ (only for low-speed testing).

### 2. Post-Processing & Hardware
* **Bearings**: The Axle housings are designed to fit standard ball bearings (check fitment with your chosen bearings, typical size is 5x11x4mm or 5x10x4mm).
* **Grease/Lubrication**: Apply a thin coating of synthetic grease (like white lithium grease or silicone-based grease) to the spur and pinion gears. This significantly reduces noise and extends the lifespan of 3D-printed gears.
* **Tuning**: Adjust the gear mesh backlash so there is a tiny amount of wiggle room between teeth (about the thickness of a piece of paper). If the mesh is too tight, it will strain the motor and melt the gears; if too loose, it will strip the teeth.
