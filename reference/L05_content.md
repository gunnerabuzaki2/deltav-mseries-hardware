--- Page 39 ---

1. Check the key settings on the corresponding Series 2 cards and set the keys on the
terminal block to match. Refer to “I/O Interface Keying” for information on key
settings.
2. Locate the assigned slot location on the I/O interface carrier. Remember that the
lower slot number must be odd and the upper slot number must be the next higher
even number. Place the tabs on the back of the I/O terminal block through the slots
on the carrier and push the I/O terminal block up to lock it into place.
3. Connect the field wiring for the redundant I/O terminal blocks as shown in the
Series 2 card wiring diagrams and redundant terminal block figures in the "Interface
Specifications" section.
Related information
I/O Interface Keying
Interface Specifications
DeltaV Series 2 I/O
Installing a Redundant I/O Card
A redundant I/O card consists of two Series 2 cards installed in a redundant terminal block.
Read “DeltaV Series 2 I/O” before installing a redundant I/O card.
1. Locate the assigned slots on the I/O interface carrier.
2. Align the connectors on the I/O card with the connectors on the I/O carrier and the
redundant I/O terminal block and push to attach.
3. Tighten the mounting screws.
Related information
DeltaV Series 2 I/O
2.5.9
Installing the DeltaV Controller
For simplex controller systems, the controller mounts on the right slot of the 2-wide
power/controller carrier.
Note
Refer to the DeltaV Power and Grounding manual for information on proper configuration
of an uninterruptible power supply (UPS) to back up the controller power during short-
term power outages. The UPS allows the controller to continue operating and to maintain
current process data even when AC main power is down. Refer to the UPS manufacturer’s
specifications for all other UPS information.
1. Align the connectors on the back of the controller with the connectors on the right
slot of the 2-wide power/controller carrier and push to attach.
2. Tighten the mounting screw.
Installing Your DeltaV System
D800001X312 
April 2021
39

--- Page 40 ---

Figure 2-13: Controller Installation
Related information
Controller Specifications
Controller Redundancy
2.5.10
Installing the DeltaV System Power Supply
The system power supply takes line power or power from a bulk power supply and
converts it to 12 VDC power to drive the controller and I/O cards. The system power
supply mounts on either slot of the 2-wide power/controller carrier. For mounting on a 4-
wide power/controller carrier refer to Appendix M DeltaV Vertical Carriers.
This section describes the connections for a simplex system power supply. Refer to
Appendix E System Power Supply Specifications for system power supply specifications
and for details on redundancy.
Refer to the figures following the steps for more information.
1. Connect the input supply wires to the input power connection on the top of the
system power supply. Figure 2-15 shows input supply wiring for the system power
supply (AC/DC). Figure 2-14 shows the input supply wiring for the system power
supply (Dual DC/DC). If you have secondary system power supplies, connect the
input supply drops to each system power supply as shown in Appendix E System
Power Supply Specifications.
Installing Your DeltaV System
April 2021
D800001X312
40

--- Page 41 ---

Warning
Always remove input power to the supply before connecting or disconnecting the
input power connection. The connector should not interrupt current flow and could
be damaged if actuated under a load condition. Refer to Appendix J Power
Guidelines for more information.
Figure 2-14: Simplex Wiring Diagram for System Power Supply (AC/DC)
Top View
Carrier
Line
Neutral
Protective Earth
From AC
Power
Distribution
Terminal
Block
Terminal
Strip
To DC Ground Bus
in Enclosure
AC-to-DC
System
Power
Supply
Installing Your DeltaV System
D800001X312 
April 2021
41

--- Page 42 ---

Figure 2-15: Redundant Wiring Diagram for System Power Supply (AC/DC)
Top View
Carrier
L
N
G
From AC
Power
Distribution
Terminal
Block
Terminal Strip
Notes:
Use separate terminal blocks as shown. Then, for optimum power redundancy, connect each system
power supply to separate power disconnect panels, powered by separate isolation transformers.
Use the left-hand terminal screw only. Only one ground wire is necessary because the return side of
both DC power supplies is internally connected to the ground terminal of either terminal strip.
L
N
G
From AC
Power
Distribution
1
1
2
1
2
Primary AC to
DC System
Power Supply
Secondary AC
to DC System
Power Supply
Neutral
Protective Earth
Line
DC
Return
Reference
Ground
To DC Gnd Bus
in enclosure
Note
If you are using a Two-Wide Power Carrier and redundant AC-to-DC power supplies,
connect only one of the power supplies to protective earth.
Refer to Appendix J Power Guidelines for power supply and grounding overviews.
Installing Your DeltaV System
April 2021
D800001X312
42

--- Page 43 ---

Figure 2-16: Simplex Wiring Diagram for System Power Supply (Dual DC/DC)
Top View
Carrier
Terminal Strip
Notes:
1
Dual DC/DC
System Power
Supply
From DC/DC
Power Supply 
or AC/DC Bulk 
Power Supply
12 VDC
Return
12 VDC
1
A fuse block and fuse are optional. If you are providing DC power to several DC/DC
passthrough system power supplies by the same bulk power supply, fuse the line to 
each supply.
.
Always use pre-formed metal shorting bars to ensure a good connection. Do not use individual
jumper wires.
Fuse
Block
12 VDC
12 VDC Return
(Ground)
DIN rail mounted
DC Power Bus (+)
2
2
DIN rail mounted
DC Return Bus (−)
Note
Do not connect the ground terminal on the power carrier when powering the dual
DC/DC system power supply from a 12 VDC supply.
2. Install alarm contact wiring as shown in the following figure.
Figure 2-17: System Power Supply Alarm Contact Wiring (Unpowered
Condition)
Example:
Alarm relay contact
normally open
(shelf condition)
DI 24 VDC
isolated card
First system
power supply
Optional
additional
system
power supplies
+
+
24 VDC external
power supply
Installing Your DeltaV System
D800001X312 
April 2021
43