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
  * [Functional Overview](/Documentation/02-functional-overview.md)
  * [Quality Attributes](/Documentation/03-quality-attributes.md)
  * [Constraints](/Documentation/04-constraints.md)
  * [Requirements](/Documentation/xx-requirements.md)
  * [Principles](/Documentation/05-principles.md)
  * [Implementation](/Documentation/07-Implementation.md)
    * List of Parts 
    * Power Distribution Electrical Diagram 
  * [Instructions](/Documentation/8-instructions.md)
  * [Manufacturing Instructions](/Documentation/8.1-manufacturing-instructions.md)
  * [Assembly Instructions](/Documentation/8.2-assembly-instructions.md)
  * [Mounting Instructions](/Documentation/8.3-mounting-instructions.md)
  * [Development Environment](/Documentation/12-development-environment.md)
  * [Support and Contributions](/Documentation/11-support-and-contributions.md)
  * [Architecture Decision Records](/Documentation/11-decision-log.md)

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
└── Other Files
```

Other
* Parts List (csv's) / BOM

## TODO
* Release everything as step files
* Check guideline for open source hardware ...

## Suggested Changes

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



## Acknowledgments
This work from the SMART research group in Saxion University of Applied Sciences was supported in part by:
...


<p align="center">
    <img src="./Images/Logos/alliander.png" style="display:inline-block; width:30%; margin-right:10px;">
    <img src="./Images/Logos/Saxion_Smart_Logo_Green.png" style="display:inline-block; width:30%; margin-right:10px;">
    <img src="./Images/Logos/TFF_logo.png" style="display:inline-block; width:30%; margin-right:10px;">
    <div style="clear:both;"></div>
</p>
