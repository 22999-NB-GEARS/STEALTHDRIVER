# STEALTHDRIVER
KMUTNB GEARS' newly developed transmission system for FTC robots utilizing voron community's galileo 2 extruder system as inspiration.

![image](https://github.com/user-attachments/assets/116e0840-8da3-4fee-a8bf-c89ba448d6c9)


# Preface
Due to the previous motor-mounting block design being outdated, the new **Stealthdriver** (Motor block v2) try to solve the problem of space efficiency and optimization issue from the motorblock v1 that was being used in BABz V2 during its operation in the FTC 2024 Into the deep season.

The **Stealthdriver** was meant to have the aesthetics of a Voron Stealthburner, hence the name are similar as well as its design aspect.

The **Stealthdriver** utilize the same tensioning method as the Galileo 2 directdrive extruder design by JaredC01. Using the same bearing (MR115) and 5x16mm dovel pin. Theoretically, buying 2 sets of G2E can assemble a **Stealthdriver**.

The **Stealthdriver** is specifically intended to be an experimental part which will be use on BABz v2, which will soon be outdated and just use as a test of theory and mechanics.

This design is purely to be FMD printed, preferably ABS and PPA-CF.


# STEALTHDRIVER
## Description
Stealthdriver is the second iteration of motor-mounting block for BABz V2, which has concluded its trial since December 14-15 2024, ranked 4th alliance out of 24 teams. During its trial, the motor-mounting block v1 is in used. The motor-mounting block v1 pose a significant volume demand on the chassis, resulting in complex belt tensioner design which is >1mm away from the front mecanum wheel on both sides.

With the Stealthdriver, the belt tensioner design changed from linear up-down spring-loaded tensioner to swing arm spring-loaded tensioner which assist in saving space for future testing of other up coming module such as [[Underbelly brace revision 2 (rev A1_1)]] and Electronic core.

The design aesthetic of the Stealthdriver rev1 is heavily inspired by VORON design team, Galileo 2 Extruder (G2E) to be exact. Although the Stealthdriver does not utilize orbital gear drive such as G2E, the Stealthdriver uses the G2E's tensioning arm design.
![image](https://github.com/user-attachments/assets/8e59a7b6-6b1d-4091-9598-cad23a2d3436)

## Criteria:
- Decrease amount of space taken by the motor-mounting block
- Simplifies tensioning procedure
- Reduce weight (around -20g)
- Increase modularity

## Constraint:
- Complex geometry (INTENTIONAL)
- Complex mechanism
- Probably more expensive (Unnecessarily expensive just like G2E)

## BOM
### 3D parts:

| Part name                     | material | Infill(%) | Wall | Top | Btm |
| ----------------------------- | -------- | --------- | ---- | --- | --- |
| Stealth_MotorBlock            | ABS      | 20-40     | 3    | 3   | 3   |
| Stealth_MotorBlock_frontplate | ABS      | 20-40     | 4    | 4   | 4   |
| Steath_ShearBearingHolder     | ABS      | 20-40     | 3    | 3   | 3   |
| Stealth_TensionArm            | PPA-CF   | 30-35     | 4    | 3   | 3   |
| Stealth_TensionArmCover       | PPA-CF   | 30-35     | 4    | 3   | 3   |
### Hardware

| Name                    | qyt | Description                                                                                               |
| ----------------------- | --- | --------------------------------------------------------------------------------------------------------- |
| F623ZZ                  | 4   | F623ZZ is a common flanged bearing used on a Voron V0 machines that act as an idler for the Stealthdriver |
| 5x16 dowel pin          | 2   | Dowel pins for the idler arms' pivot points.                                                              |
| MR115                   | 4   | Bearing for the idler arms' pivot points                                                                  |
| 3x4x5 heat insert       | 16  |                                                                                                           |
| 3x12 Flat head screws   | 8   |                                                                                                           |
| 3x12 socket head screws | 2   |                                                                                                           |
| 4x12 flat head screws   | 8   |                                                                                                           |
| 3x20 Thumbscrews        | 2   |                                                                                                           |
| Extruder spring         | 2   |                                                                                                           |


## Tensioning system
