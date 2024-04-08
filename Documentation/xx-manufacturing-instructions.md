## Manufacturing Instructions

This sections includes manufacturing instructions for the sheet metal and 3D printed parts of the backpack.

### Sheet Metal Parts

`.SLDPRT` and `.step` files of the sheet metal parts can be found in `./Components/Sheet Metal Parts`. All sheet metal parts are designed for 3mm aluminum sheet metal.

Within CHARISMA, we let these sheet metal parts be manufactured by [247TailorSteel](https://www.247tailorsteel.com/en) by uploading the `.step` files in [SOPHIA](https://www.247tailorsteel.com/en/sophia). In SOPHIA,  select 
- Material: 3mm AlMg3 EN AW 5754 H111
- Cutting: Oxygen

If you design your own parts make sure that they are compatible with SOPHIA. You can find design guidelines [here](https://www.247tailorsteel.com/en/service/submission-rules-and-guidelines). 
If you choose a different manufaturer make sure you are complying with their guidelines (e.g. for bending parts and screw hole sizes and locations). 

### 3D Printed Parts

`.SLDPRT` and `.3MF` files of the 3D printed parts can be found in `./Components/3D Printed Parts`. All 3D printed parts have been printed with:
- PLA
- 30% infill
- Default settings in [CURA](https://ultimaker.com/software/ultimaker-cura/) (5.6.0).

Furthermore, all 3D printed parts have been designed to be used with heat set inserts. 
Insert the heat set inserts with a soldering iron. Tip: don’t insert the last bit of the insert with the soldering iron, but quickly push it in with a flat surface (e.g. a table) in order to make it flush.

If you use different heat set inserts than specified in the [parts list](@TODO), you may need to adjust the hole diameter of these parts. You can use the `heat_insert_test_print.SLDPRT` file as a test file for finding the proper hole dimensions. You also find these [guidelines](https://www.spirol.com/assets/files/ins-wp-how-to-design-the-proper-hole-for-heat-ultrasonic-inserts-us.pdf) useful for adjusting the heat set insert holes.

### Vinyl Wrap (Optional)

You may want to apply vinyl wrap to the sheet metal to make it look more professional. 
You can roughly follow the steps described [here](https://www.wikihow.com/Apply-Vinyl-Wrap). Furthermore, to remove excess vinyl wrap, you can also use a small file. This is especially handy for smaller parts and screw holes. 

