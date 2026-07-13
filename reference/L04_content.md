--- Page 36 ---

2.5.7
Installing Extender Cables
This section applies to horizontal and Legacy Vertical carriers. For VerticalPLUS carriers,
refer to “Extending LocalBus Power to Other Carriers.”
When carriers are installed on separate DIN rails, extender cables are used to extend
LocalBus power. Extender cables connect to one-wide carriers on the left and right sides of
the 2-wide, 4-wide, and 8-wide carriers.
Note
The 4-wide and 8-wide carriers must be left-aligned when using extender cables.
A standard installation uses one extender cable; however, dual extender cables can also be
used. The following procedure is for a standard installation that uses one carrier extender
cable.
To install carrier extender cables
1. Install the right and left-side one-wide extender cable carriers by sliding together
the 48-pin connectors on the sides of the carriers.
2. Connect the 44-pin D-shell (male) connector on the extender cable to the top D-
shell connector labeled A on the right-side carrier and fasten the retainer screws.
3. Connect the 44-pin D-shell connector on the other end of the cable to the top D-
shell connector labeled A on the left-side carrier and fasten the retainer screws.
Related information
Extending LocalBus Power to Other Carriers
2.5.8
Installing the DeltaV I/O Interface
To install the I/O interface, install the I/O terminal blocks on the I/O interface carrier and
connect field wiring to the I/O terminal blocks. Next, install the I/O cards on the I/O
interface carrier. The steps for installing both simplex and redundant terminal blocks are
discussed in the following procedures.
Related information
DeltaV Vertical Carriers
Interface Specifications
Installing an I/O Terminal Block
1. Check the key settings on the corresponding I/O card, and set the keys on the I/O
terminal block to match.
2. Locate the assigned slot location on the I/O interface carrier. Place the tabs on the
back of the I/O terminal block through the slots on the carrier and push the I/O
terminal block up to lock it into place as shown in the following figure.
Installing Your DeltaV System
April 2021
D800001X312
36

--- Page 37 ---

Figure 2-10: I/O Terminal Block Installation
3. Connect field wiring for the I/O terminal block as shown in Figure 2-11 or in the I/O
card wiring diagrams in the "Interface Specifications" section.
Note
Field wiring connections are specific to the I/O card type associated with the I/O
terminal block.
Figure 2-11: I/O Terminal Block Channel Assignments
Installing Your DeltaV System
D800001X312 
April 2021
37

--- Page 38 ---

Note
The channel assignments in the preceding image pertain to the I/O terminal block,
the fused I/O terminal block, and the 4-wire terminal block.
Related information
I/O Interface Keying
Interface Specifications
Installing an I/O Card
Warning
Before installing a card in a carrier slot, ensure that the bussed field power voltage at the
slot matches the field power requirements for the card. Card damage can result during
installation if there is a mismatch between the field power voltage at a carrier slot and the
card installed in the slot.
Refer to Figure 2-12.
1. Locate the assigned slot on the I/O interface carrier.
Warning
I/O cards are designed to be installed on terminal blocks. If you temporarily install a
card on the carrier without a terminal block, be sure to carefully align the pins on
the card with the connector on the carrier to prevent damage to the pins.
2. Align the connectors on the I/O card with the connectors on the I/O carrier and the
I/O terminal block and push to attach
3. Tighten the mounting screw.
Figure 2-12: I/O Card Installation
Installing a Redundant Terminal Block
Read the information in “DeltaV Series 2 I/O” before installing a redundant terminal block.
Installing Your DeltaV System
April 2021
D800001X312
38

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