# Poppy
### 70% Alice keyboard using THT components expanding upon [elmo's Sesame](https://github.com/kb-elmo/sesame).
![image](https://user-images.githubusercontent.com/68519705/221083385-95e5aae6-dc23-4963-9001-a93c030e5cd6.png)
### Expanding upon the Sesame, the Poppy includes a function row, solenoid support, and a resin printable case.

### Board Bill of Materials
 |Count|Part|Reference|
 |-|-|-|
 |1|ATmega32A 40 Pin DIP|U1|
 |1|40 Pin DIP Socket|U1|
 |1|USB4085-GF-A USB Type-C|J1|
 |1|500mA Polyfuse|F1|
 |2|6mm Push Button|SW1, SW2|
 |1|16MHz Quartz Crystal|X1|
 |1|4.7uF Electrolytic Capacitor|C1|
 |2|0.1uF Ceramic Disk Capacitor|C2,C3|
 |2|22pF Ceramic Disk Capacitor|C4,C5|
 |1|1.5kΩ Resistor|R1|
 |2|68Ω Resistor|R2,R3|
 |2|5.1kΩ Resistor|R4,R5|
 |1|10kΩ Resistor|R6|
 |2|3.6V Zener Diode (DO-35 BZX55C3V6)|D77,D78|
 |76|Universal Switching Diode (DO-35 1N4148)|D1-D76|
 
 This bill of materials is identical to the Sesame's minus the quantity of diodes.
 
 ### Solenoid Bill of Materials
 |Count|Part|Reference|
 |-|-|-|
 |1|uxcell Mini Push 4.5V Solenoid| |
 |1|1N4001 Diode|D1|
 |1|TIP120 Transistor|Q1|
 |1|2.2kΩ Resistor|R1|
 
 The solenoid, [purchasable on Amazon](https://www.amazon.com/gp/product/B013DR655A/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1), addon is optional and does not employ the most polished mounting and connection to the main PCB, but is functional and supported in both QMK/VIAL firmware. The easiest method is to run wires from the ATmega32A's solenoid pin (B4/pin 5) and +5V and GND from the ISP header above the 32A. Some slight changes to the PCB could be made to add a header or JST connector to the solenoid, but I haven't gotten around to it at this time.
 
 ### Case Bill of Materials
  |Count|Part|
  |-|-|
  |1|PCB|
  |1|Plate|
  |1|Bottom Case (3D/Resin Printed)|
  |1|Top Case (3D/Resin Printed)|
  |1|Weight|
  |19|Brass Screw-to-Expand Inserts, M2x4mm|
  |19|M2x5mm Button Head Screw|
  |1|Solenoid Daugherboard PCB (Optional)|
  |1|Solenoid Driver PCB (Optional)|
  |2|M2x3mm Socket/Button Head Screw (Optional)|
  
  8 M2x5mm screws and screw-to-expend inserts are used to secure both halves of the case. 4 M2x5mm screws and inserts are used to secure the plate to the top case. 5 M2x5mm screws and inserts are used to secure the optional solenoid/driver board to the bottom case. 2 M2x3mm screws are used to secure the solenoid to the solenoid daughterboard. 2 M2x5mm screws are used to secure the weight to the bottom case, countersunk holes can be drilled and flat head screws can be used for a flush look.
