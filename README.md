# CHARISMA Backpack

<p align="center" width="100%">
  <img src="./Images/Logos/charisma_logo_blackwhite.png">
    <img src="./Images/KIWA_Test_Day/KIWA_2.jpg">
    <br>
    <em>SPOT backpack being used in the CHARISMA project.</em>
</p>

This repository contains the SolidWorks files for the SPOT backpack that is used in the CHARISMA project. 

# Documentation
  * [Context](/Documentation/01-context.md)
  * Functional Overview / System Arch
  * [Quality Attributes](/Documentation/03-quality-attributes.md)
  * [Constraints](/Documentation/04-constraints.md)
  * [Requirements](/Documentation/xx-requirements.md)
  * [Principles](/Documentation/05-principles.md)
  * Code (Implementation)
    * Power Distribution Electrical Diagram 
    * List of Parts
  * Deployment (Instructions)
    * [Manufacturing Instructions](/Documentation/xx-manufacturing-instructions.md)
    * [Assembly Instructions](/Documentation/xx-assembly-instructions.md)
    * [Mounting Instructions](/Documentation/xx-mounting-instructions.md)
  * [Development Environment](/Documentation/12-development-environment.md)
  * [SUpport and Contributions](/Documentation/11-support-and-contributions.md)
  * Decision Log (ADRs)

# Specifications

| Parameter | Backpack V2.0.0 | 
| --- | --- |
| Weight | 3 kg |
| Dimensions | 20 x 40 x 10.5 cm|
| Material | Aluminium Sheet Metal |
| Voltage Outputs | 5, 12, 24 V (M12 Connectors) |
| Media Connectors | 4x USB 3.0, HDMI, Ethernet |
| On-board PC | VECOW SPC-7000|

# Directory Structure

```md
SPOT Backpack Repository
├── Backpack Assembly.SLDASM                  # Solidworks Assembly containing all parts
├── Solidworks Files 
│   ├── Components (FIND BETTER NAME)
│   ├── Sheet Metal Components
│   └── 3D Printed Components
├── Documentation
├── Images
└── ...
```

Other
* PWR Distribution
* Parts List (csv's) / BOM

## TODO
* Upload images
* Release everything as step files
* Check guideline for open source hardware ...

## Suggested Changes

**MOVE TO DOCUMENTATION!**
* Remove the holes on the sides of the outer shell for for the panels, they are not needed.
* Remove the sheet metal bend in the middle of the main mounting plate, it is not needed.
* Make the backpack larger, the current design is very cramped when you add all the wiring.
* Make it rain proof
* Improve design of braces, too many screws for such a simple part ...

<p align="center">
    <img src="./Images/CAD%20Images/full_backpack.png" style="display:inline-block; width:40%; margin-right:10px;">
    <img src="./Images/CAD%20Images/inner_backpack2.png" style="display:inline-block; width:40%; margin-right:10px;">
    <div style="clear:both;"></div>
    <div style="text-align: center;">
        <em>Solidworks assembly of the backpack.</em>
    </div>
</p>

<p align="center" width="100%">
    <img src="./Images/KIWA_Test_Day/KIWA_1.jpg">
    <br>
    <em>SPOT backpack being used in the CHARISMA project.</em>
</p>

<p align="center">
  <img src="./Images/Logos/Saxion_Smart_Logo_Green.png" style="width:50%">
</p>