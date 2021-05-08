# Astrodymium Flat Field Panel

# Changelogs: 

### V3:

1. Removed recommendation to use PWM style dimmers since they increase flicker/scan lines. This issue is solved by stacking more diffusing material (to increase exposure length) which has been made much easier to do with the newer design
2. Cleaner design as a result of relocating half the screws to the bottom of the panel
3. Increased outer diameter from 150mm to 160mm for better compatibility with more telescope dew shields
4. Added thicker walls and a wider central post which makes the panel have no flex
5. An integrated diffuser will be added (0.25mm frosted plastic) to reduce light output, because the standard brightness is too much for most optical setups. In theory this should improve the quality of the flats as well, since the light will be more evenly spread out.
6. Size of the housing will be decreased for less filament usage. This will also require a redesign of the cable management clips.
7. The illuminated diameter has been increased from 110mm to 115mm. 

### V4.0

Release 4.0 focuses on cutting away needless material by introducing an overall more compact design. User replacability of diffusing material was also added.

1. The overall design has been remade to a slimmer format that many other commercial flat field panels use. This minimizes the amount of required material and saves on weight (over 30%), while still retaining the same rigidity and offering better build quality.
2. Bottom plate has been split into two parts (P1/P2) - these two parts make assembling the diffuser material + EL panel significantly easier.
3. Bottom plates are now held in place with 6 screws, this prevents light from shining through cracks in the plates.
4. Clear aperture has been increased from 115mm to 125mm. 
5. Distance between diffuser and EL panel is now 2mm apart, instead of being right on top of each other. This makes the field even more uniform than before.
6. A combination of two new materials will be used for diffusing the light, which should result in less flicker, due to it having a lower opacity. One of the new materials used also has significantly better diffusion properties.
7. An easy way to add more diffusing material (usually paper) will be implemented. This should allow users to achieve a good exposure length, no matter how fast their setup is, 8. because they can adjust the amount of light the panel lets through.
9. The lid is now only held in by two screws, which lessens the time needed to do any maintenance.
10. Low profile M3X6 screws are now used, these thin screws give a lot more flexibility in the design process, look more professional, and reduces the thickness of the FFP.

### V4.1

Changes that could not be implemented due to the CN deadline were added in this update, as well as any potential optimizations found when building 4.0.

1. Version naming scheme changed from "MK" to "V"
2. The position of screw holes were adjusted to allow for a reduced outer diameter. Down from 160mm to 154mm. This smaller diameter makes the panel more compact and reduces material usage.
3. Location of the printed diffuser was moved to be on top of the EL panel. This eliminates the fine grain texture and any other aberrations present on the printed diffuser.
4. Thickness of the panel was reduced by 0.6mm (8.8 -> 8.2)
5. The EL panel output wire housing was lengthened all the way, to make assembly easier, and to reduce cable strain.
6. Source CAD file was redesigned from the ground up to be more parametric. Stuff doesn't blow up when changes are made, and revisions are much easier to make now. Part organization (components/assemblies) has also been cleaned up. 

### V4.2 (Unreleased, currently being designed and tested)

1. Low profile M3x10 screws are now used instead of M3x6. The extra 4mm in thread length allows more flexibility in how the panel can be designed, and increases long term durability due to having more material to self tap into. 
2. Distance between EL panel and duralar diffuser has been increased by 1mm for a more uniform field.
3. Certain screwholes were made more durable by increasing depth and amount of material surrounding them.

# Details (Outdated)

Features: 

* Modularity allows quick swapping of the bottom plate for use with different diffuser materials
* Compact & integrated design (EL power supply is housed inside)
* Easy assembly process and very little support material required
* 3 cable management clips ensure no wires dangle during storage

### Bill of materials (BOM) for MK3-5V variant:

| Item        | Quantity Needed |
| ------------- |-------------| 
| M3x6 screws (1mm thin cap)      | 8 |
| 13cm EL panel      | 1  
| 5V DC-AC inverter power supply | 1 |
| Filament* | Aprox. 115g |  

* PETG is recommended due to its heat resistance and ease of printing. PLA may deform under the sun depending on your climate. For best results use dark filament to prevent any intrusion of stray light.

### Printed Parts:

| Name        | Quantity |
| ------------- |-------------| 
| Bottom Plate P1      | 1 |
| Bottom Plate P2      | 1 |
| Housing      | 1  
| Lid | 1 |

### Recommended print settings:

* 0.2mm layer height (this is required for bridging to work as expected)
* 0.48mm line/extrusion width - first and top layer should use 0.42mm width for a better finish.
* 1mm top and bottom
* 20% rectilinear infill
* 4-5 perimeters
