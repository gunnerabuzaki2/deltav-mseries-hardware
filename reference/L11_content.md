--- Page 125 ---

C
Interface Specifications
This section provides specifications and wiring diagrams for all of the I/O cards and
terminal blocks.
C.1
I/O Cards
The DeltaV I/O subsystem supports multiple types of I/O cards including analog and
discrete input and output cards, HART input and output cards, serial cards, Thermocouple
mV, RTD, ohms and intrinsically safe analog and discrete input and output cards. Bus cards
such as the Fieldbus H1, Profibus DP, AS-Interface, and DeviceNet are also supported. In
addition, some of the Series 2 versions of the cards are available in Redundant mode for
high-availability applications. The I/O subsystem consists of terminal blocks that snap onto
the carrier to provide screw termination for field wiring and the I/O cards which snap over
the terminal blocks and onto the carrier. The I/O cards convert field signals to the
appropriate format for control and communications.
Figure C-1: Standard I/O Card
Up to 64 I/O cards are supported by a single I/O subsystem.
To simplify installation and ensure that the I/O interface is suitable for the plant
environment, I/O terminal blocks have field wiring protection keys that correspond to keys
on the I/O cards. The keys ensure that the I/O card and the I/O terminal block match; an
I/O card plugs into an I/O terminal block only if the keys agree.
Warning
Be sure that your I/O cards and terminal blocks are compatible before plugging in I/O
cards. Card damage can result if an I/O card and terminal block are incompatible.
Related information
I/O Interface Keying
Intrinsically Safe I/O Interface Keying
Interface Specifications
D800001X312 
April 2021
125

--- Page 126 ---

C.1.1
DeltaV Series 2 I/O
DeltaV Series 2 I/O cards have a wider operating temperature range than pre-Series 2
cards and some Series 2 cards support redundancy.
The following DeltaV I/O cards are available as Series 2:
• AI, 8-Channel, 4-20 mA (Series 2 simplex)
• AI, 4-20 mA, HART (Series 2 simplex and redundant; 2 and 4 wire)
• AI, 16, Channel, 4-20 mA, HART (Series 2 simplex)
• AO, 8-channel, 4-20 mA, HART (Series 2 simplex and redundant)
• AS-Interface (Series 2 simplex)
• DeviceNet (Series 2 simplex)
• DI, 8-Channel, 24 VDC, Dry Contact (Series 2 simplex and redundant)
• DI, 8-Channel, 24 VDC, Isolated (Series 2 simplex)
• DI, 8-Channel, 120 VAC, Dry Contact (Series 2 simplex)
• DI, 8-Channel, 120 VAC, Isolated (Series 2 simplex)
• DI, 32-Channel, 24 VDC, Dry Contact (Series 2 simplex)
• DO, 8-Channel, 24 VDC, High-Side (Series 2 simplex and redundant)
• DO, 8-Channel, 24 VDC, Isolated (Series 2 simplex)
• DO, 8-Channel, 120 VAC/230 VAC, High-Side (Series 2 simplex)
• DO, 8-Channel, 120 VAC/230 VAC, Isolated (Series 2 simplex)
• DO, 32-Channel, 24 VDC, High-Side (Series 2 simplex)
• Series 2 H1 (Series 2 simplex and redundant)
• Isolated Input (Series 2 simplex)
• Multifunction (Series 2 simplex)
• RTD, ohms (Series 2 simplex)
• Thermocouple (Series 2 simplex)
• Series 2 Profibus DP (Series 2 simplex)
• Series 2 Plus Profibus DP (Series 2 simplex and redundant)
• Sequence of Events (Series 2 simplex)
• Series 2 Serial (Series 2 simplex and redundant)
Series 2 redundant capable cards are configured, autosensed, upgraded, and operated
just like pre-Series 2 cards. Series 2 cards in Simplex mode can function as drop-in
replacements for pre-Series 2 cards of the same type. With the exception of the Simplex
mode Series 2 H1 card, which requires the Series 2 H1 terminal block, no wiring change is
required to replace a pre-Series 2 card. Series 2 cards report their operating mode (simplex
or redundant) to the DeltaV controller based on the type of terminal block on which they
are installed. Redundant terminal blocks provide wiring terminations for the redundant
Interface Specifications
April 2021
D800001X312
126

--- Page 127 ---

cards. If a card is installed on a redundant terminal block, it reports itself as operating in
Redundant mode; otherwise, it reports itself as operating in Simplex mode.
Other than redundant terminal blocks, no additional software or hardware is required to
support redundancy. A redundant terminal block spans two adjacent slots on the carrier. A
redundant I/O card consists of two Series 2 cards installed in a redundant terminal block.
Note
For redundant I/O, the lower slot number (in the carrier) in a redundant pair must be odd
and the upper slot number must be the next higher even number. For example, redundant
pairs can be installed in slots 1 and 2, 3 and 4, 9 and 10. Redundant pairs cannot be
installed in slots 6 and 7, 24 and 25. Configuration tools such as the DeltaV Explorer
enforce this requirement.
The double-wide redundant terminal blocks require only a single set of wires for each
redundant channel or fieldbus segment. (The exception is the Redundant Interface
terminal block which uses two sets of wires for the Series 2 Serial card. One set of wires is
used for each interface such as a computer.) The redundant terminal blocks contain screw
terminals appropriate for the card type and signals from the screw terminals are
connected to both cards in a redundant pair.
If all cards are redundant, the controller can support up to 32 redundant pairs. Refer to
DeltaV Books Online for more information on using Series 2 cards in a DeltaV system.
Related information
Environmental Specifications
C.1.2
AI, 8-Channel, 4-20 mA
The DeltaV system supports the following types of AI, 8-Channel, 4-20 mA cards:
• AI, 8-Channel, 4-20 mA
• AI, 8-Channel, 4–20 mA, HART (2 and 4-wire)
• Series 2 AI, 8-Channel, 4–20 mA, Simplex mode (2-wire)
• Series 2 AI, 8-Channel, 4–20 mA, HART, Simplex mode and Redundant mode (2 and 4-
wire)
Installation Notes
• The I/O terminal block is recommended to provide screw terminations for field wiring
for the AI, 8-Channel, 4–20 mA, AI, 8-Channel, 4–20 mA, HART and the Series 2 AI, 8-
Channel, 4–20 mA, HART cards. Optional terminal blocks are the fused and 4-wire I/O
blocks, the 16 pin mass termination block for 2-wire applications, and the 24-pin mass
termination block for 4-wire applications.
• The Redundant Analog Input terminal block is recommended to provide screw
terminations for field wiring for Series 2 Redundant AI, 8-Channel, 4–20 mA, HART
cards for either 2-wire or 4-wire applications.
• To function correctly, the AI cards require that 24 VDC be supplied through the bussed
field power connection. The 4-wire termination block is designed for use with 4-wire
field-powered transmitters. Power for these transmitters must be provided from an
appropriate external power source. See the transmitter specifications for power source
Interface Specifications
D800001X312 
April 2021
127

--- Page 128 ---

information. For example, if you are using the DeltaV AI, 4–20 mA I/O card with a
DeltaV 4-wire Termination Block, an external power source must be connected to the
4-wire transmitter.
• The open HART protocol layers digital information on the standard analog 4-20 mA
process signal.
Specifications
Table C-1: AI, 8-Channel, 4–20 mA, Specifications (HART and Series 2)
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Nominal signal range (span)
4 to 20 mA
Full signal range
1 to 22.5 mA, with overrange checking
Valid range for LED indication
0.75 to 23 mA
LocalBus current (12 VDC nominal), per card
120 mA typical, 150 mA maximum
Series 2 (for each card in Redundant mode
only1):
•
175 mA typical
•
250 mA maximum
Field circuit power, per card
300 mA maximum at 24 VDC (±10%)
Field circuit per channel
32 mA maximum
Series 2:
•
30 mA maximum
Accuracy over temperature range
0.1% of span
Resolution
16 bits
Repeatability
0.05% of span
Rolloff frequency
-3 dB at 2.7 Hz, -20.5 dB at one-half the
sampling frequency
Calibration
None required
Communications Support (only for version with
HART)
•
HART pass-through request/response
•
HART variable report
•
Field device status report
HART scan time
600-800 ms (typical) per enabled channel
Optional fuse (Simplex mode only)
2.0 A
Mounting
Assigned slot of I/O carrier
1
Double for a redundant pair.
Interface Specifications
April 2021
D800001X312
128

--- Page 129 ---

Wiring Diagrams
Figure C-2: Wiring Diagram for 2-Wire AI, 8-Channel, 4–20 mA and AI, 8-Channel, 4–
20 mA, HART
+
+
-
-
Carrier
I/O Card
Termination
(Odd no.)
(Even no.)
250 Ω
Common
connection
for 8 channels
T
Low
pass
filter
Current
limiter
A/D
Converter
System
24 VDC Bussed
field power connection
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
Optional fuse
2-Wire analog
and/or HART
field transmitter
I/O Terminal block
Interface Specifications
D800001X312 
April 2021
129

--- Page 130 ---

Figure C-3: Wiring Diagram for Series 2, 2-Wire AI, 8-Channel, 4–20 mA, HART in
Simplex Mode
+
+
-
-
Carrier
Termination
I/O Card
(Odd no.)
(Even no.)
250 Ω
Common
connection
for 8 channels
T
Low
pass
filter
Current
limiter
A/D
Converter
System
24 VDC Bussed
field power connection
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
Optional fuse
2-wire analog
and/or HART
field transmitter
I/O
Terminal block
Interface Specifications
April 2021
D800001X312
130

--- Page 131 ---

Figure C-4: Wiring Diagram for Series 2, 2-Wire AI, 8-Channel, 4–20 mA, HART in
Redundant Mode
+
-
Carrier
2-Wire
redundant
termination
Primary I/O card
Secondary I/O card
(Even no.)
Common
connections
for 8 channels
System
+
-
-
+
(Odd no.)
T
Low pass
filter
Current
limiter
250 Ω
System
Low pass
filter
Mode
Current
limiter
250 Ω
A/D
Converter
A/D
Converter
24 VDC Bussed
field power connection
1
2
3
4
5
6
7
8
Ch 1
+ -
Ch 2
+ -
Ch 3
+ -
Ch 4
+ -
9 10 11 12 13 14 15 16
Ch 5
+ -
Ch 6
+ -
Ch 7
+ -
Ch 8
+ -
2-Wire analog
and/or HART
field transmitter
Relay
Redundant
analog input
terminal block
Interface Specifications
D800001X312 
April 2021
131

--- Page 132 ---

Figure C-5: Wiring Diagram for Series 2, 4-Wire AI, 8-Channel, 4–20 mA, HART in
Simplex Mode
Common
connection
for 8 channels
+
+
-
-
Carrier
I/O Card
4-Wire
termination
(Odd no.)
(Even no.)
250 Ω
T
Low
pass
filter
System
A/D
Converter
24 VDC Bussed
field power connection
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
4-Wire analog and/or
HART field transmitter
(with user supplied power
and isolated current output)
4-Wire I/O terminal block
Interface Specifications
April 2021
D800001X312
132

--- Page 133 ---

Figure C-6: Wiring Diagram for Series 2, 4-Wire AI, 8-Channel, 4–20 mA, HART in
Redundant Mode
+
-
Carrier
4-wire
redundant
termination
Primary I/O card
Secondary I/O card
(Even no.)
Common
connections
for 8 channels
System
+
-
-
+
(Odd no.)
T
250 Ω
System
Mode
250 Ω
Low pass
filter
A/D
Converter
Low pass
filter
A/D
Converter
24 VDC Bussed
field power connection
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
4-Wire analog
and/or HART field
transmitter (with user
supplied power and
isolated current output)
Relay
Redundant analog
input terminal block
Related information
16-Pin Mass Termination Block
24-Pin Mass Termination Block
Redundant Analog Input Terminal Block
I/O Terminal Blocks
C.1.3
AI, 8-Channel, 1-5 VDC
Installation Notes
• The 4-wire I/O terminal block is recommended to provide screw terminations for field
wiring for the AI, 8-Channel, 1–5 VDC card. The 24-pin mass termination block can also
be used.
• The AI, 1–5 VDC card does not provide power to the field transmitter. To function
correctly, the AI cards require that 24 VDC power be connected for field power.
Interface Specifications
D800001X312 
April 2021
133

--- Page 134 ---

Specifications
Table C-2: AI, 8-Channel, 1–5 VDC Specifications
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Nominal signal range (span)
1 to 5 VDC
Full signal range
0.25 to 5.64 VDC, with overrange checking
Valid range for LED indication
0.18 to 5.77 VDC
LocalBus current (12 VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Field circuit power, per card
100 mA (used on card) at 24 VDC (±10%)
Input impedance
2 MΩ
Accuracy over temperature range
0.1% of span
Resolution
16 bits
Repeatability
0.05% of span
Rolloff frequency
•
-3 dB at 1.3 Hz
•
-25 dB at one-half the sampling frequency
Calibration
None required
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
134

--- Page 135 ---

Wiring Diagram
Figure C-7: Wiring Diagram for AI, 8-Channel, 1–5 VDC
+
-
Carrier
4-Wire
termination
I/O Card
(Even no.)
Common
connection
for 8 channels
System
-
+
(Odd no.)
T
Low
pass
filter
A/D
Converter
24 VDC Bussed
field power connection
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
4-Wire analog and/or
HART field transmitter
(with user-supplied power
and isolated voltage output)
4-Wire I/O terminal block
Related information
24-Pin Mass Termination Block
I/O Terminal Blocks
C.1.4
AI, 16-Channel, 4-20 mA, HART
The DeltaV system supports the Series 2 AI, 16-Channel, 4-20 mA, HART card in Simplex
mode and the AI, 16-Channel, 4-20 mA, HART, Series 2 Plus card in redundant mode.
Installation Notes
• The 16-channel Analog Input terminal block provides screw terminations for field
wiring for the simplex Series 2 AI, 16-Channel, 4-20 mA, HART card used with 2-wire
field devices.
• The 4-wire 16-Channel Analog Input Terminal Block provides screw terminations for
field wiring for the simplex, Series 2 AI, 16-Channel, 4-20 mA, HART card used with 4-
wire field devices.
• The Redundant 16-Channel Analog Input Terminal Block provides screw terminations
for a redundant pair of AI, 16-Channel, 4-20 mA, HART, Series 2 Plus cards used with 2-
or 4-wire field devices.
• The Redundant Analog Input 48-Pin Mass Termination Block can also be used to
provide terminations for a redundant pair of AI, 16-Channel, 4-20 mA, HART, Series 2
Plus cards.The AI/AO Mass Connection Board can be used to provide an interface to the
AI, 16-Channel, 4-20 mA, HART, Series 2 Plus card used with the Redundant Analog
Input 48-Pin Mass Termination Block.
Interface Specifications
D800001X312 
April 2021
135

--- Page 136 ---

• To function correctly, the card requires that 24 VDC be supplied through the bussed
field power connection.
Specifications
Table C-3: AI, 16-Channel, 4-20 mA, HART (Series 2 and Series 2 Plus)
Item
Specifications
Number of channels
16
Isolation
Field to system isolation is factory tested to
1000 VDC. No channel to channel isolation.
Nominal signal range (span)
4 to 20 mA
Full signal range
2 to 22 mA
2-wire transmitter power
13.5 V min. at 20 mA (current limited to 29 mA
maximum)
LocalBus current (12 VDC nominal)
85 mA typical, 150 mA maximum
Field circuit power (per card)
600 mA maximum at 24 VDC (±10%)
Field circuit per channel
30 mA maximum
Accuracy over temperature range
0.2% of span
Resolution
16 bits
Repeatability
0.05% of span
Filtering
•
-3 db at 2.7 Hz
•
-6 db at 4.6 Hz
•
-20.5 db at 20 Hz
•
-34 db at 50 Hz
•
-90 db at 1200 Hz
Rolloff frequency
-3 dB at 2.7 Hz, -20.5 dB at one-half the
sampling frequency
Calibration
None required
Communications support
•
HART pass-through request/response
•
HART variable report
•
Field device status report
HART scan time
600-800 ms (typical) per enabled channel
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
136

--- Page 137 ---

Wiring Diagrams
Figure C-8: Wiring Diagram for Series 2 AI, 16-channel, 4-20 mA, HART connected to a
two-wire device
Common
connection
for 16 channels
+
-
Carrier
I/O Card
Termination
(Odd no.)
(Even no.)
System
+
-
24 VDC Bussed
field power connection
Low
pass
filter
Current 
limiter
A/D
Converter
T
250 Ω
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
2-Wire analog and/or
HART field transmitter
AI 16-channel
terminal block
Interface Specifications
D800001X312 
April 2021
137

--- Page 138 ---

Figure C-9: Wiring Diagram for Series 2 AI, 16-channel, 4-20 mA, HART connected to a
4-wire device
Low
pass
filter
Common
connection
for 16 channels
+
-
Carrier
I/O Card
4-wire
Termination
(Odd no.)
(Even no.)
System
+
-
24 VDC Bussed
field power connection
A/D
Converter
T
250 Ω
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
4-Wire analog and/or
HART field transmitter
4-wire 16-channel
Analog Input
terminal block
Interface Specifications
April 2021
D800001X312
138

--- Page 139 ---

Figure C-10: Wiring Diagram for Redundant AI, 16-Channel, 4-20 mA, HART, Series 2
Plus
+
-
Carrier
Redundant
termination
Primary I/O card
Secondary I/O card
Common
connections
for 16 channels
System
+
-
-
+
-
+
Low pass
filter
Current
limiter
250 Ω
System
Low pass
filter
Mode
Current
limiter
250 Ω
A/D
Converter
A/D
Converter
24 VDC Bussed
field power connection
T
T
Redundant 16-channel
Analog Input terminal 
block
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
34
35
36
37
38
39
40
41
42
43
44
45
46
47
33
48
+
–
+
–
2-wire
4-wire
2-Wire analog
and/or HART
field transmitter
Relay
4-Wire analog
and/or HART
field transmitter
Related information
16-Channel Analog Input Terminal Block
C.1.5
AO, 8-Channel, 4-20 mA
The DeltaV system supports the following types of AO, 8-Channel, 4–20 mA cards:
• AO, 8-Channel, 4-20 mA
• AO, 8-Channel, 4-20 mA, HART
• Series 2 AO, 8-Channel, 4-20 mA, HART (Simplex and Redundant modes)
Interface Specifications
D800001X312 
April 2021
139

--- Page 140 ---

Installation Notes
• The I/O terminal block is recommended to provide terminations for field wiring for the
AO, 8-Channel, 4–20 mA, AO, 8-Channel, 4–20 mA, HART and the Series 2 AO, 8-
Channel, 4–20 mA, HART cards in Simplex mode. Optional terminal blocks are the
fused I/O block and the 16-pin mass termination block.
• The Redundant Analog Output terminal block is recommended to provide
terminations for field wiring for the Series 2 AO, 8-Channel, 4–20 mA, HART card in
Redundant mode.
• The open HART protocol layers digital information on the standard analog 4-20 mA
process signal.
Specifications
Table C-4: AO, 8-Channel, 4–20 mA Specifications (HART and Series 2)
Item
Specifications
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Nominal signal range (span)
4 to 20 mA
Full signal range
1 mA to 23 mA
LocalBus current (12 VDC nominal), per card
120 mA typical, 150 mA maximum
Series 2 (for each card in Redundant mode
only 1 :)
•
175 mA typical
•
250 mA maximum
Field circuit power, per card
300 mA maximum at 24 VDC (±10%)
Accuracy over temperature range
0.25% of span (0 - 60°C)
Series 2:
•
0.25% (0 to 60°C)
•
0.4% (-40 to 70°C)
Resolution
•
12 bits for AO, 8-channel, 4-20 mA
•
14 bits for AO, 8-channel, 4-20 mA, HART
•
14 bits for Series 2 AO, 8-channel, 4-20
mA, HART
Output compliance
20 mA at 21.6 VDC supply into 700 Ω load
Calibration
Information stored on card
Communications Support (only for version with
HART)
•
HART pass-through request/response
•
HART variable report
•
Field device status report
HART scan time
600-800 ms (typical) per enabled channel
Interface Specifications
April 2021
D800001X312
140

--- Page 141 ---

Table C-4: AO, 8-Channel, 4–20 mA Specifications (HART and Series 2) (continued)
Item
Specifications
Optional fuse (Simplex mode only)
2.0 A
Mounting
Assigned slot of I/O carrier
1
Double for a redundant pair.
Wiring Diagrams
Figure C-11: Wiring Diagram for Series 2 AO, 8-Channel, 4–20 mA, HART in Simplex
Mode
+
+
-
-
Carrier
I/O Card
Termination
(Odd no.)
(Even no.)
Common
connection
for 8 channels
System
D/A
Converter
Load
24 VDC Bussed
field power connection
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
4-20 mA current source
4-20 mA device and/or HART 
Optional fuse
I/O Terminal block
Interface Specifications
D800001X312 
April 2021
141

--- Page 142 ---

Figure C-12: Wiring Diagram for Series 2 AO, 8-Channel, 4–20 mA, HART in
Redundant Mode
+
-
Carrier
Redundant
termination
Primary I/O card
Secondary I/O card
(Even no.)
Common
connections
for 8 channels
System
+
-
-
+
(Odd no.)
System
Mode
Load
D/A
Converter
D/A
Converter
24 VDC Bussed
field power connection
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
4-20 mA device
and/or HART
Relay
Redundant analog
output terminal block
Related information
I/O Terminal Blocks
16-Channel Analog Input Terminal Block
Redundant Analog Output Terminal Block
C.1.6
AO, 16-Channel, 4-20 mA HART, Series 2 Plus
Installation notes
• The Redundant 16-Channel Analog Output Terminal Block is recommended to provide
screw terminations for a redundant pair of AO, 16-Channel, 4-20 mA HART, Series 2
Plus cards.
• The Simplex 16-Channel Analog Output terminal Block provides screw terminations for
the AO, 16-Channel, 4-20 mA HART, Series 2 Plus card in Simplex mode.
Interface Specifications
April 2021
D800001X312
142

--- Page 143 ---

Specifications
Table C-5: AO, 16-Channel, 4-20 mA HART, Series 2 Plus specifications
Item
Specification
Number of channels
16
Isolation
Each channel is galvanically isolated from the
system and factory tested to 1000 VDC. (No
channel to channel isolation.)
Nominal signal range (span)
4 to 20 mA
Full signal range
1 to 23 mA
LocalBus current (12 VDC nominal), per card
260 mA maximum in redundant configurations
Field power (per card)
400 mA maximum at 24 VDC
Accuracy over temperature range
0.25% of span
Resolution
14 bits
Output compliance
•
Voltage to load: 14 V minimum @ 20 mA
•
Load Resistance: 700 Ω maximum
Open loop detection
Detection threshold: 0.70 mA
HART communications support
•
HART pass-through request/response
•
HART variable report
•
Field device status report
HART scan time
600-800 ms (typical) per enabled channel
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
143

--- Page 144 ---

Wiring diagram
Figure C-13: Wiring diagram for AO, 16-Channel, 4-20 mA HART, Series 2 Plus
+
-
Carrier
Redundant
termination
Primary I/O card
Secondary I/O card
(Even no.)
System
+
-
-
+
(Odd no.)
System
Mode
Load
D/A
Converter
D/A
Converter
Common
connections
for 16 channels
24 VDC Bussed
field power connection
4-20 mA device
and/or HART
Relay
Redundant 16 Channel Analog
Output Terminal Block
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
+
–
Interface Specifications
April 2021
D800001X312
144

--- Page 145 ---

Figure C-14: Wiring diagram for AO, 16-Channel, 4-20 mA HART, Series 2 Plus
(Simplex)
Carrier
Primary I/O card
(Even no.)
System
+
-
-
+
(Odd no.)
Load
D/A
Converter
Common
connections
for 16 channels
24 VDC Bussed
field power connection
4-20 mA device
and/or HART
Simplex 16-Channel Analog
Output Terminal Block
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
C.1.7
AS-Interface
The DeltaV system supports the Actuator Sensor-Interface card (AS-Interface) and the
Series 2 AS-Interface card in Simplex mode.
The AS-Interface is a digital, serial, bi-directional communications protocol and bus system
that interconnects simple binary on/off devices such as actuators, sensors, and discrete
devices in the field. The AS-Interface standard is defined by CENELEC standard EN 50295.
The two-conductor AS-Interface cable supplies both power and data for field devices. An
AS-Interface network can include branches. The total cable length, (main line and all
branches), cannot exceed 100 meters. Refer to the following table for AS-Interface cable
distance limits and to the AS-Interface standard (EN 50295) for design and engineering
details on AS-Interface cable.
Interface Specifications
D800001X312 
April 2021
145

--- Page 146 ---

Table C-6: AS-Interface Cable Distance Limits
Item
Specification
Recommended cable
Unshielded AS-Interface yellow cable1
Distance limits
•
100 meters total length (main line and
branches) without repeater or extender
•
300 meters total length (main line and
branches) with two repeaters2
•
300 meters total length (main line and
branches) with one extender and one
repeater
1
Any other cable, shielded or unshielded, can be used if the installation meets all the impedance
requirements specified in the AS-Interface standard (EN 50295).
2
Repeaters require an additional AS-Interface power supply on the far side of the repeater.
For more information on the AS-Interface and for information on installing AS-Interface
devices, refer to the AS-Interface web site at www.as-interface.com.
Installation Notes
• The Interface terminal block provides terminations for field wiring for the AS-Interface
card and the Series 2 AS-Interface card in Simplex mode.
• It is recommended that you do not connect the AS-Interface devices directly to the AS-
Interface card terminals. Use one AS-Interface cable to connect the AS-Interface card to
the power supply and use another AS-Interface cable to connect the devices to the
power supply.
• If you are using extenders and repeaters, refer to the device data sheet for additional
cabling recommendations.
• The AS-Interface bus requires a special AS-Interface power supply (purchased
separately) that provides electrical isolation from the data signals. A standard power
supply can be used but it must have a conditioning module added to its output. Refer
to the AS-Interface standard (EN 50295) for design and engineering details on the AS-
Interface power supply.
• The "System Power Guidelines" section provides information on extending power to an
AS-Interface bus.
Table C-7: AS-Interface Specifications
Item
Specification
Number of ports
Two
Port Type
Actuator Sensor-Interface – 167 kb/second
Isolation
Each port is optically isolated from the system
and from each other and factory tested to 1500
VDC.
LocalBus Current
300 mA (max)
24 VDC Field circuit power, per card
None
30 VDC AS-Interface field power per port
70 mA (max)
Interface Specifications
April 2021
D800001X312
146

--- Page 147 ---

Table C-7: AS-Interface Specifications (continued)
Item
Specification
Mounting
Assigned slot of I/O carrier
Wiring Diagram
Figure C-15: Wiring Diagram for AS-Interface
I/O Card
Carrier
Termination
AS-i
Encoder/
decoder
System
10 AS-i (-)
12, 14, 16 AS-i (-)
9 AS-i (+)
11, 13, 15 AS-i (+)
2 AS-i (-)
4, 6, 8 AS-i (-)
3, 5, 7 AS-i (+)
1 AS-i (+)
AS-i
Encoder/
decoder
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
Port
1
Port
2
AS-i +
AS-i -
Interface terminal block
Related information
Interface Terminal Block
System Power Guidelines
C.1.8
DeviceNet
The DeltaV system supports the DeviceNet card and Series 2 DeviceNet card in Simplex
mode.
DeviceNet is an all digital, serial, bi-directional communication protocol that interconnects
devices in the field. For information on installing DeviceNet devices, refer to the DeviceNet
web site at www.odva.org.
Interface Specifications
D800001X312 
April 2021
147

--- Page 148 ---

Installation Notes
• The Fieldbus H1 terminal block is recommended to provide terminations for field
wiring for the DeviceNet card and Series 2 DeviceNet card in Simplex mode. The key on
the H1 terminal block is set to D6 at the factory. Change the key position to D5 to
match the key on the Series 2 DeviceNet card.
• The shield on the terminal block can be grounded at pin 8 if required by the
application. Refer to Figure C-16.
• The section "System Power Guidelines" provides information on extending power to a
DeviceNet network.
Specifications
Table C-8: DeviceNet Interface Specifications (includes Series 2)
Item
Specification
Number of Ports
One
Port Type
DeviceNet
LocalBus current (12 VDC nominal), per card
400 mA typical, 600 mA maximum
Field circuit power (24 VDC nominal), per card
40 mA maximum at 24 VDC (±10%)
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
148

--- Page 149 ---

Wiring Diagram
Figure C-16: Wiring Diagram for DeviceNet
I/O Card
Carrier
Termination
Regulator
System
1
2
3
4
5
6
7
8
+
V
V CL
S CH
-
S
Fieldbus H1 terminal
block (change key
position to D5)
2  CAN LO
8  Shield
4  CAN HI
3  Shield
1  24 VDC return
5  +24 VDC
Related information
System Power Guidelines
Fieldbus H1 Terminal Block
C.1.9
DI, 8-Channel, 24 VDC, Dry Contact
The DeltaV system supports the DI, 8-Channel, 24 VDC, Dry Contact card and the Series 2
DI, 8-Channel, 24 VDC, Dry Contact card (Simplex and Redundant modes).
Installation Notes
• The Fused I/O terminal block is recommended to provide screw terminations for field
wiring for the DI, 8-Channel, 24 VDC, Dry Contact card and the Series 2 DI, 8-Channel,
24 VDC, Dry Contact card in Simplex mode. Optional terminal blocks are the I/O
terminal block and the 16-pin mass termination block.
• The Redundant Discrete terminal block is recommended to provide screw terminations
for field wiring for the Series 2 DI, 8-Channel, 24 VDC, Dry Contact card in Redundant
mode.
• Compatibility with NAMUR Sensors — The Series 2 DI, 8-channel, 24 VDC, Dry
Contact card is compatible with many NAMUR sensors that operate within an
excitation voltage range of 5 to 18 V. Emerson recommends testing your application if
Interface Specifications
D800001X312 
April 2021
149

--- Page 150 ---

it includes NAMUR sensors. You may need to adjust the field circuit power by altering
the supply voltage in order to ensure proper operation. NAMUR sensors not designed
to operate in the 5 to 18 V range may not work with Series 2 DI, 8-channel, 24 VDC, Dry
Contact cards.
• Line Fault Detection — The Series 2 DI, 8-Channel, 24 VDC Dry Contact card has line
fault detection for detecting open or short circuits in field wiring. To use this capability
you must:
— Enable line fault detection in your configuration. Enable line fault detection on a
channel-by-channel basis when you configure the channels.
— Connect the dry contact to external resistors. Connect the dry contact to a 6.8 KΩ
resistor in parallel (allows the open circuit detection) and a 2.4 KW resistor in series
(allows short circuit detection).
Figure C-17: External Line Fault Detection Resistors
+
-
2.4KΩ
6.8KΩ
(Odd no.)
(Even no.)
Line Fault Detection
Value Detected
Short Circuit
<100 Ω for guaranteed short circuit
detection
Open Circuit
>100 kΩ for guaranteed open loop detection
— Line Fault Detection in NAMUR Sensors — Line fault detection is built into NAMUR
sensors. Do not use external resistors with NAMUR sensors; however, you must
enable line fault detection in your configuration when using NAMUR sensors.
Specifications
Table C-9: DI, 8-Channel, 24 VDC, Dry Contact Specifications (includes Series 2)
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Detection level for On
> 2.2 mA
Detection level for Off
< 1 mA
Impedance
5 kΩ
Interface Specifications
April 2021
D800001X312
150

--- Page 151 ---

Table C-9: DI, 8-Channel, 24 VDC, Dry Contact Specifications (includes Series 2)
(continued)
Item
Specification
LocalBus current (12 VDC nominal), per card
•
75 mA typical
•
100 mA maximum
Series 2:
•
90 mA typical
•
150 mA maximum
Field circuit power, per card
100 mA at 24 VDC (±10%)
Optional fuse (Simplex mode only)
2.0 A
Mounting
Assigned slot of I/O carrier
Wiring Diagrams
Figure C-18: Wiring Diagram for DI, 8-Channel, 24 VDC, Dry Contact
+
+
-
-
Carrier
I/O Card
Termination
(Odd no.)
(Even no.)
Common
connection
for 8 channels
System
24 VDC Bussed
field power connection
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
Optional fuse
I/O Terminal block
Interface Specifications
D800001X312 
April 2021
151

--- Page 152 ---

Figure C-19: Wiring Diagram for Series 2 DI, 8-Channel, 24 VDC, Dry Contact in
Simplex Mode
Carrier
Termination
I/O Card
(Even no.)
Common
connection
for 8 channels
+
-
-
System
5K Ω
Logic
+
(Odd no.)
24 VDC Bussed
field power connection
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
I/O Terminal block
Optional fuse
Interface Specifications
April 2021
D800001X312
152

--- Page 153 ---

Figure C-20: Wiring Diagram for Series 2 DI, 8-Channel, 24 VDC, Dry Contact in
Redundant Mode
+
+
-
Carrier
Redundant
termination
Primary I/O card
Secondary I/O card
(Even no.)
Common
connections
for 8 channels
System
+
-
-
(Odd no.)
5K Ω
Mode
System
5K Ω
Logic
Logic
24 VDC Bussed
field power connection
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
Redundant
discrete
terminal block
Relay
Related information
I/O Terminal Blocks
16-Pin Mass Termination Block
Redundant Discrete Terminal Block
C.1.10
DI, 8-Channel, 24 VDC, Isolated
The DeltaV system supports the DI, 8-Channel, 24 VDC, Isolated card and the Series 2 DI,
8-Channel, 24 VDC, Isolated card in Simplex mode.
Installation Notes
• The I/O terminal block is recommended to provide screw terminations for field wiring
for the DI, 8-Channel, 24 VDC, Isolated card and the Series 2 DI, 8-Channel, 24 VDC,
Isolated card in Simplex mode. Optional terminal blocks are the fused I/O terminal
block and the 16-pin mass termination block.
• If you use a mass termination block with the DI, 8-Channel, 24 VDC, Isolated card, refer
to the termination block specifications for the input rating for each block. Those
Interface Specifications
D800001X312 
April 2021
153

--- Page 154 ---

specifications might be more restrictive than the specifications listed in the following
table.
Specifications
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and from each other and factory tested
to 1500 VDC.
Detection level for On
> 10 VDC
Detection level for Off
< 5 VDC
Input impedance
5 kΩ
LocalBus current (12 VDC nominal), per card
•
75 mA typical
•
100 mA maximum
Field circuit power, per card
None
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
Wiring Diagram
Figure C-21: Wiring Diagram for DI, 8-Channel, 24 VDC, Isolated
+
-
I/O Card
Termination
Carrier
(Odd no.)
(Even no.)
System
5K Ω
24
VDC
Source-
+
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
I/O Terminal block
Optional fuse
Related information
I/O Terminal Blocks
16-Pin Mass Termination Block
Interface Specifications
April 2021
D800001X312
154

--- Page 155 ---

C.1.11
DI, 8-Channel, 120 VAC, Dry Contact
The DeltaV system supports the DI, 8-Channel, 120 VAC Dry Contact card and the Series 2
DI, 8-Channel, 120 VAC Dry Contact card in Simplex mode.
Installation Notes
The Fused I/O terminal block is recommended to provide screw terminations for field
wiring for the DI, 8-channel, 120 VAC, Dry Contact card and the Series 2 DI, 8-channel, 120
VAC, Dry Contact card in Simplex mode. An optional terminal block is the I/O block.
Specifications
Item
Specifications
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC.
Detection level for On
> 1.4 mA
Detection level for Off
< 0.56 mA
Impedance
60 kΩ
LocalBus current (12 VDC nominal), per card
•
75 mA
•
100 mA maximum
Field circuit power, per card
15 mA at 120 VAC
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
155

--- Page 156 ---

Wiring Diagram
Figure C-22: Wiring Diagram for DI, 8-Channel, 120 VAC, Dry Contact
L
+
-
N
Carrier
Termination
I/O Card
(Odd no.)
(Even no.)
Common
connection
for 8 channels
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
120 VAC Bussed
field power connection
Optional fuse
I/O Terminal block
Related information
I/O Terminal Blocks
C.1.12
DI, 8-Channel, 120 VAC, Isolated
The DeltaV system supports the DI, 8-channel, 120 VAC, Isolated card and the Series 2 DI,
8-channel, 120 VAC, Isolated card in Simplex mode.
Installation Notes
The I/O terminal block is recommended to provide screw terminations for field wiring for
the DI, 8-channel, 120 VAC, Isolated card and the Series 2 DI, 8-channel, 120 VAC, Isolated
card in Simplex mode. An optional terminal block is the Fused I/O block.
Specifications
Table C-10: DI, 8-Channel, 120 VAC, Isolated Specifications
Item
Specifications
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC and from other channels at
250 VAC.
Detection level for On
84 VAC to 130 VAC1
Interface Specifications
April 2021
D800001X312
156

--- Page 157 ---

Table C-10: DI, 8-Channel, 120 VAC, Isolated Specifications (continued)
Item
Specifications
Detection level for Off
0 VAC to 34 VAC
Input load (contact cleaning)
2 mA at 120 VAC
Input impedance
60 kΩ
LocalBus current (12 VDC nominal), per card
•
75 mA typical
•
100 mA maximum
Field circuit power, per card
None
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
1
Phase should be considered when applying AC voltage to multiple input channels.
Wiring Diagram
Figure C-23: Wiring Diagram for DI, 8-Channel, 120 VAC, Isolated
L
+
-
N
Termination
I/O Card
Carrier
(Odd no.)
(Even no.)
System
120
VAC
Source
60K Ω
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
Optional fuse
I/O Terminal block
Related information
I/O Terminal Blocks
C.1.13
DI, 8-Channel, 230 VAC, Dry Contact
Installation Notes
The Fused I/O terminal block is recommended to provide screw terminations for field
wiring for the DI, 8-channel, 230 VAC, Dry Contact card. An optional terminal block is the
I/O block.
Interface Specifications
D800001X312 
April 2021
157

--- Page 158 ---

Specifications
Table C-11: DI, 8-Channel, 230 VAC, Dry Contact Specifications
Item
Specifications
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC.
Detection level for On
> 0.71 mA
Detection level for Off
< 0.28 mA
Impedance
238 kΩ
LocalBus current (12 VDC nominal), per card
•
75 mA
•
100 mA maximum
Field circuit power, per card
7 mA at 230 VAC
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
Wiring Diagram
Figure C-24: Wiring Diagram for DI, 8-Channel, 230 VAC, Dry Contact
L
+
-
N
Carrier
Termination
I/O Card
(Odd no.)
(Even no.)
Common
connection
for 8 channels
System
230 VAC Bussed
field power connection
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
Optional fuse
I/O Terminal block
Related information
I/O Terminal Blocks
Interface Specifications
April 2021
D800001X312
158

--- Page 159 ---

C.1.14
DI, 8-Channel, 230 VAC, Isolated
Installation Notes
The I/O terminal block is recommended to provide screw terminations for field wiring for
the DI, 8-channel, 230 VAC, Isolated card. An optional terminal block is the Fused I/O
block.
Specifications
Table C-12: DI, 8-Channel, 230 VAC, Isolated Specifications
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC and from other channels at
250 VAC.
Detection level for On
168 VAC to 250 VAC
Detection level for Off
0 VAC to 68 VAC
Input load (contact cleaning)
1 mA at 230 VAC
Input impedance
238 kΩ
LocalBus current (12 VDC nominal), per card
•
75 mA
•
100 mA maximum
Field circuit power, per card
None
Optional fuse
2.0 A
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
159

--- Page 160 ---

Wiring Diagram
Figure C-25: Wiring Diagram for DI, 8-Channel, 230 VAC, Isolated
L
+
-
N
Termination
Carrier
I/O Card
(Odd no.)
(Even no.)
System
230
VAC
Source
238K Ω
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
Optional fuse
I/O Terminal block
Related information
I/O Terminal Blocks
C.1.15
DI, 32-Channel, 24 VDC, Dry Contact
The DeltaV system supports the DI, 32-Channel, 24 VDC, Dry Contact card and the Series 2
DI, 32-Channel, 24 VDC, Dry Contact card in simplex mode and the DI, 32-Channel, 24
VDC, Dry Contact Series 2 Plus card in redundant mode.
Installation Notes
• The 32-Channel terminal block can provide screw terminations for field wiring for the
simplex DI, 32-channel, 24 VDC, Dry Contact and Series 2 DI, 32-channel, 24 VDC, Dry
Contact cards in simplex mode.
• The 40-pin mass termination block can provide terminations for field wiring for the
simplex DI, 32-channel, 24 VDC, Dry Contact and Series 2 DI, 32-channel, 24 VDC, Dry
Contact cards.
• The DI Mass Connection Board (single) or the DI Mass Connection Solution (two) can be
used to provide an interface to the Series 2 DI, 32-Channel, 24 VDC, Dry Contact card
used with the 40-pin mass termination block in simplex mode.
• The Redundant 32-Channel Discrete Input Terminal Block is recommended to provide
screw terminations for field wiring for the redundant DI, 32-Channel, 24 VDC, Dry
Contact Series 2 Plus card.
Interface Specifications
April 2021
D800001X312
160

--- Page 161 ---

• The Redundant Discrete Input 40-Pin Mass Termination Block can be used to provide
terminations for a redundant pair of DI, 32-Channel, 24 VDC, Dry Contact Series 2 Plus
cards
• The Series 2 Plus DI Mass Connection Board (single) or the Series 2 Plus DI Mass
Connection Solution (two) can be used to provide an interface to the DI, 32-Channel,
24 VDC Dry Contact Series 2 Plus card used with the Redundant Discrete Input 40-Pin
Mass Termination Block.
• For the Series 2 DI, 32-Channel, 24 VDC, Dry Contact card, the return connection for all
32 channels is the 24 VDC field power ground. You must supply an external wire to
make this connection. However the connection is internally made if the 40-pin mass
termination block is used and no external wire is required.
• For the DI, 32-Channel, 24 VDC, Dry Contact Series 2 Plus card, the common
connection for all 32 channels is the 24 VDC field power. You must supply an external
wire to make this connection. However the connection is internally made if the 40-pin
mass termination block is used and no external wire is required.
• When the redundant DI, 32-Channel, 24 VDC, Dry Contact, Series 2 Plus card is used
with the Redundant Discrete Input 40-Pin Mass Termination Block and the DI Mass
Connection Solution, the card can be configured to detect faults in the termination.
Two parameters, T1_FAULT_DETECT (for the ribbon cable connection for channels
1-16), and T2_FAULT_DETECT (for the ribbon cable connection for channels 17-32),
can be enabled in DeltaV Explorer for the card. When these parameters are set to True,
detection of the ribbon cable connection between the Redundant Discrete Input 40 Pin
Mass Termination Block and the DI Mass Connection Board is enabled and the system
detects faults such as a missing cable or missing Mass Connection Board.
Note
The termination fault detection feature is available only when the redundant DI, 32-
Channel, 24 VDC, Dry Contact Series 2 Plus card is used with the Redundant Discrete Input
40-Pin Mass Termination Block connected to the DI Mass Connection Solution.
Specifications
Table C-13: DI, 32-Channel, 24 VDC, Dry Contact (includes Series 2 and Series 2 Plus)
Item
Specification
Number of channels
32
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Detection level for ON
> 2 mA
Detection level for OFF
< 0.25 mA
Impedance
5 KΩ
LocalBus current (12VDC nominal), per card
•
50 mA typical
•
75 mA maximum
Field circuit power, per card
150 mA at 24 VDC (±10%)
Series 2: 150 mA at 24 VDC (-15%/+20%)
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
161

--- Page 162 ---

Wiring Diagram
Figure C-26: Wiring Diagram for DI, 32-Channel, 24 VDC Dry Contact and Series 2
+
Common
connection
for 32
channels
System
+
-
Carrier
I/O Card
Termination
24 VDC Bussed
field power connection
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
32-Channel terminal
block (the numbers
indicate the channel
assigments)
Interface Specifications
April 2021
D800001X312
162

--- Page 163 ---

Figure C-27: Wiring Diagram for DI, 32-Channel, 24 VDC Dry Contact, Series 2 Plus
+
Carrier
Redundant
termination
Primary I/O card
Secondary I/O card
Common
connections
for 32 channels
-
System
System
24 VDC Bussed
field power connection
Redundant 32-channel
terminal block (numbers
indicate channel
assignments)
Common
connections
for 32 channels
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
Related information
32-Channel Terminal Block
40-Pin Mass Termination Block
C.1.16
DO, 8-Channel, 24 VDC, High-Side
The DeltaV system supports the DO, 8-Channel, 24 VDC, High-Side card and the Series 2
DO, 8-Channel, 24 VDC, High-Side card (Simplex and Redundant modes).
Installation Notes
• The Fused I/O terminal block is recommended to provide screw terminations for field
wiring for the DO, 8-channel, 24 VDC, High-Side and the Series 2 DO, 8-channel, 24
VDC, High-Side card in Simplex mode. Optional terminal blocks are the I/O terminal
block, and the 10 and 16-pin mass termination blocks.
• If you use a mass termination block with the DO, 8-channel, 24 VDC, High-Side I/O
card, refer to the termination block specifications for the output rating for each block.
Interface Specifications
D800001X312 
April 2021
163

--- Page 164 ---

Those specifications might be more restrictive than the specifications listed in Table
C-14.
• The Redundant Discrete terminal block is recommended to provide screw terminations
for field wiring for the Series 2 DO, 8-channel, 24 VDC, High-Side card.
• Line Fault Detection — The Series 2 DO, 8-Channel, 24 VDC High-Side card has line
fault detection that can be enabled on a channel-by-channel basis as a configuration
item. When line fault detection is enabled, the card detects open and short line fault
conditions by performing an internal readback of the output to verify its value in both
on and off states. The card tests the opposite state of its current value by temporarily
changing the output to that value, performing the internal readback, then returning
the output to its configured output value. The pulses to the opposite state are never
greater than 200 µSec. High speed inputs that connect to a DO channel with line fault
enabled must consider these pulses in the input software scheme. When line fault
detection is not enabled, a more limited detection of open and short line fault
conditions is available on the active redundant card only. This is accomplished by the
internal readback mechanism without pulsing the output to the opposite state.
Therefore, shorts can be detected only when the DO channel is on, and opens can be
detected only when the DO channel is off. When line fault detection is not enabled, and
the card is simplex, line fault tests do not run and line fault conditions are not reported.
Line Fault Detection
Value Detected
Short Circuit
< 5 Ω for > 3 seconds
Open Circuit
—
>25 KΩ for guaranteed open loop
detection
—
< 8 KΩ for guaranteed no open loop
detection
• When pulse testing is enabled, the LED on the output device may be slightly
illuminated.
Note
Line fault detection is not compatible with significant capacitive loading (cable + load > 30
nF) and must be disabled under these conditions.
Specifications
Table C-14: DO, 8-Channel, 24 VDC, High-Side Specifications (includes Series 2) 
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Output range
2 VDC to 60 VDC
Series 2: 24 VDC ±10%
Output rating
1.0 A continuous per channel (inrush 4.0 A for
<100 ms; 6.0 A for <20 ms); 3.0 A maximum per
card
Optional fuse (Simplex mode only)
2.0 A (inrush 5.0 A for <10 ms at 0.1% duty
cycle)
Interface Specifications
April 2021
D800001X312
164

--- Page 165 ---

Table C-14: DO, 8-Channel, 24 VDC, High-Side Specifications (includes Series 2)
(continued)
Item
Specification
Off-state leakage
1.2 mA maximum
LocalBus current (12 VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Series 2:
•
90 mA typical
•
150 mA maximum
Field circuit power, per card
3.0 A at 24 VDC (±10%)
Configurable channel types:
Discrete Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output stays in last state
submitted by the controller.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value.
Momentary Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output finishes current pulse.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Continuous Pulse Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output continues pulsing.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Mounting
Assigned slot of I/O carrier
Interface Specifications
D800001X312 
April 2021
165

--- Page 166 ---

Wiring Diagrams
Figure C-28: Wiring Diagram for Series 2 DO, 8-Channel, 24 VDC, High-Side in Simplex
Mode
+
+
-
-
Termination
Carrier
I/O Card
(Odd no.)
(Even no.)
System
Load
Common
connection
for 8
channels
24 VDC Bussed
field power connection
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
I/O Terminal block
Optional fuse
Interface Specifications
April 2021
D800001X312
166

--- Page 167 ---

Figure C-29: Wiring Diagram for Series 2 DO, 8-Channel, 24 VDC, High-Side in
Redundant Mode
+
-
Carrier
Redundant
termination
Primary
I/O card
Secondary
I/O card
(Even no.)
Common
connections
for 8 channels
System
+
-
-
+
(Odd no.)
Mode
Load
System
24 VDC Bussed
field power connection
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
Relay
Redundant discrete
terminal block
Related information
I/O Terminal Blocks
Redundant Discrete Terminal Block
C.1.17
DO, 8-Channel, 24 VDC, Isolated
The DeltaV system supports the DO, 8-channel, 24 VDC, Isolated card and the Series 2 DO,
8-channel, 24 VDC, Isolated card in Simplex mode.
Installation Notes
• The I/O terminal block is recommended to provide screw terminations for field wiring
for the DO, 8-channel, 24 VDC, Isolated card and the Series 2 DO, 8-channel, 24 VDC,
Isolated card in Simplex mode. Optional terminal blocks are the Fused I/O terminal
block and 16-pin mass termination block.
• If you use a mass termination block with the DO, 8-channel, 24 VDC, Isolated card,
refer to the termination block specifications for the output rating for each block. Those
Interface Specifications
D800001X312 
April 2021
167

--- Page 168 ---

specifications might be more restrictive than the specifications listed in the following
table.
• This card requires snubbers for inductive loads. Refer to the Related information
section of this topic for links to additional information.
Specifications
Table C-15: DO, 8-Channel, 24 VDC, Isolated Specifications
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system and from each other and factory tested
to 1500 VDC.
Output range
2 VDC to 60 VDC
Output rating
1.0 A (inrush 4.0 A for <100 ms; 6.0 A for <20
ms)
Off-state leakage
1.2 mA maximum
LocalBus current (12 VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Field circuit power, per card
None
Configurable channel types:
Discrete Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output stays in last state
submitted by the controller.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value.
Momentary Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output finishes current pulse.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Continuous Pulse Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output continues pulsing.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Optional fuse
2.0 A (inrush 5.0 A for <10 ms at 0.1% duty
cycle)
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
168

--- Page 169 ---

Wiring Diagram
Figure C-30: Wiring Diagram for DO, 8-Channel, 24 VDC, Isolated
+
-
+
-
Termination
I/O Card
Carrier
(Odd no.)
(Even no.)
System
DC
Power
supply
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
Optional fuse
I/O Terminal block
Solenoid
S
Related information
I/O Terminal Blocks
16-Pin Mass Termination Block
10-Pin Mass Termination Block
Implementing Bussed Field Power for Applications using DI and DO Cards
Sizing R-C Snubbers
C.1.18
DO, 8-Channel, 120 VAC/230 VAC, High-Side
The DeltaV system supports the DO, 8-channel, 120/230 VAC, High-Side card and the
Series 2 DO, 8-channel, 120/230 VAC, High-Side card in Simplex mode.
Installation Notes
The Fused I/O terminal block is recommended to provide screw terminations for field
wiring for the DO, 8-channel, 120/230 VAC, High-Side card and the Series 2 DO, 8-
channel, 120/230 VAC, High-Side card in Simplex mode. An optional terminal block is the
I/O terminal block.
Specifications
Table C-16: DO, 8-Channel, 120/230 VAC, High-Side Specifications 
Item
Specification
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC.
Interface Specifications
D800001X312 
April 2021
169

--- Page 170 ---

Table C-16: DO, 8-Channel, 120/230 VAC, High-Side Specifications (continued)
Item
Specification
Output range
20 VAC to 250 VAC
Output rating
•
1.0 A continuous per channel (inrush 5 A for
< 100 ms; 20 A for < 20 ms)
•
3.0 A maximum per card up to 5°C
•
2.0 A maximum per card up to 60°C
Series 2:
•
1.0 A continuous per channel (inrush 5 A
for < 100 ms; 20 A for < 20 ms)
•
3.0 A maximum per card
Optional fuse
2.0 A (inrush 5A for <10 ms at 0.1% duty cycle)
Off state leakage
2 mA maximum at 120 VAC, 4 mA maximum at
230 VAC
LocalBus current (12 VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Field circuit power, per card
3.0 A at 120 VAC or 230 VAC per I/O Interface
Configurable channel types:
Discrete Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output stays in last state
submitted by the controller.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value.
Momentary Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output finishes current pulse.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Continuous Pulse Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output continues pulsing.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
170

--- Page 171 ---

Wiring Diagram
Figure C-31: Wiring Diagram for DO, 8-Channel, 120 VAC/230 VAC, High-Side
+
-
Termination
Carrier
I/O Card
(Odd no.)
(Even no.)
System
Load
Common
connection
for 8 channels
L
N
120/230 VAC Bussed AC
field power connection
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
Optional fuse
I/O Terminal block
Related information
I/O Terminal Blocks
C.1.19
DO, 8-Channel, 120 VAC/230 VAC, Isolated
The DeltaV system supports the DO, 8-channel, 120/230 VAC, Isolated card and the Series
2 DO, 8-channel, 120/230 VAC, Isolated card in Simplex mode.
Installation Notes
The I/O terminal block is recommended to provide screw terminations for field wiring for
the DO, 8-channel, 120/230 VAC, Isolated card and the Series 2 DO, 8-channel, 120/230
VAC, Isolated card in Simplex mode. An optional terminal block is the Fused I/O block.
Table C-17: DO, 8-Channel, 120 VAC/230 VAC, Isolated Specifications
Item
Specifications
Number of channels
Eight
Isolation
Each channel is optically isolated from the
system at 250 VAC and from other channels at
250 VAC.
Output range
20 VAC to 250 VAC
Interface Specifications
D800001X312 
April 2021
171

--- Page 172 ---

Table C-17: DO, 8-Channel, 120 VAC/230 VAC, Isolated Specifications (continued)
Item
Specifications
Output rating
•
1.0 A continuous per channel (inrush 5 A for
<100 ms; 20 A for <20 ms)
•
3.0 A maximum per card up to 50°C (122°F)
•
2.0 A maximum per card up to 60°C (140°F)
Series 2:
•
1.0 A continuous per channel (inrush 5 A
for <100 ms; 20 A for <20 ms)
•
3.0 A maximum per card
Optional fuse
2.0 A (inrush 5A for <10 ms at 0.1% duty cycle)
Off state leakage
•
2 mA maximum at 120 VAC
•
4 mA maximum at 230 VAC
LocalBus current (12 VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Field circuit power, per card
None
Configurable channel types:
Discrete Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output stays in last state
submitted by the controller.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value.
Momentary Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output finishes current pulse.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Continuous Pulse Output
•
If FAIL_ACTION_MODE is Hold last value
(default): Output continues pulsing.
•
If FAIL_ACTION_MODE is Go to configured
failure action mode: Output is driven to the
configured faultstate value and the channel
is re-configured as a latched output.
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
172

--- Page 173 ---

Wiring Diagram
Figure C-32: Wiring Diagram for DO, 8-Channel, 120 VAC/230 VAC, Isolated
+
-
Termination
I/O Card
Carrier
(Odd no.)
(Even no.)
System
Load
L
N
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
Optional fuse
I/O Terminal block
120/230 VAC Power
Related information
I/O Terminal Blocks
C.1.20
DO, 32-Channel, 24 VDC, High-Side
The DeltaV system supports the DO, 32-Channel, 24 VDC, High Side card and the Series 2
DO, 32-Channel, 24 VDC, High Side card in simplex mode and the DO, 32-Channel, 24
VDC High-Side, Series 2 Plus card in redundant mode.
Installation Notes
• The DO Mass Connection Board (single) or the DO Mass Connection Solution (two) can
be used to provide an interface to the simplex DO, 32-Channel, 24 VDC, High-Side card
used with the 40-pin mass termination block.
• The Redundant 32-Channel Discrete Output Terminal Block and the Redundant
Discrete Output 40 Pin Mass Termination Block can be used with the redundant DO,
32-Channel, 24 VDC High-Side Series 2 Plus card.
• The DO Mass Connection Board (single) or the DO Mass Connection Solution (two) can
be used to provide an interface to the redundant DO, 32-Channel, 24 VDC, High-Side
Series 2 Plus card used with the Redundant Discrete Output 40 Pin Mass Termination
Block.
• The return connection for all 32 channels is the 24 VDC Field Power Ground. You must
supply an external wire to make this connection. However the connection is internally
made if the 40-pin mass termination block is used with the Series 2 DO, 32-Channel, 24
VDC, High Side card and no external wire is required. A resettable 1A fuse protects each
Interface Specifications
D800001X312 
April 2021
173

--- Page 174 ---

group of four channels (1-4, 5-8,...29-32) from a short circuit. Excessive current on any
single channel can trip the fuse and disable all four channels in the group. If the fuse
trips, turn off or disconnect the group of four channels and allow the fuse to cool and
reset.
Specifications
Table C-18: DO, 32-Channel, 24 VDC, High-Side (includes Series 2 and Series 2 Plus)
Item
Specification
Number of channels
32
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC
Output range
24 VDC (±10%)
Series 2: 24 VDC (-15%/+20%)
Output rating
100 mA per channel
Off-state leakage
0.1 mA maximum
LocalBus current (12VDC nominal), per card
•
100 mA typical
•
150 mA maximum
Field circuit power, per card
3.2 A at 24 VDC (±10%)
Series 2: 3.2 A at 24 VDC (-15%/+20%)
Mounting
Assigned slot of I/O carrier
Interface Specifications
April 2021
D800001X312
174

--- Page 175 ---

Wiring Diagram
Figure C-33: Wiring Diagram for DO, 32-Channel, 24 VDC, High-Side
+
-
Termination
Carrier
Common
connection for
32 channels
System
Load
24 VDC Bussed
field power connection
I/O Card
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
32-Channel terminal
block (the numbers
indicate the channel
assigments)
Interface Specifications
D800001X312 
April 2021
175

--- Page 176 ---

Figure C-34: Wiring diagram for redundant DO, 32-Channel, 24 VDC High-Side Series
2 Plus card
Carrier
Redundant
DO 40 pin
Mass Term
Block
Primary I/O card
Secondary I/O card
System
+
–
+
–
System
Common
connections
for 32 channels
Common
connections
for 32 channels
24 VDC Bussed
field power connection
Load
Related information
32-Channel Terminal Block
40-Pin Mass Termination Block
C.1.21
Fieldbus H1 and Series 2 H1
The DeltaV system supports the following types of H1 cards:
• Fieldbus H1
• Series 2 H1 (Simplex and Redundant modes)
Fieldbus is an all digital, serial, bi-directional communication protocol that interconnects
devices such as actuators, sensors, discrete devices, and controllers in the field. It is a Local
Area Network (LAN) for instruments that enables basic control and I/O to be moved to the
field device. Refer to the manual Fieldbus Installations in a DeltaV TMDistributed Control
System for more information.
Installation Notes
• The Fieldbus H1 terminal block is recommended to provide screw terminations for field
wiring for the H1 card.
• The Series 2 H1 terminal block is recommended to provide screw terminations for field
wiring for the Series 2 H1 card in Simplex mode.
Interface Specifications
April 2021
D800001X312
176

--- Page 177 ---

• The Redundant H1 terminal block is recommended to provide screw terminations for
field wiring for the Series 2 H1 card in Redundant mode.
• The "System Power Guidelines" section provides information on extending power to a
fieldbus segment.
Specifications
Item
Specification
Number of Ports
Two
Port Type
Foundation Fieldbus H1 - 31.25 Kbit/second
Isolation
Each port is isolated from the system and from
each other and factory tested to 1500 VDC.
LocalBus current (12VDC nominal), per card
400 mA typical, 600 mA maximum
Series 2:
•
200 mA typical
•
300 mA maximum
Field circuit power, per card
None
Fieldbus power (for Series 2 card)
9 to 32 VDC, 12 mA per port
Mounting
Assigned slot of I/O carrier
Wiring Diagrams
Figure C-35: Wiring Diagram for Fieldbus H1
System
1 +
+
2 +
4 -
3 -
System
5 +
6 +
8 -
7 -
I/O Card
Carrier
Termination
-
+
- +
-
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
Port
1
Port
2
Port 1
Port 2
Fieldbus H1
terminal block
Interface Specifications
D800001X312 
April 2021
177

--- Page 178 ---

Figure C-36: Wiring Diagram for Series 2 H1 in Simplex Mode
1, 7  (no connection)
2, 8  (no connection)
4 Port 1 (-)
3 Port 1 (+) 
5 Port 2 (+)
6 Port 2 (-)
I/O Card
Carrier
Termination
System
Port 2
H1
encoder/
decoder
Port 1
H1
encoder/
decoder
Port
1
Port
2
Port 1
Port 2
+ - + -
1
2
3
4
5
6
7
8
Series 2 H1
terminal block
Interface Specifications
April 2021
D800001X312
178

--- Page 179 ---

Figure C-37: Wiring Diagram for Series 2 H1 in Redundant Mode
Carrier
Primary
I/O card
Redundant
termination
System
2 , 8    (no connection)
1, 7    (no connection)
10, 16 (no connection)
9, 15   (no connection)
Port 1
4, 12 -
3, 11 +
+
+
-
-
Port 1
H1 encoder/decoder
Port 2
6, 14 -
5, 13 +
+
+
-
-
Port 2
H1 encoder/decoder
Secondary
I/O card
System
+
-
Port 1
H1 encoder/decoder
+
-
Port 2
H1 encoder/decoder
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
24 VDC Bussed
field power connection
Redundant H1
terminal block
Related information
Fieldbus H1 Terminal Block
Series 2 H1 Terminal Block
Redundant H1 Terminal Block
System Power Guidelines
C.1.22
Fieldbus H1 4-Port Series 2 Plus
The DeltaV system supports a simplex and redundant Fieldbus H1 4-Port Series 2 Plus
card, the Fieldbus H1 card, and the simplex and redundant Series 2 H1 card.
Installation notes
• The Simplex H1 4-Port Terminal Block is recommended to provide screw terminations
for field wiring for the Fieldbus H1 4-Port Series 2 Plus card in simplex mode.
• The Redundant H1 4-Port Terminal Block is recommended to provide screw
terminations for field wiring for the Series 2 H1 4 Port card in redundant mode.
Interface Specifications
D800001X312 
April 2021
179

--- Page 180 ---

• The "System Power Guidelines" section provides information on extending power to a
fieldbus segment.
Specifications
Table C-19: Fieldbus H1 4-Port Series 2 Plus card specifications
Item
Specification
Number of ports
Four
Port type
Foundation Fieldbus H1 (9-32 VDC) - 31.25 Kbit/
second
Isolation
Each port is isolated from the system and from
each other and factory tested to 1500 VDC.
LocalBus current (12VDC nominal), per card
300 mA typical
Fieldbus power
9 to 32 VDC, 12 mA per port
Mounting
Assigned slot of I/O carrier
Wiring Diagrams
Figure C-38: Wiring diagram for Fieldbus H1 4-Port Series 2 Plus in Simplex Mode
Carrier
IO card
System
Termination
1
Port 1
2
+
–
3
Port 2
4
+
–
5
Port 3
6
+
–
7
Port 4
8
+
–
Simplex H1 4-port 
terminal block
+
–
+
–
5 +
Port 3
6 –
+
–
+
–
7 +
Port 4
8 –
+
–
+
–
1 +
Port 1
2 –
+
–
+
–
3 +
Port 2
4 –
Port 3
H1 encoder/decoder
Port 4
H1 encoder/decoder
Port 1
H1 encoder/decoder
24V bussed 
field power connection
Port 2
H1 encoder/decoder
Interface Specifications
April 2021
D800001X312
180

--- Page 181 ---

Figure C-39: Wiring diagram for Fieldbus H1 4-Port Series 2 Plus in Redundant Mode
Carrier
Primary IO card
System
System
Secondary IO card
Redundant termination
1
Port 1
2
+
–
3
Port 2
4
+
–
5
Port 3
6
+
–
7
Port 4
8
+
–
9
Port 1
10
+
–
11
Port 2
12
+
–
13
Port 3
14
+
–
15
Port 4
16
+
–
Redundant H1 4 port
terminal block
+
–
+
–
5, 13 +
Port 3
6, 14 +
+
–
+
–
7, 15 +
Port 4
8, 16 +
+
–
+
–
1,
9 +
Port 1
2, 10 –
+
–
+
–
3, 11 +
Port 2
4, 12 –
+
–
+
–
+
–
+
–
Port 3
H1 encoder/decoder
Port 4
H1 encoder/decoder
Port 1
H1 encoder/decoder
24V bussed 
field power connection
Port 2
H1 encoder/decoder
Port 3
H1 encoder/decoder
Port 4
H1 encoder/decoder
Port 1
H1 encoder/decoder
Port 2
H1 encoder/decoder
C.1.23
Isolated Input
The DeltaV system supports the Series 2 Isolated Input card in Simplex mode.
Interface Specifications
D800001X312 
April 2021
181

--- Page 182 ---

The Isolated Input card supports thermocouple, millivolt, RTD, ohm, and voltage input
ranges.
The Isolated Input card does not support overrange and underrange values.
Installation Notes
The Isolated Input card uses the Isolated Input Terminal Block to provide terminations for
wiring.
Specifications
Table C-20: Isolated Input Card Specifications
Item
Specification
Number of channels
Four
Isolation CAN/CSA-C22.2 No.1010.1 or CAN/
CSA-C22.2 No.61010.1
•
Installation Cat II, Pollution degree 2
•
Channel to system - 600 VAC double
insulation. Each channel is optically isolated
from the system and factory tested to 5000
VDC.
•
Channel to channel - 600 VAC basic
insulation. Each channel is optically isolated
from each other and factory tested to 3100
VDC.1
ADC resolution
16 bit
-3dB filter frequency
2.7 Hz
DC/50/60 Hz common-mode rejection
120 dB
Input impedance
10 MΩ
Thermocouple sensor types
B, E, J, K, N, R, S, T, uncharacterized
RTD Sensor Types
PT100, PT200, Ni120, Cu10, resistance, user-
defined
mV and V ranges
Refer to Table C-24 and Table C-27.
Input type mix
Independently configurable
Ambient temperature
-40 to 70 °C
Calibration
None required
Mounting
Assigned slot of I/O carrier
LocalBus power rating
12 VDC, 350 mA, no field power required
1
Warning: When hazardous live voltages are present on a channel, adjacent channel wiring must
be inaccessible.
Table C-21: Isolated Input Card, Thermocouple and Millivolt Input Specifications
Item
Specification
Linearization error
±0.003% full scale
Cold-junction compensation accuracy
±1.0 °C
Interface Specifications
April 2021
D800001X312
182

--- Page 183 ---

Table C-21: Isolated Input Card, Thermocouple and Millivolt Input Specifications
(continued)
Item
Specification
Cold-junction compensation types
Off, local, remote
Cold-junction compensation range
-40 to 85 °C
Temperature scale
ITS90
Open-circuit detection (thermocouple only)
0.4 µA DC
Detection time
1 second
In the 25°C Reference Accuracy column in the following table, total error is made up of
reading accuracy, CJC accuracy, and sensor accuracy.
Table C-22: Isolated Input Card Thermocouple Input Range Specifications
Sensor Types
25 °C
Reference
Accuracy
Temperature
Drift
Nominal
Resolution
Full Scale
Operating
Range
B
±1.2 °C
±0.116 °C/°C
0.09 °C
250 to 1810 °C
500 to 1810 °C
E
±0.5 °C
±0.004 °C/°C
0.05 °C
-200 to
1000 °C
-200 to
1000 °C
J
±0.6 °C
±0.005 °C/°C
0.06 °C
-210 to
1200 °C
-190 to
1200 °C
K
±0.5 °C
±0.013 °C/°C
0.05 °C
-270 to
1372 °C
-140 to
1372 °C
N
±1.0 °C
±0.015 °C/°C
0.05 °C
-270 to
1300 °C
-190 to
1300 °C
R
±1.7 °C
±0.083 °C/°C
0.06 °C
-50 to 1768 °C
0 to 1768 °C
S
±1.8 °C
±0.095 °C/°C
0.08 °C
-50 to 1768 °C
0 to 1768 °C
T
±0.7 °C
±0.025 °C/°C
0.04 °C
-270 to 400 °C
-200 to 400 °C
Uncharacteriz
ed; no
linearization or
CJC
±0.05 mV
±0.0003
mV/°C
0.0031 mV
-100 to 100
mV
-100 to 100
mV
Table C-23: Isolated Input Card Millivolt Input Range Specifications
Sensor Type
Input Ranges
25 °C Reference
Accuracy
Temperature
Drift
Maximum
Resolution
20 mV
±20 mV
±0.02 mV
±0.001 mV/°C
0.0008 mV
50 mV
±50 mV
±0.03 mV
±0.0005 mV/°C
0.0017 mV
100 mV
±100 mV
±0.05 mV
±0.0003 mV/°C
0.0031 mV
Interface Specifications
D800001X312 
April 2021
183

--- Page 184 ---

Table C-24: Isolated Input Card, RTD, ohms Input Specifications
Item
Specification
Measurement configurations
2, 3, and 4 wire
Excitation current
100 µA DC
Temperature scale
ITS90
Open sensor detection time
1 second
Short circuit detection time
1 second
Pt 100 and Pt 200 alpha
0.00385
Table C-25: Isolated Input Card, RTD, ohms Input Range Specifications
Sensor Type
25 °C Reference
Accuracy
Temperature
Drift
Resolution
Sensor Input
Range
Pt100
±0.5 °C
±0.018 °C/°C
0.05 °C
-200 to 850 °C
Pt200
±0.5 °C
±0.012 °C/°C
0.05 °C
-200 to 850 °C
Ni120
±0.2 °C
±0.006 °C/°C
0.02 °C
-70 to 300 °C
Cu10
±2.0 °C
±0.076 °C/°C
0.23 °C
-30 to 140 °C
Resistance
±0.5 Ω
±0.018 Ω/°C
0.02 Ω
1 to 1000 Ω
User defined
±0.4 Ω
±0.009 Ω/°C
∼0.05 Ω
0 to 1000 Ω
Table C-26: Isolated Input Card, Voltage Input Range Specifications
Sensor Type
Sensor Range
25 °C Reference
Accuracy
Temperature
Drift
Maximum
Resolution
0 - 5 V
0 - 5 V
±0.005 V
±0.0002 V/°C
0.00009 V
0 - 10 V
0 - 10 V
±0.010 V
±0.0004 V/°C
0.00016 V
1 - 5 V
1 - 5 V
±0.005 V
±0.0002 V/°C
0.00009 V
1 V
±1 V
±0.0025 V
±0.0002 V/°C
0.00015 V
5 V
±5 V
±0.005 V
±0.0002 V/°C
0.00017 V
10 V
±10 V
±0.010 V
±0.0004 V/°C
0.0003 V
Interface Specifications
April 2021
D800001X312
184

--- Page 185 ---

Wiring Diagram
Figure C-40: Wiring Diagram for Series 2 Isolated Input
Termination
Carrier
I/O Card
Excitation
current
1, 5, 9, 13
2, 6, 10, 14
3, 7, 11, 15
4, 8, 12, 16
+
-
4
wire
3
wire
2
wire
A/D
Conv.
To
system
TC
mV
V
+
-
Sensor -
Sensor +
4-wire sensor excitation
Wire compensation
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
Isolated input
terminal block
Related information
Isolated Input Terminal Block
C.1.24
Multifunction
The DeltaV system supports the Multifunction card and the Series 2 Multifunction card in
Simplex mode.
The Multifunction card uses the 32-channel terminal block to provide terminations for
wiring. The following table lists the cable pin out connections for the Multifunction card.
Table C-27: 32-Channel Terminal Block used with Multifunction Card
Terminal on
Termination Block
Channel
Nomenclature
Terminal on
Termination Block
Channel
Nomenclature
Terminal 1
Reserved for future use
Terminal 17
DI or PIN (pulse input),
Ch1+
Interface Specifications
D800001X312 
April 2021
185

--- Page 186 ---

Table C-27: 32-Channel Terminal Block used with Multifunction Card (continued)
Terminal on
Termination Block
Channel
Nomenclature
Terminal on
Termination Block
Channel
Nomenclature
Terminal 2
Reserved for future use
Terminal 18
DI or PIN (pulse input),
Ch1-
Terminal 3
Reserved for future use
Terminal 19
Reserved for future use
Terminal 4
Reserved for future use
Terminal 20
Reserved for future use
Terminal 5
Reserved for future use
Terminal 21
DI or PIN (pulse input),
Ch2+
Terminal 6
Reserved for future use
Terminal 22
DI or PIN (pulse input),
Ch2-
Terminal 7
Reserved for future use
Terminal 23
Reserved for future use
Terminal 8
Reserved for future use
Terminal 24
Reserved for future use
Terminal 9
Reserved for future use
Terminal 25
DI or PIN (pulse input),
Ch3+
Terminal 10
Reserved for future use
Terminal 26
DI or PIN (pulse input),
Ch3-
Terminal 11
+24 VDC
Terminal 27
Reserved for future use
Terminal 12
- 24 VDC (return)
Terminal 28
Reserved for future use
Terminal 13
Reserved for future use
Terminal 29
DI or PIN (pulse input),
Ch4+
Terminal 14
Reserved for future use
Terminal 30
DI or PIN (pulse input),
Ch4-
Terminal 15
+24 VDC
Terminal 31
Reserved for future use
Terminal 16
- 24 VDC (return)
Terminal 32
Reserved for future use
The Multifunction I/O Card discrete input channel has a switching hysteresis of 80 mV.
Noise signals above this amplitude are detected by the input channel.
Specifications
Table C-28: Multifunction Specifications
Item
Specification
Number of channels
Four
Isolation
Each channel is optically isolated from the
system and from each other and factory tested
to 1500 VDC.
Detection level for ON
4.8 VDC (minimum)
Detection level for OFF
1.0 VDC (maximum)
Input impedance
3 to 25 mA at 5 to 24 VDC
Input accuracy
0.1% reading (over 10 Hz - 50 kHz signals)1
Interface Specifications
April 2021
D800001X312
186

--- Page 187 ---

Table C-28: Multifunction Specifications (continued)
Item
Specification
Input frequency
•
Sine wave - 10 Hz to 50 kHz
•
Square wave - 0.1 Hz to 50kHz
Resolution
1 pulse
Minimum pulse width
10 µS
Maximum input voltage
26.4 VDC
Resolution counter
32 bits
LocalBus current
250 mA maximum
Series 2: 150 mA maximum
Mounting
Assigned slot of I/O carrier
1
For a pulse input channel, filtering may be required to meet the accuracy specification.
Wiring Diagram
Figure C-41: Wiring Diagram for Multifunction 24 VDC
+
-
I/O Card
Termination
Carrier
System
750 Ω
24
VDC
Source
+
-
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
Use 32-channel
terminal block (refer
to table for pin out
connections and
channel nomenclature)
Related information
32-Channel Terminal Block
C.1.25
Profibus DP
The DeltaV system supports the Profibus DP card, the Series 2 Profibus DP card in Simplex
mode, and the Series 2 Plus Profibus DP card in Simplex and Redundant modes.
Interface Specifications
D800001X312 
April 2021
187

--- Page 188 ---

Profibus is an all digital, serial, bi-directional communication protocol that interconnects
devices in the field. For information on installing Profibus devices, refer to the Profibus
web site at www.profibus.com.
Installation Notes
• The Profibus terminal block is recommended to provide screw terminations for field
wiring for the Profibus DP card and Series 2 Profibus DP card in Simplex mode.
• The Redundant Profibus DP terminal block is recommended to provide screw
terminations for field wiring for the Series 2 Plus Profibus DP card in Redundant mode.
Do not plug a simplex Profibus DP or Series 2 Profibus DP card into a Redundant
Profibus DP terminal block. For simplex or redundant applications, when the
termination is in the OUT position, pins 1 and 3 and 4 and 6 can be used. When the
termination is in the IN position only pins 1 and 3 can be used.
Item
Specification
Number of Ports
One
Port Type
Profibus DP
LocalBus current (12 VDC nominal), per card
400 mA typical, 600 mA maximum
Field circuit power, per card
None
Mounting
Assigned slot of I/O carrier.
Wiring Diagram
The following figure shows a wiring diagram for the Series 2 Plus Profibus DP card. For a
redundant card, the wiring shown in the I/O Card portion of the image is replicated.
Interface Specifications
April 2021
D800001X312
188

--- Page 189 ---

Figure C-42: Wiring Diagram for Series 2 Plus Profibus DP Card in Simplex or
Redundant Mode
I/O Card 
Carrier
Termination
1 A1
System
T in
T out
Terminator
3 B1
4 A2
6 B2
7 CTS
2, 5, 8 S
1
2
3
4
5
6
7
8
A1
A2
B1
B2 CTS S
S
S
Profibus DP or redundant Profibus DP
terminal block
(refer to terminal
block specifications for
terminator positions)
Wiring in the area labeled
I/O Card is duplicated 
for redundancy
Related information
Profibus DP Terminal Block
Redundant Profibus DP Terminal Block
C.1.26
RTD, ohms
The DeltaV system supports the RTD, ohms card and the Series 2 RTD, ohms card in
Simplex mode.
Installation Notes
The RTD, ohms terminal block is recommended to provide screw terminations for field
wiring for the RTD, ohms card.
Table C-29: RTD, ohms Specifications
Item
Specification
Number of channels
Eight
Sensor Types
2-wire, 3-wire, or 4-wire: Resistance, Pt100,
Pt200, Pt500, Ni120, Cu10, user defined
Full scale signal range
Selectable based on sensor. Refer to Table C-30.
LocalBus Power Rating
12 VDC, 160 mA
Interface Specifications
D800001X312 
April 2021
189

--- Page 190 ---

Table C-29: RTD, ohms Specifications (continued)
Item
Specification
Ambient Temperature
0 to 60°C
Series 2: -40 to 70°C
Accuracy over temperature range
Refer to Table C-30.
Resolution (Varies with sensor type. Refer to
Table C-32).
16 bits conversion
Repeatability
0.05% of span
DC/50/60/Hz Common Mode Rejection
120 dB
Calibration
None required
Mounting
Assigned slot of I/O carrier
The following table shows the full scale, operating range, reference accuracy, temperature
drift, and resolution for the RTD, ohms sensor types
Table C-30: RTD, ohms Sensor Type Specifications
Sensor Type
Full Scale
Operating
Range
25° Reference
Accuracy
Temperature
Drift
Resolution
Resistance
0 to 2,000 Ω
0 to 2,000 Ω
±6.2 Ω
±0.112 Ω/°C
∼0.02 Ω
Pt100
-200 to 850°C
-200 to 850°C
±0.5°C
±0.018°C/°C
∼0.05°C
Pt200
-200 to 850°C
-200 to 850°C
±0.5°C
±0.012°C/°C
∼0.05°C
Pt500
-200 to 850°C
-200 to 850°C
±3.5°C
±0.063°C/°C
∼0.18°C
Ni120
-70 to 300°C
-70 to 300°C
±0.2°C
±0.006°C/°C
∼0.02°C
Cu10
-30 to 140°C
-30 to 140°C
±2.0°C
±0.157°C/°C
∼0.23°C
Resistance/
user defined1
0 to 1000 Ω
0 to 1000 Ω
±0.4 Ω
±0.009 Ω/°C
∼0.05 Ω
1
The Callendar-Van Dusen linearization equation can be used with user defined Pt RTDs. Refer to
Recommended I/O Practices in DeltaV Books online for usage information.
Interface Specifications
April 2021
D800001X312
190

--- Page 191 ---

Wiring Diagram
Figure C-43: Wiring Diagram for Series 1 RTD, ohms
Termination
Carrier
I/O Card
Excitation
current
Sensor
excitation
Sensor
excitation
Sensor +
+ Sensor
Circuit
common
Circuit
common
Sensor -
- Sensor
A/D
Conv.
4
wire
3
wire
2
wire
System
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
RTD, ohms
Terminal block
Interface Specifications
D800001X312 
April 2021
191

--- Page 192 ---

Figure C-44: Wiring Diagram for Series 2 RTD, ohms
Termination
Carrier
I/O Card
Excitation
current
Excitation
current
Sensor
excitation
Sensor
excitation
Sensor +
+ Sensor
Circuit
common
Circuit
common
Sensor -
- Sensor
A/D
Conv.
4
wire
3
wire
2
wire
System
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
RTD, ohms
Terminal block
Related information
RTD, ohms Terminal Block
C.1.27
Sequence of Events
The DeltaV system supports the Sequence of Events card and the Series 2 Sequence of
Events card in Simplex mode.
Installation Notes
The 32-channel terminal block is recommended to provide screw terminations for field
wiring for the Sequence of Events card and the Series 2 Sequence of Events card in Simplex
mode. The 40-pin mass termination block also can be used. The following table lists the
cable pin out connections for the Sequence of Events card
Table C-31: 32-Channel Terminal Block used with Sequence of Events 
Terminal
Channel
Nomenclature
Terminal
Channel
Nomenclature
Terminal 1
Channel 1+
Terminal 17
Channel 9+
Interface Specifications
April 2021
D800001X312
192

--- Page 193 ---

Table C-31: 32-Channel Terminal Block used with Sequence of Events (continued)
Terminal
Channel
Nomenclature
Terminal
Channel
Nomenclature
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
Terminal 16
Channel 8-
Terminal 32
Channel 16-
A Network Time Server is required for a Sequence of Events card.
Specifications
Table C-32: Sequence of Events Specifications
Item
Specification
Number of channels
16; each channel can be configured for SOE or DI
operation.
Scan rate
0.25 msec for all 16 channels
Time stamp accuracy (for SOE channels only)
0.25 msec on a card; 1 msec in a controller.
Accuracy with reference to system clock time
after a 4 msec debounce filter has been applied.
Isolation
Each channel is optically isolated from the
system and factory tested to 1500 VDC.
Detection level for ON
> 2 mA
Detection level for OFF
< 0.25 mA
Impedance
5K Ω
Interface Specifications
D800001X312 
April 2021
193

--- Page 194 ---

Table C-32: Sequence of Events Specifications (continued)
Item
Specification
LocalBus current (12VDC nominal), per card
•
50 mA typical
•
75 mA maximum
Series 2
•
75 mA typical
•
100 mA maximum
Field circuit power, per card
75 mA at 24 VDC (±10%)
Series 2: 75 mA at 24 VDC (±20%)
Mounting
Assigned slot of I/O carrier
Wiring Diagram
Figure C-45: Wiring Diagram for Sequence of Events
Common
connection
for 16 channels
+
+
-
-
Carrier
I/O card
Termination
(Odd no.)
(Even no.)
System
24 VDC Bussed
field power connection
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
Ch
2
+
-
+
-
Ch
4
Ch
6
Ch
8
Ch
10
Ch
12
Ch
14
Ch
16
Ch
1
Ch
3
Ch
5
Ch
7
Ch
9
Ch
11
Ch
13
Ch
15
32-Channel
terminal block
Related information
32-Channel Terminal Block
40-Pin Mass Termination Block
Setting Up a Network Time Server
Interface Specifications
April 2021
D800001X312
194

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