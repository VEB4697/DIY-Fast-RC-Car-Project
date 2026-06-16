# 🏎️ DIY Fast RC Car Project

Welcome to the **DIY Fast RC Car Project** repository! This project contains all the necessary fabrication files—including 3D printing models (STL/3MF) and laser cutting profiles (DXF)—to build a high-performance, custom-designed radio-controlled (RC) car. 

By combining 3D-printed mechanical components (steering blocks, gearbox, mounts) with a rigid, laser-cut chassis plate, this design achieves a balance of structural strength, agility, speed, and ease of assembly.

---

## 📂 Repository Directory Structure

For easy navigation, here is the complete directory structure and the purpose of each file:

```directory
DIY Fast RC Car Project/
│
├── 📁 3D printing Files/               # 3D printable components
│   ├── 📁 Gear Box/                    # Gearbox housing & drivetrain gears
│   │   ├── Left AxlePart.stl           # Left axle housing/mount
│   │   ├── Right Axle Part.stl         # Right axle housing/mount (STL format)
│   │   ├── Right Axle Part.3mf         # Right axle housing/mount (3MF format)
│   │   ├── pinion gear_..._layer.stl   # Motor pinion gear (100% infill required)
│   │   └── spur gear_..._layer.stl     # Main spur gear (100% infill required)
│   │
│   └── 📁 Steering/                    # Steering knuckles, mounts, & suspension arms
│       ├── Angle mount.stl             # Bracket for steering link angles
│       ├── Left Wing Part 1.stl        # Left front suspension wing (part 1)
│       ├── Left Wing Part 2.stl        # Left front steering knuckle/wing (part 2)
│       ├── Right Wing part1.stl        # Right front suspension wing (part 1)
│       ├── Right Wing Part 2.stl       # Right front steering knuckle/wing (part 2)
│       ├── Mount x 5.stl               # Standard mounts for linkages (print 5 copies)
│       ├── Servo Mount.stl             # Bracket for mounting the steering servo
│       └── Spacer.stl                  # Suspension and linkage spacer
│
├── 📁 Laser Cutting Files/             # Flat plate designs for laser cutting
│   ├── Base.dxf                        # Main chassis plate (chassis deck)
│   └── Steering.dxf                    # Steering assembly plate / linkage top plate
│
└── .gitignore                          # Standard git ignore rules for clean tracking
```

---

## 🔧 Component Details & Fabrication Guides

### 1. 🛠️ Laser Cutting Files (`/Laser Cutting Files`)
These DXF files are meant for laser cutting or CNC routing. 
* **Recommended Materials**: 2.0mm to 3.0mm Carbon Fiber, Acrylic, Delrin (POM), or 3.0mm Aluminum for maximum rigidity.
* **Files**:
  * **[Base.dxf](file:///d:/DIY%20Fast%20RC%20Car%20Project/Laser%20Cutting%20Files/Base.dxf)**: The main bottom chassis plate. It serves as the backbone of the car where the battery, ESC, receiver, servo mount, and gearbox are bolted.
  * **[Steering.dxf](file:///d:/DIY%20Fast%20RC%20Car%20Project/Laser%20Cutting%20Files/Steering.dxf)**: The steering linkage deck or top plate. It provides support for the steering linkages and adds torsional rigidity to the front end.

### 2. ⚙️ Gearbox & Drivetrain (`/3D printing Files/Gear Box`)
Contains the gears and axle parts that transmit power from the electric motor to the drive wheels.
* **Files**:
  * **[Left AxlePart.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Left%20AxlePart.stl)** / **[Right Axle Part.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Right%20Axle%20Part.stl)** (and [3MF](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/Right%20Axle%20Part.3mf)): Rear axle support housings that anchor the spinning axles and enclose the gear meshes.
  * **[pinion gear_100%_Infill_fine_layer.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/pinion%20gear_100%_Infill_fine_layer.stl)**: Small motor gear.
  * **[spur gear_100%_Infill_fine_layer.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Gear%20Box/spur%20gear_100%_Infill_fine_layer.stl)**: Large spur gear.
* **3D Printing Tips**:
  * **Material**: Use **Nylon** or **PETG** for the gears to withstand friction and heat. **PLA+** can be used for prototyping but may wear out quickly under high RPM.
  * **Infill**: **100% Infill** is mandatory for both the pinion and spur gear.
  * **Resolution**: Use **0.1mm - 0.12mm layer height** (fine layer) for precise tooth engagement.

### 3. 转向/悬挂 Steering Assembly (`/3D printing Files/Steering`)
Controls the direction of the front wheels and provides suspension support.
* **Files**:
  * **[Servo Mount.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Servo%20Mount.stl)**: Holds the steering servo motor securely to the chassis.
  * **Left/Right Wing Parts ([1](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Left%20Wing%20Part%201.stl) & [2](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Left%20Wing%20Part%202.stl))**: Steering knuckles and control arms.
  * **[Mount x 5.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Mount%20x%205.stl)**: Standard brackets; print 5 copies to secure steering linkages and upper suspension parts.
  * **[Angle mount.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Angle%20mount.stl)** & **[Spacer.stl](file:///d:/DIY%20Fast%20RC%20Car%20Project/3D%20printing%20Files/Steering/Spacer.stl)**: Alignments and hardware spacers.
* **3D Printing Tips**:
  * **Infill**: 40-50% Gyroid infill with at least 4-5 walls (perimeters) for impact strength during crashes.
  * **Material**: **PETG** or **ABS/ASA** are recommended for their impact resistance and slight flexibility.

---

## 🏁 Outro: Bring It to the Track!

Building your own high-speed RC car from scratch is a highly rewarding engineering project. It bridges the gap between digital CAD design and physical mechanical assembly. 

### What's Next?
1. **Fabricate the Chassis**: Send the `Base.dxf` and `Steering.dxf` files to a local laser-cutting service or cut them on a CNC router.
2. **3D Print the Parts**: Load the STL files into your slicer of choice (like Cura or PrusaSlicer). Ensure you follow the material and infill recommendations, especially for the high-wear gears.
3. **Source the Electronics**:
   * **Motor & ESC**: A brushless motor setup (e.g., 3650 motor with a 60A ESC) for extreme speed, or a brushed motor (e.g., 540 size) for beginners.
   * **Servo**: Standard 1/10th scale steering servo (e.g., 20kg high torque).
   * **Battery**: 2S or 3S LiPo battery.
   * **Transmitter & Receiver**: Any standard 2.4GHz 2-channel or 3-channel radio system.
4. **Assembly**: Use M3 and M4 machine screws, locknuts, and bearings (typically MR115 or similar depending on axle size) to assemble the rotating and structural parts. Use grease/lubricant on the plastic gears to extend their lifespan and reduce noise.

*Happy building, and see you on the racetrack!* 🚗💨
