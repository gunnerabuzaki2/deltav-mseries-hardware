--- Page 79 ---

Table 3-25: Serial Card, 2 Ports, RS232/RS485 LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Yellow - Port 1
and Port 2
(configured as
Slave)
•
On -
Communicatin
g
•
Off - No
communication
•
Flashing -
Intermittent
communication
VIM 2 card LEDs
The VIM 2 card has 6 LEDs. The LEDs can have 3 states: On, Off, or Blink (only used for the
VIMNet network communications LED). From top to bottom the LEDs are:
• Power: should always be On (green). If the power LED is off, provide power to the card.
• Error: Whenever the Fault LED is on (red), the VIM 2 is in error; all other LED states are
not significant.
• Active: When lit (green) indicates that the card is commissioned and operating as the
active card in a redundant pair.
• Standby: When lit (green) indicates that the card is commissioned and operating as the
standby card in a redundant pair. The Standby LED is always off in simplex mode.
• Network: When lit (amber) indicates valid VIMNet network communications.
• Ctlr Comm: When lit (amber) indicates valid LocalBus communications.
LED pattern when the VIM 2 is decommissioned
The following table shows the LED pattern when the VIM 2 is decommissioned.
LED
State
Corrective action
Active
Off
A decommissioned VIM 2 does
not have an IP address. Use the
VIMNet Explorer to configure a
placeholder that contains the IP
address for your network, then
commission the VIM 2.
Standby
Off
Network
Blinking
Ctlr Comm
Off
Power
On
Example LED patterns when the VIM 2 is commissioned
The following table shows the LED pattern when the VIM 2 is commissioned and
communicating with both the DeltaV controller and with external devices. Note that if the
Active LED is on and the Standby LED is off, the redundancy role is Active. If the Active LED
is off and the Standby LED is on the redundancy role is Standby.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
79

--- Page 80 ---

Table 3-26: VIM 2 is commissioned and communicating on both networks
LED
State
Active
On
Standby
Off
Network
On
Ctlr Comm
On
Power
On
The following table shows the LED pattern when the VIM 2 is commissioned but not
communicating on the LocalBus and there is a VIMNet network error. The redundancy role
is Active. If the Standby LED is On and the Active is Off with all other LED states the same,
the redundancy role is Standby.
Table 3-27: VIM 2 is commissioned but not communicating on the LocalBus; VIMNet
network error
LED
State
Corrective action
Active
On
Verify that the DeltaV
controller is downloaded. Also
verify that the external device
configuration has been
uploaded to the VIM 2 from the
VIMNet Explorer
Standby
Off
Network
Blink
Ctlr Comm
Off
Power
On
The following table shows the LED pattern when the VIM 2 is commissioned and
communicating on the LocalBus but there are errors on the VIMNet network. The
redundancy role is Active. If the Standby LED is On and the Active is Off with all other LED
states the same, the redundancy role is Standby.
Table 3-28: VIM 2 is commissioned, communicating on the LocalBus, VIMNet network
errors
LED
State
Active
On
Standby
Off
Network
Blink
Ctlr Comm
On
Power
On
I.S. AI 8-Channel HART Card LEDs
The following table describes the LEDs for the I.S. AI, 8-Channel, 4-20 mA HART card.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
80

--- Page 81 ---

Table 3-29: I.S. AI 8-Channel HART Card LEDs
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green – Power
On
Off
1. System power
is not supplied to
unit. Possible line
power problem.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red – Error
Off
On (continuous)
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Unit failed self-
test.
2. Contact
technical support.
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Address
conflict.
2. Replace card
with known good
card of same
type; contact
technical support.
Yellow - Ch.1 - Ch.
8
On
Off
1. Input is out of
range. (See
specifications in
Appendix C for
correct range.)
1. Check input
source and
connections.
2. Internal fault.
2. Contact
technical support.
Flashing
1. Input is out of
range. See
specifications in
Appendix C for
correct range.)
1. Check input
source and
connections.
2. Channel is
configured for
HART, but there is
no HART
communication.
2. Check HART
input source and
connections.
3. Channel is
configured for
NAMUR limits and
they have been
exceeded.
3. Check input
levels compared
to NAMUR limits.
Related information
Interface Specifications
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
81

--- Page 82 ---

I.S. AO 8-Channel HART Card LEDs
The following table describes the LEDs for the I.S. AO 8-Channel HART card.
Table 3-30: I.S. AO 8-Channel HART Card LEDs
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green – Power
On
Off
1. System power
is not supplied to
unit. Possible line
power problems.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red – Error
Off
On (continuous)
Unit failed self-
test.
Contact technical
support.
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Unit failed self-
test.
2. Contact
technical support.
3. Address
conflict.
3. Replace card
with known good
card of same
type; contact
technical support.
Yellow – Ch.1 to
Ch. 8
On
Off
1. No output
device (load).
1. Check output
connections.
2. Internal fault.
2. Contact
technical support.
Flashing
1. No output
device (load).
1. Check output
connections.
2. Internal fault.
2. Contact
technical support.
3. Card is
configured for
HART but there is
no HART
communication.
3. Check HART
input source and
connections.
I.S. DI 16-Channel Card LEDs
The following table describes the LEDs for the I.S. DI 16-channel card.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
82

--- Page 83 ---

Table 3-31: I.S. DI 16-Channel Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green - Power
On
Off
1. System power
is not supplied to
unit. Possible line
power problem.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red - Error
Off
On (continuous)
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Unit failed self-
test.
2. Contact
technical support.
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Address
conflict.
2. Replace card
with known good
card of same
type; contact
technical support.
Yellow - Ch.1-
Ch.16
•
On = input >
detection level.
•
Off = input <
detection level.
See specifications in
Appendix C for
detection levels for
each card type.
Flashing
Line fault
detected.
Check field
wiring.
Running light
from Channel 1 -
Channel 16 with
Red Error On.
No terminal block
installed or
incorrect terminal
block used.
Make sure that
the correct
terminal block is
installed.
Related information
Interface Specifications
I.S. DO 4-Channel Card LEDs
Table 3-32: I.S. DO 4-Channel Card LEDs
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green - Power
On
Off
1. System power
is not supplied to
unit. Possible line
power problem.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
83

--- Page 84 ---

Table 3-32: I.S. DO 4-Channel Card LEDs (continued)
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Red
Off
On (continuous)
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Unit failed self-
test.
2. Contact
technical support.
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Address
conflict.
2. Replace card
with known good
card of same
type; contact
technical support.
Yellow - Ch. 1 -
Ch. 4
Depends on
setpoint and
configuration.
Flashing
Line fault
detected.
Check field
wiring.
MD20 and MD30 Smart Switch LEDs
There are two types of LEDs on the DeltaV MD20 and MD30 Smart Switches: device status
LEDs that describe the status of the MD20 and MD30 base switches and display status
LEDs that describe the status of the ports on the media modules that plug into the base
switches.
Table 3-33: MD20 and MD30 Device Status LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Green P (Power)
On
Off
Internal supply voltage
is too low.
Green P1 (Power 1)
On
Off
Supply voltage 1 is less
than 18 V.
Green P2 (Power 2)
On
Off
Supply voltage 2 is less
than 18 V.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
84

--- Page 85 ---

Table 3-33: MD20 and MD30 Device Status LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Green/yellow LOCK
•
On (green
continuous) - The
device is locked.
•
On (yellow
continuous) - The
device is
temporarily
unlocked but will
be locked down
after the lockdown
timer has expired.
•
Flashing (green) -
Device passes into
the lockdown
state.
Off
Device is in an
unlocked state.
Red/yellow RL1 (Relay
1)
Off - Signal contact is
closed; not reporting
an error.
Red On (continuous)
Signal contact is open;
reporting an error.
Yellow On
(continuous)
Signal contact is open;
the Manual Setting is
active.
Red/yellow RL2 (Relay
2)
Off - Signal contact is
closed; not reporting
an error
Red On (continuous)
Signal contact is open;
reporting an error.
Yellow On
(continuous)
Signal contact is open;
the Manual Setting is
active.
Green RUN
•
On (continuous) -
The device is ready
for operation.
•
On (flashing) - The
device is booting.
Off
Device is in reset
mode.
Green TEST
On - LED test activated. Off
LED test not activated.
Green ACA/Flash
Access - displays the
ACA flash access with
the Run LED.
Every DeltaV media module has one LED per port. The meaning of the media modules’
port status LED depends upon the item selected on the MD20 or MD30 base Smart
Switches. Press the Select button to cycle through the items on the base switch. The
following table describes the display status LEDs on the DeltaV MD20 and MD30 Smart
Switches and the meaning of the port LEDs on the media modules
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
85

--- Page 86 ---

Table 3-34: Display Status LEDs on MD Base Smart Switches and Meaning on Media
Modules 
Display Status LED on MD Base
Smart Switches
Meaning on Media Module
Green L/D (Data/link status)
The port LEDs on the media
modules display the connection
status.
•
Ports glowing green - valid connection.
•
Ports not glowing green- no valid connection.
•
Ports flashing green once a period - port is switched to
standby.
•
Ports flashing green three times a period - port is locked by
the One-Click Lockdown application (DeltaV version 10.3);
the Smart Switch Command Center (DeltaV version 11.3 and
12.3); or, the Network Device Command Center (NDCC) in
DeltaV version 13.3 and higher.
•
Ports flashing yellow - port is receiving data.
Green FDX (full duplex)
The port LEDs on the media
modules display the half duplex
or full duplex connection status.
•
Ports glowing green - Full-duplex is active.
•
Ports not glowing green - Half duplex is active.
Green 1000 (10/100/1000Mbit/
sec)
The port LEDs on the media
modules display the
transmission speed.
•
Ports glowing green - 100Mbit/sec is active.
•
Ports not glowing green - 10/Mbit/sec is active.
•
Ports glowing yellow - 1000Mbit/sec is active.
Green AN (autonegotiation)
The port LEDs on the media
modules display the
autonegotiation setting.
•
Ports glowing green - autonegotiation is active.
•
Ports not glowing green - autonegotiation is inactive.
Green TP (twisted pair/fiber-
optic)
The port LEDs on the media
modules display the media type.
•
Ports glowing green - twisted pair ports.
•
Ports glowing yellow - fiber-optic ports.
Green PoE status
The port LEDs on the media
modules display the Power over
Ethernet status.
•
Ports not glowing - No PoE port or PoE disabled.
•
Ports glowing yellow - PoE port searching for terminal device
(PD); PoE status is searching.
•
Ports glowing green - PoE port supplying terminal device
(PD); PoE status is delivering power.
RM100 and FP20 Smart Switch LEDs
The following table describes the device status LEDs on the DeltaV RM100 and FP20 Smart
Switches.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
86

--- Page 87 ---

Table 3-35: Device Status LEDs on DeltaV RM100 and FP20 Smart Switches
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Green/yellow P
(Power)
•
On (green
continuous) -
Supply voltages are
on.
•
On (yellow
continuous) - Only
one supply voltage
is on.
Off
Supply voltage is off or
too low.
Green RUN
•
On (green
continuous) -
Device is ready for
operation.
•
Flashing (green) -
Device is booting.
Off
Device is in reset
mode.
Green/yellow LOCK
•
On (green
continuous) -
Device is locked.
•
On (yellow
continuous) -
Device is
temporarily
unlocked but will
enter the locked
state after the
lockdown timer
expires.
•
Flashing (green) -
Device passes into
the locked state.
Off
Device is in an
unlocked state.
Red FAULT
Off - not reporting an
error.
On (red continuous)
Reporting an error.
The following table describes the port status LEDs on the DeltaV RM100 and FP20 Smart
Switches
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
87

--- Page 88 ---

Table 3-36: Port Status LEDs on DeltaV RM100 and FP20 Smart Switches
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Green/LS (Link Status)
•
On (green
continuous) - Valid
link or connection.
•
Flashing green
once per second -
Port is in standby.
•
Flashing green
three times per
second. - Port is
locked by the One-
Click Lockdown
application (DeltaV
version 10.3); the
Smart Switch
Command Center
(DeltaV version
11.3 and 12.3)
higher); or, the
Network Device
Command Center
(DeltaV version
13.3 and higher).
Off
No valid link or
connection.
Yellow/DA (Data)
Flashing yellow -
Receiving data.
Off
Not receiving data.
3.1.4
Step 4. Testing the Field Wiring Connections
To troubleshoot field wiring connection problems, test access points are located on the
I/O terminal blocks. The access point for each wire connection is located in the square hole
above the corresponding field screw terminal. To contact the field signals, use a test probe
at least 25 mm (1 in.) long and 2 mm (0.08 in.) or less in diameter.
To determine the expected voltage levels for your application, refer to the:
• Wiring diagrams for the specific I/O card type in the "Interface Specifications" section
• Connection information supplied with your field device
 CAUTION
The test probe is not retained within the access hole. It can fall out and short across field
wiring if it is not held in place.
3.2
Troubleshooting Your System
After checkout, start up the DeltaV software and verify and troubleshoot your hardware
installation with the DeltaV Explorer, workstation diagnostics utilities, and DeltaV
Diagnostics. To start the DeltaV Explorer, click Start → All Programs → DeltaV →
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
88

--- Page 89 ---

Engineering → DeltaV Explorer. To start DeltaV Diagnostics, click Start → All Programs
→ DeltaV → Operator → Diagnostics.
3.2.1
Using the DeltaV Explorer
The DeltaV Explorer presents a view of the overall structure and layout of your system. The
tree view shows your control strategies and the hierarchy of the nodes on your Control
Network. These nodes can be physically connected to the system, or they can be
placeholders configured prior to the installation of the actual hardware.
When you check out your system, remember that the DeltaV Explorer gives you a view of
your database, but this may not necessarily match what is actually installed on the
network. For example, before connecting controllers, you can define them as controller
placeholders in the Control Network. The icons for the placeholders appear in the DeltaV
Explorer but are not bound to any device. Then, when the controllers are available and
connected, you drag and drop them from the Decommissioned Controllers section to the
controller placeholder icons in the Control Network.
Resolving system problems is often a matter of making sure the database and the network
match and making sure all the nodes on the network have information about all other
nodes. The Download commands in the DeltaV Explorer provide the nodes with all the
information they need to operate and interact with other nodes.
See the manual Getting Started with Your DeltaV Software for information on:
• Downloading Setup Data
• Downloading Controllers and Installing Workstations
• Dragging decommissioned controllers to the Control Network
Status Indicators
After you have completed the above steps and the controllers are listed in the Control
Network, look for these indicators next to the nodes:
Indicates the downloading node (the workstation) does not have all the
information about this node.
Indicates the node is not communicating. This indicator occurs if there is a bad
connection, if the controller is not powered up, or if the controller is
decommissioned. It also occurs for a few seconds after a controller is
commissioned.
Indicates the node is communicating but has an integrity problem. Integrity
problems can occur if there is a mismatch between the I/O configuration and
the installed I/O or if the node is configured for network redundancy but does
not have the necessary connections to support it.
Indicates that the node does not have a configuration. This can occur if the
node has never been downloaded. For controllers, this can occur if there is a
power failure and cold restart was not enabled for the node.
Note
If a node shows a status indicator, check for hardware faults shown in the Troubleshooting
Guide before changing your configuration.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
89

--- Page 90 ---

You can automate the comparison between the physical I/O and the configured I/O with
the Auto-sense I/O cards command. To use the command, click on the I/O for the node,
click the right mouse button, and then select Auto-sense I/O Cards. The Auto-sense Cards
dialog lists the card sensed in the controller and the card listed in the database for each
slot.
For example, if you add a card to the controller, the dialog displays:
• The type of card sensed in the Auto-sensed Type
• <empty> in the database column
Click OK to add the configuration to the database. (Clicking OK does not affect existing
cards.) Click Cancel to decommission the controller and close the dialog.
3.2.2
Using the Workstation Diagnostics
The documentation supplied with your workstation describes the diagnostics programs
available for the workstation hardware and operating system software. If you need to test
the workstation subsystems (memory, processors, video, keyboard, mouse, disk
controller, ports), use the diagnostics disk and follow the instructions in the manual
supplied with your workstation.
3.2.3
Using DeltaV Diagnostics
The DeltaV Explorer allows you to launch the DeltaV Diagnostics application and view
diagnostics data for any selected DeltaV Explorer object. This provides useful diagnostic
information for nodes that have good status or show the 
indicator. To investigate
integrity problems for a node or subsystem, select its icon, click the right mouse button,
and then click Diagnose. Information about DeltaV Diagnostics is located in online help.
3.2.4
Troubleshooting Guide
The following information can be used to help you detect system hardware problems with
the DeltaV Explorer and correct them.
Problem: Controller not listed in the Decommissioned Controllers tree.
Possible Cause
Corrective Action
Node is not connected to the switch.
Check the LEDs on the controller (see the LED
Checklists).
Control network cable is not working correctly.
Test the cable between the controller and the
switch. If the cable is not working correctly,
repair or replace it.
Node is not connected correctly to the network.
Make sure cables are connected to the correct
ports on the switch and the controller.
Connection on the carrier is not secure.
Remove the controller from its power/controller
carrier for at least 15 seconds and replace it onto
the carrier.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
90

--- Page 91 ---

Possible Cause
Corrective Action
DeltaV Explorer is not connected to the active
database, or the DeltaV Database Server
(DvDbServer) is not running.
Exit the DeltaV Explorer and restart the
connection to the active database.
Problem: The controller has an 
 indicator.
 appears for nodes that are not communicating. Typically, this indicator occurs if there
is a bad connection or the controller is not powered up. To clear this indicator, go to the
node and make sure it is connected, the wiring is correct and sound, and the node is
powered up. This indicator also occurs for a few seconds after a controller is commissioned
Possible Cause
Corrective Action
Node is not connected to the switch.
1. Check the LEDs on the controller.
2. Check the Control Network cables to make
sure they are connected to the correct ports on
the switch and controller.
Control network cable is not working correctly.
Test the cable between the controller and the
switch. If the cable is not working correctly,
repair or replace it.
You are looking at the wrong controller.
Make sure you are looking at the correct
controller by selecting DeltaV Explorer
Controller Properties → Controller → Flash
Lights.
Primary and secondary Control Network
connections are crossed.
1. Use DeltaV Explorer Node Properties →
Identify Controller to flash the controller LEDs.
If the LEDs flash, use the Check Node Integrity
function in DeltaV Diagnostics and verify that a
Not Connected status is returned.
2. Verify that the primary Control Network
cables are connected to the correct primary
ports on the controller, workstation, and switch.
3. Verify that the secondary Control Network
cables are connected to the correct secondary
ports on the controller, workstation, and switch.
Problem: The workstation has an 
 indicator.
 appears for nodes that are not communicating. Typically, this indicator occurs if there
is a bad connection or if the workstation is not powered up. To clear this indicator, go to
the node and make sure it is connected, the wiring is correct and sound, and the node is
powered up.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
91

--- Page 92 ---

Possible Cause
Corrective Action
Workstation is not set up properly.
Make sure the workstation is powered up. Look
in Control Panel → Administrative Tools →
Services and verify that DeltaV Services are
running.
Node is not connected to the switch.
Check the Control Network cables to make sure
they are connected to the correct ports on the
switch and workstation.
Control network cable is not working correctly.
Test the cable between the workstation and the
switch. If the cable is not working correctly,
repair or replace it.
Workstation address is set to a default value or
an incorrect address.
1. Look at the Internet Protocol (IP) address and
verify that the address matches the DeltaV
Explorer address for the node. If the address is
not correct, run Workstation Configuration.
2. Use the Utilities from the 3Com Install disk to
verify that the Plug N Play feature is turned off
for the workstation Control Network card.
Problem: A node has an 
 indicator.
Possible Cause
Corrective Action
Installing node (the workstation) does not have
all the information on the node.
Click the node with the indicator, click the right
mouse button, and then click Install Setup Data.
This transfers setup data from the database to
the physical node. It also updates the installing
workstation node so that the workstation has all
the information it needs to manage the new
node.
This indicator can appear on controllers that are physically connected to the network or on
controller placeholders. Note that you cannot install setup data for a controller
placeholder; the physical node must be connected first.
Problem: A node has a 
 indicator.
Possible Cause
Corrective Action
Node is communicating but has an integrity
problem.
Most integrity problems are due to hardware
problems. Check the LEDs on the nodes (refer to
the LED tables in this chapter) and correct the
hardware problem.
Occasionally, integrity problems occur if there is a mismatch between the I/O
configuration and the installed I/O. In this case, compare the controller I/O configuration
in the DeltaV Explorer with the actual I/O cards connected to the controller. This
comparison can be accomplished by viewing either the I/O Auto-Sense dialog in DeltaV
Explorer, or by examining the I/O hierarchy in Diagnostics.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
92

--- Page 93 ---

Integrity problems can occur if the controller is configured for network redundancy but
does not have the necessary connections to support it. Verify that the controller is
configured to support network redundancy. If it is, make sure the controller is connected
to the network correctly.
This indicator also occurs if workstations have Event Chronicle problems (configured for a
directory that does not exist, for example), or if workstations are not communicating with
the controller.
If the indicator persists, use DeltaV Diagnostics to pinpoint the problem.
Problem: The node has a 
 indicator.
Possible Cause
Corrective Action
The node has never been downloaded or has
lost its configuration.
Download the node.
3.3
Getting Help
DeltaV Books Online provides information on the DeltaV system and the Online Help for
the DeltaV applications provides procedural help on using the applications and popup help
for dialog boxes.
Online Help
All DeltaV applications have online help that provides instructions on using the
application. To access help for any application, open the application, and select the help
topics command under the Help menu on the application’s menu bar. For example to start
DeltaV Diagnostics and then access the help, click Start → DeltaV Operator →
Diagnostics, and then click Help → Help in DeltaV Diagnostics. To search the help for
information on specific topics, click the left mouse button on the Index tab or the Search
tab on the Help Topics dialog box, and follow the directions. For help on dialogs, click the
question mark in the upper right hand corner of the dialog, drag it to the field for which
you want help, and click the left mouse button.
Books Online
Books Online provides reference information and detailed information on installing,
configuring, operating, and troubleshooting your DeltaV system. Click Start → DeltaV
Help → Books Onlineand then click on the title of the book that you want to read. The
System Administration and Maintenance manual in Books Online contains helpful technical
information related to hardware troubleshooting.
DeltaV Installation and Instruction Manuals
Most DeltaV product information is in Books Online. You can print any of that information
or you can order a paper copy from Emerson. The Getting Started with Your DeltaV Software
manual and the Fieldbus Installations in a DeltaV Distributed Control System manual are also
available in printed form. The Getting Started with Your DeltaV Software contains general
information about the software and helps you get started with configuration and the
Fieldbus Installations in a DeltaV Distributed Control System provides important information
about installing a fieldbus system.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
93

--- Page 94 ---

3.4
Hazardous Area Installation Manuals, NAMUR
Installation Manuals, and ATEX Instruction
Sheets
The following files related to Hazardous Area installations and NAMUR compliant
installations are on the DeltaV Documentation Library DVD. The files are in Portable
Document Format (.PDF). A letter (A-Z) is appended to the filenames that begin with 12P
and is incremented for each release of the document.
• 12P1293 — DeltaV™ Scalable Process System, Class I Division 2 Installation Instructions
(Part Number - 12P1293)
• 12P1892 — DeltaV™ Scalable Process System, Class I Div. 2 with Class I, II, III Div. 1 Field
Circuits Installation Instructions (Part Number - 12P1892)
• 12P1990 — DeltaV™ Scalable Process System with Zone 0 Field Circuits Installation
Instructions (Part Number - 12P1990)
• 12P2046 — DeltaV™ Scalable Process System, Zone 2 Installation Instructions (Part
Number - 12P2046)
• 12P2524 — DeltaV™ IS I/O Code of Practice for Installation and Maintenance in Zone 2
Hazardous Areas (Part Number - 12P2524)
• 12P2822 — DeltaV™ Digital Automation System Namur NE 21 Installation Instructions (Part
Number - 12P2822)
• 12P3292 — DeltaV™ Type KJ7000 Series Zone 1 I/O System Installation Instructions
• 12P3517 — DeltaV™ KJ1710 Single Port Fiber Switch Installation Instructions
• ATEX Instruction Sheets — The DeltaV ATEX Instruction Sheets (in PDF format) can also
be found on the DeltaV web site.
3.5
Technical Service
There are several options available for technical service, including help desk support,
remote diagnosis, 24-hour emergency support, and software update service. Please
complete the SureService registration process.
If the information presented in this manual does not solve your problem, refere to the
contact information on the Emerson Automation Solutions website and follow the
directions for your world area.
Make sure you have the following information ready:
• System Identification Number
• Software Version Number
• Description of the problem
If you are calling, be at your DeltaV system if possible. This enables the Technical Support
Representative to step you through the proper problem solving procedures.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
94