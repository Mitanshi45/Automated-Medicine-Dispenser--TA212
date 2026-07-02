# Automated-Medicine-Dispenser--TA212
Motor-driven automated medicine dispenser (TA212 ME project) — bevel-gear rotating disc mechanism, torque-sized drivetrain, CAD-drafted &amp; fabricated in mild steel/PLA.


A terminal-driven mechanical prototype built as part of **TA212 Lab (Manufacturing Engineering)**, IIT Kanpur, 2nd Semester 2025-26. The system automates timed medicine dispensing for patients, particularly the elderly, using a motor-driven rotating disc mechanism.

## Team

| Name | Roll No. |
|---|---|
| Mudita Jalan | 240665 |
| Mitanshi Khandelwal | 240655 |
| Paveet Singh Saluja | 240742 |
| Palak Meena | 240720 |
| Kanhaiya Kumar | 240515 |
| Manish Gurjar | 240621 |
| M Rohith Kumar | 240671 |

## Objective

Develop an automated smart medicine dispenser using a motor-driven mechanism to ensure timely and accurate medication intake, addressing a real accessibility need for elderly and mobility-limited patients.

## Design & Mechanism

The dispenser consists of a rotating **medicine holder disc** driven via a **vertical shaft, bevel gear pair, and horizontal drive shaft** connected to a single motor. A **slope and tray assembly** guides dispensed medicine to a collection point. The full assembly is built on a **400×400mm base plate** with L-shaped vertical and horizontal steel supports holding the mechanism in place.

**Subsystems:**
- Base Plate & Support Structure (vertical/horizontal L-supports, shaft holder)
- Rotating Disc Mechanism (medicine holder, vertical shaft, blades)
- Drive Train (bevel gear pair, horizontal shaft, motor clamp)
- Dispensing Path (slope, tray)

## Engineering Analysis

**Motor Torque Sizing** — Calculated using moment of inertia of all rotating components (blades, rod, bevel gear):
- Total moment of inertia: I_total = 6.83 × 10⁻³ kg·m²
- Required torque (with 8× combined factor for efficiency, friction, and FOS): **M_motor = 0.0856 N·m**
- Motor selected (rated 1 N·m) confirmed sufficient with margin
- Required power: **0.2687 W**

**Bevel Gear Design** — Straight bevel gear pair (Module 2, 20 teeth, 90° shaft angle) with calculated face angle (49.045°), root cone angle (39.948°), and pitch cone geometry per standard gear design tables.

## Manufacturing

15 distinct machined parts fabricated from **mild steel, PLA, and GI sheet** using:
- Cutting, drilling, milling, and lathe work (mild steel components)
- 3D printing (holder, motor clamp)
- Welding (blades, slope)

All part-level isometric drawings, dimensions, and tolerances were modeled and drafted individually by team members and compiled into a full assembly drawing.

## Cost Analysis

| Category | Cost (Rs.) |
|---|---|
| Raw Material | 967 |
| Machinery | 4,850 |
| Labour | 11,918 |
| Electronics (single motor) | 2,500 |
| **Total** | **20,235** |

## Future Improvements

- Scale the prototype for multi-user hospital environments
- Integrate IoT capabilities for remote monitoring and caregiver alerts

## Tools & Skills

`Mechanical Design` · `CAD Drafting` · `GD&T` · `Torque & Power Calculation` · `Bevel Gear Design` · `Manufacturing Processes (Milling, Lathe, 3D Printing, Welding)` · `Cost Estimation`
