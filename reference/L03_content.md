--- Page 28 ---

9. Read the manual Getting Started with your DeltaV Digital Automation System for
information on the software applications for the DeltaV system.
Related information
DeltaV Vertical Carriers
Checking Out and Troubleshooting Your DeltaV System
System Power Guidelines
Installing Your DeltaV System
2.5
Installing the System
The DeltaV system is designed for installation in an enclosure suitable for the location in
which the equipment is installed.
The following sections describe how to:
• Install the DIN rails and carriers
• Connect bussed field power
• Install the DeltaV I/O interface, Controller, System Power Supply, and Workstations
• Setup the DeltaV Control Network
• Connect power to the system
• Setup the DeltaV Remote Network
• Setup a Network Time Server
2.5.1
Installing the DIN Rails and Carriers
The power/controller carriers and 8-wide I/O interface carriers install on standard 35 mm
(1.38 in.) T- or G-type DIN rails. If you use T-type rails, use the heavier (15mm-deep) rails
because they better accommodate the weight distribution of DeltaV equipment. The
optional carrier shield bar provides a connection point for field shield wires for the I/O
interface carrier. You cannot connect a vertical carrier to a horizontal carrier or a horizontal
carrier to a vertical carrier. You must choose one carrier configuration. Refer to Appendix
M DeltaV Vertical Carriers for information on installing vertical DIN rails and carriers.
 CAUTION
The DeltaV I/O Cards and Controller must be installed vertically on the horizontal carrier
for cooling purposes.
Related information
DeltaV Vertical Carriers
2.5.2
DIN Rail Recommendations
Figure 2-1 shows suggested spacing for DIN rail installation on your mounting surface. To
avoid clearance problems with the heads of mounting screws, avoid using screws at the
following locations, as shown in Figure 2-2
Installing Your DeltaV System
April 2021
D800001X312
28

--- Page 29 ---

• An area 1.3 cm (0.5 in.) wide, centered 4.5 cm (1.75 in.) from the left side of a 2-wide
power/controller carrier.
• An area 1.3 cm (0.5 in.) wide, centered 8.3 cm (3.25 in.) from either side of an 8-wide
I/O interface carrier.
If more than one carrier is needed, connect carriers end-to-end on one rail or stack them
on separate rails by using a DeltaV LocalBus Cable.
Figure 2-1: DIN Rail Installation
Figure 2-2: Screw Clearance Guidelines for DIN Rail Mounting
Installing Your DeltaV System
D800001X312 
April 2021
29

--- Page 30 ---

Related information
Carrier Specifications
2.5.3
Installing the 2-Wide Power Controller Carrier
To install the 2-wide power/controller carrier
Refer to Figure 2-3.
1. Install the DIN rail at the appropriate location.
2. Connect each power/controller carrier to any adjacent carriers by sliding the 48-pin
connectors on the sides of the carriers together.
3. Turn the screws counter-clockwise on the power/controller carrier to disengage the
latch. Place the carrier on the rail and tighten the screws clockwise to latch.
Note
The middle two screws are for G-rail mounting and the upper and lower screws are
for T-rail mounting.
Figure 2-3: 2-Wide Power/Controller Carrier Installation
Note
2-wide carriers should be installed to the left of any 8-wide carriers.
Installing Your DeltaV System
April 2021
D800001X312
30

--- Page 31 ---

2.5.4
Installing the I/O Interface Carrier
Figure 2-4: I/O Interface Carrier Installation
1. Install the DIN rail at the appropriate location.
2. Connect each I/O interface carrier to any adjacent carriers by sliding together the
48-pin connectors on the sides of the carriers.
3. Turn the screws counter-clockwise on the I/O interface carrier to disengage the
latch. Place the carrier on the rail and tighten the screws clockwise to latch. The
middle two screws are for G-rail mounting and the upper and lower screws are for T-
rail mounting.
4. If you are installing I/O interface carriers on separate rails, connect them with the
LocalBus cable from the 48-pin connector on the right side of one carrier to the 48-
pin connector on the left side of the next carrier.
5. Install the carrier ground wiring as shown in Figure J-20.
2.5.5
Connecting Bussed Field Power
The carrier type determines how bussed field power is provided. The bussed field power
connectors on the horizontal and Legacy Vertical carriers differ from those on the
VerticalPLUS carriers. The following section explains how to connect bussed field power to
the three carrier types. Refer to Appendix M for additional information on vertical carriers.
Horizontal and Legacy Vertical Carriers
Each pair of slots on the Legacy Vertical and horizontal I/O carriers have four screw
terminals for bussed field power. Two of the terminals are for the supply connection and
two of the terminals are for the supply return connection.
Installing Your DeltaV System
D800001X312 
April 2021
31

--- Page 32 ---

Each bussed field power connection routes power to two adjacent I/O cards. You can use a
different bulk power supply for each bussed field power connection or you can extend
power to another pair of I/O cards.
The bussed field power connection provides power to two adjacent I/O cards to power
field devices. Cards 1 and 2 are paired together and must use the same field voltage level.
Similarly, cards 3 and 4 must use the same field voltage level, although this level can be
different from cards 1 and 2.
VerticalPLUS Carriers
Each slot on the VerticalPLUS carrier has four screw terminals for bussed field power. Two
of the terminals are for the + field power connection and two of the terminals are for the -
field power connection. Refer to "Extending Bussed Field Power to VerticalPLUS Carriers"
for the bussed field power terminal assignments.
Each bussed field power connection routes power to one slot. You can use a different
power source for each bussed field power connection or you can extend power to another
slot. Jumpers are pre installed at the factory to extend field power to slots 1-4. With these
jumpers installed, the I/O cards installed in slots 1-4 must use the same field voltage level.
Similarly, slots 5-8 have jumpers pre installed at the factory to extend field power to slots
5-8 and the I/O cards installed in slots 5-8 must use the same field voltage level. It is
recommended that you use a separate power feed to each field power connector. A field
power connector is the connector that connects to a bank of four I/O cards.
 CAUTION
Ensure that the bussed field power connection to each carrier slot is correct for the card
being installed in the slot. Card damage can result if there is a mismatch between the field
power voltage at the carrier slot and the card installed in the slot.
Related information
DeltaV Vertical Carriers
Extending Bussed Field Power to VerticalPLUS Carriers
2.5.6
Extending Bussed Field Power
Note
The decision to extend bussed field power depends on plant standards and procedures.
However, if separate power supplies, breakers, or shutdown switches are required, it is not
recommended that bussed field power be extended.
For all carrier types, supply the same voltage at bussed field power to all cards on a carrier
whenever possible. Supply clean bussed field power to the I/O carriers and use inductive
noise reduction techniques on I/O signals. Refer to Appendix K for bussed field power
guidelines.
Warning
If more than one bussed power source is used, place a label near the bussed field power
connectors containing the following English and French statements: “WARNING: MORE
THAN ONE LIVE CIRCUIT. SEE INSTALLATION DIAGRAM.” “AVERTISSEMENT: CÉT
EQUIPMENT RENFERME PLUSIEURS CICUITS SOUS TENSION. VOIR LE SCHÉMA
D’INSTALLATION”.
Installing Your DeltaV System
April 2021
D800001X312
32

--- Page 33 ---

Extending Bussed Field Power to Horizontal and Legacy Vertical Carriers
This section explains how to extend bussed field power to the horizontal and Legacy
Vertical carriers. For VerticalPLUS carriers, refer to the “Extending Bussed Field Power to
VerticalPLUS Carriers” topic.
Bussed field power can be extended to horizontal carriers and Legacy Vertical carriers if the
addition of the next two I/O cards does not exceed the 6.5 A rating of the connection to
the source. Figure 2-5 shows the screw terminal assignments on the bussed field power
connector on horizontal and Legacy Vertical carriers.
Warning
For Legacy Vertical and horizontal carriers, field power for one I/O card can be extended to
additional pairs of I/O cards only if they have the same field voltage requirements.
Warning
If extending bussed field power to Legacy Vertical and horizontal carriers, removing the
connector will remove power from all extended connectors.
Figure 2-5: Bussed Field Power Connector on Horizontal and Legacy Vertical Carriers
Keys supplied with the two-part connector on the horizontal and Legacy Vertical carriers
prevent damage to the cards if an incorrect power source is connected after the cards are
installed. Install the keys in each field power connector based on the power source you
connect to that connector. Because bussed field power can be supplied separately to each
half of a connector, make sure you install keys in each side. As an example, Figure 2-6
shows bussed field power keying connections for horizontal and Legacy Vertical Carriers
for 120 VAC only.
Installing Your DeltaV System
D800001X312 
April 2021
33

--- Page 34 ---

Figure 2-6: Bussed Field Power Keying Connections for 120 VAC Only
You can set up any standard that meets your needs for the keying scheme. Figure 2-7
shows an example keying scheme.
Figure 2-7: Bussed Field Power Keying Scheme Example for Horizontal and Legacy
Vertical Carriers
Note
This connector can be used for both DC and AC power.
Installing Your DeltaV System
April 2021
D800001X312
34

--- Page 35 ---

Wire the bulk power supply for bussed field power
The following information pertains to horizontal and Legacy Vertical Carriers. For
VerticalPLUS carriers refer to Appendix M.
• If the bussed field power supplies one pair of I/O cards only and is not extended to
additional I/O cards, connect wiring to the assigned screw terminal connection on the
top of the I/O interface carrier as shown in Figure 2-8.
Note
You might prefer to remove the screw terminal connector to install wiring and replace
it on the I/O interface carrier after wiring is installed.
Figure 2-8: Bussed Field Power Wiring Diagram
• If the bussed field power is extended to additional I/O cards, connect wiring to the
assigned screw terminal connection on the top of the I/O interface carrier as shown in
Figure 2-9.
Warning
When power is extended, removing the connector will break the connection between the
power supply and downstream devices.
Figure 2-9: Bussed Field Power Wiring Diagram (Extended Power)
Refer to Appendix J for power supply overviews.
Related information
Extending Bussed Field Power to VerticalPLUS Carriers
Bussed Field Power Guidelines
Installing Your DeltaV System
D800001X312 
April 2021
35