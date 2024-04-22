# CHARISMA Backpack

This repository contains the SolidWorks files for the SPOT backpack that is used in the CHARISMA project. 

<p align="center" width="100%">
    <img src="./Images/Photos/KIWA_2.jpg">
    <br>
    <em>SPOT backpack being used in the CHARISMA project.</em>
</p>


# Documentation
  * [Context](/Documentation/01-context.md)
  * [Constraints](/Documentation/04-constraints.md)
  * [Requirements](/Documentation/03-quality-attributes.md)
  * [Principles](/Documentation/05-principles.md)
  * [Manufacturing Instructions](/Documentation/xx-manufacturing-instructions.md)
  * [Assembly Instructions](/Documentation/xx-assembly-instructions.md)
  * Power Distribution Electrical Diagram 
  * List of Parts
  * ADRs

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
        <em>Full Solidworks assembly of the backpack.</em>
    </div>
</p>

<p align="center" width="100%">
    <img src="./Images/Photos/KIWA_1.jpg">
    <br>
    <em>SPOT backpack being used in the CHARISMA project.</em>
</p>