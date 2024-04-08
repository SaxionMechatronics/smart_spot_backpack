# CHARISMA Backpack

This repository contains the SolidWorks files for the SPOT backpack that is used in the CHARISMA project. 

![Picture of backpack.](/Images/Photos/KIWA_2.jpg "SPOT backpack being used in the CHARISMA project.") 

# Documentation
  - [Context](/Documentation/01-context.md)
  - [Constraints](/Documentation/04-constraints.md)
  - [Requirements](/Documentation/03-quality-attributes.md)
  - [Principles](/Documentation/05-principles.md)
  - List of Parts
  - [Manufacturing Instructions](/Documentation/xx-manufacturing-instructions.md)
  - [Assembly Instructions](/Documentation/xx-assembly-instructions.md)
  - Power Distribution Electrical Diagram 
  - ...

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
- PWR Distribution
- Parts List (csv's) / BOM


## Known Issues
- Sometimes the assembly does not load after closing it. Restart the PC ...

## TODO
- Release everything as step files
- Check guideline for open source hardware ...

## Suggested Changes

**MOVE TO DOCUMENTATION!**
- Remove the holes on the sides of the outer shell for for the panels, they are not needed.
- Remove the sheet metal bend in the middle of the main mounting plate, it is not needed.
- Make the backpack larger, the current design is very cramped when you add all the wiring.
- Make it rain proof


![Picture of backpack.](/Images/Photos/KIWA_1.jpg "SPOT backpack being used in the CHARISMA project.")