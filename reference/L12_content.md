--- Page 195 ---

C.1.28
Serial Card, 2 Ports, RS232/RS485
The DeltaV system supports the Serial Card, 2 Ports, RS232/RS485 and the Series 2 Serial
Card, 2 Ports, RS232/RS485.
The DeltaV Serial Card provides an interface to a variety of serial devices, such as PLCs
(Programmable Logic Controllers) that use the Modbus RTU or ASCII protocol. With the
DeltaV Explorer, you can configure each of the two ports provided on the serial card to
support RS232, RS422/485 half duplex, or RS422/485 full duplex signals and you can
configure the baud rate of each port.
Installation Notes
• For CE compliance, use shielded cables to connect the serial card to external devices.
Ground the cable shield at one end only. If the external device does not provide a
mechanism to ground the cable shield, connect the shield to the DeltaV Carrier Shield
Bar. If you use the RS422/485 ports, the shield must also provide the ground reference
for the port. Connect the cable shield to the corresponding ground (GND) terminal on
the interface terminal block.
• The Interface terminal block is recommended to provide screw terminations for field
wiring for the Serial card and the Series 2 Serial card in Simplex mode.
• The Redundant Interface terminal block is recommended to provide screw
terminations for field wiring for the Series 2 Serial card in Redundant mode.
• Refer to ANSI TIA/EIA-485-A for RS485 full duplex termination requirements.
The following tables define the terminal assignments for RS232, RS422/485 half duplex,
and RS422/485 full duplex port types.
Table C-33: RS232 Terminal Assignments
Terminal
Assignment
Terminal 1
Port 1 GND
Terminal 3
Port 1 TXD
Terminal 5
Port 1 RXD
Terminal 7
Port 1 DTR
Terminal 8
Port 1 DSR
Terminal 9
Port 2 GND
Terminal 11
Port 2 TXD
Terminal 13
Port 2 RXD
Terminal 15
Port 2 DTR
Terminal 16
Port 2 DSR
Table C-34: RS422/485 Half Duplex Terminal Assignments
Terminal
Assignment
Terminal 1
Port 1 GND
Terminal 2
Port 1 DATA+
Interface Specifications
D800001X312 
April 2021
195

--- Page 196 ---

Table C-34: RS422/485 Half Duplex Terminal Assignments (continued)
Terminal
Assignment
Terminal 4
Port 1 DATA-
Terminal 9
Port 2 GND
Terminal 10
Port 2 DATA+
Terminal 12
Port 2 DATA-
Note
RS-485 Full Duplex is not supported when the card is configured as a Modbus slave in a
multidrop environment.
Table C-35: RS422/485 Full Duplex Terminal Assignments
Terminal
Assignment
Terminal 1
Port 1 GND
Terminal 2
Port 1 TXD+
Terminal 4
Port 1 TXD-
Terminal 6
Port 1 RXD+
Terminal 8
Port 1 RXD-
Terminal 9
Port 2 GND
Terminal 10
Port 2 TXD+
Terminal 12
Port 2 TXD-
Terminal 14
Port 2 RXD+
Terminal 16
Port 2 RXD-
Table C-36: Serial Card, 2 Ports, RS232/RS485 Specifications
Item
Specification
Number of serial ports
Two
Port types
RS232, RS422/485 half duplex, RS422/485 full
duplex (configurable with the DeltaV Explorer)
Isolation
Each port is optically isolated from the system
and from each other and factory tested to 1500
VDC. The ports must be grounded via the
external device.
Baud rate
Configurable with the DeltaV Explorer
Maximum cable lengths
•
RS232: 15 m (50 ft)
•
RS422/485: 610 m (2000 ft)
LocalBus current (12 VDC nominal), per card
200 mA typical, 300 mA maximum
Field circuit power, per card
None
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
196

--- Page 197 ---

Figure C-46shows a wiring scheme from Port 1 on the Interface terminal block for a Serial
card and a Series 2 Serial card in Simplex mode to a Modicon Model 984 controller.
Figure C-46: Wiring Example, Interface Terminal Block, Serial Card
The following figure shows an example for connecting a primary and secondary computer
to a Redundant Interface terminal block for a Series 2 Serial card in Redundant mode. For
each computer, use the same wiring scheme as shown in Figure C-46.
Figure C-47: Wiring Example for Redundant Interface Terminal Block
Related information
Interface Terminal Block
Redundant Interface Terminal Block
Interface Specifications
D800001X312 
April 2021
197

--- Page 198 ---

C.1.29
Thermocouple, mV
The DeltaV system supports the Thermocouple, mV card and the Series 2 Thermocouple,
mV card in Simplex mode.
Installation Notes
• The Thermocouple terminal block is recommended to provide screw terminations for
field wiring for the Thermocouple, mV card. An optional terminal block is the I/O
terminal block.
• If this card is used with a Thermocouple terminal block, it functions as a Thermocouple
card; if it is used with an 8-channel terminal block, it functions as a mV card.
• If this card is used with a Thermocouple terminal block, it passes a small current
through the thermocouple wire continuously to detect an open loop. The longer the
thermocouple wire, the greater the offset voltage. Refer to Emerson Knowledge Base
Article NK-1900-1146 for information about calculating the offset voltage for your
application.
Specifications
Table C-37: Thermocouple, mV Specifications
Item
Specification
Number of channels
Eight
Sensor Types: mV Thermocouple
Low level voltage source
B, E, J, K, N, R, S, T, uncharacterized
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Channels 1, 2, 3, and 4 are isolated from
channels 5, 6, 7, and 8 (verified by 1500 VDC
factory test). Thermocouples attached to
channels 1, 2, 3,and 4 are not electrically isolated
and should be within ±0.7 VDC of each other.
Thermocouples attached to channels 5, 6, 7,and
8 are not electrically isolated and should be
within ±0.7 VDC of each other.
Full scale signal range
Selectable based on sensor type. Refer to Table
C-38 .
LocalBus Power Rating
12 VDC, 350 mA
Series 2 12 VDC, 210 mA
Ambient Temperature
0 to 60°C
Series 2 -40 to 70°C
Accuracy over temperature range (linearized)
Thermocouple: Refer to Table C-38 .
mV: Refer to Table C-39 .
Cold Junction Compensation
±1°C
Resolution (Varies with sensor type. Refer to
Table C-40 ).
16 bits
Repeatability
0.05% of span
Interface Specifications
April 2021
D800001X312
198

--- Page 199 ---

Table C-37: Thermocouple, mV Specifications (continued)
Item
Specification
DC/50/60Hz Common Mode Rejection
120 dB
Calibration
None required
Mounting
Assigned slot of I/O carrier
The following table shows specifications for the Thermocouple sensor types.
Note
In the 25° C Reference Accuracy column in the following table, total error is made up of
reading accuracy, CJC accuracy, and sensor accuracy.
Table C-38: Thermocouple Sensor Type Specifications
Sensor Type
Full Scale
Operating
Range
25° C
Reference
Accuracy
Temperature
Drift
Resolution
Uncharacteriz
ed (No
linearization,
no cold
junction
compensation
.)
-100 to 100
mV
-100 to 100
mV
0.1 mV
±0.002 mV/°C
∼ 0.003mV
B
250 to 1810°C
500 to 1810°C
±2.4°C
±0.056°C/°C
∼ 0.18°C
E
-200 to
1000°C
-200 to
1000°C
±0.6°C
±0.008°C/°C
∼ 0.07°C
J
-210 to
1200°C
-190 to
1200°C
±0.8°C
±0.011°C/°C
∼ 0.05°C
K
-270 to
1372°C
-200 to
1372°C
±0.5°C
±0.016°C/°C
∼ 0.18°C
N
-270 to
1300°C
-190 to
1300°C
±1.0°C
±0.007°C/°C
∼ 0.10°C
R
-50 to 1768°C
-50 to 1768°C
±2.1°C
±0.013°C/°C
∼ 0.14°C
S
-50 to 1768°C
-40 to 1768°C
±2.2°C
±0.067°C/°C
∼ 0.24°C
T
-270 to 400°C
-200 to 400°C
±0.7°C
±0.001°C/°C
∼ 0.04°C
The following table shows specifications for the mV sensor types
Table C-39: mV Sensor Type Specifications
Sensor Type
Full Scale
Operating
Range
25 ° Reference
Accuracy
Temperature
Drift
Resolution
Low Level
Voltage
Source
-100 to 100
mV
-100 to 100
mV
0.1 mV
0.002 mV/°C
∼ 0.003 mV
Interface Specifications
D800001X312 
April 2021
199

--- Page 200 ---

Wiring Diagram
Figure C-48: Wiring Diagram for Thermocouple, mV
+
-
I/O Card
Termination
Carrier
(Odd no.)
(Even no.)
A/D
Converter
System
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
Ch
1
+
-
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
Thermocouple,
mV terminal block
Related information
I/O Terminal Blocks
Thermocouple Terminal Block
C.1.30
VIM 2 card specifications
Installation notes
• The VIM 2 card mounts in the right slot of a Power / Controller Carrier.
• The VIM 2 card requires a controller and a dedicated system power supply (24 VDC).
• The Power / Controller Carrier holding a VIM 2 card and power supply must be installed
to the left of the first 8-Wide I/O Carrier on the DIN rail. It can be installed either to the
left or right of the Power / Controller Carrier holding the controller and its power
supply.
• This card supports redundancy.
Specifications
Table C-40: VIM 2 card specifications
Item
Specifications
Input power requirement (supplied through the
System Power Supply (24 VDC)
+5 VDC @ 1.4 A maximum
Fuse protection
3.0 A , nonreplaceable internal fuses
Interface Specifications
April 2021
D800001X312
200

--- Page 201 ---

Table C-40: VIM 2 card specifications (continued)
Item
Specifications
External connectors
•
VIMNet network: One, 10/100BASE-TX with
RJ45 connector
•
Redundancy link: One, 10/100BASE-TX with
RJ45 connector
Mounting
Right slot of Power / Controller Carrier
Image
Figure C-49: VIM 2 card and power supply on the Power / Controller Carrier
C.2
Intrinsically Safe I/O Cards
The I/O subsystem supports the following types of Intrinsically Safe (I.S.) I/O cards:
• I.S. AI, 8-Channel, 4-20 mA, HART
• I.S. AO, 8-Channel, 4-20 mA and I.S. AO, 8-Channel, 4-20 mA, HART
• I.S. DI, 16-Channel
• I.S. DO, 4-Channel
Interface Specifications
D800001X312 
April 2021
201

--- Page 202 ---

C.2.1
I.S. AI, 8-Channel, 4-20 mA, HART
Installation Notes
The I.S. 8-channel terminal block is recommended to provide screw terminations for field
wiring for the I.S. AI, 8-channel, 4-20 mA, HART card. An optional block is the I.S. loop
disconnect 8-channel terminal block.
Specifications
Table C-41: I.S. AO, 8-Channel, 4-20 mA (includes HART) 
Item
Specification
Number of channels
Eight
Isolation
LocalBus to any channel: 60 VAC
Between channels: None
I.S. channel to non-I.S. rail: 250 VAC
Nominal signal range (span)
4 to 20 mA
Full scale signal range
2 to 22 mA
Valid range for LED indication
0.78 to 21.9 mA
LocalBus current (12 VDC nominal), per card
600 mA
Line fault detection
Short circuit: >21.5 mA
Open circuit: <0.5 mA
Accuracy over temperature range
±0.006% of span per °C
Accuracy over EMC conditions
1% of span
Resolution
16 bits
Repeatability
0.05% of span
Calibration
Not required
Communications Support
HART pass-through request/response HART
variable report Field device status report
Optional loop disconnect
Yes
Mounting
Assigned slot of I/O carrier
Warning
Hand-held, two-way radios should not be keyed within 0.5 M (1.64 ft., 19.7 in.) of
Intrinsically Safe Analog Input cards as the level of radiated emissions from these units can
interfere with the operation of the system.
Interface Specifications
April 2021
D800001X312
202

--- Page 203 ---

Wiring Diagram
Figure C-50: Wiring Diagram for I.S. AI, 8-Channel, 4-20 mA, HART
Common
connection
for 8 channels
+
-
I/S Carrier
I/O Card
IS Termination
(Odd no.)
(Even no.)
System
A/D
Converter
Loop
disconnect
(optional)
12 VDC IS
Power
IS Power
T
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
Ch
1
+
-
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
I.S. 8-channel
terminal block
Related information
I.S. 8-Channel Terminal Block
C.2.2
I.S. AO, 8-Channel, 4-20 mA
The DeltaV system supports the I.S. AO, 8-channel, 4-20 mA card and the I.S. AO, 8-
channel, 4-20 mA, HART card.
Installation Notes
The I.S. 8-channel terminal block is recommended to provide screw terminations for field
wiring for the HART and non-HART versions of the I.S. AO, 8-channel, 4-20 mA card. An
optional block is the I.S. loop disconnect 8-channel terminal block.
Specifications
Table C-42: I.S. AO, 8-Channel, 4-20 mA (includes HART) 
Item
Specification
Number of channels
Eight
Isolation
LocalBus to any channel: 60 VAC
Between channels: None
I.S. channel to non-I.S. rail: 250 VAC
Nominal signal range (span)
4 to 20 mA
Interface Specifications
D800001X312 
April 2021
203

--- Page 204 ---

Table C-42: I.S. AO, 8-Channel, 4-20 mA (includes HART) (continued)
Item
Specification
Full scale signal range
1 to 22 mA
Voltage to load
13 V minimum @ 20 mA
Load resistance
450 Ω maximum 650 Ω maximum with HART
LocalBus current (12 VDC nominal), per card
630 mA
Open circuit detection threshold
0.7 mA ±0.2 mA
Accuracy (@ 25 °C)
±20 µA
Accuracy over temperature range
±0.006% of span per °C
Accuracy over EMC conditions
0.5% of span
Resolution
12 bits
Output compliance
20 mA stored into 450 Ω load; independent of
supply (non-HART) 20 mA stored into 650 Ω
load; independent of supply (HART)
Optional loop disconnect
Yes
Calibration
Stored on card
Mounting
Assigned slot of I/O carrier
Warning
Before substituting an I.S. AO, 4-20 mA card with an I.S. AO, 4-20 mA, HART card, you
must perform a loop analysis or reassess the field parameters. Refer to the following
documents for valid field parameters:
• 12P1892, DeltaVTM Scalable Process System Class I Div.2 with Class I, II, III, Div. 1 Field
Circuit Installation Instructions
• 12P2524, DeltaVTM I.S. I/O Code of Practice for Installation and Maintenance in Zone 2
Hazardous Areas
• 12P1990, DeltaVTM Scalable Process System with Zone 0 Field Circuits, Installation
Instructions
Interface Specifications
April 2021
D800001X312
204

--- Page 205 ---

Wiring Diagrams
Figure C-51: Wiring Diagram for I.S. AO, 8-Channel, 4-20 mA
Common
connection
for 8 channels
+
-
Carrier
I/O Card
IS Termination
(Odd no.)
(Even no.)
System
A/D
Converter
Loop
disconnect
(optional)
12 VDC IS
Power
IS Power
Load
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
Ch
1
+
-
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
I.S. 8-channel
terminal block
Figure C-52: Wiring Diagram for I.S. AO, 8-Channel, 4-20 mA, HART
Common
connection
for 8 channels
+
-
I/S Carrier
I/O Card
IS Termination
(Odd no.)
(Even no.)
System
A/D
Converter
Loop
disconnect
(optional)
12 VDC IS
power
IS Power
Load
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
Ch
1
+
-
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
I.S. 8-channel
terminal block
Interface Specifications
D800001X312 
April 2021
205

--- Page 206 ---

Related information
I.S. 8-Channel Terminal Block
C.2.3
I.S. DI, 16-Channel
Installation Notes
The I.S. 16-channel terminal block must be used to provide screw terminations for field
wiring for the I.S. DI, 16-channel card. If this terminal block is not used, the card will not
communicate with the DeltaV controller.
Specifications
Table C-43: I.S. DI, 16-Channel 
Item
Specification
Number of channels
Sixteen
Isolation
LocalBus to any channel: 60 VAC
Between channels: None
I.S. channel to non-I.S. rail: 250 VAC
Detection level for On
>2.1 mA
Detection level for Off
<1.2 mA
Voltage applied to sensor
7.0 to 9.0 V from 1 kΩ ±10%
Line fault detection
Short circuit: <100 Ω
Open circuit: > 50 kΩ
Maximum input frequency
20 Hz
Minimum pulse width detected
45 ms
Output impedance
100 Ω @ > 6 mA (wetting current)
LocalBus current
350 mA
Switching hysteresis
200 µA (nominal)
Optional loop disconnect
Not offered
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
206

--- Page 207 ---

Wiring Diagram
Figure C-53: Wiring Diagram for I.S. DI, 16-Channel
+
-
IS Carrier
I/O Card
IS
Termination
(Odd no.)
(Even no.)
System
12 VDC IS
Power
Sense
circuit
680 Ω
22k Ω
Resistors
optional
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
Ch
1
+
-
+
-
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
Common
connection
for 16 channels
I.S.16-channel
terminal block
Related information
I.S. 16-Channel Terminal Block
C.2.4
I.S. DO, 4-Channel
Installation Notes
The I.S. 8-channel terminal block is recommended to provide screw terminations for field
wiring for the I.S. DO, 4-channel card. An optional block is the I.S. loop disconnect 8-
channel terminal block.
Specifications
Table C-44: I.S. DO, 4-Channel
Item
Specification
Number of channels
Four
Isolation
LocalBus to any channel: 60 VAC
Between channels: None
I.S. channel to non-I.S. rail: 250 VAC
Interface Specifications
D800001X312 
April 2021
207

--- Page 208 ---

Table C-44: I.S. DO, 4-Channel (continued)
Item
Specification
Output range
22 V (open circuit) 11 V at 45 mA 25 VDC
(maximum)
Output rating
45 mA (min.)
Off state leakage
N/A
LocalBus current (12 VDC nominal), per card
560 mA
Current limit per channel
45 mA
Configurable channel types
Discrete output : Output stays in the last state
submitted by the controller.
Momentary output : Output is active for a pre-
configured time period (100 ms to 100 s).
Continuous pulse output : Output is active as a
percentage of a pre-configured base time period
(100 ms to 100 s). Resolution is 2 ms.
Optional loop disconnect
Yes
Mounting
Assigned slot of I/O carrier
Wiring Diagram
Figure C-54: Wiring Diagram for I.S. DO, 4-Channel
+
-
IS Termination
Carrier
I/O Card
Common
connection for
4 channels
(Odd no.)
System
12 VDC IS
Power connection
(Odd no.)
Loop
disconnect
(optional)
IS Power
Load
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
I.S. 8-channel
terminal block
(refer to terminal block
specifications for
pin out connections
and channel
nomenclature)
Interface Specifications
April 2021
D800001X312
208

--- Page 209 ---

Related information
I.S. 8-Channel Terminal Block
C.3
Terminal Blocks
The DeltaV system supports Terminal Blocks, Redundant Terminal Blocks, Mass
Termination Blocks, and Intrinsically Safe Termination Blocks.
The I/O subsystem supports the following types of terminal blocks:
• I/O, Fused I/O, and 4-wire I/O
• Fieldbus H1 Terminal Block
• Series 2 H1 Terminal Block
• Interface Terminal Block
• Isolated Input Terminal Block
• Profibus DP Terminal Block
• RTD, ohms Terminal Block
• Thermocouple Terminal Block
• 32-Channel Terminal Block
• 16-Channel Analog Input Terminal Block
Note
The terminal blocks contain a latch for quick release. To remove the terminal block,
depress the latch with a screw driver or finger and pull the terminal block down and off.
C.3.1
I/O Terminal Blocks
Specifications
The following table show specifications for the I/O, Fused I/O, and 4-wire I/O terminal
blocks.
Table C-45: I/O, Fused I/O, and 4-Wire I/O Terminal Block Specifications
Item
Specification
Voltage rating
I/O and fused I/O: 250 VAC and 60 VDC
between non-connected signals for I/O and
fused I/O
4-wire I/O: 30 VDC
Maximum current
1 A per I/O channel
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
209

--- Page 210 ---

Terminal Block Connections
Figure C-55: I/O, Fused I/O, and 4-Wire I/O Terminal Block
Bottom View
Front View
Keying depends upon
the card type. Refer to
"I/O Interface Keying"
for key position.
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
+
-
C.3.2
Fieldbus H1 Terminal Block
The DeviceNet and Fieldbus H1 cards use the Fieldbus H1 terminal block to provide
terminations for wiring.
Specifications
Table C-46: Fieldbus H1 Terminal Block Specifications
Item
Specification
Voltage Rating
32 VDC
Max Current
500 mA
Mounting
Assigned slot of I/O carrier
Terminal Block Connections
The wiring shown in the following figure is for the Fieldbus H1 card.
Interface Specifications
April 2021
D800001X312
210

--- Page 211 ---

Figure C-56: Fieldbus H1 Terminal Block
+
+
- -
+
+
- -
1
2
3
4
5
6
7
8
Port
1
Port
2
Bottom View
Front View
Keying (D6)
Note
Change the key position to D5 for the DeviceNet card.
Related information
DeviceNet
C.3.3
Series 2 H1 Terminal Block
The Series 2 H1 card uses the Series 2 H1 terminal block to provide terminations for wiring.
Specifications
Item
Specification
Voltage Rating
35 VDC
Max Current
500 mA
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
211

--- Page 212 ---

Terminal Block Connections
Figure C-57: Series 2 H1 Terminal Block
1
2
3
4
5
6
7
8
Port
1
Port
2
+ - + -
H1
Bottom View
Front View
Cover with
I/O labels
Keying (D6)
C.3.4
Simplex H1 4-Port Terminal Block
Installation notes
• The Simplex H1 4-Port Terminal Block provides wiring terminations for the simplex
Fieldbus H1 4-Port Series 2 Plus card.
• Set the keys on the terminal block to D2 to match the simplex Fieldbus H1 4-Port Series
2 Plus card.
Specifications
Table C-47: Simplex H1 4-Port Terminal Block specifications
Item
Specification
Voltage rating
35 VDC
Maximum current
500 mA
Isolation
Each channel is isolated from each other and
factory tested to 1000 VDC.
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
212

--- Page 213 ---

Terminal Block Connections
Figure C-58: Simplex H1 4-Port Terminal Block
Bottom view
Front view
+
–
+
–
+
–
+
Port 1
Port 2
Port 3
Port 4
–
2
1
4
3
6
5
8
7
Keying (D2)
C.3.5
Simplex 2-Wire 16-Channel Analog Input Terminal Block
Installation Notes
• The simplex 2-wire 16-Channel Analog Input Terminal Block provides 2-wire
terminations for the AI, 16-Channel, 4-20 mA HART, Series 2 Plus card in simplex mode.
• Set the keys on the terminal block to A2 to match the AI, 16-Channel, 4-20 mA HART,
Series 2 Plus card.
Specifications
Table C-48: Simplex 2-Wire 16-Channel Analog Input Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
500 mA per channel
Mounting
Assigned slot of I/O carrier.
Interface Specifications
D800001X312 
April 2021
213

--- Page 214 ---

Terminal Block Connections
Figure C-59: Simplex 2-Wire 16-Channel Analog Input Terminal Block
Keying (A6)
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
Bottom View
Front View
C.3.6
Simplex 4-Wire 16-Channel Analog Input Terminal Block
Installation Notes
• The simplex 4-wire 16-Channel Analog Input Terminal Block provides 4-wire
terminations for the AI, 16-Channel, 4-20 mA HART, Series 2 Plus card in simplex mode.
• Set the keys on the terminal block to A6 to match the AI, 16-Channel, 4-20 mA HART,
Series 2 Plus card.
Specifications
Table C-49: Simplex 4-Wire 16-Channel Analog Input Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
500 mA per channel
Mounting
Assigned slot of I/O carrier.
Interface Specifications
April 2021
D800001X312
214

--- Page 215 ---

Terminal Block Connections
Figure C-60: Simplex 4-Wire 16-Channel Analog Input Terminal Block
Keying (A6)
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
Bottom View
Front View
C.3.7
Simplex 16-Channel Analog Output Terminal Block
Installation Notes
• The simplex 16-Channel Analog Output Terminal Block provides wiring terminations
for the AO, 16-Channel, 4-20 mA HART, Series 2 Plus card in simplex mode.
• Set the keys on the terminal block to A5 to match the AO, 16-Channel, 4-20 mA HART,
Series 2 Plus card.
Specifications
Table C-50: Simplex 16-Channel Analog Output Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
200 mA per channel
Mounting
Assigned slot of I/O carrier.
Interface Specifications
D800001X312 
April 2021
215

--- Page 216 ---

Terminal Block Connections
Figure C-61: Simplex 16-Channel Analog Output Terminal Block
Keying (A5)
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
Bottom View
Front View
C.3.8
Simplex 32-Channel Discrete Input Terminal Block
Installation Notes
• The Simplex 32-Channel Discrete Input Terminal Block provides wiring terminations for
a DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card.
• Set the keys on the terminal block to E3 to match the DI, 32-Channel, 24 VDC, Dry
Contact Series 2 Plus card.
Specifications
Table C-51: Simplex 32-Channel Discrete Input Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per I/O channel; 160 mA per card
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
216

--- Page 217 ---

Terminal Block Connections
Figure C-62: Simplex 32-Channel Discrete Input Terminal Block
Front view
Bottom view
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
17 19 21 23 25 27 29 31
18 20 22 24 26 28 30 32
Keying (E3)
C.3.9
Simplex 32-Channel Discrete Output Terminal Block
Installation Notes
• The Simplex 32-Channel Discrete Output Terminal Block provides wiring terminations
for a DO, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card.
• Set the keys on the terminal block to E3 to match the DO, 32-Channel, 24 VDC, Dry
Contact Series 2 Plus card.
Specifications
Table C-52: Simplex 32-Channel Discrete Output Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per I/O channel; 160 mA per card
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
D800001X312 
April 2021
217

--- Page 218 ---

Terminal Block Connections
Figure C-63: Simplex 32-Channel Discrete Output Terminal Block
Front view
Bottom view
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
17 19 21 23 25 27 29 31
18 20 22 24 26 28 30 32
Keying (E3)
C.3.10
Interface Terminal Block
The AS-Interface and Serial cards use the Interface terminal block to provide terminations
for wiring.
Specifications
Table C-53: Interface Terminal Block Specifications
Item
Specification
Voltage Rating
35 VDC
Max Current
1.0 A
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
218

--- Page 219 ---

Terminal Block Connections
Figure C-64: Interface Terminal Block
Keying depends upon
the card type.
Refer to "I/O Interface
Keying" for key position.
Bottom View
Front View
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
Port
1
Port
2
C.3.11
Isolated Input Terminal Block
The Isolated Input card uses the Isolated Input terminal block to provide terminations for
wiring.
Specifications
Item
Specification
Voltage Rating
10 VAC/DC
Max Current
500 mA
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
219

--- Page 220 ---

Terminal Block Connections
Figure C-65: Isolated Input Terminal Block
Front View
+
-
Ch
1
Ch
2
Ch
3
Ch
4
1
2
5
6
9
10
13
14
3
4
7
8
11
12
15
16
Sensor -
Sensor +
4-wire sensor excitation
Wire compensation
Keying (C2)
Bottom View
C.3.12
Profibus DP Terminal Block
The Profibus DP card uses the Profibus DP terminal block to provide terminations for
wiring.
Specifications
Table C-54: Profibus DP Terminal Block Specifications
Item
Specification
Voltage Rating
5 VDC
Max Current
100 mA
Mounting
Assigned slot of I/O carrier
Terminal Block Connections
The Profibus terminal block has two terminator positions on the front of the unit.
Terminator OUT is the bottom position; terminator IN is the top position. The terminal
block is shipped in the IN position.
Interface Specifications
April 2021
D800001X312
220

--- Page 221 ---

Figure C-66: Profibus DP Terminal Block
1
2
3
4
5
6
7
8
1 2 3 4 5 6 7 8
IN
OUT
Bottom View
Front View
Terminator in
Keying (D3)
A1
S
S
S
B1
B2
A2
C
T
S
Gently tug on the jumper to remove it and then push the jumper onto a terminator
position. The location of the terminal block on the segment determines the terminator
position.
Terminal Block Position
Terminator Position
End of segment
IN
A terminator in the IN position provides
termination for the end of a segment. This type
of termination is usually made with a single
cable.
Middle of segment
OUT
A terminator in the OUT position provides a
connection to other devices on the segment
through the terminal block. These connections
are typically made with two cables that run in
two different directions (for example to two
cabinets). The OUT position can also be used to
connect two cables to a redundant DP/PA
segment coupler for line redundancy.
• When terminal blocks are located either at the middle of a segment or at the end of a
long, single cable run, fiber-optic converters could be required in the line to provide
isolation between the different locations. For example, a fiber-optic converter could be
used to ensure that two cabinets installed in different buildings do not affect each
other in terms of potential differences, surges, or hazardous area classification.
• When redundant DP/PA segment couplers are used for line redundancy or full duplex
fiber-optic converters are used to isolate sections of the Profibus segment, be sure to
properly configure status handling for the Profibus slaves in the control strategy. For
example, be sure to configure the application software to determine the integrity and
Interface Specifications
D800001X312 
April 2021
221

--- Page 222 ---

status of the slave device and the status of the communication to and from the slave
device and the master.
C.3.13
RTD, ohms Terminal Block
The Series 1 and Series 2 RTD, ohms card uses the RTD, ohms terminal block to provide
terminations for wiring.
Table C-55: RTD, ohms Terminal Block Specifications
Item
Specification
Voltage Rating
5 VDC
Max Current
100 mA
Mounting
Assigned slot of I/O carrier
Terminal Block Connections
Figure C-67: RTD, ohms Terminal Block
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
+
-
Sensor -
Sensor +
Sensor
excitation
Circuit common
Keying (C3)
Bottom View
C.3.14
Thermocouple Terminal Block
The Series 1 and Series 2 Thermocouple, mV card uses either the Thermocouple or I/O
terminal block to provide terminations for wiring.
Specifications
Table C-56: Thermocouple, mV Terminal Block
Item
Specification
Voltage rating
5 VDC
Maximum current
100 mA
Interface Specifications
April 2021
D800001X312
222

--- Page 223 ---

Table C-56: Thermocouple, mV Terminal Block (continued)
Item
Specification
Mounting
Assigned slot of I/O carrier
Terminal Block Connections
Figure C-68: Thermocouple, mV Terminal Block
+
-
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
Bottom View
Front View
Keying (C1)
Thermocouple
C.3.15
32-Channel Terminal Block
Specifications
Table C-57: 32-Channel Terminal Block Specifications
Item
Specifications
Voltage rating
30 VDC
Maximum current
1 A
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
223

--- Page 224 ---

Terminal Block Connections
Figure C-69: 32-Channel Terminal Block
The numbers on the
terminal block indicate
the channel assigments.
Bottom View
Keying depends upon
the card type. Refer to
"I/O Interface Keying"
for key position.
1
2
5
6
9
10
13
14
17
18
21
22
25
26
29
30
3
4
7
8
11
12
15
16
19
20
23
24
27
28
31
32
Front View
C.3.16
16-Channel Analog Input Terminal Block
Specifications
Table C-58: 16-Channel Analog Input Terminal Block Specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
100 mA
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
224

--- Page 225 ---

Terminal Block Connections
Figure C-70: 16-Channel Analog Input Terminal Block
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
Keying (A2)
The following table lists the cable pin out connections for the 16-channel analog input
terminal block.
Table C-59: 16-Channel Analog Input Terminal Block
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
Interface Specifications
D800001X312 
April 2021
225

--- Page 226 ---

Table C-59: 16-Channel Analog Input Terminal Block (continued)
Terminal on
Termination Block
Channel
Nomenclature
Terminal on
Termination Block
Channel
Nomenclature
Terminal 16
Channel 8-
Terminal 32
Channel 16-
C.3.17
4-wire 16-Channel Analog Input Terminal Block
Installation Notes
• The 4-wire 16-Channel Analog Input Terminal Block provides 4-wire terminations for
the AI, 16-Channel, 4-20 mA HART, Series 2 card.
• Set the keys on the terminal block to A2 to match the AI, 16-Channel, 4-20 mA HART,
Series 2 card.
Specifications
Table C-60: 4-wire 16-Channel Analog Input Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
100 mA per channel
Mounting
Assigned slot of I/O carrier.
Terminal Block Connections
Figure C-71: 4-wire 16-Channel Analog Input Terminal Block
Front view
Bottom view
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
18 20 22 24 26 28 30 32
17 19 21 23 25 27 29 31
CH
1
CH
2
CH
3
CH
4
CH
5
CH
6
CH
7
CH
8
CH
9
CH
10
CH
11
CH
12
CH
13
CH
14
CH
15
CH
16
+
–
+
–
Interface Specifications
April 2021
D800001X312
226

--- Page 227 ---

C.4
Redundant Terminal Blocks
The DeltaV system can use the following types of redundant terminal blocks:
• Redundant Analog Input Terminal Block
• Redundant Analog Output Terminal Block
• Redundant Discrete Terminal Block
• Redundant H1 Terminal Block
• Redundant Interface Terminal Block
• Redundant Profibus DP Terminal Block
Note
The redundant terminal blocks contain a latch for quick release. To remove the terminal
block, depress the latch with a screw driver or finger and pull the terminal block down and
off. The Redundant Interface terminal block contains two latches. To remove the terminal
block, depress both latches and pull the terminal block down and off.
C.4.1
Redundant Analog Input Terminal Block
Specifications
Table C-61: Redundant Analog Input Terminal Block Specifications
Item
Specification
Voltage rating
30 VDC
Maximum Current
200 mA
Operating Temperature
-40°C to 60°C (-40°F to 140°F)
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Figure C-72 shows the Redundant Analog Input terminal block. You can change between
two and four wire connections in groups of four channels. The 2-wire and 4-wire jumpers
on the left are for channels 1-4 and the 2-wire and 4-wire jumpers on the right are for
channels 5-8.
For 4-wire transmitter applications, rotate the jumper module 180° until the Field Type
arrows on the terminal block point to the 4-wire transmitter on the jumper.
Interface Specifications
D800001X312 
April 2021
227

--- Page 228 ---

Figure C-72: Redundant Analog Input Terminal Block (shown as shipped)
1
2
3
4
5
6
7
8
9 10 11 12 13 14 15 16
Ch 1
+ -
Ch 2
+ -
Ch 3
+ -
Ch 4
+ -
Ch 5
+ -
Ch 6
+ -
Ch 7
+ -
Ch 8
+ -
Analog Input Field Type
2-WIRE
4-WIRE
2-WIRE
4-WIRE
Bottom View
Front View
I/O labels
Jumper module
(shipped as 2-wire
transmitter field type)
2-WIRE
4-WIRE
Remove jumper module 
from the terminal block.
Rotate jumper module 
180 degrees to the 
connected transmitter 
field type.
Place it back into the 
terminal block.
1.
2.
3.
To set the jumpers
from 2-wire to 4-wire
transmitters:
(Keying A1)
C.4.2
Redundant 16-Channel Analog Input Terminal Block
Installation Notes
• The Redundant 16-Channel Analog Input Terminal Block provides wiring terminations
for the 2 or 4-wire redundant AI, 16-Channel, 4-20 mA , HART, Series 2 Plus card.
• Set the keys on the terminal block to A6 to match the AI, 16-Channel, 4-20 mA , HART,
Series 2 Plus card.
Specifications
Table C-62: Redundant 16-Channel Analog Input Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
500 mA per I/O channel
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
228

--- Page 229 ---

Terminal Block Connections
Figure C-73: Redundant 16-Channel Analog Input Terminal Block
+
–
Front view
Bottom view
+
–
2
5
8
11 14 17 20 23
3
6
9
12 15 18 21 24
26 29 32 35 38 41 44 47
27 30 33 36 39 42 45 48
1
4
7
10 13 16 19 22
25 28 31 34 37 40 43 46
CH
1
2-wire
4-wire
CH
2
CH
3
CH
4
CH
5
CH
6
CH
7
CH
8
CH
9
CH
10
CH
11
CH
12
CH
13
CH
14
CH
15
CH
16
Keying (A6)
C.4.3
Redundant Analog Output Terminal Block
Specifications
Table C-63: Redundant Analog Output Terminal Block Specifications
Item
Specification
Voltage rating
30 VDC
Maximum Current
200 mA
Operating Temperature
-40°C to 60°C (-40°F to 140°F)
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
D800001X312 
April 2021
229

--- Page 230 ---

Terminal Block Connections
Figure C-74: Redundant Analog Output Terminal Block
1
2
3
4
5
6
7
8
9 10 11 12 13 14 15 16
Ch 1
+ -
Ch 2
+ -
Ch 3
+ -
Ch 4
+ -
Ch 5
+ -
Ch 6
+ -
Ch 7
+ -
Ch 8
+ -
Bottom View
Front View
(Keying A4)
I/O labels
Redundant Analog Output
C.4.4
Redundant 16-Channel Analog Output Terminal Block
Installation Notes
• The Redundant 16-Channel Analog Output Terminal Block provides wiring
terminations for the redundant AO, 16-Channel, 4-20 mA, HART, Series 2 Plus card.
• Set the keys on the terminal block to A5 to match the AO, 16-Channel, 4-20 mA, HART,
Series 2 Plus card.
Specifications
Table C-64: Redundant 16-Channel Analog Output Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current per channel
200 mA
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
230

--- Page 231 ---

Terminal Block Connections
Figure C-75: Redundant 16-Channel Analog Output Terminal Block
+
–
Front view
Bottom view
CH
1
CH
2
CH
3
CH
4
CH
5
CH
6
CH
7
CH
8
CH
9
CH
10
CH
11
CH
12
CH
13
CH
14
CH
15
CH
16
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
17 19 21 23 25 27 29 31
18 20 22 24 26 28 30 32
Keying (A5)
C.4.5
Redundant Discrete Terminal Block
Specifications
Table C-65: Redundant Discrete Terminal Block Specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
1 A per I/O channel 3 A per card
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal Block Connections
Table C-65 shows the Redundant Discrete terminal block. The key on the Redundant
Discrete terminal block is set to B1 at the factory for use with the Series 2 DI, 8-channel, 24
VDC Dry Contact card. Change the key position to B6 to use this terminal block with the
Series 2 DO, 8-channel, 24 VDC High-Side card.
Interface Specifications
D800001X312 
April 2021
231

--- Page 232 ---

Figure C-76: Redundant Discrete Terminal Block
1
2
3
4
5
6
7
8
9 10 11 12 13 14 15 16
Ch 1
+ -
Ch 2
+ -
Ch 3
+ -
Ch 4
+ -
Ch 5
+ -
Ch 6
+ -
Ch 7
+ -
Ch 8
+ -
Bottom View
Front View
I/O labels
Keying B1 for
DI card (as
shown), B6
for DO card
Redundant Discrete
C.4.6
Redundant 32-Channel Discrete Input Plus Terminal
Block
Installation Notes
• The Redundant 32-Channel Discrete Input Terminal Block provides wiring terminations
for a redundant pair of DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus cards.
• Set the keys on the terminal block to E3 to match the DI, 32-Channel, 24 VDC, Dry
Contact Series 2 Plus cards.
Specifications
Table C-66: Redundant 32-Channel Discrete Input Plus Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per I/O channel; 160 mA per card
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
232

--- Page 233 ---

Terminal Block Connections
Figure C-77: Redundant 32-Channel Discrete Input Plus Terminal Block
Front view
Bottom view
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
17 19 21 23 25 27 29 31
18 20 22 24 26 28 30 32
Keying (E3)
C.4.7
Redundant 32-Channel Discrete Output Plus Terminal
Block
Installation Notes
• The Redundant 32-Channel Discrete Output Terminal Block provides wiring
terminations for a redundant pair of DO, 32-Channel, 24 VDC, Dry Contact, Series 2
Plus cards.
• Set the keys on the terminal block to E3 to match the DO, 32-Channel, 24 VDC, Dry
Contact Series 2 Plus cards.
Specifications
Table C-67: Redundant 32-Channel Discrete Output Plus Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per I/O channel; 160 mA per card
Interface Specifications
D800001X312 
April 2021
233

--- Page 234 ---

Table C-67: Redundant 32-Channel Discrete Output Plus Terminal Block
specifications (continued)
Item
Specification
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal Block Connections
Figure C-78: Redundant 32-Channel Discrete Output Plus Terminal Block
Front view
Bottom view
1
3
5
7
9
11 13 15
2
4
6
8
10 12 14 16
17 19 21 23 25 27 29 31
18 20 22 24 26 28 30 32
Keying (E3)
C.4.8
Redundant H1 Terminal Block
Specifications
Table C-68: Redundant H1 Terminal Block Specifications
Item
Specification
Voltage rating
35 VDC
Maximum Current
500 mA
Interface Specifications
April 2021
D800001X312
234

--- Page 235 ---

Table C-68: Redundant H1 Terminal Block Specifications (continued)
Item
Specification
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal Block Connections
Figure C-79: Redundant H1 Terminal Block
Port 1
+ -
Port 2
+ -
Port 1
+ -
Port 2
+ -
1
2
3
4
5
6
7
8
9 10 11 12 13 14 15 16
Bottom View
Front View
I/O labels
Keying (D6)
Redundant H1
C.4.9
Redundant H1 4-Port Terminal Block
Installation notes
• The Redundant H1 4-Port Terminal Block provides wiring terminations for a redundant
pair of Fieldbus H1 4-Port Series 2 Plus cards.
• Set the keys on the terminal block to D2 to match the redundant Fieldbus H1 4-Port
Series 2 Plus card.
Specifications
Table C-69: Redundant H1 4-Port Terminal Block specifications
Item
Specification
Voltage rating
35 VDC
Maximum current
500 mA
Interface Specifications
D800001X312 
April 2021
235

--- Page 236 ---

Table C-69: Redundant H1 4-Port Terminal Block specifications (continued)
Item
Specification
Mounting
Assigned slots on the I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal Block Connections
Figure C-80: Redundant H1 4-Port Terminal Block
Bottom view
Front view
+
–
+
–
+
–
+
Port 1
Port 2
Port 3
Port 4
–
2
1
4
3
6
5
8
7
+
–
+
–
+
–
+
Port 1
Port 2
Port 3
Port 4
–
10
9
12
11
14
13
16
15
Keying (D2)
C.4.10
Redundant Interface Terminal Block
Specifications
Table C-70: Redundant Interface Terminal Block Specifications
Item
Specification
Voltage rating
35 VDC
Maximum Current
1 A
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
236

--- Page 237 ---

The Series 2 Serial cards use the Redundant Interface terminal block.
Note
The Redundant Interface terminal block contains two latches for quick release. To remove
the terminal block, depress both latches with a screw driver or finger and pull the terminal
block down and off.
Terminal Block Connections
Figure C-81: Redundant Interface Terminal Block
Bottom View
Front View
Cover with
I/O labels
Refer to card
specifications for pin out
connections and channel
nomenclature.
Keying (D4)
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
Redundant
Interface
Refer to the tables in the Serial Card topic for information on the terminal assignments.
Related information
Serial Card, 2 Ports, RS232/RS485
C.4.11
Redundant Profibus DP Terminal Block
Specifications
Table C-71: Redundant Profibus DP Terminal Block Specifications
Item
Specification
Voltage rating
5 VDC
Maximum Current
100 mA
Interface Specifications
D800001X312 
April 2021
237

--- Page 238 ---

Table C-71: Redundant Profibus DP Terminal Block Specifications (continued)
Item
Specification
Mounting
Assigned slot of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
The Series 2 Plus Profibus DP cards in Redundant mode use the Redundant Profibus DP
terminal block.
Notes
Do not plug a simplex Series 1 or Series 2 Profibus DP card into a Redundant Profibus DP
terminal block. Only redundant Series 2 Plus Profibus DP cards can be used with the
Redundant Profibus DP terminal block.
For simplex or redundant applications, when the termination is in the OUT position, pins 1
and 3 and 4 and 6 can be used. When the termination is in the IN position only pins 1 and 3
can be used.
The Redundant Profibus DP terminal block contains two latches for quick release. To
remove the terminal block, depress both latches with a screw driver or finger and pull the
terminal block down and off.
Terminal Block Connections
Figure C-82: Redundant Profibus DP Terminal Block
Terminator In
Terminator Out
1 2 3 4 5 6 7 8
Front View
Keying (D3)
Gently tug on the jumper to remove it and then push the jumper onto a terminator
position. The location of the terminal block on the segment determines the terminator
position.
Interface Specifications
April 2021
D800001X312
238

--- Page 239 ---

Terminal Block Position
Terminator Position
End of segment
IN
A terminator in the IN position provides
termination for the end of a segment. This type
of termination is usually made with a single
cable.
Middle of segment
OUT
A terminator in the OUT position provides a
connection to other devices on the segment
through the terminal block. These connections
are typically made with two cables that run in
two different directions (for example to two
cabinets). The OUT position can also be used to
connect two cables to a redundant DP/PA
segment coupler for line redundancy.
• When terminal blocks are located either at the middle of a segment or at the end of a
long, single cable run, fiber-optic converters could be required in the line to provide
isolation between the different locations. For example, a fiber-optic converter could be
used to ensure that two cabinets installed in different buildings do not affect each
other in terms of potential differences, surges, or hazardous area classification.
• When redundant DP/PA segment couplers are used for line redundancy or full duplex
fiber-optic converters are used to isolate sections of the Profibus segment, be sure to
properly configure status handling for the Profibus slaves in the control strategy. For
example, be sure to configure the application software to determine the integrity and
status of the slave device and the status of the communication to and from the slave
device and the master.
C.5
Mass Termination Blocks
The DeltaV mass termination blocks allow you to connect external marshalling panels and
termination assemblies to your DeltaV system, significantly reducing wiring costs. The
mass termination blocks provide a method to route the wiring within an enclosure and are
used with low-level signals that are conducted over either 0.093 mm2 (28 AWG) off-the-
shelf, flat ribbon cable or round instrument cable. For distances over 3 m, standard 20-pin
round ribbon cable, 0.14 mm2 (26 AWG) is available. These mass termination blocks
interface to a feed-through IDC-to-discrete-wire module such as the Phoenix Contact
FLKM20 VARIOFACE ribbon connector module. For more information on these modules,
visit the Phoenix Contact website. The Phoenix Contact FLKM20 VARIOFACE ribbon
connector module is an Emerson Alliance Program product.
The 40-Pin Mass Termination Block interfaces to either the DI or DO Mass Connection
Solutions through the same ribbon cable or round ribbon cable with 20-pin connectors.
If connectivity to IS barriers is required, additional HiD Series Boards from Pepperl+Fuchs
are available. For more information on these Boards and Barriers, visit the Pepperl+Fuchs
website. The HiD Series Boards from Pepperl+Fuchs are Emerson Alliance Program
products.
Interface Specifications
D800001X312 
April 2021
239

--- Page 240 ---

Specifications
Table C-72: Mass Termination Block Specifications
Item
Specification
Models
10-pin mass termination block 16-pin mass
termination block 24-pin mass termination
block 40-pin mass termination block
Voltage rating
30 VDC between non-connected signals
Maximum current
1 A per I/O channel (16-pin, 40-pin) 1 A per
cable (10-pin, 24-pin)
Maximum flat ribbon cable length
3 m (9.8 ft)
Maximum round ribbon cable length
6 m (19.6 ft)
Mounting
Assigned slot of I/O carrier
Key position
Set key position based on I/O card type. Factory
settings:
•
10-pin: B 6
•
16-pin: A 1
•
24-pin: A 3
•
40-pin: B 3
Note
The above specifications might be more restrictive than the specifications listed for the DI,
8-channel, 24 VDC, Isolated card, the DO, 8-channel, 24 VDC, Isolated card, and the DO, 8-
channel, 24 VDC, High-Side card.
Figure C-83: Mass Termination Block
C.5.1
10-Pin Mass Termination Block
The 10-pin mass termination block is used for relay panels or optically isolated panels. The
10-pin assembly provides an interface to many off-the-shelf, 8-channel PLC terminations
and to other termination panels that use a 10-pin cable.
Interface Specifications
April 2021
D800001X312
240

--- Page 241 ---

The two-row header accepts a 10-pin 0.093 mm2 (28 AWG) ribbon cable with 2x5 header
connectors (AMP part #1658622-1, Strain Relief #499252-5) that can interface with a
Phoenix Contact UMK-8 RM24/KSR-G24/21 VARIOFACE output module (part #29709772)
or other similar module.
Termination Block Connections
The following table provides a pinout for the 10-pin mass termination block.
Table C-73: 10-Pin Mass Termination Block Cable Pinout
Pin
Signal
1
Channel 1+
2
Channel 2+
3
Channel 3+
4
Channel 4+
5
Channel 5+
6
Channel 6+
7
Channel 7+
8
Channel 8+
9
No connection
10
Common return for all eight channels
C.5.2
16-Pin Mass Termination Block
The 16-pin mass termination block provides 1:1 signal transmission of eight signals to
external passive input/output modules. The two-row header accepts a 16-pin 1-for-1
passthrough, 0.093 mm2 (28 AWG) ribbon cable with 2x8 header connectors (AMP part
#1658622-3, Strain Relief #499252-8). The assembly interfaces with an IDC-to-discrete-
wire module, such as the Phoenix Contact FLKM 16/DV VARIOFACE ribbon connector
module (part #2304432) or other similar module.
The following table provides a pinout for the 16-pin mass termination block.
Table C-74: 16-Pin Mass Termination Block Cable Pinout
Pin
Signal
1
Channel 1-
2
Channel 1+
3
Channel 2-
4
Channel 2+
5
Channel 3-
6
Channel 3+
7
Channel 4-
8
Channel 4+
Interface Specifications
D800001X312 
April 2021
241

--- Page 242 ---

Table C-74: 16-Pin Mass Termination Block Cable Pinout (continued)
Pin
Signal
9
Channel 5-
10
Channel 5+
11
Channel 6-
12
Channel 6+
13
Channel 7-
14
Channel 7+
15
Channel 8-
16
Channel 8+
C.5.3
24-Pin Mass Termination Block
The 24-pin mass termination block can be used with 4-wire analog input 4-20 mA and 1-5
VDC applications that are conducted over 0.093 mm2 (28 AWG) ribbon cable with 2x12
header connectors (AMP part # 1658622-3, Strain Relief # 1-499252-0) or round
instrument cable.
The Phoenix Contact FLK16/24DV-AI/EZ-DR/100 24-pin to 16-pin conversion cable (part #
2301134) can be used with 4-wire applications. The conversion cable uses the Phoenix
Contact FLKM 16/DV VARIOFACE ribbon connector module (part # 2304432) and is
available in 1 m and other lengths.
 CAUTION
Be careful when closing the cover if you have a 24-pin ribbon cable connected. The cover
can damage the cable.
Termination Block Connections
The following table provides a pinout for the 24-pin mass termination block.
Table C-75: 24-Pin Mass Termination Block Cable Pinout
Pin
Signal
1
Channel 1+
3
Common channel for Channels 1 and 2
5
Channel 2+
7
Channel 3+
9
Common channel for Channels 3 and 4
11
Channel 4+
13
Channel 5+
15
Common channel for Channels 5 and 6
17
Channel 6+
Interface Specifications
April 2021
D800001X312
242

--- Page 243 ---

Table C-75: 24-Pin Mass Termination Block Cable Pinout (continued)
Pin
Signal
19
Channel 7+
21
Common channel for Channels 7 and 8
23
Channel 8+
Note
The 24 VDC return for the Analog Devices 7 V power supply must be connected to the
DeltaV 24 VDC return.
C.5.4
40-Pin Mass Termination Block
The 40-pin mass termination block provides terminations for the 32-channel digital input
and output cards and the Sequence of Events card.
For Use with 32-Channel DO and DI Cards
The 40-pin mass termination block has two 20-pin IDC headers that split the 32 channels
into two 16-channel headers. Each of the two-row headers accepts a 20-pin 1-for-1
passthrough, 0.093 mm2 (28 AWG) ribbon cable with 2x10 header connectors (AMP part #
1658622-4, Strain Relief # 499252-2). The assembly interfaces with a feed-through IDC-
to-discrete-wire module such as the Phoenix Contact FLKM20 VARIOFACE ribbon
connector module (part # 2281047) or other similar module. Phoenix Contact provides
two ways to connect to the 20-pin connection:
• A 20-pin to 2x14-pin configuration cable that connects to all 8-channel digital input
and output modules. These modules include the PLC-RELAY with V-8 adapter, fuse,
feed-through and relay (both solid-state (SSR) and electromechanical relays (EMR)).
• A 20-pin 1-for-1 cable that is connected to 16-channel modules. These modules
include feed-through, fuse, and SSR and EMR relay modules with fuses on the relay
contact commons.
The 40-pin mass termination block can also interface to the DO and DI Mass Connection
Solutions as well as to the Pepperl+Fuchs HiD Series Boards if IS Barriers are required. The
Pepperl+Fuchs HiD Series Boards are Emerson Alliance Program products.
The return connection is made internally when the 40-pin mass termination block is used
with Series 2 DI and DO 32-channel cards. No external wire is required. Refer to the cards’
installation notes for more information.
 CAUTION
Be careful when closing the cover if you have a 24-pin ribbon cable connected. The cover
can damage the cable.
For Use with SOE Cards
The 40-pin mass termination block has two 20-pin IDC headers that split the 16 channels
into two 8-channel headers. Both of the two-row headers accept a 20-pin 1-for-1
passthrough, 0.093 mm2 (28 AWG) ribbon cable with 2x10 header connectors (AMP part
#1658622-4, Strain Relief #499252-2). The assembly interfaces to a feed-through IDC-to-
Interface Specifications
D800001X312 
April 2021
243

--- Page 244 ---

discrete-wire module such as the Phoenix Contact 2281047 FLKM20 VARIOFACE ribbon
connector module. Phoenix Contact provides the following way to connect to the 20-pin
connection:
• A 20-pin to 14-pin configuration cable that connects to all 8-channel digital input
modules. These modules include the PLC-RELAY with V-8 adapter, fuse, feed-through
and relay (both solid-state (SSR) and electromechanical relays (EMR)).
Terminal Block Connections
The following table provides a pinout for the 40-pin mass termination block.
Table C-76: 40-Pin Mass Termination Block Cable Pinout 
J3 (Left
Connector)
Pin
Signal
J4 (Right
Connector)
Pin
Signal
32-channel DI
and DO
SOE
32-channel DI
and DO
SOE
1
Channel 1+
1+
1
Channel 17+
9+
2
Channel 2+
1-
2
Channel 18+
9-
3
Channel 3+
2+
3
Channel 19+
10+
4
Channel 4+
2-
4
Channel 20+
10-
5
Channel 5+
3+
5
Channel 21+
11+
6
Channel 6+
3-
6
Channel 22+
11-
7
Channel 7+
4+
7
Channel 23+
12+
8
Channel 8+
4-
8
Channel 24+
12-
9
Channel 9+
5+
9
Channel 25+
13+
10
Channel 10+
5-
10
Channel 26+
13-
11
Channel 11+
6+
11
Channel 27+
14+
12
Channel 12+
6-
12
Channel 28+
14-
13
Channel 13+
7+
13
Channel 29+
15+
14
Channel 14+
7-
14
Channel 30+
15-
15
Channel 15+
8+
15
Channel 31+
16+
16
Channel 16+
8-
16
Channel 32+
16-
17
no connection
no connection
17
no connection
no connection
18
return
N/A
18
return
N/A
19
no connection
no connection
19
no connection
no connection
20
return
N/A
20
return
N/A
Related information
DI Mass Connection Board (single)
DO Mass Connection Board (single)
Interface Specifications
April 2021
D800001X312
244

--- Page 245 ---

C.5.5
Redundant Analog Input 48-Pin Plus Mass Terminal
Block specifications
Installation notes
• This terminal block is used to terminate wiring for a redundant pair of M-series AI 16-
channel 4-20 mA HART Plus cards. Set the terminal block key to A6 before installing the
card.
• The mass terminal block has two 24-pin IDC headers that split the 16 channels into two
8-channel headers. Each of the two-row headers accepts a 24-pin, 1-for-1 passthrough
cable with 2x12 header connectors. The assembly can interface with a feed-through
IDC to analog wire module.
Specifications
Table C-77: Redundant Analog Input 48-Pin Plus Mass Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
30 mA per channel; 480 mA total
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal block connections
Table C-78: Redundant Analog Input 48-Pin Plus Mass Terminal Block cable pinout
J5 (Upper Connector)
Pin
Signal
J6 (Lower Connector)
Pin
Signal
1
Channel 1-
1
Channel 9-
2
Channel 1+
2
Channel 9+
3
Channel 2-
3
Channel 10-
4
Channel 2+
4
Channel 10+
5
Channel 3-
5
Channel 11-
6
Channel 3+
6
Channel 11+
7
Channel 4-
7
Channel 12-
8
Channel 4+
8
Channel 12+
9
Channel 5-
9
Channel 13-
10
Channel 5+
10
Channel 13+
11
Channel 6-
11
Channel 14-
12
Channel 6+
12
Channel 14+
Interface Specifications
D800001X312 
April 2021
245

--- Page 246 ---

Table C-78: Redundant Analog Input 48-Pin Plus Mass Terminal Block cable pinout
(continued)
J5 (Upper Connector)
Pin
Signal
J6 (Lower Connector)
Pin
Signal
13
Channel 7-
13
Channel 15-
14
Channel 7+
14
Channel 15+
15
Channel 8-
15
Channel 16-
16
Channel 8+
16
Channel 16+
17
4-wire channel 1
17
4-wire channel 9
18
4-wire channel 2
18
4-wire channel 10
19
4-wire channel 3
19
4-wire channel 11
20
4-wire channel 4
20
4-wire channel 12
21
4-wire channel 5
21
4-wire channel 13
22
4-wire channel 6
22
4-wire channel 14
23
4-wire channel 7
23
4-wire channel 15
24
4-wire channel 8
24
4-wire channel 16
C.5.6
Redundant Analog Output 48-Pin Plus Mass Terminal
Block specifications
Installation Notes
• This terminal block is used to terminate wiring for a redundant pair of M-series AO 16-
channel 4-20 mA HART Plus cards. Set the terminal block key to A5 before installing the
card.
• The mass terminal block has two 24-pin IDC headers that split the 16 channels into two
8-channel headers. Each of the two-row headers accepts a 24-pin 1-for-1 passthrough
cable with 2x12 header connectors. The assembly can interface to a feed-through IDC
to analog wire module such as the Phoenix Contact FLKM20 VARIOFACE ribbon
connector module. It can also interface to the Pepperl+Fuchs HiD Series Boards if IS
Barriers are required. The Phoenix Contact FLKM20 VARIOFACE ribbon connector
module and the Pepperl+Fuchs HiD Series Boards are Emerson Alliance Program
products.
Specifications
Table C-79: Redundant Analog Output 48-Pin Plus Mass Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
30 mA per I/O channel; 480 mA total
Interface Specifications
April 2021
D800001X312
246

--- Page 247 ---

Table C-79: Redundant Analog Output 48-Pin Plus Mass Terminal Block specifications
(continued)
Item
Specification
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal Block Connections
Table C-80: Redundant Analog Output 48-Pin Plus Mass Terminal Block cable pinouts
J5 (Upper Connector)
Pin
Signal
J6 (Lower Connector)
Pin
Signal
1
Channel 1-
1
Channel 9-
2
Channel 1+
2
Channel 9+
3
Channel 2-
3
Channel 10-
4
Channel 2+
4
Channel 10+
5
Channel 3-
5
Channel 11-
6
Channel 3+
6
Channel 11+
7
Channel 4-
7
Channel 12-
8
Channel 4+
8
Channel 12+
9
Channel 5-
9
Channel 13-
10
Channel 5+
10
Channel 13+
11
Channel 6-
11
Channel 14-
12
Channel 6+
12
Channel 14+
13
Channel 7-
13
Channel 15-
14
Channel 7+
14
Channel 15+
15
Channel 8-
15
Channel 16-
16
Channel 8+
16
Channel 16+
17
-
17
-
18
-
18
-
19
-
19
-
20
-
20
-
21
-
21
-
22
-
22
-
23
-
23
-
24
-
24
-
Interface Specifications
D800001X312 
April 2021
247

--- Page 248 ---

C.5.7
Redundant Discrete Input 40-Pin Mass Termination
Block
Installation notes
• The Redundant Discrete Input 40 Pin Mass Termination Block provides wiring
terminations for a redundant pair of DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus
cards.
• Set the keys on the terminal block to E3 to match the DI, 32-Channel, 24 VDC, Dry
Contact, Series 2 Plus card.
• The mass termination block has two 20-pin IDC headers that split the 32 channels into
two 16-channel headers. Each of the two-row headers accepts a 20-pin 1-for-1
passthrough cable with 2x10 header connectors.
• When the redundant DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card is used
with the Redundant Discrete Input 40-Pin Mass Termination Block and the DI Mass
Connection Solution, the card can be configured to detect faults in the termination.
Two parameters, T1_FAULT_DETECT (for the ribbon cable connection for channels
1-16), and T2_FAULT_DETECT (for the ribbon cable connection for channels 17-32),
can be enabled in DeltaV Explorer for the card. When these parameters are set to True,
detection of the ribbon cable connection between the Redundant Discrete Input 40 Pin
Mass Termination Block and the DI Mass Connection Board is enabled and the system
detects faults such as a missing cable or missing Mass Connection Board.
• The return connection is made internally between the mass termination block and the
DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card. No external wire is required.
Note
The termination fault detection feature is available only when the redundant DI, 32-
Channel, 24 VDC, Dry Contact Series 2 Plus card is used with the Redundant Discrete Input
40-Pin Mass Termination Block connected to the DI Mass Connection Solution.
Specifications
Table C-81: Redundant Discrete Input 40-Pin Mass Termination Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per channel; 160 mA total
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
April 2021
D800001X312
248

--- Page 249 ---

Termination block connections
Table C-82: Redundant Discrete Input 40-Pin Mass Termination Block cable pinout
J5 (Left Connector)
Pin
Signal
J6 (Right Connector)
Pin
Signal
1
Channel 1
1
Channel 17
2
Channel 2
2
Channel 18
3
Channel 3
3
Channel 19
4
Channel 4
4
Channel 20
5
Channel 5
5
Channel 21
6
Channel 6
6
Channel 22
7
Channel 7
7
Channel 23
8
Channel 8
8
Channel 24
9
Channel 9
9
Channel 25
10
Channel 10
10
Channel 26
11
Channel 11
11
Channel 27
12
Channel 12
12
Channel 28
13
Channel 13
13
Channel 29
14
Channel 14
14
Channel 30
15
Channel 15
15
Channel 31
16
Channel 16
16
Channel 32
17
Left cable detection
17
Right cable detection
18
+24 V
18
+24 V
19
Left cable detection
19
Right cable detection
20
+24 V
20
+24 V
C.5.8
Redundant Discrete Output 40-Pin Mass Termination
Block
Installation notes
• The Redundant Discrete Output 40-Pin Mass Termination Block provides wiring
terminations for a redundant pair of DO, 32-Channel, 24 VDC, High-Side, Series 2 Plus
cards.
• Set the keys on the terminal block to B4 to match the DO, 32-Channel, 24 VDC, High-
Side, Series 2 Plus card.
• The mass termination block has two 20-pin IDC headers that split the 32 channels into
two 16-channel headers. Each of the two-row headers accepts a 20-pin 1-for-1
passthrough cable with 2x10 header connectors.
Interface Specifications
D800001X312 
April 2021
249

--- Page 250 ---

• The return connection is made internally between the mass termination block and the
DO, 32-Channel, 24 VDC, High-Side, Series 2 Plus card. No external wire is required.
Specifications
Table C-83: Redundant Discrete Output 40-Pin Mass Termination Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
1 A per channel; 5 A total
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Termination block connections
Table C-84: Redundant Discrete Output 40-Pin Mass Termination Block cable pinout
J5 (Left Connector)
Pin
Signal
J6 (Right Connector)
Pin
Signal
1
Channel 1+
1
Channel 17+
2
Channel 2+
2
Channel 18+
3
Channel 3+
3
Channel 19+
4
Channel 4+
4
Channel 20+
5
Channel 5+
5
Channel 21+
6
Channel 6+
6
Channel 22+
7
Channel 7+
7
Channel 23+
8
Channel 8+
8
Channel 24+
9
Channel 9+
9
Channel 25+
10
Channel 10+
10
Channel 26+
11
Channel 11+
11
Channel 27+
12
Channel 12+
12
Channel 28+
13
Channel 13+
13
Channel 29+
14
Channel 14+
14
Channel 30+
15
Channel 15+
15
Channel 31+
16
Channel 16+
16
Channel 32+
17
Left cable detection
17
Right cable detection
18
return
18
return
19
Left cable detection
19
Right cable detection
20
return
20
return
Interface Specifications
April 2021
D800001X312
250

--- Page 251 ---

C.5.9
Simplex Analog Input 48-Pin Plus Mass Terminal Block
specifications
Installation notes
• This terminal block is used to terminate wiring for the M-series simplex AI 16-channel
4-20 mA HART Plus card. Set the terminal block key to A6 before installing the card.
• The mass terminal block has two 24-pin IDC headers that split the 16 channels into two
8-channel headers. Each of the two-row headers accepts a 24-pin 1-for-1 passthrough
cable with 2x12 header connectors. The assembly can interface to a feed-through IDC
to analog wire module such as the Phoenix Contact FLKM20 VARIOFACE ribbon
connector module. It can also interface to the Pepperl+Fuchs HiD Series Boards if IS
Barriers are required. The Phoenix Contact FLKM20 VARIOFACE ribbon connector
module and the Pepperl+Fuchs HiD Series Boards are Emerson Alliance Program
products.
Specifications
Table C-85: Simplex Analog Input 48-Pin Plus Mass Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
30 mA per channel; 480 mA total
Mounting
Assigned slots of I/O carrier.
Terminal block connections
Table C-86: Simplex Analog Input 48-Pin Plus Mass Terminal Block cable pinout
J3 (Upper Connector)
Pin
Signal
J4 (Lower Connector)
Pin
Signal
1
Channel 1-
1
Channel 9-
2
Channel 1+
2
Channel 9+
3
Channel 2-
3
Channel 10-
4
Channel 2+
4
Channel 10+
5
Channel 3-
5
Channel 11-
6
Channel 3+
6
Channel 11+
7
Channel 4-
7
Channel 12-
8
Channel 4+
8
Channel 12+
9
Channel 5-
9
Channel 13-
10
Channel 5+
10
Channel 13+
11
Channel 6-
11
Channel 14-
12
Channel 6+
12
Channel 14+
13
Channel 7-
13
Channel 15-
Interface Specifications
D800001X312 
April 2021
251

--- Page 252 ---

Table C-86: Simplex Analog Input 48-Pin Plus Mass Terminal Block cable pinout
(continued)
J3 (Upper Connector)
Pin
Signal
J4 (Lower Connector)
Pin
Signal
14
Channel 7+
14
Channel 15+
15
Channel 8-
15
Channel 16-
16
Channel 8+
16
Channel 16+
17
4-wire channel 1
17
4-wire channel 9
18
4-wire channel 2
18
4-wire channel 10
19
4-wire channel 3
19
4-wire channel 11
20
4-wire channel 4
20
4-wire channel 12
21
4-wire channel 5
21
4-wire channel 13
22
4-wire channel 6
22
4-wire channel 14
23
4-wire channel 7
23
4-wire channel 15
24
4-wire channel 8
24
4-wire channel 16
C.5.10
Simplex Analog Output 48-Pin Mass Terminal Block
specifications
Installation Notes
• This terminal block is used to terminate wiring for an M-series simplex AO 16-channel
4-20 mA HART Plus card. Set the terminal block key to A5 before installing the card.
• The mass terminal block has two 24-pin IDC headers that split the 16 channels into two
8-channel headers. Each of the two-row headers accepts a 24-pin 1-for-1 passthrough
cable with 2x12 header connectors. The assembly can interface to a feed-through IDC
to analog wire module such as the Phoenix Contact FLKM20 VARIOFACE ribbon
connector module. It can also interface to the Pepperl+Fuchs HiD Series Boards if IS
Barriers are required. The Phoenix Contact FLKM20 VARIOFACE ribbon connector
module and the Pepperl+Fuchs HiD Series Boards are Emerson Alliance Program
products.
Specifications
Table C-87: Simplex Analog Output 48-Pin Mass Terminal Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
30 mA per I/O channel; 480 mA total
Mounting
Assigned slots of I/O carrier
Interface Specifications
April 2021
D800001X312
252

--- Page 253 ---

Terminal Block Connections
Table C-88: Simplex Analog Output 48-Pin Mass Terminal Block cable pinout
J2 (Upper Connector)
Pin
Signal
J3 (Lower Connector)
Pin
Signal
1
Channel 1-
1
Channel 9-
2
Channel 1+
2
Channel 9+
3
Channel 2-
3
Channel 10-
4
Channel 2+
4
Channel 10+
5
Channel 3-
5
Channel 11-
6
Channel 3+
6
Channel 11+
7
Channel 4-
7
Channel 12-
8
Channel 4+
8
Channel 12+
9
Channel 5-
9
Channel 13-
10
Channel 5+
10
Channel 13+
11
Channel 6-
11
Channel 14-
12
Channel 6+
12
Channel 14+
13
Channel 7-
13
Channel 15-
14
Channel 7+
14
Channel 15+
15
Channel 8-
15
Channel 16-
16
Channel 8+
16
Channel 16+
17
-
17
-
18
-
18
-
19
-
19
-
20
-
20
-
21
-
21
-
22
-
22
-
23
-
23
-
24
-
24
-
C.5.11
Simplex Discrete Input 40-Pin Mass Termination Block
Installation notes
• The Simplex Discrete Input 40 Pin Mass Termination Block provides wiring terminations
for a DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card.
• Set the keys on the terminal block to E3 to match the DI, 32-Channel, 24 VDC, Dry
Contact, Series 2 Plus card.
Interface Specifications
D800001X312 
April 2021
253

--- Page 254 ---

• The mass termination block has two 20-pin IDC headers that split the 32 channels into
two 16-channel headers. Each of the two-row headers accepts a 20-pin 1-for-1
passthrough cable with 2x10 header connectors.
• When the DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card is used with the
Simplex Discrete Input 40-Pin Mass Termination Block and the DI Mass Connection
Solution, the card can be configured to detect faults in the termination. Two
parameters, T1_FAULT_DETECT (for the ribbon cable connection for channels 1-16),
and T2_FAULT_DETECT (for the ribbon cable connection for channels 17-32), can be
enabled in DeltaV Explorer for the card. When these parameters are set to True,
detection of the ribbon cable connection between the Simplex Discrete Input 40 Pin
Mass Termination Block and the DI Mass Connection Board is enabled and the system
detects faults such as a missing cable or missing Mass Connection Board.
• The return connection is made internally between the mass termination block and the
DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card. No external wire is required.
Note
The termination fault detection feature is available only when the DI, 32-Channel, 24 VDC,
Dry Contact Series 2 Plus card is used with the Simplex Discrete Input 40-Pin Mass
Termination Block connected to the DI Mass Connection Solution.
Specifications
Table C-89: Simplex Discrete Input 40-Pin Mass Termination Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
5 mA per channel; 160 mA total
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Terminal block connections
Table C-90: Simplex Discrete Input 40-Pin Mass Termination Block cable pin outs
J3 (Upper Connector)
Pin
Signal
J4 (Lower Connector)
Pin
Signal
1
Channel 1
1
Channel 17
2
Channel 2
2
Channel 18
3
Channel 3
3
Channel 19
4
Channel 4
4
Channel 20
5
Channel 5
5
Channel 21
6
Channel 6
6
Channel 22
7
Channel 7
7
Channel 23
8
Channel 8
8
Channel 24
Interface Specifications
April 2021
D800001X312
254

--- Page 255 ---

Table C-90: Simplex Discrete Input 40-Pin Mass Termination Block cable pin outs
(continued)
J3 (Upper Connector)
Pin
Signal
J4 (Lower Connector)
Pin
Signal
9
Channel 9
9
Channel 25
10
Channel 10
10
Channel 26
11
Channel 11
11
Channel 27
12
Channel 12
12
Channel 28
13
Channel 13
13
Channel 29
14
Channel 14
14
Channel 30
15
Channel 15
15
Channel 31
16
Channel 16
16
Channel 32
17
Left cable detection
17
Right cable detection
18
+24 V
18
+24 V
19
Left cable detection
19
Right cable detection
20
+24 V
20
+24 V
C.5.12
Simplex Discrete Output 40-Pin Mass Termination Block
Installation notes
• The Simplex Discrete Output 40-Pin Mass Termination Block provides wiring
terminations for a DO, 32-Channel, 24 VDC, High-Side, Series 2 Plus card.
• Set the keys on the terminal block to B4 to match the DO, 32-Channel, 24 VDC, High-
Side, Series 2 Plus card.
• The mass termination block has two 20-pin IDC headers that split the 32 channels into
two 16-channel headers. Each of the two-row headers accepts a 20-pin 1-for-1
passthrough cable with 2x10 header connectors.
• The return connection is made internally between the mass termination block and the
DO, 32-Channel, 24 VDC, High-Side, Series 2 Plus card. No external wire is required.
Specifications
Table C-91: Simplex Discrete Output 40-Pin Mass Termination Block specifications
Item
Specification
Voltage rating
30 VDC
Maximum current
1 A per channel; 5 A total
Mounting
Assigned slots of I/O carrier. The lower slot
number must be odd and the upper slot number
must be the next higher even number. For
example, slots 1 and 2, slots 3 and 4, and slots 5
and 6 are valid pairs. Slots 2 and 3 are not a valid
pair.
Interface Specifications
D800001X312 
April 2021
255

--- Page 256 ---

Terminal block connections
Table C-92: Simplex Discrete Output 40-Pin Mass Termination Block cable pin outs
J3 (Upper Connector)
Pin
Channel
Nomenclature
J4 (Lower Connector)
Pin
Channel
Nomenclature
1
Channel 1+
1
Channel 17+
2
Channel 2+
2
Channel 18+
3
Channel 3+
3
Channel 19+
4
Channel 4+
4
Channel 20+
5
Channel 5+
5
Channel 21+
6
Channel 6+
6
Channel 22+
7
Channel 7+
7
Channel 23+
8
Channel 8+
8
Channel 24+
9
Channel 9+
9
Channel 25+
10
Channel 10+
10
Channel 26+
11
Channel 11+
11
Channel 27+
12
Channel 12+
12
Channel 28+
13
Channel 13+
13
Channel 29+
14
Channel 14+
14
Channel 30+
15
Channel 15+
15
Channel 31+
16
Channel 16+
16
Channel 32+
17
Left cable detection
17
Right cable detection
18
return
18
return
19
Left cable detection
19
Right cable detection
20
return
20
return
C.6
Signal Conditioning Cards
C.6.1
16-Channel Analog Input 4-20 mA Signal Conditioning
Card for PLC-5/1771 I/O
Installation notes
• The 16-Channel Analog Input 4-20 mA Signal Conditioning Card for PLC-5/1771 I/O
replaces the 16-channel 1771-IFE single-ended AI card, providing an interface between
16 analog PLC signals and simplex or redundant Series 2 Plus 16-channel AI cards.
• The swing-arm attachment point on the front of the card provides secure mechanical
and electrical connections for a 1771-WG or 1771-WH swing arm.
Interface Specifications
April 2021
D800001X312
256

--- Page 257 ---

• The two 24-pin ribbon-cable connectors on the bottom of the card provide
connections for a Simplex or Redundant Analog Input 48-Pin Plus Mass Termination
Block, which is required to connect to a simplex or redundant Series 2 Plus 16-channel
AI card.
• Use the consolidated ribbon cable with shield ground wire to connect the signal
conditioning card to the mass termination block. The J1 connector of the signal
conditioning card connects to the upper connector of the mass termination block, and
the J2 connector of the signal conditioning card connects to the lower connector of the
mass termination block. Be sure to install the strain reliefs included with the cable at
the end connected to the signal conditioning card, and connect the shield ground wire
to the shield ground bar of the DeltaV I/O carrier.
• Up to 16 analog 4-20 mA non-HART field devices can be connected to the swing-arm
screw terminals.
• You can connect single-ended, field-powered, non-isolated, channel-to-channel signals
to the swing-arm screw terminals. Field power from the DeltaV AI card is not
supported.
• This solution is not compatible with differential analog input signals.
Dimensional drawings
Figure C-84: Dimensions of Analog Input 4-20 mA Signal Conditioning Card for
PLC-5/1771 I/O
J1 connector
J2 connector
16.84 cm
(6.63 in.)
20.77 cm
(8.18 in.)
3.43 cm
(1.35 in.)
Wiring diagrams
The following diagrams show wiring methods for the Analog Input 4-20 mA Signal
Conditioning Card for PLC-5/1771 I/O.
Interface Specifications
D800001X312 
April 2021
257

--- Page 258 ---

Figure C-85: 2-wire transmitter, field power supply, loop power
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
AI 4-20 mA Signal 
Condi"oning Card for 
1771 I/O
AI 16-Channel 4-20 mA HART Series 2 Plus
 24 Pin Ribbon 
Cable
AI 16-Channel 4-20 mA HART Series 2 Plus
Primary
Secondary
Field Power
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
April 2021
D800001X312
258

--- Page 259 ---

Figure C-86: 2-wire transmitter, control-room power supply, loop power
CH1
DeltaV Chassis 
Ground (CG)
CH2
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
250Ω 
Low 
Pass 
Filter
A/D 
Converter
4-20mA 
Signal
AI 16-Channel 4-20 mA HART Series 2 Plus
Carrier
Field Power
Isola!on
Field 
48-Pin
Mass
Termblock
Channel 1
Module Common
Chassis
Ground (CG)
To DIG
DeltaV Chassis 
Ground (CG)
Control 
Room
Field
 24 Pin Ribbon 
Cable
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
AI 4-20 mA Signal 
Condi!oning Card for 
1771 I/O
Primary
Secondary
DC Ground
(DCG)
Isolated Bus
To DIG
Interface Specifications
D800001X312 
April 2021
259

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