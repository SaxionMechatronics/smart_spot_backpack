## Constraints

This section states the constraints that affect the design of the backpack. The constraints and images are taken from the [Payload Developer Guide](https://dev.bostondynamics.com/docs/payload/payload_configuration_requirements.html) by Boston Dynamics and where applicable, further elaborated on.

These constraints are: 
- Mounting Surface
- Weight
- Width
- Length
- Height
- Power Connections

## Mounting Surface
The only mounting surface that SPOT provides are aluminum rails that are located along the left and right edges of the body. The rails accept T-slot nuts such as Misumi HNTR5-5. Mounting screws should not project more than 6.3mm below the top surface of the mounting rail.

![Payload width constraint.](/Images/Constraints/mounting_2.png "Aluminum rails for mounting.") 

![Mounting rail keying pin specifications.](/Images/Constraints/mounting_1.png "Mounting rail keying pin specifications in mm") 

## Payload Weight

SPOT has a maximum payload of 14.8 kg. Additionally, the weight of payload will also affect SPOT's battery consumption.
Furthermore, Spot can better handle payload mass if the combined center of mass lies between the front and rear hips. Spot will be more agile and less likely to fall if the total payload mass is centered on the middle of the robot.

## Payload Width
 
The maximum recommended width by Boston Dynamics for a body-mounted payload is 190mm. Wider payloads will result in reduced overall mobility and significant interference with the legs. 
For instance, SPOT's legs may shoot up when walking stairs or when self-righting.
One should thus avoid interference with the robot’s legs as shown below by avoiding the areas immediately adjacent to the robot’s hips.

![Payload width constraint.](/Images/Constraints/payload_width.png "Payload width constraint") 

## Payload Length
The payload should not overhang the front or rear of the robot as this will reduce maneuverability. For instance, when SPOT is standing in a corner or a narrow, it may not be able to turn around.

![Payload length constraint.](/Images/Constraints/payload_length.png "Payload length constraint") 

## Payload Height

The height of the payload impacts the robot’s ability to self-right and increases the height of the center of mass. Therefore, the center of mass low should be kept as low as possible, as the robot may not self-right if the payload is too top-heavy.

## Power connections

The [General Expansion Payload (GXP)](https://support.bostondynamics.com/s/article/Spot-General-Expansion-Payload-GXP) provides power and ethernet communication to SPOT. 
Specifically, it provides a maximum of 150W shared between 12V and 24V 5V at a maximum of 10W via a HD15 connector. The pin out can be found on the documentation site of the GXP.




