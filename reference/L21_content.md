--- Page 515 ---

Figure M-18: Left and Right 8-Wide Legacy Vertical I/O Interface Carriers
Note
The 8-wide Legacy Vertical I/O carriers are designed with a split high-side power plane and
a shared common return plane. A jumper bridges both high-side planes for a continuous
conductive path. If additional power is required, you can break this high-side path and add
another power source to the unpowered end.
To decide when to use external power, calculate the power used per position on the
carrier. Add these values to determine if they exceed the power supply’s capabilities. If the
calculation of a given position exceeds the power supply’s capabilities:
• Locate the power jumper that is just before this position (count from the power supply
end).
• Insert additional power at this node.
DeltaV Vertical Carriers
D800001X312 
April 2021
515

--- Page 516 ---

If multiple power supplies are used, be sure they are grounded at the same point.
Adding External Power to a Legacy Vertical System
Figure M-19: Remove Jumper to Add Power
1. Remove the jumper on the 8-wide I/O interface carrier.
Warning
Removing the jumper removes all 12 VDC power to all cards on all downstream
carriers. When 12 VDC power is removed, cards are unable to hold the last value.
2. Insert 12 VDC power:
• + to the center terminal
• - to the - negative terminal
 CAUTION
On the right 8-wide Legacy Vertical carriers removing the jumper only disconnects
the 96 pin carrier connector; it does not disconnect the 48 pin cable connector.
This caution only applies if power is extended to a right 8-wide Legacy Vertical
carrier with a cable connected to it. As an example, in the configuration shown in
the following figure power should be extended at carriers 3 and 5. This allows
carriers 1 and 2 to receive power from the system power supply; carriers 3 and 4 to
receive power extended at carrier 3; and carriers 5, 6, 7, and 8 to receive power
extended at carrier 5.
DeltaV Vertical Carriers
April 2021
D800001X312
516

--- Page 517 ---

Figure M-20: Extending Power at Right 8-Wide Legacy Vertical Carriers
1
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1 2 3 4
C1
C2
C3
C4
C5
C6
C7
C8
4-wide carrier
Top
2
Bussed field
power connector
Remove jumper and
extend power here
Remove jumper 
and extend power 
here
The following figure shows a typical Legacy Vertical configuration with six, 8-wide
I/O interface carriers.
DeltaV Vertical Carriers
D800001X312 
April 2021
517

--- Page 518 ---

Figure M-21: Typical Legacy Vertically Mounted Configuration
Carrier #1
Carrier #2
Carrier #3
Carrier #6
Carrier #5
Carrier #4
Top Position
4-Wide
Carrier
Bottom Cable Extender
Addressing
Positions
17 - 24
Addressing
Positions
25 - 32
Addressing
Positions
09 - 16
Addressing
Positions
33 - 40
Addressing
Positions
01 - 08
Addressing
Positions
41 - 48
Vertical
Mounted
DIN Rail
LEFT
DIN Rail
Mounting
RIGHT
DIN Rail
Mounting
Bussed
Field
Power
Connector
Another Legacy Vertical configuration uses the top cable extender to bridge a left to
right 8-wide I/O Interface carrier, as shown here.
DeltaV Vertical Carriers
April 2021
D800001X312
518

--- Page 519 ---

Figure M-22: Top Cable Extender Bridging Left and Right Legacy Vertical I/O Interface Carriers
Bussed
Field
Power
Connector
Addressing
Positions
09 - 16
Addressing
Positions
17 - 24
Addressing
Positions
01 - 08
Top Position
4-Wide Carrier
LEFT
DIN Rail
Mounting
LEFT
DIN Rail
Mounting
RIGHT
DIN Rail
Mounting
Bottom Cable Extender
Carrier #1
Carrier #2
Top Cable Extender
Carrier #3
Addressing
Positions
33 - 40
Carrier #5
Addressing
Positions
25 - 32
Vertical
Mounted
DIN Rail
Carrier #4
Another Legacy Vertical configuration, shown in the following figure, shows a
bottom 4-wide Legacy Vertical carrier connected to a right 8-wide Legacy Vertical
I/O interface carrier. A top cable extender bridges the right I/O carrier to a left I/O
carrier on the back side of the cabinet.
DeltaV Vertical Carriers
D800001X312 
April 2021
519

--- Page 520 ---

Figure M-23: Bottom 4-Wide Legacy Vertical Carrier
Bussed
Field
Power
Connector
Addressing
Positions
01 - 08
Addressing
Positions
25 - 32
Addressing
Positions
09 - 16
Bottom
Position
4-Wide
Carrier
DIN Rail
DIN Rail
Carrier #2
Top Cable Extender
Carrier #4
Addressing
Positions
17 - 24
Carrier #3
Carrier #1
Cables for Legacy Vertical Systems
Two types of cables are used to connect the 8-wide Legacy Vertical I/O carriers:
• The bottom cable extender connects a left I/O carrier (card position 1-8) to a right I/O
carrier (card positions 8-1) at the bottom of the DIN rails. The bottom cable extender
exits in a downward direction.
• The top cable extender connects a right I/O carrier (card position 8-1) to a left I/O
carrier (card positions 8-1) on the opposite side of the cabinet at the top of the DIN
rails. The top cable extender exits in an upward direction.
The figures in "4-Wide Legacy Vertical Power/Controller Carriers" show how the bottom
cable extender is used in a typical legacy vertical configuration and how the top cable
extender is used as a bridge.
Note
Failure to use the correct cables can result in a corrupt addressing scheme.
DeltaV Vertical Carriers
April 2021
D800001X312
520

--- Page 521 ---

Related information
4-Wide Legacy Vertical Power/Controller Carriers
Calculating the Total Length of a Legacy Vertical System
For both vertically and horizontally mounted systems, the length of the LocalBus,
including all cabling is the same; it cannot exceed 6.5 m (21.3 feet). The LocalBus at this
length can support eight, 8-wide carriers, one, 4-wide carrier, one, bottom cable extender,
and one, top cable extender. However, there is a difference in how maximum length is
calculated for Legacy Vertical systems. The following figure shows a standard Legacy
Vertical configuration for an eight carrier, 64 card system.
Figure M-24: Standard Configuration for an Eight Carrier Legacy Vertical System
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1
2
2
3
4
5
6
7
8
1
2
3
4
5
6
7
8
1 2 3 4
Bottom cable extender
 (1 meter/39.37 inches)
C1 addressing positions 01-08
C2 addressing positions 09-16
C3 addressing positions 17-24
C4 addressing positions 25-32
C5 addressing positions 33-40
C6 addressing positions 41-48
C7 addressing positions 49-56
C8 addressing positions 57-64
4-wide carrier
Top
C1
C2
C3
C4
C5
C6
C7
C8
Bussed field
power connector
Top cable extender 
(2-meters/78.74 inches)
Notes
Each carrier (C1-C8) is 22 inches long
The length to carriers 6 and 7 (C6 and C7) is not counted in the overall length calculation
since C6 and C7 are considered spurs and are not in series with the rest of the system. Spur
lengths are equal to or less than the total system length.
Refer to preceding figure. There are three carrier ends: 6, 7, and 8. For a vertically
mounted system, the signal path starts at the first carrier. The following table shows how
to calculate the lengths to the three carrier ends. The cable lengths are 1m. (39.37 in.) or
2m (78.74 in.) and the carrier lengths (C) are 22 inches.
DeltaV Vertical Carriers
D800001X312 
April 2021
521

--- Page 522 ---

Table M-1: Cable Length Calculations
Total length to the end of
carrier:
Calculation
6
C1 + C2 + C3 + 1m + C4 +C5 + C6 = 14.3 ft
7
C1 + C2 + C3 + 1m + C4 +C5 + 2m + C7 = 20.8 ft
8
C1 + C2 + C3 + 1m + C4 +C5 + 2m + C8 = 20.8 ft
Note
Do not connect additional carriers to spurs as this will corrupt the addressing scheme.
Referring to Figure M-24, if you connect a carrier to the end of carrier 6, it will become
carrier 7. In the addressing scheme shown in the figure, carrier 7 already exists at the end
of the 2 meter cable.
Related information
DeltaV System Equipment
DIN Rail Recommendations
The following figure shows suggested spacing for vertical DIN rail installation.
Figure M-25: Vertical DIN Rail Installation
Installing the 4-Wide Legacy Vertical Power/Controller
Carriers
1. Mount the DIN rail at the appropriate location.
DeltaV Vertical Carriers
April 2021
D800001X312
522

--- Page 523 ---

2. Turn the screws counter-clockwise on the power/controller carrier to disengage the
latch.
3. Place the carrier on the rail and tighten the screws clockwise to latch.
Note
The middle two screws are for G-rail mounting and the outer screws are for T-rail
mounting.
Installing the 8-Wide Legacy Vertical I/O Interface Carriers
Refer to the following figure when performing these steps.
Figure M-26: 8-Wide Legacy Vertical I/O Interface Carrier Installation
Previously
Mounted
Top Position
4-wide Carrier
Previously
Mounted
Bottom
Position
4-wide Carrier
T-Rail or G-Rail
T-Rail Latch Screws
G-Rail Latch Screws
Push
and
Hold
Push
and
Hold
Push
and
Hold
Wiring
Point for
Shield
Bar
Carrier
Shield
Bar
Bussed Field
Power Connector
1. Mount the DIN rail at the appropriate location.
2. Connect each 8-wide carrier to any adjacent carriers by sliding the 96-pin
connectors at the top or bottom of the carriers together. Hold the carrier in position
to ensure that it does not fall.
3. Turn the screws counter-clockwise to disengage the latch. With the carrier on the
rail, tighten the screws clockwise to latch.
DeltaV Vertical Carriers
D800001X312 
April 2021
523

--- Page 524 ---

Note
The middle two screws are for G-rail mounting and the outer screws are for T-rail
mounting.
4. If you are mounting 8-wide carriers on separate rails, use the bottom cable extender
for a left-to-right bridge and the top cable extender for a right-to-left bridge.
5. Install ground wiring as shown in the following figure. For a good connection, use a
signal ground cable and a block spade terminal, sized for AC/DC system power.
Figure M-27: Ground Wiring for System Power Supplies
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
AC/DC
Power Supply
Power
Error
Active
Standby
Controller
MD Plus
Power
Error
AC/DC
Power Supply
Power
Error
Active
Standby
Controller
MD Plus
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Power
Error
Active
Standby
Chassis
Ground
Enclosure PE Ground Lug
Enclosure Door
Adjacent Enclosure
Isolated
Bus
To DIG
To DIG
To DC Return
To AC Ground
DC
Ground
To DIG
DC 
Reference
Ground
Bussed
Field
Power
Connector
Connects to 
 Jumper Bar on
Next I/O Carrier
I/O Carrier
Shield Bar
Related information
Cables for Legacy Vertical Systems
DeltaV Vertical Carriers
April 2021
D800001X312
524

--- Page 525 ---

Installing the Cables
Use the bottom cable extender to connect a left Legacy Vertical I/O carrier to a right
Legacy Vertical I/O carrier at the bottom of the DIN rails. Use the top cable extender to
connect a right Legacy Vertical I/O carrier to a left I/O carrier on the opposite side of the
cabinet at the top of the DIN rails.
Note
Be sure that the bottom cable extender exits in a downward position and the top cable
extender exits in an upward position.
 CAUTION
Be careful when inserting sockets and plugs. The connectors are fragile and bend easily.
Ensure that the pins are straight before connecting the cable ends.
1. Connect the plugs and sockets on the carriers.
2. Tighten the two mounting screws on each cable end.
DeltaV Vertical Carriers
D800001X312 
April 2021
525

--- Page 526 ---

DeltaV Vertical Carriers
April 2021
D800001X312
526

--- Page 527 ---

N
Installation Worksheets
This appendix provides worksheets to calculate your system power supply requirements
and includes a checklist that you can use to create your own worksheets to document your
installation.
N.1
Installation Information Checklist
Document the following information about your system and archive it for use in the event
that any problems arise.
• Create a diagram of the Control Network equipment and cables, include:
— Equipment location
— Cable routing
— Cable lengths
— Type of connectors at each end of the cables
— The manufacturer and type of cable
— Boot color on the cables
— Certification report for each 10BaseT cable
— Certification report for each fiber-optic cable
• Create a diagram of the power supplies and power and ground wiring, include:
— Power supply locations
— Power sizing calculations (Refer to the tables in this chapter.)
— Wiring routing
— Wiring gauges and lengths
— Current flow through the wiring (measured after startup)
• Document the sizing and heat rise calculations for any enclosures
• Document each I/O terminal block and I/O card types for each slot
Related information
I/O Cards
Power Dissipation Considerations
N.2
Worksheets for Calculating Power
Requirements
Use the tables in this chapter to calculate your power supply requirements for system
power supplies and legacy bulk power supplies for non-I.S. systems.
Installation Worksheets
D800001X312 
April 2021
527

--- Page 528 ---

Use the Worksheet for Intrinsically Safe System Power Requirements to determine the
number of power supplies required for Intrinsically Safe systems and add the total number
of I.S. power supplies to the Worksheet for Products Using Only 24 VDC Power.
Make a copy of the tables and use them for each DeltaV system in your plant. If you are
using redundant power, remember to include calculations for redundant system power.
Calculating Power Requirements
Follow these steps to calculate your power requirements:
• For products that use 12 VDC LocalBus power and 24 VDC bussed field power, use the
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power to
record quantity for each product and multiply quantity by the required amperage to
determine the:
— 12 VDC LocalBus power requirements for each product
— 24 VDC bussed field power requirements for each product
Enter the totals in the appropriate column (12 VDC or 24 VDC) in the Worksheet for
Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power. Add the total
amperage requirements to get a subtotal of amperage requirements for all products and
enter the subtotal as Subtotal 1.
• For products that use 24 VDC power, use the Worksheet for Products Using Only 24
VDC Power to record quantity for each product and multiply quantity by the required
amperage to determine the:
— 24 VDC power requirements for each product
— Number of Intrinsically Safe power supplies (if I.S. cards are used) required for I.S.
systems and add the total number of I.S. power supplies to the worksheet. Use the
Worksheet for Intrinsically Safe System Power Requirements to determine the
number of I.S. power supplies.
— Enter the totals in the 24 VDC column in the worksheet.
— Add the total amperage requirements to get a subtotal of amperage requirements
for all products and enter as Subtotal 2 at the end of the worksheet.
24 VDC Systems
• For 24 VDC systems, use the Worksheet for System Power Requirements - 24 VDC
Power Input to determine the:
— Number of system power supplies required to power the I/O cards.
— Amperage required from the legacy bulk 24 VDC power supplies to power the
system power supplies and bussed field power requirements.
12 VDC Systems
• For 12 VDC systems, use the Worksheet for System Power Requirements - 12 VDC
Power to determine the:
— Number of system power supplies required to power the I/O cards.
— Amperage required from the legacy bulk 12 VDC Power Supplies to power the
system power supplies and 24 VDC bussed field power requirements.
Use the Worksheet for Bulk Power Requirements to determine the number of legacy bulk
power supplies required.
Installation Worksheets
April 2021
D800001X312
528

--- Page 529 ---

Related information
Worksheet for Intrinsically Safe System Power Requirements
Worksheet for Products Using Only 24 VDC Power
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power
Worksheet for System Power Requirements - 12 VDC Input
Worksheet for System Power Requirements - 24 VDC Power Input
Worksheet for Bulk Power Requirements
N.3
Worksheet for Products Using 12 V LocalBus
Power and 24 VDC Bussed Field Power
Use this table to calculate the power requirements for products that use 12 VDC LocalBus
power and 24 VDC bussed field power.
Table N-1: Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed
Field Power 
Product Type Quanti
ty
Curent Required for Each Product (A)
Total for Product Type
12 VDC LocalBus
Power
24 VDC Bussed Field
Power
12 VDC
24 VDC
Controllers
0.01
0.01
Remote
Interface Unit
0.01
0.01
I/O Cards
AI, 8-Channel,
4-20 mA
0.150
0.300
AI, 8-Channel,
4-20 mA,
HART
0.150
0.300
AI, 8-Channel,
1-5 VDC
0.150
0.100
AO, 8-
Channel, 4-20
mA
0.150
0.300
AO, 8-
Channel, 4-20
mA, HART
0.150
0.300
AS-Interface
0.300
N/A
DeviceNet
0.600
N/A
DI, 8-
Channel, 24
VDC, Isolated
0.100
N/A
Installation Worksheets
D800001X312 
April 2021
529

--- Page 530 ---

Table N-1: Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed
Field Power (continued)
Product Type Quanti
ty
Curent Required for Each Product (A)
Total for Product Type
12 VDC LocalBus
Power
24 VDC Bussed Field
Power
12 VDC
24 VDC
DI, 8-
Channel, 24
VDC, Dry
Contact
0.100
0.040
DI, 8-
Channel, 120
VAC, Isolated
0.100
N/A
DI, 8-
Channel, 120
VAC, Dry
Contact
0.100
N/A
DI, 8-
Channel, 230
VAC, Isolated
0.100
N/A
DI, 8-
Channel, 230
VAC, Dry
Contact
0.100
N/A
DI, 32-
Channel, 24
VDC, Dry
Contact
0.075
0.150
DO, 8-
Channel,
120/230 VAC,
Isolated
0.150
N/A
DO, 8-
Channel,
120/230 VAC,
High Side
0.150
N/A
DO, 8-
Channel, 24
VDC, Isolated
0.150
N/A
DO, 8-
Channel, 24
VDC, High
Side
0.150
depends upon field
devices (max 3 A total
each card)
DO, 32-
Channel, 24
VDC, High-
Side
0.150
depends upon field
devices (max 3.2 A
total each card)
Fieldbus H1
card
0.600
N/A
Installation Worksheets
April 2021
D800001X312
530

--- Page 531 ---

Table N-1: Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed
Field Power (continued)
Product Type Quanti
ty
Curent Required for Each Product (A)
Total for Product Type
12 VDC LocalBus
Power
24 VDC Bussed Field
Power
12 VDC
24 VDC
Media
Converter
0.300
N/A
Multifunction
0.250
N/A
Profibus DP
0.600
N/A
RTD, ohms
0.160
N/A
Sequence of
Events
0.075
0.075
Serial Card, 2
Ports, RS232/
RS485
0.300
N/A
Thermocoupl
e, mV
0.350
N/A
Series 2 I/O Cards 2
Series 2 AI,
4-20 mA with
HART
Simplex: 0.150
Redundant: 0.250
(each card)
Simplex: 0.300
Redundant: 0.200
(each card)
Series 2 AI,
16-Channel,
4-20 mA,
HART Simplex
0.150
0.600
Series 2 AO,
4-20 mA with
HART
Simplex: 0.150
Redundant: 0.250
(each card)
Simplex: 0.300
Redundant: 0.200
(each card)
Series 2 AS-
Interface
Simplex
0.300
N/A
Series 2 DI, 8-
Channel, 24
VDC Dry
Contact
Simplex: 0.150
Redundant: 0.150
(each card)
Simplex: 0.040
Redundant: 0.020
(each card)
Series 2 DI, 8-
Channel, 24
VDC Isolated
Simplex
0.100
N/A
Series 2 DI, 8-
Channel, 120
VAC, Dry
Contact
Simplex
0.100
N/A
Installation Worksheets
D800001X312 
April 2021
531

--- Page 532 ---

Table N-1: Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed
Field Power (continued)
Product Type Quanti
ty
Curent Required for Each Product (A)
Total for Product Type
12 VDC LocalBus
Power
24 VDC Bussed Field
Power
12 VDC
24 VDC
Series 2 DI, 8-
Channel, 120
VAC Isolated
Simplex
0.100
N/A
Series 2 DI,
32-Channel,
24 VDC, Dry
Contact
Simplex
0.075
0.150
Series 2 DO,
8-Channel, 24
VDC, High-
Side
Simplex: 0.150
Redundant: 0.150
(each card)
Simplex: depends
upon field devices;
(max 3 A total each
card)
Redundant: depends
upon field devices;
(max 1.5 A each card)
Series 2 DO,
8-Channel, 24
VDC Isolated
Simplex
0.150
N/A
Series 2 DO,
8-Channel,
120/230 VAC
High Side
Simplex
0.150
N/A
Series 2 DO,
8-Channel,
120/230 VAC,
Isolated
Simplex
0.150
N/A
Series 2 DO,
32-Channel,
24 VDC, High-
Side Simplex
0.150
depends upon field
devices
(max 3.2 A total each
card)
Series 2 H1
Simplex: 0.300
Redundant: 0.300
(each card)
N/A
N/A
Series 2
Isolated Input
0.350
N/A
Series 2
DeviceNet
0.600
N/A
Series 2
Profibus DP
0.600
N/A
Installation Worksheets
April 2021
D800001X312
532

--- Page 533 ---

Table N-1: Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed
Field Power (continued)
Product Type Quanti
ty
Curent Required for Each Product (A)
Total for Product Type
12 VDC LocalBus
Power
24 VDC Bussed Field
Power
12 VDC
24 VDC
Series 2
Thermocoupl
e
0.210
Series 2
Sequence of
Events
Simplex
0.100
0.075
Series 2 Serial
Simplex: 0.300
Redundant: 0.300
(each card)
N/A
N/A
Subtotal 1
1
Require no LocalBus current as controllers are powered separately by the system power supply.
2
For Series 2 cards in redundant applications, the numbers shown in the table are for each card of
a redundant pair. For example, the power required for a redundant pair of Series 2 DO cards is .
300 A at 12 VDC and a maximum of 3 A at 24 VDC for 24 VDC field power.
Installation Worksheets
D800001X312 
April 2021
533

--- Page 534 ---

N.4
Worksheet for Products Using Only 24 VDC
Power
Table N-2: Worksheet for Products Using Only 24 VDC Power 
Miscellaneous Products
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
H1 carrier input
power
Bussed field
power
N/A
N/A
0.020 (carrier
only)
0.500 (max
with cards)
Bussed field
power: Add
the current
required for
the cards
installed on
the carrier
unless
accounted for
elsewhere in
the calculation
in the table for
products that
use 12 V
LocalBus
power and 24
VDC bussed
field power.
N/A
Logic Solver
N/A
1 plus DO field
power (4 max)
N/A
Redundant Logic
Solvers
N/A
2 plus DO field
power
N/A
SISNet
Repeaters
N/A
0.300 (per
Repeater)
N/A
Auxiliary Relay
Modules,
Energize to
Actuate and De-
Energize to
Actuate, 24 VDC
N/A
0.010 plus
field power (5
max)
N/A
DeltaV Smart Switches and Media Modules
FP20-6TX2TX
N/A
0.221
N/A
Installation Worksheets
April 2021
D800001X312
534

--- Page 535 ---

Table N-2: Worksheet for Products Using Only 24 VDC Power (continued)
Miscellaneous Products
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
FP20-6TX1MM1
TX
FP20-6TX1SM1T
X
FP20-6TX1SMLH
1TX
N/A
0.271
N/A
FP20-6TX2MM
FP20-6TX2SM
FP20-6TX2SMLH
N/A
0.321
N/A
MD20-8
N/A
0.208
N/A
MD20-16
MD20-24
N/A
0.500
N/A
MD30-8
N/A
0.317
N/A
MD30-16
MD30-24
N/A
0.609
N/A
MD2-4TX1
MD2-4TX1-PoE
N/A
0.034
N/A
MD3-4FX/M2
MD3-4FX/M4
MD3-4FXS2
N/A
0.292
MD2-2FXM2
MD3-2FXM2/2T
X1
MD3-2FXM4/2T
X1
MD2-2FXS2
MD3-2FXS2/2TX
1
MD3-1FXS2/3TX
1
N/A
0.142
Power Supplies
I.S. System
Power Supply
(Refer to the
table for IS
System Power
requirements for
calculations.)
N/A
3.4
Installation Worksheets
D800001X312 
April 2021
535

--- Page 536 ---

Table N-2: Worksheet for Products Using Only 24 VDC Power (continued)
Miscellaneous Products
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
Fieldbus Power
Supply
N/A
Refer to
manufacturer'
s
specifications.
N/A
I.S. Fieldbus
Power Supply
N/A
Refer to
manufacturer'
s
specifications.
N/A
Subtotal 2
N/A
N.5
Worksheet for System Power Requirements -
24 VDC Power Input
To calculate the number and type of system power supplies required to power the system
based on the 12 VDC LocalBus power requirements calculated in the Worksheet for
Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power, use the following
table for systems in which the system power supply is powered by a 24 VDC supply or use
the Worksheet for System Power Requirements - 12 VDC for systems in which the system
power supply is powered by a 12 VDC supply. Remember to not exceed 8 A on the
horizontal carrier and 15 A on the vertical carrier and remember to include calculations for
redundant system power. Add Subtotal 1 from Worksheet for Products Using 12 V
LocalBus Power and 24 VDC Bussed Field Power and Subtotal 2 from the Worksheet for
products Using Only 24 VDC Power to do the calculation
Table N-3: System Power Requirements - 24 VDC Input
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
System Power
Supply (Dual
DC/DC) 24 V
input
Provides 8.0
Amps @ 12 V
(Subtotal
1 /8.0 A =
Quantity)1
N/A
7.5 max
N/A
Installation Worksheets
April 2021
D800001X312
536

--- Page 537 ---

Table N-3: System Power Requirements - 24 VDC Input (continued)
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
Redundant
system Power
Supply (Dual
DC/DC) 24 V
input for
either Simplex
or Redundant
controllers (if
applicable)
NA
1.0 max2
N/A
Add for
Subtotal 3
Subtotal 3
N/A
Add Subtotal 1
(24 VDC only)
from
Worksheet for
Products
Using 12 V
LocalBus
Power and 24
VDC Bussed
Field Power.
Subtotal 1
N/A
Add Subtotal 2
from
Worksheet for
Products
Using Only 24
VDC Power
Subtotal 2
N/A
Add Subtotals
1, 2, and 3 for
total 24 VDC
power
required.
Grand Total
N/A
1
Older models of the Dual DC/DC System Power Supply provided 4.5 A of +12 V power and
required 4.0 A input from +24 V power.
2
If your system requires redundant system power, a redundant system power supply can be added
to either a 2-wide horizontal carrier, (may require an additional 2-wide carrier) or to the 4-wide
vertical carrier.
Example Calculation for 24 VDC Input
As an example, suppose your calculations from the Worksheet for Products Using 12 V
LocalBus Power and 24 VDC Bussed Field Power showed that the total 12 VDC LocalBus
power requires 6.1 A. Calculate the number of power supplies that you will need as
follows:
6.1 A/8.0 A/supply = 0.76 or 1 system power supply for simplex
power
Installation Worksheets
D800001X312 
April 2021
537

--- Page 538 ---

If redundant power is required, an additional 2-wide carrier is necessary for a horizontally
mounted DeltaV system. Use the Worksheet for Legacy Bulk Power Requirements to
calculate the number of bulk supplies required to power the system for each type based
on the 12 and 24 VDC power requirements calculated in the Worksheet for System Power
Requirements - 24 VDC Power Input.
Related information
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power
Worksheet for System Power Requirements - 12 VDC Input
Worksheet for System Power Requirements - 24 VDC Power Input
N.6
Worksheet for System Power Requirements -
12 VDC Input
For systems in which the system power supply is powered from a 12 VDC supply, use the
following table to calculate the number and type of system power supplies required to
power the system based on the 12 VDC LocalBus power requirements calculated in the
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power.
Remember to not exceed 8 A on the horizontal carrier and 15 A on the vertical carrier and
remember to include calculations for redundant system power. Add Subtotal 1 from the
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power and
Subtotal 2 from the Worksheet for Products Using Only 24 VDC Power to do the
calculation.
Table N-4: System Power Requirements - 12 VDC Input
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
System Power
Supply (Dual
DC/DC) 12 V
input
Provides 13
Amps @ 12 V
(Subtotal 1 /13
A = Quantity)
1.81
N/A
N/A
Redundant
System Power
Supply for
either Simplex
or Redundant
controllers (if
applicable)
1.82
N/A
Add for
Subtotal 4
Subtotal 4
N/A
Installation Worksheets
April 2021
D800001X312
538

--- Page 539 ---

Table N-4: System Power Requirements - 12 VDC Input (continued)
Product Type
Quantity
Amps Required for Each
Product
Total for Product Type
12 VDC
24 VDC
12 VDC
24 VDC
Add Subtotal 1
from
Worksheet for
Products
Using 12 V
LocalBus
Power and 24
VDC Bussed
Field Power.
Subtotal 1
Add Subtotal 2
from
Worksheet for
Products
Using Only 24
VDC Power
Subtotal 2
Add Subtotals
1, 2, and 4 for
total 12 and
24 VDC power
required.
Grand Total
1
The current required for I/O cards is included in the calculations in Table N-1 and is transferred
from Table N-1 to Table N-4 as Subtotal 1. The system power supply requires 1.8 A from the Bulk
12 VDC Power Supply to provide the power for each controller (one controller assumed for each
system power supply.) If on a large system, the current exceeds: the 8 A limit for horizontally
mounted systems, the 15 A limit for vertically mounted systems, or the 13 A system power
supply limit, use the cable extender and split the 12 VDC as described in Appendix J
2
The system power supply requires 1.8 A from the Bulk 12 VDC Power Supply to provide the power
for each controller (one controller assumed for each system power supply.)
Example Calculation for 12 VDC Input
Suppose your calculations from the Worksheet for Products Using 12 V LocalBus Power
and 24 VDC Bussed Field Power showed that the total 12 VDC power requires 6.1 A.
Calculate the number of power supplies required as follows:
6.1 A/13 A/supply =.47 or 1 system power supply for simplex power
and 2 system power supplies for redundant power.
If on a large system, the currents exceeds: the 8 A limit for horizontally mounted systems,
the 13 A system power supply limit, or the 15 A limit for vertically mounted systems, use
the cable extender and split out the 12 VDC as described in "System Power Guidelines" for
horizontal systems and "DeltaV Vertical Carriers" for vertical systems.
Related information
Worksheet for Products Using 12 V LocalBus Power and 24 VDC Bussed Field Power
Worksheet for Products Using Only 24 VDC Power
System Power Guidelines
Installation Worksheets
D800001X312 
April 2021
539

--- Page 540 ---

DeltaV Vertical Carriers
N.7
Worksheet for Bulk Power Requirements
Use the following table to calculate the number of legacy bulk supplies required to power
the system for each type based on the 12 VDC and 24 VDC power requirements calculated
in Worksheet for System Power Requirements - 12 VDC Input.
Table N-5: Bulk Power Requirements
Product Type
Quantity
Total Amps Needed for
System
Total Amps Available for
system
12 VDC
24 VDC
12 VDC
24 VDC
Legacy DIN
rail-mounted
Bulk Power
Supply 12 VDC
Provides 12
Amps each
(Grand Total
Table N-3 or
Table N-4 / 12
A = Quantity)
N/A
N/A
Legacy DIN
rail-mounted
Bulk Power
Supply 24 VDC
Provides 12
Amps each
(Grand Total
Table N-3 or
Table N-4 /12
A = Quantity)
N/A
N/A
Redundant
Legacy DIN
rail-mounted
12 VDC Bulk
Power Supply
(if applicable)
N/A
N/A
Redundant
Legacy DIN
rail-mounted
24 VDC Bulk
Power Supply
(if applicable)
N/A
N/A
Installation Worksheets
April 2021
D800001X312
540

--- Page 541 ---

Table N-5: Bulk Power Requirements (continued)
Product Type
Quantity
Total Amps Needed for
System
Total Amps Available for
system
12 VDC
24 VDC
12 VDC
24 VDC
Legacy Panel-
mounted Bulk
Power Supply
12 VDC
Provides 25
Amps each
(Grand Total
Table N-3 or
Table N-4 /25
A = Quantity)
N/A
N/A
Legacy Panel-
mounted Bulk
Power Supply
24 VDC
Provides 12.5
Amps each
(Grand Total
Table N-3 or
Table N-4 /
12.5 A =
Quantity)
N/A
N/A
Redundant
Legacy Panel-
mounted 12
VDC Bulk
Power Supply
(if applicable)1
N/A
N/A
Redundant
Legacy Panel-
mounted 24
VDC Bulk
Power Supply
(if applicable)1
N/A
N/A
1
An OR-ing diode is required for redundant bulk power supplies. Refer to Appendix I for
information.
N.8
Worksheet for Intrinsically Safe System Power
Requirements
Use the following table to size I.S. power for I.S. systems and add the total number of
required I.S. power supplies to Worksheet for Products Using Only 24 VDC Power.
Installation Worksheets
D800001X312 
April 2021
541

--- Page 542 ---

Table N-6: I.S. System Power Requirements
Product Type
Quantity
Amps Required for
Each Product
Total for Product
Type
I.S AI, 4-20, mA, 8-
Channel with HART
0.600
I.S. AO, 4-20 mA, 8-
Channel (with HART)
0.630
I.S. DI, 16-Channel
0.350
I.S. DO, 4-Channel
0.560
I.S. LocalBus Isolator
0.060
Grand total
I.S. System Power
Supply (5 A max each)
Provides 5 A @ 12 V
(Grand Total / 5A =
Quantity)
Redundant I.S. System
Power Supplies (1 max)
Total number of power
supplies (add to the
Worksheet for
Products Using Only 24
VDC Power )
Related information
Worksheet for Products Using Only 24 VDC Power
Installation Worksheets
April 2021
D800001X312
542