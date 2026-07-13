--- Page 260 ---

Figure C-87: 3-wire transmitter, field power supply
CH1
CH2
Power 
Supply
Common
DeltaV 
DC Ground
(DCG)
DeltaV Chassis 
Ground (CG)
Power 
Supply
Common
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Module Common
Channel 9
Channel 10
Channel 11
Channel 12
Module Common
Channel 13
Channel 14
Channel 15
Channel 16
Module Common
Module Common
Channel 1
Module Common
Chassis
Ground (CG)
To DIG
DeltaV Chassis 
Ground (CG)
DeltaV 
DC Ground
(DCG)
Control 
Room
Field
250Ω 
Low 
Pass 
Filter
A/D 
Converter
4-20mA 
Signal
Carrier
Isola!on
Field 
48-Pin
Mass
Termblock
250Ω 
Low 
Pass 
Filter
A/D 
Converter
4-20mA 
Signal
Isola!on
Field 
Channel 2
AI 16-Channel 4-20 mA HART Series 2 Plus
Field Power
 24 Pin Ribbon 
Cable
AI 16-Channel 4-20 mA HART Series 2 Plus
AI 4-20 mA Signal 
Condi"oning Card for 
1771 I/O
Primary
Secondary
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
April 2021
D800001X312
260

--- Page 261 ---

Figure C-88: 4-wire transmitter, field power supply
CH1
CH2
Power 
Supply
Common
DeltaV 
DC Ground
(DCG)
DeltaV Chassis 
Ground (CG)
Power 
Supply
Common
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Module Common
Channel 9
Channel 10
Channel 11
Channel 12
Module Common
Channel 13
Channel 14
Channel 15
Channel 16
Module Common
Module Common
Channel 1
Module Common
Chassis
Ground (CG)
To DIG
DeltaV Chassis 
Ground (CG)
DeltaV 
DC Ground
(DCG)
Control 
Room
Field
250Ω 
Low 
Pass 
Filter
A/D 
Converter
4-20mA 
Signal
Carrier
Isola!on
Field 
48-Pin
Mass
Termblock
250Ω 
Low 
Pass 
Filter
A/D 
Converter
4-20mA 
Signal
Isola!on
Field 
Channel 2
AI 16-Channel 4-20 mA HART Series 2 Plus
Field Power
 24 Pin Ribbon 
Cable
AI 16-Channel 4-20 mA HART Series 2 Plus
AI 4-20 mA Signal 
Condi"oning Card for 
1771 I/O
Primary
Secondary
DC Ground
(DCG)
Isolated Bus
To DIG
Note
Emerson recommends using isolated four-wire transmitters. For DC-powered, isolated 4-
wire transmitters, connect the power supply return to DeltaV DC ground to prevent
ground bounce from localized transients.
Ribbon-cable connector pinout
The following table shows the pinouts for the two ribbon-cable connectors of the Analog
Input 4-20 mA Signal Conditioning Card for PLC-5/1771 I/O.
Rear Connector (J1)
Front Connector (J2)
Pin 1
Channel 1 Signal
Pin 1
Channel 9 Signal
Pin 2
No Connection
Pin 2
No Connection
Pin 3
Channel 2 Signal
Pin 3
Channel 10 Signal
Pin 4
No Connection
Pin 4
No Connection
Pin 5
Channel 3 Signal
Pin 5
Channel 11 Signal
Pin 6
No Connection
Pin 6
No Connection
Pin 7
Channel 4 Signal
Pin 7
Channel 12 Signal
Pin 8
No Connection
Pin 8
No Connection
Pin 9
Channel 5 Signal
Pin 9
Channel 13 Signal
Interface Specifications
D800001X312 
April 2021
261

--- Page 262 ---

Rear Connector (J1)
Front Connector (J2)
Pin 10
No Connection
Pin 10
No Connection
Pin 11
Channel 6 Signal
Pin 11
Channel 14 Signal
Pin 12
No Connection
Pin 12
No Connection
Pin 13
Channel 7 Signal
Pin 13
Channel 15 Signal
Pin 14
No Connection
Pin 14
No Connection
Pin 15
Channel 8 Signal
Pin 15
Channel 16 Signal
Pin 16
No Connection
Pin 16
No Connection
Pin 17
Channel 1 DC GND
Pin 17
Channel 9 DC GND
Pin 18
Channel 2 DC GND
Pin 18
Channel 10 DC GND
Pin 19
Channel 3 DC GND
Pin 19
Channel 11 DC GND
Pin 20
Channel 4 DC GND
Pin 20
Channel 12 DC GND
Pin 21
Channel 5 DC GND
Pin 21
Channel 13 DC GND
Pin 22
Channel 6 DC GND
Pin 22
Channel 14 DC GND
Pin 23
Channel 7 DC GND
Pin 23
Channel 15 DC GND
Pin 24
Channel 8 DC GND
Pin 24
Channel 16 DC GND
Specifications
Table C-93: Analog Input 4-20 mA Signal Conditioning Card for PLC-5/1771 I/O
specifications
Item
Specification
Field device type
4-20 mA
Number of channels
16
Field signals
2- and 4-wire field-powered transmitters
Electrical connections
•
Front: one 1771-WG/WH swing arm
•
Bottom: two 24-pin ribbon-cable connectors
Maximum input voltage per channel
24 VDC
Maximum input current per channel
30 mA
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Interface Specifications
April 2021
D800001X312
262

--- Page 263 ---

Table C-93: Analog Input 4-20 mA Signal Conditioning Card for PLC-5/1771 I/O
specifications (continued)
Item
Specification
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.2
16-Channel, Discrete Input, 24 VDC Signal Conditioning
Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Input, 24 VDC Signal Conditioning Card for PLC-5/1771 I/O
replaces the 16-channel 1771-IBD 24 VDC DI card, providing an interface between 16
discrete input PLC signals and simplex or redundant Series 2 Plus DI, 32-Channel, 24
VDC, Dry Contact cards. Two 16-Channel, Discrete Input, 24 VDC Signal Conditioning
Cards for PLC-5/1771 I/O are required to connect to all 32 channels of one Series 2 Plus
DI, 32-Channel, 24 VDC, Dry Contact card.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 1771-WH swing arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Input 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant Series 2 Plus DI, 32-Channel, 24 VDC,
Dry Contact card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete input, 24 VDC-based field devices can be connected to the swing-arm
screw terminals.
Interface Specifications
D800001X312 
April 2021
263

--- Page 264 ---

Dimensional drawings
Figure C-89: Dimensions of 16-Channel, Discrete Input, 24 VDC Signal Conditioning
Card for PLC-5/1771 I/O
16.84 cm
(6.63 in.)
20.77 cm
(8.18 in.)
3.43 cm
(1.35 in.)
Wiring diagrams
The following diagram shows how to connect discrete input signals to a DeltaV system.
Figure C-90: Wiring diagram for redundant DC discrete input
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Channel 9
Channel 10
Channel 11
Channel 13
Channel 14
Channel 15
Channel 1
Chassis
Ground (CG)
To DIG
Carrier
Field Power
40-Pin
Mass
Termblock
Channel 16
Channel 2
 
 
 
DeltaV 
System
DeltaV 
System
Module Common
Channel 1
Channel 12
Channel 16
Primary
Secondary
 20-Pin Ribbon Cable
DI 32-Channel 24 VDC Dry 
Contact Series 2 Plus
DI 24 VDC Signal 
Condi!oning Card 
for 1771 I/O
DI 32-Channel 24 VDC Dry 
Contact Series 2 Plus
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
April 2021
D800001X312
264

--- Page 265 ---

Specifications
Table C-94: 16-Channel, Discrete Input, 24 VDC Signal Conditioning Card for 1771 I/O
specifications
Item
Specification
Field device type
24 VDC dry contact
Number of channels
16
Isolation
Channels share a common ground return.
Electrical connections
•
Front: one 1771-WH swing arm
•
Bottom: one 20-pin ribbon-cable connector
Nominal input current
•
4.5 mA at 10 VDC
•
15 mA at 30 VDC
Minimum ON-state voltage
10 VDC
Minimum OFF-state voltage
5 VDC
Input voltage range
10-30 VDC
Maximum nominal input impedance
2.2 kΩ
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.3
16-Channel, Discrete Input, 120 VAC/VDC Signal
Conditioning Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Input, 120 VAC/VDC Signal Conditioning Card for
PLC-5/1771 I/O replaces the 16-channel 1771-IAD 120 VAC/VDC DI card, providing an
interface between 16 discrete input PLC signals and simplex or redundant Series 2 Plus
DI, 32-Channel, 24 VDC, Dry Contact cards. Two 16-Channel, Discrete Input, 120
VAC/VDC Signal Conditioning Cards for 1771 I/O are required to connect to all 32
channels of one Series 2 Plus DI, 32-Channel, 24 VDC, Dry Contact card.
Interface Specifications
D800001X312 
April 2021
265

--- Page 266 ---

• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 1771-WH swing arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Input 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant Series 2 Plus DI, 32-Channel, 24 VDC,
Dry Contact card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete input, 120 VAC/VDC-based field devices can be connected to the
swing-arm screw terminals.
Time-delay jumper
The jumper switch on the bottom of the card determines the time delay of input signals
from OFF to ON. The time delay can be set at 5 ms or 20 ms. The default setting is 5 ms.
The following figure shows the two jumper settings.
Figure C-91: Time-delay jumper settings
5 ms filter setting
20 ms filter setting
Interface Specifications
April 2021
D800001X312
266

--- Page 267 ---

Dimensional drawings
Figure C-92: Dimensions of 16-Channel, Discrete Input, 120 VAC/VDC Signal
Conditioning Card for PLC-5/1771 I/O
16.84 cm
(6.63 in.)
20.77 cm
(8.18 in.)
3.43 cm
(1.35 in.)
Wiring diagrams
Figure C-93: Wiring diagram for 16-Channel, Discrete Input, 120 VAC/VDC Signal
Conditioning Card for PLC-5/1771 I/O
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Channel 9
Channel 10
Channel 11
Channel 13
Channel 14
Channel 15
Channel 1
Chassis
Ground (CG)
To DIG
Carrier
Field Power
 20-Pin Ribbon Cable
40-Pin
Mass
Termblock
Channel 16
Channel 2
 
 
 
DeltaV 
System
DeltaV 
System
Channel 1
Channel 12
Channel 16
N
G
Module Common
Primary
Secondary
DI 32-Channel 24 VDC Dry 
Contact Series 2 Plus
DI 120 VAC Signal 
Condi!oning Card 
for 1771 I/O
Secondary
DI 32-Channel 24 VDC Dry 
Contact Series 2 Plus
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
D800001X312 
April 2021
267

--- Page 268 ---

Specifications
Table C-95: 16-Channel, Discrete Input, 120 VAC/VDC Signal Conditioning Card for
PLC-5/1771 I/O specifications
Item
Specification
Field device type
120 VAC/VDC dry contact
Number of channels
16
Isolation
•
Field to system tested to 2,000 VDC for 2 s.
•
Channels must share a common return.
Electrical connections
•
Front: one 1771-WH swing arm
•
Bottom: one 20-pin ribbon-cable connector
Nominal input voltage
•
120 VAC at 50/60 Hz
•
125 VDC
Nominal input current
•
9.9 mA at 120 VAC at 60 Hz
•
8.7 mA at 120 VAC at 50 Hz
•
2.56 mA at 125 VDC
ON-state voltage range
79-138 VAC/VDC
Maximum OFF-state voltage
43 VAC/VDC
Input impedance
11.2 kΩ at 60 Hz
Input signal delay, OFF to ON
Time-delay jumper for 5 ms (default setting) and
20 ms
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
Interface Specifications
April 2021
D800001X312
268

--- Page 269 ---

C.6.4
16-Channel, Discrete Input, 120 VAC/VDC, Isolated
Signal Conditioning Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Input, 120 VAC/VDC, Isolated Signal Conditioning Card for
PLC-5/1771 I/O replaces the 16-channel 1771-ID16 120 VAC/VDC DI card, providing an
interface for 16 discrete input PLC signals and simplex or redundant Series 2 Plus DI,
32-Channel, 24 VDC, Dry Contact cards.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 40-position card-edge 1771-WN swing-arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Input 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant Series 2 Plus DI, 32-Channel, 24 VDC,
Dry Contact card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete input, 120 VAC/VDC-based field devices can be connected to the
swing-arm screw terminals.
Time-delay jumpers
Jumpers J1 and J4, on the bottom of the card, determine the time delay of input signals
from OFF to ON. J1 determines the time delay for channels 1-8 and J4 determines the time
delay for channels 9-16. The time delay can be set at 5 ms or 20 ms. The default setting is
20 ms. The following figure shows the two jumpers and their settings. Note that the figure
shows both jumpers in the same position in each example, but the jumpers are
independent of each other.
Interface Specifications
D800001X312 
April 2021
269

--- Page 270 ---

Figure C-94: Time-delay jumper settings
5 ms filter setting
20 ms filter setting
J4
J1
Dimensional drawings
Figure C-95: Dimensions of 16-Channel, Discrete Input, 120 VAC/VDC, Isolated Signal
Conditioning Card for PLC-5/1771 I/O
Field wiring
For each pair of screw terminals, connect the lower-numbered screw terminal to the load
and the higher-numbered screw terminal to the positive output of the power supply. The
following figure shows how to connect screw terminals 1 and 2 to discrete input 1.
Interface Specifications
April 2021
D800001X312
270

--- Page 271 ---

Figure C-96: Wiring diagram for 16-Channel, Discrete Input, 120 VAC/VDC, Isolated
Signal Conditioning Card for PLC-5/1771 I/O
L
120 VAC Source
N
1
3
5
4
2
6
DI1-
DI1+
Specifications
Table C-96: 16-Channel, Discrete Input, 120 VAC/VDC, Isolated Signal Conditioning
Card for PLC-5/1771 I/O specifications
Item
Specification
Field device type
120 VAC/VDC dry contact
Number of channels
16
Isolation
Field to system tested to 2,000 VDC for 2 s
Electrical connections
•
Front: one 1771-WN swing arm
•
Bottom: one 20-pin ribbon-cable connector
Nominal input voltage
•
120 VAC at 50/60 Hz
•
125 VDC
Nominal input current
•
9.9 mA at 120 VAC at 60 Hz
•
8.7 mA at 120 VAC at 50 Hz
•
2.56 mA at 125 VDC
ON-state voltage range
79-138 VAC/VDC
Maximum OFF-state voltage
43 VAC/VDC
Input impedance
11.2 kΩ at 60 Hz
Input signal delay, OFF to ON
Two time-delay jumpers for 5 ms and 20 ms
•
J1: channels 1-8
•
J4: channels 9-16
Interface Specifications
D800001X312 
April 2021
271

--- Page 272 ---

Table C-96: 16-Channel, Discrete Input, 120 VAC/VDC, Isolated Signal Conditioning
Card for PLC-5/1771 I/O specifications (continued)
Item
Specification
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.5
16-Channel, Discrete Output, 24 VDC Signal
Conditioning Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Output, 24 VDC Signal Conditioning Card for PLC-5/1771 I/O
replaces the 16-channel 1771-OBD 24 VDC DO card, providing an interface between16
discrete output PLC signals and simplex or redundant DO, 32-Channel, 24 VDC, High-
Side, Series 2 Plus cards. Each 16-Channel, Discrete Output, 24 VDC Signal
Conditioning Card for PLC-5/1771 I/O can drive 16 channels.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 1771-WH swing arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Output 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant Series 2 Plus DO, 32-Channel, 24 VDC,
High-Side card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete output, 24 VDC-based field devices can be connected to the swing-
arm screw terminals.
Interface Specifications
April 2021
D800001X312
272

--- Page 273 ---

Dimensional drawings
Figure C-97: Dimensions of 16-Channel, Discrete Output, 24 VDC Signal Conditioning
Card for PLC-5/1771 I/O
16.84 cm
(6.63 in.)
20.77 cm
(8.18 in.)
3.43 cm
(1.35 in.)
Wiring diagrams
Figure C-98: Wiring diagram for discrete output
Chassis
Ground (CG)
To DIG
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Channel 9
Channel 10
Channel 11
Channel 13
Channel 14
Channel 15
Channel 2
DO 32-Channel 24VDC 
High-Side, Series 2 Plus
Carrier
Field Power
40-Pin Mass 
Termblock
DeltaV 
System
Primary
Secondary
DO 32-Channel 24VDC 
High-Side, Series 2 Plus
DeltaV 
System
DO 24VDC
Signal 
Conditioning Card
for 1771 I/O
CH 1
Load
Channel 1
 20 Pin Ribbon 
Cable
Channel 12
Channel 16
DC Return
10 A
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
D800001X312 
April 2021
273

--- Page 274 ---

Specifications
Table C-97: 16-Channel, Discrete Output, 24 VDC Signal Conditioning Card for
PLC-5/1771 I/O specifications
Item
Specification
Field device type
24 VDC high-side
Number of channels
16
Isolation
•
1,000 VDC channel to system
•
Channels share a common ground return.
Electrical connections
•
Front: one 1771-WH swing arm
•
Bottom: one 20-pin ribbon-cable connector
User supply voltage
10-60 VDC
Output current rating
2 A per channel, not to exceed 8 A per card
Maximum surge current
•
4 A per channel for 10 ms, repeatable every
2 s
•
25 A per card for 10 ms, repeatable every 2 s
Maximum ON-state voltage drop
1.5 VDC at rated current
Minimum load current
2.5 mA per channel
Maximum OFF-state leakage current
0.5 mA per channel
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.6
16-Channel, Discrete Output, 120 VAC Signal
Conditioning Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Output, 120 VAC Signal Conditioning Card for PLC-5/1771
I/O replaces the 16-channel 1771-OAD 120 VAC DO card, providing an interface
between 16 discrete output PLC signals and simplex or redundant DO, 32-Channel, 24
Interface Specifications
April 2021
D800001X312
274

--- Page 275 ---

VDC, High-Side, Series 2 Plus cards. Each Discrete Output 120 VAC Signal Conditioning
Card for 1771 I/O can drive 16 discrete output channels.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 1771-WH swing arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Output 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant DO, 32-Channel, 24 VDC, High-Side,
Series 2 Plus card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete output, 120 VAC-based field devices can be connected to the swing-
arm screw terminals.
Dimensional drawings
Figure C-99: Dimensions of 16-Channel, Discrete Output, 120 VAC Signal
Conditioning Card for PLC-5/1771 I/O
16.84 cm
(6.63 in.)
20.77 cm
(8.18 in.)
3.43 cm
(1.35 in.)
Interface Specifications
D800001X312 
April 2021
275

--- Page 276 ---

Wiring diagrams
Figure C-100: Wiring diagram for 16-Channel, Discrete Output, 120 VAC Signal
Conditioning Card for PLC-5/1771 I/O
Chassis
Ground (CG)
To DIG
N
G
Channel 3
Channel 4
Channel 5
Channel 6
Channel 7
Channel 8
Channel 9
Channel 10
Channel 11
Channel 13
Channel 14
Channel 15
Channel 2
DO 32-Channel 24VDC 
High-Side, Series 2 Plus
Carrier
Field Power
40-Pin Mass 
Termblock
DeltaV 
System
Primary
Secondary
DO 32-Channel 24VDC 
High-Side, Series 2 Plus
DeltaV 
System
DO 120VAC
Signal Conditioning Card
for 1771 I/O
Zero-Crossing 
Opto-isola!on 
CH 1
Load
Channel 1
 20 Pin Ribbon 
Cable
Channel 12
Channel 16
Op!onal landing loca!on 
for AC return
10 A
DC Ground
(DCG)
Isolated Bus
To DIG
Specifications
Table C-98: 16-Channel, Discrete Output, 120 VAC Signal Conditioning Card for
PLC-5/1771 I/O specifications
Item
Specification
Field device type
120 VAC high-side
Number of channels
16
Isolation
•
Field to system tested to 2,000 VDC for 2 s.
•
Channels must share a common return.
Electrical connections
•
Front: one 1771-WH swing arm
•
Bottom: one 20-pin ribbon-cable connector
Output voltage range
10-138 VAC at 47-63 Hz
Output current rating
2 A per channel, not to exceed 8 A per card
Maximum surge current
•
25 A per channel for 10 ms, repeatable every
2 s
•
25 A per card for 10 ms, repeatable every 2 s
Interface Specifications
April 2021
D800001X312
276

--- Page 277 ---

Table C-98: 16-Channel, Discrete Output, 120 VAC Signal Conditioning Card for
PLC-5/1771 I/O specifications (continued)
Item
Specification
Maximum ON-state voltage drop
1.5 V at load current, 50 mA to 2 A
Minimum ON-state load current
50 mA per channel
Maximum OFF-state leakage current
3.0 mA at 138 VAC
Fusing
•
One fuse (10 A / 250 VAC, fast-acting,
cartridge, ceramic, 3AB, 3AG, 1/4” x 1-1/4”)
•
Littlelfuse P/N 0332010.HXP
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.7
16-Channel, Discrete Output, 120 VAC, Isolated Signal
Conditioning Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel, Discrete Output, 120 VAC, Isolated Signal Conditioning Card for
PLC-5/1771 I/O replaces the 16-channel 1771-OD16 and -ODD 120 VAC DO cards,
providing an interface between 16 discrete output PLC signals and simplex or
redundant DO, 32-Channel, 24 VDC, High-Side, Series 2 Plus cards. Each Discrete
Output 120 VAC Signal Conditioning Card for 1771 I/O can drive 16 discrete output
channels.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 40-position card-edge 1771-WN swing-arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Output 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant DO, 32-Channel, 24 VDC, High-Side,
Series 2 Plus card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
Interface Specifications
D800001X312 
April 2021
277

--- Page 278 ---

• Up to 16 discrete output, 120 VAC-based field devices can be connected to the swing-
arm screw terminals.
Dimensional drawings
Figure C-101: Dimensions of 16-Channel, Discrete Output, 120 VAC, Isolated Signal
Conditioning Card for PLC-5/1771 I/O
Field wiring
Each discrete output 1-16 corresponds to one pair of screw terminals on the 16-Channel,
Discrete Output, 120 VAC, Isolated Signal Conditioning Card for PLC-5/1771 I/O. For each
discrete-output, 120 VAC-based field device, connect the lower-numbered screw terminal
to the top of the load and the higher-numbered screw terminal to the bottom of the
power supply. The following figure shows how to use screw terminals 1 and 2 to connect
discrete output 1 to a field device.
Figure C-102: Wiring diagram for 16-Channel, Discrete Output, 120 VAC, Isolated
Signal Conditioning Card for PLC-5/1771 I/O
Load
L
120 VAC Source
N
1
3
5
4
2
6
DO1-
DO1+
Interface Specifications
April 2021
D800001X312
278

--- Page 279 ---

Specifications
Table C-99: 16-Channel, Discrete Output, 120 VAC, Isolated Signal Conditioning Card
for PLC-5/1771 I/O specifications
Item
Specification
Field device type
120 VAC
Number of channels
16
Isolation
Field to system tested to 2,000 VDC for 2 s
Electrical connections
•
Front: one 1771-WN swing arm
•
Bottom: one 20-pin ribbon-cable connector
Output voltage range
74-138 VAC at 47-63 Hz
Output current rating
2 A per channel, not to exceed 8 A per card
Maximum surge current
20 A per channel for 100 ms, repeatable every 2
s
Maximum ON-state voltage drop
•
5.8 V at load current less than 50 mA
•
1.5 V at load current 50 mA to 2 A
Minimum ON-state load current
5 mA per channel
Maximum OFF-state leakage current
3.0 mA at 138 VAC
Fusing
•
One fuse per channel (3.5 A, 250 VAC, fast-
acting, 2AG)
•
Littlelfuse P/N 022903 5MXP
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.8
16-Channel PLC-5 250 VAC/150 VDC DO Relay Signal
Conditioning Card
Installation notes
• The 16-Channel PLC-5 250 VAC/150 VDC DO Relay Signal Conditioning Card replaces
the 16-channel 1771-OW16 discrete output relay card, providing an interface between
Interface Specifications
D800001X312 
April 2021
279

--- Page 280 ---

16 discrete output PLC signals and simplex or redundant DO, 32-Channel, 24 VDC,
High-Side, Series 2 Plus cards. Each 16-Channel PLC-5 250 VAC/150 VDC DO Relay
Signal Conditioning Card can drive 16 discrete output channels.
• Use discrete outputs 1-8 for applications with normally open (NO) contacts. Use
discrete outputs 9-16 for applications with selectable normally closed (NC) and NO
contacts.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 40-position card-edge 1771-WN swing-arm.
• The 20-pin ribbon-cable connector on the bottom of the card provides connections for
a simplex or redundant Discrete Output 40-Pin Plus Mass Termination Block, which is
required to connect to a simplex or redundant DO, 32-Channel, 24 VDC, High-Side,
Series 2 Plus card.
• Use the consolidated ribbon cable to connect the signal conditioning card to the mass
termination block. Be sure to install the strain relief included with the cable at the end
connected to the signal conditioning card.
• Up to 16 discrete-output, 250 VAC/150 VDC field devices can be connected to the
swing-arm screw terminals.
Dimensional drawings
Figure C-103: Dimensions of 16-Channel PLC-5 250 VAC/150 VDC DO Relay Signal
Conditioning Card
Field wiring for applications with NO contacts only (discrete outputs 1-8)
Each discrete output 1-8 corresponds to one pair of screw terminals on the 16-Channel
PLC-5 250 VAC/150 VDC DO Relay Signal Conditioning Card. For each field device, connect
the lower-numbered screw terminal to the top of the load and the higher-numbered screw
terminal to the bottom of the power supply. The following table shows the discrete
outputs and their corresponding screw terminals.
Table C-100: Discrete outputs 1-8 and corresponding screw terminals
Discrete output
Screw terminal to top of load
Screw terminal to bottom of power
supply
1
1
2
Interface Specifications
April 2021
D800001X312
280

--- Page 281 ---

Table C-100: Discrete outputs 1-8 and corresponding screw terminals (continued)
Discrete output
Screw terminal to top of load
Screw terminal to bottom of power
supply
2
3
4
3
5
6
4
7
8
5
9
10
6
11
12
7
13
14
8
15
16
The following figure shows how to use screw terminals 1 and 2 to connect discrete output
1 to a field device.
Figure C-104: Example wiring for discrete output 1
Load
L
120 VAC Source
N
1
3
5
4
2
6
Common of DO1
Output of DO1
Coil
Field wiring for applications with selectable NO and NC contacts (discrete outputs
9-16)
Each discrete output 9-16 corresponds to one set of three screw terminals on the 16-
Channel PLC-5 250 VAC/150 VDC DO Relay Signal Conditioning Card. The following table
shows the outputs and their corresponding screw terminals.
Table C-101: 
Discrete output
Screw terminal to NC
Screw terminal to NO
Screw terminal to
common
9
17
18
19
10
20
21
22
11
23
24
25
12
26
27
28
Interface Specifications
D800001X312 
April 2021
281

--- Page 282 ---

Table C-101: (continued)
Discrete output
Screw terminal to NC
Screw terminal to NO
Screw terminal to
common
13
29
30
31
14
32
33
34
15
35
36
37
16
38
39
40
The following figure shows how to use screw terminals 17, 18, and 19 to connect discrete
output 9 to a relay and load.
Figure C-105: Example wiring for relay output 9
Load
L
120 VAC Source
N
17
19
21
20
18
22
Output 9 NO
Output 9 NC
Output 9 Common
OR
Specifications
Table C-102: 16-Channel PLC-5 250 VAC/150 VDC DO Relay Signal Conditioning Card
Item
Specification
Field device type
250 VAC/150VDC
Number of channels
•
16
—
1-8 NO
—
9-16 selectable NO/NC
Isolation
•
Channel to system: 250 VAC
•
Channel to channel: 250 VAC
Electrical connections
•
Front: one 1771-WN swing arm
•
Bottom: one 20-pin ribbon-cable connector
Output voltage range
•
24-250 VAC at 47-63 Hz
•
24-150 VDC
Interface Specifications
April 2021
D800001X312
282

--- Page 283 ---

Table C-102: 16-Channel PLC-5 250 VAC/150 VDC DO Relay Signal Conditioning Card
(continued)
Item
Specification
Output current rating
•
2 A per channel up to 260 VAC
•
2 A per channel at up to 40 VDC
•
1 A per channel at 100 VDC
•
0.5 A per channel at 100 VDC
•
0.25 A per channel at 150 VDC
Maximum surge current at 120 VAC
•
Make: 30 A
•
Break: 3 A
•
Continuous carrying current: 2 A
Maximum surge current at 240 VAC
•
Make: 15 A
•
Break: 1.5 A
•
Continuous carrying current: 2 A
Minimum contact load
10 mA
Operate time
8 ms
Release time
6 ms
Maximum switching frequency at maximum
load
1/3 Hz
Dimensions
•
Height: 208 mm (8.2 in.)
•
Width: 32 mm (1.3 in.)
•
Depth: 168 mm (6.6 in.)
Operating temperature range
-40 to 60 °C
Storage temperature range
-40 to 85 °C
Relative humidity range
5 to 95% non-condensing
Protection from airborne contaminants
ISA-S71.04-1985 Airborne Contaminants Class
G3 conformal coating
Shock
10 g, 1/2-sine wave for 11 ms
Vibration
1 mm peak-to-peak from 2 to 13.2 Hz, 0.7 g
from 13.2 to 150 Hz
C.6.9
Mounting brackets for signal conditioning cards
Five mounting kits are available to replace the 4-, 8-, 12-, and 16-wide OEM I/O chassis.
The two versions of the 12-wide mounting kit have ground studs in different locations to
match two versions of the 12-wide OEM I/O chassis. The mounting plate contained in the
replacement I/O chassis mounting kit fits into the same space and uses the same
mounting bolts as the OEM I/O chassis. There is a DIN rail installed on the mounting plate
that is used for the DeltaV I/O carrier, carrier extenders, and possibly a DeltaV controller.
Interface Specifications
D800001X312 
April 2021
283

--- Page 284 ---

There are 4-wide Signal Conditioning Card mounting hangers pre-installed on the
mounting plate.
The ground studs are in the same location on the OEM I/O chassis and on the DeltaV
mounting plates, so the grounding mechanisms can be re-used. The thread size of the
ground studs is M5 x 0.8 mm. Refer to the illustrations in this topic for the locations of
ground studs.
If your application requires a DeltaV controller to be mounted in the cabinet alongside the
PLC-5 I/O chassis, you can replace the DIN rail in the mounting kit with a longer DIN rail.
Each mounting kit includes a plastic spacer for use between the longer DIN rail and the
cabinet mounting plate.
For installations that do not require the entire mounting kit, the 4-wide Signal
Conditioning Card mounting hanger assembly is available as a spare part. Four screws are
required to mount this assembly to the cabinet mounting sub-panel.
Use a #2 Phillips screwdriver with a minimum 8-in. shank to attach a signal conditioning
card to the mounting-kit hanger assembly. Tighten until hand-tight.
Route the ribbon cables from the bottom of the signal conditioning card through the
plastic clips on each side of the mounting kit up to the mass termination block. Do not run
the ribbon cables through the space between the backplane of the mounting kit and the
4-wide mounting hanger assembly. The maximum length for ribbon cables is 10 m. Be
sure to install the strain relief included with the consolidated ribbon cable at the end
connected to the signal conditioning card.
Figure C-106: 4-Wide Mounting Kit for Signal Conditioning Cards
3.05 cm
1.20 in.
34.1 cm
13.43 in.
22.9 cm
9.02 in.
Ground stud
Interface Specifications
April 2021
D800001X312
284

--- Page 285 ---

Figure C-107: 8-Wide Mounting Kit for Signal Conditioning Cards
3.05 cm
(1.20 in.)
34.1 cm
(13.43 in.)
35.6 cm
(14.02 in.)
Ground stud
Figure C-108: 12-Wide R0 Mounting Kit for Signal Conditioning Cards
48.3 cm
(19.02 in.)
3.05 cm
(1.20 in.)
34.1 cm
(13.43 in.)
Ground studs
Interface Specifications
D800001X312 
April 2021
285

--- Page 286 ---

Figure C-109: 12-Wide R1 Mounting Kit for Signal Conditioning Cards
48.3 cm
(19.02 in.)
3.05 cm
(1.20 in.)
34.1 cm
(13.43 in.)
Ground stud
Figure C-110: 16-Wide Mounting Kit for Signal Conditioning Cards
34.1 cm
(13.43 in.)
3.05 cm
(1.20 in.)
Ground stud
61 cm
(24.02 in.)
Interface Specifications
April 2021
D800001X312
286

--- Page 287 ---

Figure C-111: 4-Card Hanger Assembly for Signal Conditioning Cards
20.59 cm
(8.11 in.)
12.8 cm
(5.04 in.)
2.4 cm
(0.94 in.)
C.7
Mass Connection Boards
The Mass Connection Boards eliminate the need for costly and complicated cabinet wiring
and simplify the process of connecting field devices to I/O cards.
C.7.1
AI/AO Mass Connection Board
Installation notes
• The AI/AO Mass Connection Board provides an interface to the simplex or redundant AI
16-channel 4-20 mA HART Plus card used with the simplex or redundant Analog Input
48-Pin Mass Terminal Block; the simplex or redundant AO 16-channel 4-20 mA HART
Plus card used with the simplex or redundant Analog Output 48-Pin Mass Terminal
Block; two AI 8-channel 4-20 mA HART cards used with the 16-Pin Mass Terminal Block;
or two AO 8-channel 4-20 mA HART cards used with the 16-Pin Mass Terminal Block; or
one AI and one AO 8-channel 4-20 mA HART card used with the 16-Pin Mass Terminal
Block.
• One AI/AO Mass Connection Board provides the interface to all 16 channels on the
simplex or redundant AI 16-channel 4-20 mA HART Plus card, on the simplex or
redundant AO 16-channel 4-20 mA HART Plus card, on two AI 8-channel 4-20 mA HART
cards, or on two AO 8-channel 4-20 mA HART cards, or on one AI and one AO 8-channel
4-20 mA HART card used with the 16-Pin Mass Terminal Block.
• Two 24-pin ribbon cables connect between the AI/AO Mass Connection Board and the
simplex or redundant Analog Input 48-Pin Mass Terminal Block or the simplex or
redundant Analog Output 48-Pin Mass Terminal Block. Two 16-pin ribbon cables
Interface Specifications
D800001X312 
April 2021
287

--- Page 288 ---

connect between the AI/AO Mass Connection Board and two 16-Pin Mass Terminal
Blocks.
• Three rows of screw terminals provide two- and four-wire connections for the AI
channels as well as two-wire connections for the AO channels. The rows of screw
terminals are numbered, top to bottom, n+, n, and n-, where n = 1-16 for each row.
• When using the AI/AO Mass Connection Board with a supported AI Plus card and a Mass
Terminal Block, connect 2-wire devices between n+ and n and 4-wire devices between
n and n-. When using any other supported AI or AO card and a Mass Terminal Block,
connect devices between n+ and n.
• Each channel has a Loop Disconnect pull switch. You can connect an ammeter to the 2
mm test points of a channel, then pull the pull switch to measure the current across the
channel without interrupting operation.
Specifications
Table C-103: AI/AO Mass Connection Board specifications
Item
Specification
Channel type
Same as attached card: AI or AO, 4-20 mA HART
Number of channels
16
Channel options and ratings
Same as attached card:
•
AI, 2-wire or 4-wire, 30 mA
•
AO, 30 mA
Isolation
None
Dimensions
•
Height: 102.7 mm (4.04 in.)
•
Width: 118.1 mm (4.65 in.)
•
Depth: 60.7 mm (2.38 in.)
Power input terminal wiring
0.05-2.08 mm2; 30-14 AWG
I/O terminal wiring
0.05-2.05 mm2; 30-12 AWG
Interface Specifications
April 2021
D800001X312
288

--- Page 289 ---

Figure C-112: AI/AO Mass Connection Board dimensions
118.1 mm
(4.65 in.)
60.7 mm
(2.38 in.)
102.7 mm
(4.04 in.)
Bottom view
Front view
Side view
Interface Specifications
D800001X312 
April 2021
289

--- Page 290 ---

Figure C-113: AI/AO Mass Connection Board parts locator diagram
24-pin connector
for 16 channels
24-pin connector
for 16 channels
16-pin connector for 
8-channel card
Channel 
test points
(x16)
16-pin connector for 
8-channel card
Loop disconnect 
pull switches
(x16)
Screw terminals for Mass
Connection Board shield connection 
Front View
Screw 
terminals
C.7.2
DI Mass Connection Board
Installation notes
• The DI Mass Connection Board provides an interface to the simplex DI 32-channel 24
VDC dry contact card used with the 40-Pin Mass Terminal Block.
• Two DI Mass Connection Boards (the DI Mass Connection Solution) are required to
provide the interface to all 32 channels on the DI 32-channel 24 VDC dry contact card.
• Two 20-pin ribbon cables (one per board) connect between the DI Mass Connection
Solution and the 40-pin Mass Terminal Blocks.
• Four screw terminals provide the connections for +24 VDC power and ground.
• The DI Mass Connection Board provides a relay output to detect termination faults that
indicate loss of input power to the board.
• For dry contact mode, connect your device between + and n, where n = 1-16. Refer to
the dry contact wiring diagram.
• For external power mode, connect the positive voltage output of your device to one
numbered screw terminal n, where n = 1-16, connect the return of the device to the
ground bar, and connect the ground bar to the GND terminals. Refer to the external
power mode wiring diagram below.
• Power-input and channel fuses can be replaced in the field.
Interface Specifications
April 2021
D800001X312
290

--- Page 291 ---

Specifications
Table C-104: DI Mass Connection Board specifications
Item
Specification
Field circuit power per board
+24 VDC ± 10% @ 75 mA typical, 100 mA
maximum
Channel type
Discrete input, +24 VDC dry contact; detection
on the - signal
Number of channels
16
Isolation
The field wiring connections are galvanically
isolated from the DI card circuits and factory
tested to 1000 VDC. No channel-to-channel
isolation.
Detection level for ON
> 2 mA @ 24 VDC
Source impedance
5 KΩ
Source voltage
+24 VDC input power, current limited with
replaceable fuse
Power input fuse
1 A, replaceable
Channel fuses
160 mA, replaceable
Dimensions
•
Height: 102.7 mm (4.04 in.)
•
Width: 102.8 mm (4.05 in.)
•
Depth: 60.7 mm (2.39 in.)
Power input terminal wiring
0.05-2.08 mm2; 30-14 AWG
I/O terminal wiring
0.05-2.05 mm2; 30-12 AWG
Interface Specifications
D800001X312 
April 2021
291

--- Page 292 ---

Figure C-114: DI Mass Connection Board dimensions
102.8 mm
(4.05 in.)
60.7 mm
(2.39 in.)
Bottom view
Front view
Side view
102.7 mm
(4.04 in.)
Interface Specifications
April 2021
D800001X312
292

--- Page 293 ---

Figure C-115: DI Mass Connection Board parts locator diagram
20-pin ribbon connector
for 16 channels
Power-input 
fuse
Power
LED
Power-input 
screw terminals
Channel
LEDs
Channel
fuses
Screw 
terminals
Front View
Interface Specifications
D800001X312 
April 2021
293

--- Page 294 ---

Figure C-116: Wiring for dry contact mode
DI BOARD
TERMINATION
+
+
+
–
–
+24 VDC
24 VDC FIELD POWER CONNECTION
System
Green
Yellow
0.16 A
1 A
5 K
+24 VDC
GND
GND
GND
1 ... 16
Figure C-117: Wiring for external power mode
DI BOARD
TERMINATION
+
+
–
–
+24 VDC
System
Green
Yellow
0.16 A
1 A
5 K
+24 VDC
GND
GND
GND
1 ... 16
24 VDC FIELD POWER CONNECTION
24
VDC
Source
+
–
+
Interface Specifications
April 2021
D800001X312
294

--- Page 295 ---

C.7.3
DI Plus Mass Connection Board
Installation notes
• The DI Plus Mass Connection Board provides an interface to the redundant DI 32-
channel 24 VDC dry contact Plus card in redundant mode only.
• Two DI Plus Mass Connection Boards (the DI Plus Mass Connection Solution) are
required to provide the interface to all 32 channels on the redundant DI 32-channel 24
VDC dry contact Plus card.
• Two 20-pin ribbon cables (one per board) connect between the DI Plus Mass
Connection Solution and the Redundant Discrete Input 40-pin Mass Terminal Block.
• When the redundant DI 32-channel 24 VDC dry contact Plus card is used with the
Redundant Discrete Input 40-pin Mass Terminal Block and the DI Plus Mass Connection
Solution, the card can be configured to detect termination faults. Two parameters,
T1_FAULT_DETECT (for the ribbon cable connection for channels 1-16), and
T2_FAULT_DETECT (for the ribbon cable connection for channels 17-32), can be
enabled in DeltaV Explorer for the card. Setting these parameters to True enables the
system to detect faults such as loss of power, a missing cable, or a missing Mass
Connection Board.
• Four screw terminals provide the connections for +24 VDC power and ground.
• The DI Plus Mass Connection Board provides a relay output to detect termination faults
that indicate loss of input power to the board.
• For dry contact mode, connect your device between + and n, where n = 1-16. Refer to
the dry contact wiring diagram below.
• For external power mode, connect the positive voltage output of your device to one
numbered screw terminal n, where n = 1-16, connect the return of the device to the
ground bar, and connect the ground bar to the GND terminals. Refer to the external
power mode wiring diagram below.
• Power-input and channel fuses can be replaced in the field.
Note
The termination fault detection feature is available only when the redundant DI 32-
channel 24 VDC dry contact Plus card is used with the Redundant Discrete Input 40-Pin
Mass Terminal Block connected to the DI Plus Mass Connection Solution.
Specifications
Table C-105: DI Plus Mass Connection Board specifications
Item
Specification
Field circuit power per board
+24 VDC ± 10% @ 75 mA typical,100 mA
maximum
Channel type
Discrete input, +24 VDC dry contact; detection
on the - signal
Number of channels
16
Interface Specifications
D800001X312 
April 2021
295

--- Page 296 ---

Table C-105: DI Plus Mass Connection Board specifications (continued)
Item
Specification
Isolation
The field wiring connections are galvanically
isolated from the DI card circuits and factory
tested to 1000 VDC. No channel-to-channel
isolation.
Detection level for ON
> 2 mA @ 24 VDC
Source impedance
5 KΩ
Source voltage
+24 VDC input power, current limited with
replaceable fuse
Power input fuse
1 A, replaceable
Channel fuses
160 mA, replaceable
Dimensions
•
Height: 102.7 mm (4.04 in.)
•
Width: 102.8 mm (4.05 in.)
•
Depth: 60.7 mm (2.39 in.)
Power input terminal wiring
0.05-2.08 mm2; 30-14 AWG
I/O terminal wiring
0.05-2.05 mm2; 30-12 AWG
Figure C-118: DI Plus Mass Connection Board dimensions
102.8 mm
(4.05 in.)
60.7 mm
(2.39 in.)
Bottom view
Front view
Side view
102.7 mm
(4.04 in.)
Interface Specifications
April 2021
D800001X312
296

--- Page 297 ---

Figure C-119: DI Plus Mass Connection Board parts locator diagram
20-pin ribbon connector
for 16 channels
Power-input 
fuse
Power
LED
Power-input 
screw terminals
Channel
LEDs
Termination-fault 
relay bypass 
jumper (affects 
signal to I/O 
card only)
Channel
fuses
Screw 
terminals
Front View
Interface Specifications
D800001X312 
April 2021
297

--- Page 298 ---

Figure C-120: Wiring for dry contact mode
DI BOARD
TERMINATION
+
+
+
–
–
+24 VDC
24 VDC FIELD POWER CONNECTION
System
Green
Yellow
0.16 A
1 A
5 K
+24 VDC
GND
GND
GND
1 ... 16
Figure C-121: Wiring for external power mode
DI BOARD
TERMINATION
+
+
–
–
+24 VDC
System
Green
Yellow
0.16 A
1 A
5 K
+24 VDC
GND
GND
GND
1 ... 16
24 VDC FIELD POWER CONNECTION
24
VDC
Source
+
–
+
Interface Specifications
April 2021
D800001X312
298

--- Page 299 ---

C.7.4
DO Mass Connection Board
Installation notes
• The DO Mass Connection Board provides an interface to the DO 32-channel 24 VDC
high-side or high-side Plus card used with the 40-Pin Mass Terminal Block in simplex
mode or with the Redundant Discrete Output 40-Pin Mass Terminal Block. The DO
Mass Connection Board also provides an interface to the DO 8-channel 24 VDC high-
side card used with the 16-Pin Mass Terminal Block.
• Four DO Mass Connection Boards (the DO Mass Connection Solution) are required to
provide the interface to all 32 channels on the DO 32-channel 24 VDC high-side card.
• Two 20-pin ribbon cables (one per board pair) connect the DO Mass Connection
Solution to the 40-pin Mass Terminal Blocks. Two additional 20-pin ribbon cables
connect each pair of DO Mass Connection Boards together, as shown in Figure C-127.
• The DO Mass Connection Board provides a relay output to detect termination faults
that indicate loss of input power to the board.
• When the redundant DO 32-channel 24 VDC high-side Plus card is used with the
Redundant Discrete Output 40-Pin Mass Terminal Block and the DO Mass Connection
Solution, the card can be configured to detect faults in the termination. Two
parameters, T1_FAULT_DETECT (for the ribbon cable connection for channels 1-16),
and T2_FAULT_DETECT (for the ribbon cable connection for channels 17-32), can be
enabled in DeltaV Explorer for the card. Setting these parameters to True enables
detection of the ribbon cable connection between the Redundant Discrete Output 40-
Pin Mass Terminal Block and the DO Mass Connection Board, and detection of faults
such as loss of power, a missing cable, or a missing Mass Connection Board. You can
disable termination-fault detection using a jumper on the board if you need to rewire
while a process is running.
• Four screw terminals provide the connections for +24 VDC power and ground.
• If you are using an external +24 VDC source for a channel, move the fuse for that
channel to the FIELD PWR position. Otherwise, leave the fuse in the MODULE PWR
position. Refer to the parts locator and wiring diagrams for more information.
• The power-input fuse, channel fuses, and relays can be replaced in the field.
Note
Termination fault detection is available only when the redundant DO 32-channel 24 VDC
high-side Plus card is used with the Redundant Discrete Output 40-Pin Mass Terminal
Block connected to the DO Mass Connection Solution.
Specifications
Table C-106: DO Mass Connection Board specifications
Item
Specification
Power for +24 VDC high-side outputs (optional)
+24 VDC ±10% at 10 A maximum
Control signal current per channel (derived from
the DO 32-channel 24 VDC, high-side plus card.)
14 mA maximum
Channel type
Relay output
Interface Specifications
D800001X312 
April 2021
299

--- Page 300 ---

Table C-106: DO Mass Connection Board specifications (continued)
Item
Specification
Number of channels
8
Output channel options and ratings
•
Isolated relay contacts: 250 VAC/24 VDC
maximum at 5 A maximum per channel.1
•
+24 VDC high side: 5 A maximum per
channel,2 10 A maximum per board.
Channel relays
Phoenix Contact no. 2961105
Termination fault relay
2 A at 30 VDC maximum
Relay contact ratings
•
28.8 VDC at 5 A switching current
•
48 VDC at 0.4 A switching current
•
250 VAC at 5 A switching current
Isolation
•
Isolated relay contacts: Isolated at 250 VAC
and factory tested to 3000 VDC (channel to
system and channel to channel).
•
+24 VDC high side: Isolated at 250 VAC and
factory tested to 3000 VDC (channel to
system). No channel-to-channel isolation.
Dimensions
•
Height: 102.7 m (4.04 in.)
•
Width: 133.3 mm (5.25 in.)
•
Depth: 60.7 mm (2.39 in.)
Power input terminal wiring
0.05-2.08 mm2; 30-14 AWG
I/O terminal wiring
0.05-2.05 mm2; 30-12 AWG
1
De-rate to 3 A per channel when operating above 60 °C ambient temperature.
2
De-rate to 3 A per channel when operating above 60 °C ambient temperature.
Interface Specifications
April 2021
D800001X312
300

--- Page 301 ---

Figure C-122: DO Mass Connection Board dimensions
133.3 mm
(5.25 in.)
60.7 mm
(2.39 in.)
Bottom view
Front view
Side view
102.7 mm
(4.04 in.)
Interface Specifications
D800001X312 
April 2021
301

--- Page 302 ---

Figure C-123: DO Mass Connection Board parts locator diagram
Channel relay 
(x8)
16-pin connector
for 8-channel card
Expansion 
jumper
Power-input
fuse
Fuse position
for module
power
Fuse position
for external
power
Screw
terminals
20-pin connector
for 16 channels of
32-channel card
20-pin connector
for 16 channels of
32-channel card
Front View
Power LED
Power-input
screw terminals
Channel LED
(x8)
Termination-fault relay
bypass jumper (affects 
signal to I/O card only)
Figure C-124: Wiring for external power mode
System
Yellow
+
+
–
–
5 A Fuse
Load
–
+
DO BOARD
TERMINATION
24 VDC FIELD POWER CONNECTION
Green
10 A Fuse
NO
NC
–
GND
COM
+24 VDC
+24 VDC
GND
GND
VDC
or VAC
Source
Interface Specifications
April 2021
D800001X312
302

--- Page 303 ---

Figure C-125: Wiring for 24 VDC high side output mode
DO BOARD
TERMINATION
+
+
–
+
NO
+
NC
–
–
+24 VDC
5 A Fuse
Green
10 A Fuse
+24 VDC
GND
GND
GND
COM
System
Yellow
Load
24 VDC FIELD POWER CONNECTION
C.7.5
Connecting DI and DO Mass Connection Boards
The following images show how to connect the DI Mass Connection Boards together and
how to connect the DO Mass Connection Boards together.
Figure C-126: Connected DI Mass Connection Boards
Ribbon cable connector for
channels 1-16
Ribbon cable connector for
channels 17-32
+24VDC+24VDC GND   GND
+24VDC+24VDC GND   GND
Interface Specifications
D800001X312 
April 2021
303

--- Page 304 ---

Figure C-127: Connected DO Mass Connection Boards
Jumper in
BASE position
Ribbon
cable
+24 VDC
Return
Ribbon cable to 
bottom connector of 
DO terminal block
Ribbon cable to 
top connector of 
DO terminal block
Jumper in
EXPANSION position
Jumper in
BASE position
Ribbon
cable
+24 VDC
Return
Channels 9–16
Channels 25–32
Channels 1–8
Channels 17–24
Jumper in
EXPANSION position
C.8
Intrinsically Safe Terminal Blocks
The DeltaV system can use the following types of Intrinsically Safe terminal blocks:
• I.S. 8-channel and I.S. loop disconnect 8-channel
• I.S. 16-Channel Terminal Block
C.8.1
I.S. 8-Channel Terminal Block
The 8-channel I.S. terminal block uses standard and loop disconnects. Loop disconnects
are located in odd numbered terminals.
Interface Specifications
April 2021
D800001X312
304

--- Page 305 ---

Specifications
Table C-107: I.S. 8-Channel Terminal Block Specifications
Item
Specification
Voltage rating
250 VAC between I.S. and non-I.S. circuits.
Maximum current
Refer to the specifications table for the I.S. card
in use.
Mounting
Assigned slot of I.S. I/O carrier.
Terminal Block Connections
The following table lists the cable pin out connections for the I.S. 8-Channel Terminal Block
and shows the channel nomenclature for the I.S. analog input and output cards (AI, 2-20
mA, 8-Channel with HART, AO, 2-20 mA, 8-Channel) and the discrete output card (DO, 4-
Channel).
Table C-108: I.S. 8-Channel Terminal Block Cable Pin Outs and Channel Nomenclature 
Pin on Termination Block
Channel Nomenclature for
Analog Cards
Channel Nomenclature for
DO card
Terminal 1
Channel 1+
Channel 1+
Terminal 2
Channel 1-
Terminal 3
Channel 2+
Channel 1-
Terminal 4
Channel 2-
Terminal 5
Channel 3+
Channel 2+
Terminal 6
Channel 3-
Terminal 7
Channel 4+
Channel 2-
Terminal 8
Channel 4-
Terminal 9
Channel 5+
Channel 3+
Terminal 10
Channel 5-
Terminal 11
Channel 6+
Channel 3-
Terminal 12
Channel 6-
Terminal 13
Channel 7+
Channel 4+
Terminal 14
Channel 7-
Terminal 15
Channel 8+
Channel 4-
Terminal 16
Channel 8-
Interface Specifications
D800001X312 
April 2021
305

--- Page 306 ---

C.8.2
I.S. 16-Channel Terminal Block
Specifications
Table C-109: I.S. 16-Channel Terminal Block Specifications
Item
Specification
Voltage rating
250 VAC between I.S. and non-I.S. circuits.
Maximum current
Refer to the specifications table for the I.S. card
in use.
Mounting
Assigned slot of I.S. I/O carrier.
Terminal Block Connections
Figure C-128: I.S. 16-Channel Terminal Block
Bottom View
Ch
1
Ch
2
Ch
3
Ch
4
Ch
5
Ch
6
Ch
7
Ch
8
Ch
9
Ch
10
Ch
11
Ch
12
Ch
13
Ch
14
Ch
15
Ch
16
+
-
+
-
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
Front View
Keying (B1)
The following table lists the cable pin out connections for the I.S.16-channel terminal
block.
Table C-110: I.S.16-Channel Terminal Block
Terminal on
Termination Block
Channel
Nomenclature
Terminal on
Termination Block
Channel
Nomenclature
Terminal 1
Channel 1+
Terminal 17
Channel 9+
Terminal 2
Channel 1-
Terminal 18
Channel 9-
Terminal 3
Channel 2+
Terminal 19
Channel 10+
Terminal 4
Channel 2-
Terminal 20
Channel 10-
Terminal 5
Channel 3+
Terminal 21
Channel 11+
Interface Specifications
April 2021
D800001X312
306

--- Page 307 ---

Table C-110: I.S.16-Channel Terminal Block (continued)
Terminal on
Termination Block
Channel
Nomenclature
Terminal on
Termination Block
Channel
Nomenclature
Terminal 6
Channel 3-
Terminal 22
Channel 11-
Terminal 7
Channel 4+
Terminal 23
Channel 12+
Terminal 8
Channel 4-
Terminal 24
Channel 12-
Terminal 9
Channel 5+
Terminal 25
Channel 13+
Terminal 10
Channel 5-
Terminal 26
Channel 13-
Terminal 11
Channel 6+
Terminal 27
Channel 14+
Terminal 12
Channel 6-
Terminal 28
Channel 14-
Terminal 13
Channel 7+
Terminal 29
Channel 15+
Terminal 14
Channel 7-
Terminal 30
Channel 15-
Terminal 15
Channel 8+
Terminal 31
Channel 16+
Terminal 16
Channel 8-
Terminal 32
Channel 16-
C.9
I/O Interface Keying
There are two keys on the I/O terminal block and two keys on the I/O card. The keys on the
I/O card are set at the factory; you can change the keys on the I/O terminal block to match
the corresponding I/O card.
Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
AI, 8-Channel, 4-20 mA
A 1
I/O terminal block
•
Fused I/O terminal
block
•
4-wire I/O terminal
block
•
16-pin mass
termination block
(2-wire
connection)
•
24-pin mass
termination block
(4-wire
connection)
Interface Specifications
D800001X312 
April 2021
307

--- Page 308 ---

Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks (continued)
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
•
AI, 8-Channel,4-20
mA, HART
•
Series 2 AI, 8-
Channel,4-20 mA,
HART (Simplex
mode)
A 1
I/O terminal block
•
Fused I/O terminal
block
•
4-wire I/O terminal
block
•
16-pin mass
termination block
(2-wire
connection)
•
24-pin mass
termination block
(4-wire
connection)
Series 2 AI, 8-Channel,
4-20 mA HART
(Redundant mode)
A 1
Redundant Analog
Input terminal block
Series 2 AI, 16-
Channel, 4-20 mA
HART (Simplex mode)
A2
16-Channel Analog
Input terminal block
4-wire 16-Channel
Analog Input Terminal
Block
Series 2 Plus, AI, 16-
Channel, 4-20 mA,
HART (Simplex mode)
A6
Simplex 2-Wire 16-
Channel Analog Input
terminal block
•
Simplex 4-Wire 16-
Channel Analog
Input terminal
block
•
48-pin AI Plus mass
termination block
Series 2 Plus, AI, 16-
Channel, 4-20 mA,
HART (Redundant
mode)
A6
Redundant 16-Channel
Analog Input terminal
block
Redundant Analog
Input 48-Pin Mass
Termination block
AI, 8-Channel, 1-5 VDC
A3
4-wire I/O terminal
block
24-pin mass
termination block
AO, 8-Channel,4-20
mA
A4
I/O terminal block
•
Fused I/O terminal
block
•
16-pin mass
termination block
•
AO, 8-channel,4-20
mA, HART
•
Series 2 AO, 8-
channel, 4-20 mA,
HART (Simplex
mode)
A4
I/O terminal block
•
Fused I/O terminal
block
•
16-pin mass
termination block
Series 2 AO, 8-channel,
4-20 mA, HART
(Redundant mode)
A4
Redundant Analog
Output terminal block
Interface Specifications
April 2021
D800001X312
308

--- Page 309 ---

Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks (continued)
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
Series 2 Plus AO, 16-
Channel, 4-20 mA,
HART (Simplex mode)
A5
Simplex 16-Channel
Analog Output
terminal block
Analog Output 48-pin
mass termination
block
Series 2 Plus AO, 16-
Channel, 4-20 mA,
HART (Redundant
mode)
A5
Redundant 16-Channel
Analog Output
terminal block
Redundant 48-pin AO
Plus mass termination
block
AS-Interface Series 2
AS-Interface (Simplex
mode)
D1
Interface terminal
block
DeviceNet
D5
Fieldbus H1 terminal
block
•
DI, 8-Channel, 24
VDC, Isolated
•
Series 2 DI, 8-
Channel, 24 VDC,
Isolated (Simplex
mode)
B2
I/O terminal block
•
Fused I/O terminal
block
•
16-pin mass
termination block
•
DI, 8-Channel, 24
VDC, Dry Contact
•
Series 2 DI, 8-
Channel, 24 VDC,
Dry Contact
(Simplex mode)
B1
Fused I/O terminal
block
•
I/O terminal block
•
16-pin mass
termination block
Series 2 DI, 8-Channel,
24 VDC, Dry Contact
(Redundant mode)
B1
Redundant Discrete
terminal block
•
DI, 8-Channel, 120
VAC, Isolated
•
Series 2 DI, 8-
Channel, 120 VAC,
Isolated
E4
I/O terminal block
Fused I/O terminal
block
•
DI, 8-Channel, 120
VAC, Dry Contact
•
Series 2 DI, 8-
Channel, 120 VAC,
Dry Contact
(Simplex mode)
E1
Fused I/O terminal
block
I/O terminal block
DI, 8-Channel, 230
VAC, Isolated
E5
I/O terminal block
Fused I/O terminal
block
DI, 8-Channel, 230
VAC, Dry Contact
E2
Fused I/O terminal
block
I/O terminal block
Interface Specifications
D800001X312 
April 2021
309

--- Page 310 ---

Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks (continued)
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
•
DI, 32-channel, 24
VDC Dry Contact
•
Series 2 DI, 32-
channel, 24 VDC
Dry (Simplex
mode)
B3
32-channel terminal
block
40-pin mass
termination block
Series 2 Plus DI, 32-
Channel, 24 VDC, Dry
Contact (Simplex
mode)
E3
Simplex 32-Channel DI
Plus terminal block
Simplex 40-pin DI Plus
mass termination
block
Series 2 Plus DI, 32-
Channel, 24 VDC, Dry
Contact (Redundant
mode)
E3
Redundant 32-Channel
Discrete Input terminal
block
Redundant Discrete
Input 40-Pin mass
termination block
•
DO, 8-Channel,
120 VAC/230 VAC,
Isolated
•
Series 2 DO, 8-
Channel, 120
VAC/230 VAC,
Isolated (Simplex
mode)
F4
I/O terminal block
Fused I/O terminal
block
•
DO, 8-Channel,
120 VAC/230 VAC,
High-Side
•
Series 2 DO, 8-
Channel, 120
VAC/230 VAC,
High-Side (Simplex
mode)
F1
Fused I/O terminal
block
I/O terminal block
•
DO, 8-Channel, 24
VDC, Isolated
•
Series 2 DO, 8-
Channel, 24 VDC,
Isolated
B5
I/O terminal block
•
Fused I/O terminal
block
•
16-pin mass
termination block
•
DO, 8-Channel, 24
VDC, High-Side
•
Series 2 DO, 8-
Channel, 24 VDC,
High-Side (Simplex
mode)
B6
Fused I/O terminal
block
•
I/O terminal block
•
10-pin mass
termination block
•
16-pin mass
termination block
Interface Specifications
April 2021
D800001X312
310

--- Page 311 ---

Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks (continued)
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
Series 2 DO, 8-
Channel, 24 VDC,
High-Side (Redundant
mode)
B6
Redundant Discrete
terminal block
•
DO, 32-Channel,
24 VDC High-Side
•
Series 2 DO, 32-
Channel, 24 VDC
High Side (Simplex
mode)
B4
32-channel terminal
block
40-pin mass
termination block
Series 2 Plus DO, 32-
Channel, 24 VDC High
Side (Simplex mode)
B4
Simplex 32-channel
DO Plus terminal block
40-pin Discrete Output
mass termination
block
Series 2 Plus DO, 32-
Channel, 24 VDC High
Side (Redundant
mode)
B4
Redundant 32-Channel
Discrete Output
terminal block
Redundant Discrete
Output 40-Pin Mass
termination block
Fieldbus H1
D6
Fieldbus H1 terminal
block
Fieldbus H1 4-Port
Series 2 Plus (Simplex
mode)
D2
Simplex H1 4-Port
Terminal Block
Fieldbus H1 4-Port
Series 2 Plus
(Redundant mode)
D2
Redundant H1 4-Port
Terminal Block
Series 2 H1 (Simplex
mode)
D6
Series 2 H1 terminal
block
Series 2 H1
(Redundant mode)
D6
Redundant H1
terminal block
Series 2 Isolated Input
(Simplex mode)
C2
Isolated Input terminal
block
Multifunction
C6
32-channel terminal
block
Profibus DP
D3
Profibus DP terminal
block
Series 2 Plus Profibus
D3
Redundant Profibus DP
terminal block
RTD, ohms
C3
RTD, ohms terminal
block
Sequence of Events
C5
32-channel terminal
block
40-pin mass
termination block
Interface Specifications
D800001X312 
April 2021
311

--- Page 312 ---

Table C-111: Non-I.S. I/O Card Keying and Compatible I/O Terminal Blocks (continued)
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
•
Serial Card, 2 Ports,
RS232/RS485
•
Series 2 Serial Card,
2 Ports, RS232/
RS485 (Simplex
mode)
D4
Interface terminal
block
Series 2 Serial Card, 2
Ports, RS232/RS485
(Redundant mode)
D4
Redundant Interface
terminal block
Thermocouple, mV
C1
Thermocouple, mV
terminal block.
Note
When the
Thermocouple, mV
card is plugged into a
Thermocouple
terminal block, it
functions as a
Thermocouple card.
I/O terminal block
Note
When the
Thermocouple, mV
card is plugged into an
I/O terminal block, it
functions as an mV
card.
Figure C-129: I/O Key Setting Example
C.9.1
Intrinsically Safe I/O Interface Keying
The following table lists I.S. I/O card keying and the recommended I.S. terminal blocks.
I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
I.S. AI, 8-Channel, 4-20
mA, HART
A1
I.S. 8-channel terminal
block
I.S. loop disconnect 8-
channel terminal block
I.S. AO, 8-Channel,
4-20 mA (HART)
A4
I.S. 8-channel terminal
block
I.S. loop disconnect 8-
channel terminal block
Interface Specifications
April 2021
D800001X312
312

--- Page 313 ---

I/O Card
I/O Card Keying
Recommended I/O
Terminal Block
Optional I/O Terminal
Block
I.S. DO, 4-Channel
B5
I.S. 8-channel terminal
block
I.S. loop disconnect 8-
channel terminal block
I.S. DI, 16-Channel1
B1
I.S. 16-channel
terminal block
1
The I.S. DI, 16-channel card will not communicate with the DeltaV controller unless the I.S. 16-
channel terminal block is used.
Figure C-130: I.S. I/O Example Key Setting
Interface Specifications
D800001X312 
April 2021
313

--- Page 314 ---

Interface Specifications
April 2021
D800001X312
314