---
name: Under Insert Piranha Flasher Board with Proximity Sensor Mounting Hole
purpose: Light up playfield insert around a proximity sensor
creators: Michael Rumore, Coleman Martin
date_added: 2020-05-16
dimensions: 33 x 49.5mm (1.3"x1.95")
tested: yes
tested_by: Michael Rumore, Coleman Martin
tags: [Inserts, Lights, Below Playfield, Switches]
---
Transistors drive 4 RGB Piranha LEDs using PD-LED power or 5V power. Transistors are switched by 3.3v logic level input from PD-LED or other microcontroller. Piranha LEDs surround a 18mm mounting hole which incorporate a proximity sensor.

## Bill Of Materials - Common

| Name                         | Purpose                   | PCB Legend          | Qty             |
|------------------------------|---------------------------|---------------------|-----------------|
| Transistor - PN2222A         |                           |                     | 3               |
| Molex - 22-23-2051           | 5 Pin - Connector header  |                     | 1               |
| 5mm - Piranha, Frosted Lens  | LED                       | LED1,LED2,LED3,LED4 | 4               |


## Bill Of Materials (5V) - In addition to Common Bill of Materials

If the you are planning on driving these from 5V you need these bill of materials.

| Name                         | Purpose                   | PCB Legend          | Qty             |
|------------------------------|---------------------------|---------------------|-----------------|
| Resistor - 120Ω 1/4W         | Red                       | R5,R8,R11,R14       | 4               |
| Resistor - 82Ω 1/4W          | Blue                      | R4,R7,R10,R13       | 4               |
| Resistor - 68Ω 1/4W          | Green                     | R6,R9,R12,R15       | 4               |
| Resistor - 220Ω 1/4W         | Transistor                | R1,R2,R3            | 3               |

## Bill Of Materials (3.3V) - In addition to Common Bill of Materials

If the you are planning on driving these from 3.3V from a PD-LED you need these bill of materials.

| Name                         | Purpose                   | PCB Legend          | Qty             |
|------------------------------|---------------------------|---------------------|-----------------|
| Resistor                     | Red                       | R5,R8,R11,R14       | 4               |
| Resistor                     | Blue                      | R4,R7,R10,R13       | 4               |
| Resistor                     | Green                     | R6,R9,R12,R15       | 4               |
| Resistor                     | Transistor                | R1,R2,R3            | 3               |

## Assembly Instructions

Assembly instructions/tips:
Through hole soldering.
Place resistors 1, 14, 5 and 9 on back side of board before Piranha LEDs.
Transistors and header plug are also mounted on the back side of the board.

Warning: silkscreen orientation icon for transistors is incorrect but Base, Collector, Emitter designations are correct.
Align transistors according to BCE.

