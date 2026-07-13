--- Page 495 ---

M
DeltaV Vertical Carriers
There are two types of DeltaV vertical carriers: VerticalPLUS and Legacy Vertical.
VerticalPLUS carriers can be used for DeltaV basic process control systems as well as for
DeltaV Safety Instrumented Systems (SIS). Legacy Vertical carriers cannot be used for
DeltaV SIS. The next section describes the VerticaPLUS carriers. Refer to the related topics
for information on Legacy Vertical carriers.
For both vertically and horizontally mounted systems, the LocalBus, including all cabling,
cannot be longer than 6.5 m (21.3 ft).
Note
In this Appendix, references to left and right, top and bottom, assume that you are facing
the equipment.
Important
The vertical carriers are mounted properly when the lettering is in the upright position.
Important
Vibration will cause vertical carriers to slip down on the DIN rail and disconnect from the
carrier above it. It is highly recommended that you install a stop on the DIN rail to prevent
the carriers from slipping.
Related information
Legacy Vertical Carriers
DeltaV System Equipment
Installing the DIN Rail Stop
M.1
VerticalPLUS Carriers
DeltaV VerticalPLUS carriers can be used for DeltaV Safety Instrumented Systems (SIS) and
DeltaV basic process control systems. The Installing Your DeltaV SIS™ Process Safety System
Hardware manual provides instructions for installing SLS 1508 hardware. VerticalPLUS
carriers mount on standard 35 mm. (1.38 in.) T-type DIN rails.
There are several types of VerticalPLUS carriers:
• 4-wide power/controller carrier
• 4-wide SISNet Repeater carrier
• 4-wide power carrier
• left and right 8-wide I/O interface carriers
• left and right 1-wide carrier extenders
Related information
DIN Rail Recommendations
DeltaV Vertical Carriers
D800001X312 
April 2021
495

--- Page 496 ---

M.2
4-Wide VerticalPLUS Power/Controller Carriers
The 4-wide VerticalPLUS power/controller carrier holds up to two controllers (primary and
secondary) and two system power supplies. The 4-wide VerticalPLUS power/controller
carriers install on the top left of a vertical system. The 96 pin connector on the bottom of
the carrier connects to the top of a left, 8-wide VerticalPLUS I/O interface carrier.
Figure M-1: 4-Wide VerticalPLUS Power/Controller Carrier
M.3
4-Wide VerticalPLUS SISNet Repeater Carriers
The 4-wide VerticalPLUS SISNet Repeater carrier holds a primary and secondary SISNet
Repeater. The 4-wide VerticalPLUS SISNet Repeater carrier installs on the top right of a
vertical system. The 96 pin connector on the bottom of the carrier connects to the top of a
right, 8-wide VerticalPLUS I/O interface carrier. The VerticalPLUS SISNet Repeater carrier
contains D-shell connectors for extending power to other carriers and BNC connectors for
extending local peer bus signals or terminating the local peer bus. Refer to the Installing
Your DeltaV SIS™ Process Safety System Hardware manual for information on how SISNet
Repeaters are used in DeltaV SLS 1508 systems and for information on the local peer bus.
DeltaV Vertical Carriers
April 2021
D800001X312
496

--- Page 497 ---

Figure M-2: 4-Wide VerticalPLUS SISNet Repeater Carrier
M.4
4-Wide VerticalPLUS Power Carriers
The 4-wide VerticalPLUS power carriers hold redundant power supplies if additional
system power is required. This carrier can be installed on the DIN rail anywhere in the
cabinet. Connect the DC reference ground when using a legacy 24 VDC bulk power supply
only. The DC reference ground connection is not required for a legacy 12 VDC bulk power
supply.
Figure M-3: 4-Wide VerticalPLUS Power Carrier
+
-
-
12 VDC output
DC reference
ground for 24
VDC power only
+
+
-
-
12 VDC output
DC reference
ground for 24 VDC power 
only
+
M.5
8-Wide VerticalPLUS I/O Interface Carriers
8-wide VerticalPLUS I/O interface carriers hold I/O cards and Logic Solvers and contain
connectors for inserting system and field power. For carrier numbering and card
addressing positions, refer to Figure M-5. The following figure shows the 8-wide
VerticalPLUS I/O interface carriers.
DeltaV Vertical Carriers
D800001X312 
April 2021
497

--- Page 498 ---

Figure M-4: Left and Right 8-Wide VerticalPLUS I/O Carriers
Latch Acess
Hole
Latch Acess
Hole
Latch Acess
Hole
Latch Acess
Hole
DeltaV Vertical Carriers
April 2021
D800001X312
498

--- Page 499 ---

Figure M-5: Carrier Numbering and Addressing Positions
7
49-56
Carrier #8
Addressing
Positions
57-64
M.6
1-Wide VerticalPLUS Carrier Extenders and
Cables
The 1-wide VerticalPLUS carrier extenders and cables are used to extend power and local
peer bus signals from a left to a right 8-wide VerticalPLUS carrier and from a right to a left
8-wide VerticalPLUS carrier.
There are two types of 1-wide VerticalPLUS carrier extenders and cables:
DeltaV Vertical Carriers
D800001X312 
April 2021
499

--- Page 500 ---

• Left 1-wide carrier extender
• Right 1-wide carrier extender
• D-shell connector cable to extend power and LocalBus signals
• BNC connector cable to extend local peer bus signals for SIS systems
Note
For SIS systems, the local peer bus must be terminated by 120 ohm BNC terminators at
either the 1-wide carrier extender connected to the last 8-wide carrier or at a 4-wide
SISNet Repeater carrier. The termination location depends upon the carrier configuration.
Refer to the Installing Your DeltaV SIS™ Process Safety System Hardware manual for
information on terminating SLS 1508 systems.
Left 1-Wide VerticalPLUS Carrier Extender
The Left 1-wide VerticalPLUS carrier extender connects to the bottom of a left 8-wide
VerticalPLUS carrier or to the top of a right 8-wide VerticalPLUS carrier.
Right 1-Wide VerticalPLUS Carrier Extender
The Right 1-wide VerticalPLUS carrier extender connects to the bottom of a right 8-wide
VerticalPLUS carrier or to the top of a left 8-wide VerticalPLUS carrier.
Figure M-6: Left and Right 1-Wide VerticalPLUS Carrier Extenders
Cables for VerticalPLUS Systems
The 25 pin D-shell connector cable connects to the D-shell connectors labeled A on the 1-
wide VerticalPLUS carrier extenders to extend power. Cable is available in the following
lengths.
• 0.4 meters (1.3 feet)
• 0.8 meters (2.6 feet)
• 1.1 meters (3.6 feet)
• 1.5 meters (4.9 feet)
• 1.9 meters (6.2 feet)
The BNC connector cable connects black-to-black and white-to-white between 1-wide
VerticalPLUS carrier extenders to extend the local peer bus for SIS systems. Refer to the
Installing Your DeltaV SIS™ Process Safety System Hardware manual for information on the
local peer bus.
DeltaV Vertical Carriers
April 2021
D800001X312
500

--- Page 501 ---

Related information
1-Wide VerticalPLUS Carrier Extenders
M.7
Installing VerticalPLUS Carriers
Carefully plan the location of all carriers on the DIN rail before installing the carriers. You
will install a DIN rail stop first to prevent the carriers from slipping down on the DIN rail and
then install the carriers after the stop is in place.
M.7.1
Installing the DIN Rail Stop
Vibration will cause the vertical carriers to slip down on the DIN rail and disconnect from
the carrier above it. Before installing the carriers, install a DIN rail stop to prevent the
carriers from slipping. The stop should be at the lowest position on the DIN rail. The DIN
rail stop (KJ4010X1-BS1) can be purchased from Emerson.
Figure M-7: DIN Rail Stop
1. Be sure the arrow on the front of the stop is pointing upward towards the device. If
the arrow is pointing downwards away from the device, the screws on the DIN rail
stop could damage pins extending from the device.
2. First hook the end with the deeper notch over the DIN rail and then hook the end
with the more shallow notch over the other side of the DIN rail.
3. Screw the stop onto the DIN rail being careful not to overtighten the screws. Be sure
that both sides of the DIN rail stop are properly secured. The torque limits are
specified on the DIN rail stop.
DeltaV Vertical Carriers
D800001X312 
April 2021
501

--- Page 502 ---

M.7.2
Installing and Removing the Carriers
After installing the DIN rail stop, install the carriers. Latches on the back of the carriers are
used to snap the carriers into place on the DIN rail. Typically, a 1-wide VerticalPLUS carrier
extender is installed after the DIN rail stop is installed.
Installing VerticalPLUS Carriers
1. Position the carrier on the DIN rail and push it against the DIN rail to snap it into
place.
2. Slide the carrier down on the DIN rail until it meets the DIN rail stop.
3. Snap the next carrier onto the DIN rail following the instructions in Step 1.
4. Connect each carrier to the adjacent carrier by sliding together the pins on the ends
of the carriers.
5. Connect ground wiring as shown in the following figure. Connect only one ground
wire for each group of carriers on a DIN rail.
DeltaV Vertical Carriers
April 2021
D800001X312
502

--- Page 503 ---

Figure M-8: Ground Wiring for System Power Supplies
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
Chassis
Ground
Enclosure PE Ground Lug
Enclosure Door
Adjacent Enclosure
Isolated
Bus
To DIG
DC Ground
Field
Power
To DIG
Primary
AC
Secondary
AC
Field
Power
DeltaV Vertical Carriers
D800001X312 
April 2021
503

--- Page 504 ---

Removing VerticalPLUS Carriers
1. Use the largest flat blade screw driver that will fit through the latch access holes on
the carrier.
2. Turn the latch cam approximately one quarter turn to the right as indicated on the
graphic printed on the carrier top.
M.7.3
Extending LocalBus Power to Other Carriers
When VerticalPLUS carriers are installed on separate DIN rails, carrier extender cables are
used to extend LocalBus power. Extender cables connect to 1-wide VerticalPLUS carrier
extenders. A standard installation uses one extender cable; however, dual extender cables
can also be used.
The following figure shows a standard installation with one carrier extender cable used to
extend power from the left to the right carriers.
DeltaV Vertical Carriers
April 2021
D800001X312
504

--- Page 505 ---

Figure M-9: Power Extended from Left to Right Carriers
DeltaV Vertical Carriers
D800001X312 
April 2021
505

--- Page 506 ---

Related information
1-Wide VerticalPLUS Carrier Extenders and Cables
Extend power from left to right 8-wide VerticalPLUS carriers
Be sure that the DIN rail stops are in place on both DIN rails. Refer to “Installing the DIN Rail
Stop”.
This procedure is for an installation with 6 carriers.
1. Connect a left 1-wide VerticalPLUS carrier extender to the last 8-wide carrier on the
left side (carrier 3) by sliding together the 96 pin connectors on the carriers.
2. Connect a right 1-wide VerticalPLUS carrier extender to the first 8-wide carrier on
the right side (carrier 4) by sliding together the 96 pin connectors on the carriers.
3. Connect the 25 pin D-shell (male) connector on the extender cable to the D-shell
connector labeled A on the left 1-wide carrier extender and fasten the retainer
screws.
4. Connect the 25 pin D-shell connector on the other end of the cable to the D-shell
connector labeled A on the right 1-wide carrier extender and fasten the retainer
screws.
Related information
Installing the DIN Rail Stop
Extending power from right to left 8-wide VerticalPLUS
carriers
This procedure is for an installation with up to 8 carriers.
Note
If a 4-wide SISNet Repeater carrier is installed on the top right, there is no need for a 1-
wide carrier because power can be extended from the D-shell connectors on the SISNet
Repeater carrier.
1. Connect the left 1-wide VerticalPLUS carrier extender or SISNet Repeater carrier to
the last 8-wide carrier on the right side (carrier 6) by sliding together the 96 pin
connectors on the carriers.
2. Connect the right 1-wide VerticalPLUS carrier extender to the first 8-wide carrier on
the left side (carrier 7) by sliding together the 96 pin connectors on the carriers.
3. Connect the 25 pin D-shell (male) connector on the extender cable to the D-shell
connector labeled A on the right 1-wide carrier extender or SISNet Repeater carrier
and fasten the retainer screws.
4. Connect the 25 pin D-shell connector on the other end of the cable to the D-shell
connector labeled A on the left 1-wide carrier extender and fasten the retainer
screws.
DeltaV Vertical Carriers
April 2021
D800001X312
506

--- Page 507 ---

Figure M-10: Power Extended from a Left to Right Carrier and Right to Left
Carrier
M.7.4
Inserting System Power
To decide when to use external system power, calculate the power used per position on
the carrier. Add these values to determine if they exceed the power supply’s capabilities. If
the calculation at a given position exceeds the power supply’s capabilities:
• Locate the power jumper that is just before this position (count from the power supply
end).
• Insert additional power at this node.
DeltaV Vertical Carriers
D800001X312 
April 2021
507

--- Page 508 ---

If multiple power supplies are used, be sure they are grounded at the same point.
1. Remove the jumper.
Warning
Removing the jumper removes all 12 VDC power to all cards on all downstream
carriers. When 12 VDC power is removed, cards are unable to hold the last value.
2. Insert 12 VDC power:
• + to the center terminal
• - to the - terminal
Figure M-11: Remove Jumper to Insert Additional System Power
M.7.5
Using Bussed Field Power with VerticalPLUS Carriers
The bussed field power connectors on the VerticalPLUS carriers differ from those on the
horizontal and Legacy Vertical carriers; however, some basic principles apply to all carrier
types. Before connecting or extending bussed field power to VerticalPLUS carriers, read
the important information in "Connecting Bussed Field Power".
Related information
Connecting Bussed Field Power
Extending Bussed Field Power to VerticalPLUS Carriers
Before extending bussed field power to VerticalPLUS carriers, read the note and warning in
"Extending Bussed Field Power".
Bussed field power can be extended to VerticalPLUS carriers if the addition of the next I/O
card does not exceed the 13 A rating of the connection to the source. The following figure
shows the screw terminal assignments on the VerticalPLUS carriers’ bussed field power
connections.
Warning
For VerticalPLUS carriers, field power for one I/O card can be extended to additional I/O
cards only if they have the same field voltage requirements.
DeltaV Vertical Carriers
April 2021
D800001X312
508

--- Page 509 ---

Figure M-12: Screw Terminal Assignments on VerticalPLUS Carriers’ Bussed Field
Power Connections
4
3
2
1
8
7
6
5
+ Field Power  
Connections
- Field Power  
Connections
If the bussed field power supplies one I/O card only and is not extended to additional I/O
cards such as in redundant card applications, connect the wiring to the assigned screw
terminal connections on the I/O interface carrier as shown in Figure M-13.
 CAUTION
Ensure that the factory installed jumpers are removed from the connectors if only one I/O
card is to be powered.
DeltaV Vertical Carriers
D800001X312 
April 2021
509

--- Page 510 ---

Figure M-13: Bussed Field Power Wiring for One Power Supply Per I/O Card on
VerticalPLUS Carriers
First Supply
- Field Power Connection
Second Supply
+ Field Power Connection
First Supply
+ Field Power Connection
Second Supply
- Field Power Connection
DC
AC
-
N
+
L
DC
AC
+
L
-
N
Warning
When supplying 250 VAC to adjacent bussed field power connections, be sure both
sources are the same phase.
If the bussed field power is extended to two I/O cards, connect the wiring to the assigned
screw terminal connections on the I/O interface carrier as shown in the following figure. Be
sure that jumpers are installed as shown in the figure.
DeltaV Vertical Carriers
April 2021
D800001X312
510

--- Page 511 ---

Figure M-14: Bussed Field Power Wiring for One Power Supply Per Two Cards
First Supply
- Field Power Connection
Second Supply
+ Field Power Connection
First Supply
+ Field Power Connection
Second Supply
- Field Power Connection
DC
AC
-
N
+
L
DC
AC
+
L
-
N
Add Jumper Wires
to Extend Power
Warning
When supplying 250 VAC to adjacent bussed field power connections, be sure both
sources are the same phase.
If the bussed field power is extended to four I/O cards, connect wiring to the assigned
screw terminal connections on the I/O interface carrier as shown in the following figure. Be
sure that jumpers are installed as shown in the figure.
DeltaV Vertical Carriers
D800001X312 
April 2021
511

--- Page 512 ---

Figure M-15: Bussed Field Power Wiring for One Power Supply Per Four I/O Cards
Supply Connection
Supply Return Connection
Optional Wires to
Extend Power to
Next Connector Slots 
Add Jumper Wires
to Extend Power
DC
AC
-
N
+
L
Return
Supply
Related information
Extending Bussed Field Power
M.7.6
Legacy Vertical Carriers
DeltaV Legacy Vertical carriers mount on standard 35 mm. (1.38 in.) T- or G-type DIN rails.
for more information on vertical DIN rails.
There are 4 types of Legacy Vertical carriers for mounting vertically in a cabinet:
• Two types of 4-wide power/controller carriers
• Two types of 8-wide I/O interface carriers
There are two separate cable lengths for connecting the 8-wide Legacy Vertical I/O
interface carriers:
• 1 meter bottom cable extender
• 2 meter top cable extender
If you are installing Legacy Vertical carriers in high vibration areas, it is highly
recommended that you install a DIN rail stop to prevent the carriers from slipping down on
the DIN rails.
DeltaV Vertical Carriers
April 2021
D800001X312
512

--- Page 513 ---

Figure M-16: 4-Wide Legacy Vertical Power/Controller Carrier
J3
Legacy Vertical
Power/Controller Carrier
(Front View)
DC Return
Reference
Ground (24
VDC ONLY)
To DC Gnd
Bus in
Enclosure
1
Note
Use the DC return reference ground only with a DC/DC system power supply powered by
24 VDC. Do not use it for 12 VDC input.
Related information
DIN Rail Recommendations
Installing the DIN Rail Stop
4-Wide Legacy Vertical Power/Controller Carriers
The 4-wide Legacy Vertical power/controller carriers supply power and communications
connections for vertically mounted controller(s) and I/O cards. There are two types of 4-
wide Legacy Vertical power/controller carriers:
• Top 4-wide Legacy Vertical power/controller carriers connect to the left Legacy Vertical
8-wide I/O interface carrier. The 96 pin connector is at the bottom of this carrier. (The
left 8-wide Legacy Vertical I/O interface carrier holds cards 1-8 from top to bottom.)
• Bottom 4-wide Legacy Vertical power/controller carriers connect to the right 8-wide
Legacy Vertical I/O interface carrier. The 96 pin connector is at the top of this carrier.
(The right 8-wide Legacy Vertical I/O interface carrier holds cards 8-1 from top to
bottom.)
Up to two controllers (primary and secondary) and two system power supplies mount on
the 4-wide Legacy Vertical power/controller carriers. The following figure shows the top
and bottom 4-wide Legacy Vertical carriers.
DeltaV Vertical Carriers
D800001X312 
April 2021
513

--- Page 514 ---

Figure M-17: 4-Wide Legacy Vertical Power/Controller Carriers
8-Wide Legacy Vertical I/O Interface Carriers
The 8-wide Legacy Vertical I/O interface carriers provide power and communications
connections for the I/O subsystem. There are two types of 8-wide Legacy Vertical I/O
interface carriers:
• Left 8-wide I/O interface carrier (card positions 1-8 from top to bottom)
• Right 8-wide I/O interface carrier (card positions 8-1 from top to bottom)
The following figure shows the left and right 8-wide Legacy Vertical I/O interface carriers.
DeltaV Vertical Carriers
April 2021
D800001X312
514

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