## Architecture Decision Records 

In this section you can read the Architecture Decision Records (ADRs). 
For an introdiction to ADRs, see [this](https://video.saxion.nl/media/Architecture+Design+Records+%28ADR%29+-+The+Basics/1_tbcapp6s) video.

Please note that ADRs are immutable. if you want to revert your decision, or change it, make a new ADR. As Michael Nygard put it:
> If a decision is reversed, we will keep the old one around, but mark it as superseded. (It's still relevant to know that it was the decision, but is no longer the decision.)

For new ADRs, you can find a template at the [bottom](#00x-template) of this page.

Decisions:
<!-- no toc -->
* [#003: Re-design version 1.0.0 such that the outershell will be mounted on top of the mounting plate](#003-re-design-version-100-such-that-the-outershell-will-be-mounted-on-top-of-the-mounting-plate)
* [#002: The backpack will not be rainproof](#002-the-backpack-will-not-be-rainproof)
* [#001: We will design our own backpack](#001-we-will-design-our-own-backpack)

## #003: Re-design version 1.0.0 such that the outershell will be mounted on top of the mounting plate
### Context
In [Version 1.0.0](https://bitbucket.org/mechatronica/spot_backpack_solidworks/src/1.0.0/), you had to slide in the mounting plate into the outershell, however, you also needed to first connected the GXP. Finally, you also needed to connect the side panels, once the mounting plate was inside the outershell.

Overall, our initial version was very cumbersome to install and not userfriendly at all.

### Decision
We will re-design version 1.0.0 such that the outershell will be mounted on top of the mounting plate.

### Consequences
The consequence is that there is more time needed in development of the backpack. However, the backpack will be a lot more userfriendly w.r.t. to mounting and serviceablity.

The alternative is to not redesign it, however this would lead to a lot of frustation when working with the backpack.

### Status
Accepted.

## #002: The backpack will not be rainproof
### Context
The [version 1.0.0](https://bitbucket.org/mechatronica/spot_backpack_solidworks/src/1.0.0/) of our backpack was made as a prototype to test if it is feasible to create our own backpack for our research group. This version was not rainproof.
During development of this backpack in the CHARISMA project, the question came up whether the backpack should be rainproof. For context, in the CHARISMA project we investigated automatic inspections of gas pipleine leakage, thus above ground and outdoors.

### Decision
The backpack will not be rainproof.

### Consequences
There several consequences of this decision:
* It will be a lot easier to adjust [version 1.0.0](https://bitbucket.org/mechatronica/spot_backpack_solidworks/src/1.0.0/) for further development.
* We still comply with Dutch norms for gas pipeline leakage inspections. Specifically, [NEN7249](https://www.nen.nl/en/nen-7249-2020-nl-272894) forbids inspection with carpet probes during rain, as rain compromises the measurements.
* Other future projects in our research group may not be able to use the backpack if is not rainproof. However, generally we design our systems not to be rainproof, instead plan outdoor tests on days where it is not raining. Thus, this is most likely not an issue for our research group. 

The alternative would be to redesign our first prototype to be rainproof. However, this would require a lot more effort for desiginig and testing, which was not feasible given the available time back then during the CHARISMA project.

### Status
Accepted.

## #001: We will design our own backpack

### Context
When we started the CHARISMA project we already had a prototype backpack by Clearpath Robotics at our lab, howerver the mountingspots on the backpack were limited and the dimenions were also unknown, because the backpack was not (yet) on the market. With this issue and some other reasons we came up with the idea to figure out if it is possible to make some adjustments on the current backpack or make a completely new one. 

### Decision
We are going to design our own backpack.

### Consequences
The consequence of this decision is that we have to spend a good amount of time in making the backpack, that is: designing, manufacturing, assemblying and testing.

Alternatives
The first alternative to our decision is to keep using the Clearpath Robotics backpack and adjust it or needs. However, the consequence of this is that also for future projects we will run into the same problems (serviceability, mounting options, etc.)

The other alternative would be to buy a different backpack. However, at the time of this decision (~ September 2023), there did not seem to be viable options on the market to replace the current backpack and make it fit for our use.

### Status
Accepted.

## #00X: Template

### Context
*What is the issue that we're seeing that is motivating this decision or change?*

### Decision
*What is the change that we're proposing and/or doing?*

### Consequences
*What becomes easier or more difficult to do because of this change?*

### Status
*What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?*