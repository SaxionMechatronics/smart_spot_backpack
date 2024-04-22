## Requirements

This section dfescribes the functional and technical requirements for the SPOT backpack. Requirements have been written based on [EARS](https://www.researchgate.net/publication/224079416_Easy_approach_to_requirements_syntax_EARS) and have been assigned a priority according to [MoSCoW](https://en.wikipedia.org/wiki/MoSCoW_method). 

*Keep in mind that these requirements have been written in context of the CHARISMA project.*

### Functional requirements

| Number | Requirement | Rationale | Priority |
| --- | --- | --- | --- | 
| FR0101 | During normal operation of SPOT (i.e. walking, crouching, sitting, posing, walking stairs), the backpack shall not interfere with the motion of the robot. | We want a reliable backpack that does not interrupt basic operations of SPOT. | M | 
| FR0102 | When changing the battery while SPOT is laying on its side, the backpack shall not interfere. | If we change the battery, spot needs to be rolled over or on the side in order to access it. | M | 


### Technical requirements

#### Electric and electronic design

| Number | Requirement | Rationale | Priority |
| --- | --- | --- | --- | 
| TR0101 | The backpack shall have clearly labelled cabling with rated voltages and current. | For maintenance reasons, it should be easy to understand the electrical wiring from just looking at it. | M | 
| TR0102 | The backpack shall provide one 24V, 12V and 5V external power connection each. | The bag pack should be able to cater the needs of various projects and their respective peripherals. | M | 
| TR0103 | The backpack shall provide different, standardized connectors for its external power connections that are labelled with rated voltages and current. | For safety reasons. For example, it should not be possible to connect a 5V to a 24V connection by accident. | M | 
| TR0104 | The backpack shall provide two WIFI antennas, one ethernet, one HDMI and four USB connections that are interfaced with its PC. | We want to easily develop on the PC of the bag pack. | M | 
| TR0105 | The backpack shall provide one power button that turns on/off its internals. | We want to power the PC and its peripherals only when needed. | M | 
| TR0106 | The power distribution of the backpack shall reserve 40W for the PC. | External devices that are powered via the 5V,12V or 24V connections should not be able to draw enough current to cut out the power to PC. The PC uses a maximum of 33.5W at peak conditions. | M | 

#### Mechanical design

| Number | Requirement | Rationale | Priority |
| --- | --- | --- | --- | 
| TR0201 | The GNSS sensors of shall be located at the highest points of the backpack and not be occluded by any objects of the backpack. | Occlusions to the sky and reflections will disturb sensor readings. By placing the GNSS sensors at the highest point, we will get the best possible signal. | M | 
| TR0202 | The bag pack shall allow for a minimum distance of 80cm between the GNSS sensors. | There needs to be sufficient distance between the sensors to accurately determine the heading of the robot. | M | 
| TR0203 | The weight of the backpack shall be lower than 14.8 Kg where lower is better. | This is the maximum payload of SPOT. Reduced payload leads to reduced power consumption and thus longer operation times. **(CONSTRAINT)** | M | 
| TR0204 | The width of the backpack shall be at most 19 cm. | When the robot is not powered or walking stairs, the robot’s legs may move into the designated design space **(CONSTRAINT)** | M | 
| TR0205 | The length of the backpack shall be at most 85 cm. | Longer payloads will reduce maneuverability. **(CONSTRAINT)**  | M | 
| TR0206 | The backpack shall have an IP rating of 0 where higher is better. | The backpack is built for research purposes only, it is therefore not required to have a higher IP rating. | M | 
| TR0207 | The backpack shall be made out of aluminum sheet metal. | Sheet metal parts are relative sturdy, cheap and easy to design. Additionally, they are easy to modify if needed  (e.g. drilling holes, filing). | S | 
| TR0208 | The backpack shall have only screw holes with insert nuts (e.g. rivets nuts, heat inserts) on its outer shell. | 1) User friendliness: A user should be able to (un)-screw any object located on outer shell as easy as possible. 2) Reliability: The threading of tapped holes may deteriorate over time with repeated (un-)screwing. | S | 
| TR0209 | When (un-)mounting,  backpack shall require one tool, and two assembly steps. | User friendliness. It should be easy to (un)-mount the backpack to facilitate switching between different projects if needed. | S | 
| TR0210 | The  backpack shall require one disassembly step to access its internals. | Debugging and maintenance purposes. | S | 
| TR0211 | The backpack shall have only 3 and 5 mm screw holes. | This is to prevent confusion between screw hole sizes during assembly | S | 

