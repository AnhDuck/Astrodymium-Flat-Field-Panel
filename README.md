# Astrodymium Flat Field Panel

![](https://i.imgur.com/RfSpceu.png)

# Changelogs: 

### MK2 -> MK3:

1. Removed recommendation to use PWM style dimmers since they increase flicker/scan lines. This issue is solved by stacking more diffusing material (to increase exposure length) which has been made much easier to do with the newer design
2. Significantly cleaner design as a result of relocating half the screws to the bottom of the panel
3. Increased diameter from 150mm to 160mm for better compatibility with more telescope dew shields
4. Added thicker walls and a wider central post which makes the panel have no flex
5. An integrated diffuser will be added (0.25mm frosted plastic) to reduce light output, because the standard brightness is too much for most optical setups. In theory this should improve the quality of the flats as well, since the light will be more evenly spread out.
6. Size of the housing will be decreased for less filament usage. This will also require a redesign of the cable management clips.
7. The illuminated diameter has been increased from 110mm to 115mm. 

### MK3 -> MK4

1. The design has been completely changed to a much slimmer format that many other commercial flat field panels use.
2. This new design significantly reduces the amount of material used - by over 50%.
3. Bottom plate has been split into two parts, these two parts will make the assembly of the diffuser material + EL panel significantly easier.
4. Distance between diffuser and EL panel is now 1mm apart, instead of being right beside each other. This should make the field even more uniform and give better results.
5. The lid now has a hinge that works by using a 1.75mm piece of filament - this makes assembly and maintinance easier since only 1 screw needs to be used to hold the lid in place.
6. An opening in the bottom plate allows the EL panel's position to be independently adjusted in relation to the diffuser material, making alignment much easier.
7. BOM will specify M3X6 screws that have a thin cap (1mm), these thin screws give a lot more flexibility and reduces the thickness of the FFP.  

# Details

Features: 

* Modularity allows quick swapping of the bottom plate for use with different diffuser materials
* Compact & integrated design (EL power supply is housed inside)
* Easy assembly process and very little support material required
* 3 cable management clips ensure no wires dangle during storage

### Bill of materials (BOM) for MK3-5V variant:

| Item        | Quantity Needed |
| ------------- |-------------| 
| M3x6 screws      | 8 |
| 13cm EL panel      | 1  
| 5V DC-AC inverter power supply | 1 |
| Filament (Recommended PETG) | Aprox. 150-180g |  

### Printed Parts:

| Name        | Quantity |
| ------------- |-------------| 
| Bottom Plate      | 1 |
| Housing      | 1  
| Lid | 1 |

### Recommended print settings:

* 0.2mm layer height (required)
* 0.48mm line/extrusion width (required)
* 1mm top and bottom
* 20% gyroid infill
* 4-5 perimeters
