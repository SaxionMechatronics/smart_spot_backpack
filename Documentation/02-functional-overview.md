## Functional Overview

This section gives a functional overview of the system as shown below: 

<p align="center" width="100%">
    <img src="../Images/Diagrams/CHARISMA_sys_arch_dark.png" style="width:70%">
    <br>
    <em>Functional overview of the SPOT Backpack.</em>
</p>

In this diagram you can see that:
- The GXP provides power and data communication from SPOT 
- The power button bridges the power from the GXP to the power distribution
- Power is distributed via the power distribution (PWR Distr.) to the PC and to the interface panel
- The PC provides WIFI via 2 Wifi antennas
- The interface panel has various connectors that allow development with the on-board PC
- The top surface of the backpack inlcudes a cable grommet and an array of screw holes

For a more in-depth electrical diagram, please see the [implementation](/Documentation/07-Implementation.md) section.

Below you can see a 3D version of the Backpack in Solidworks (without any add-on components):

<p align="center">
    <img src="../Images/CAD%20Images/basic_backpack.png" style="display:inline-block; width:40%; margin-right:10px;">
    <img src="../Images/CAD%20Images/inner_backpack2.png" style="display:inline-block; width:40%; margin-right:10px;">
    <div style="clear:both;"></div>
    <div style="text-align: center;">
        <em>Solidworks assembly of the backpack.</em>
    </div>
</p>