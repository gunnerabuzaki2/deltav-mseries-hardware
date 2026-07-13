--- Page 315 ---

D
DeltaV Controllers and the Remote
Interface Unit
This appendix provides specifications for the controller and specifications and installation
information for the Remote Interface Unit and the Fiber-Optic Media Converter.
D.1
Controller Specifications
Specifications
The following table shows specifications for the MD Plus, MX, and MQ controllers.
Item
MD Plus, MX, MQ
Power requirement (supplied by system power
supply through 2-wide power/controller carrier)
+5 VDC at 1.4 A maximum
Fuse protection
3.0 A, non-replaceable fuses
Power dissipation
5.0 W typical 7.0 W maximum
Mounting
On right slot of power/controller carrier
Figure D-1: Controller Dimensions
DeltaV Controllers and the Remote Interface Unit
D800001X312 
April 2021
315

--- Page 316 ---

D.2
Remote Interface Unit
The Remote Interface Unit allows standard DeltaV I/O cards to be installed remotely from
the controller. The remote subsystem, consisting of the Remote Interface Unit, system
power supply, carriers, and I/O cards, can be located in Zone 2. The Remote Interface Unit
communicates with the controller over redundant, Control Network (ethernet)
connections.
Specifications
The following table shows specifications for the Remote Interface Unit.
Item
Specification
Power requirement (supplied by system power
supply through 2-wide power/controller carrier)
+3.3 VDC at 500 mA maximum +5 VDC at 200
mA maximum
Fuse protection
3.0 A, non-replaceable fuses
Power dissipation
3.0 W maximum
Mounting
On right slot of power/controller carrier
Connections and Dimensions
The Remote Interface Unit mounts in the controller slot of a 2-wide carrier and has
redundant ethernet connections to the DeltaV Control Network switch or hub. Connect
the primary port to the primary switch or hub and the secondary port to the secondary
switch or hub. The primary Control Network connection is capable of 10/100Mbit ethernet
while the secondary connection is limited to 10Mbit ethernet.
DeltaV Controllers and the Remote Interface Unit
April 2021
D800001X312
316

--- Page 317 ---

Figure D-2: Remote Interface Unit Dimensions
D.3
Fiber-Optic Media Converter
This section describes controller connections with a fiber-optic media converter. The
media converter converts 10BaseT TP to 10Base-FL ST fiber cable without repeating the
signals and is used in conjunction with the controller to allow an Ethernet link to a range of
2000 meters. The following table shows the media converter specifications.
Table D-1: Fiber-Optic Media Converter Specifications
Item
Specification
LAN interface
Ethernet IEEE802.3 compatible
Port interface
10BaseT RJ45 compatible
Data rate
10 MBPS
Fiber interface
10Base-FL compatible
Fiber type
Multimode 62.5/125 microns
LocalBus current (12 VDC nominal), per card
•
250 mA typical
•
300 mA maximum
The media converter mounts on a 2-wide carrier next to (or close to) the controller and
connects to the controller with two standard 12 to 16 inch twisted pair cables with
shielded connectors on both ends of the cable. The four fiber-optic cables connect
DeltaV Controllers and the Remote Interface Unit
D800001X312 
April 2021
317

--- Page 318 ---

transmit to receive between the Workstation’s media converter and the controller’s media
converter as shown in the following figure. The dimensions for the fiber-optic media
converter case are the same as the controller case. The connectors on the media converter
extend one half inch above the case.
Figure D-3: Fiber-Optic Media Converter
1
2
3
To
Controller
2
1
Fiber optic
media converter
Twisted pair cable
with shielded
connectors
on both ends
Controller
Top View
To 10Base-FL
fiber optic hub or
media converter
Power
Error
Pri F Link
Pri C Link
Sec F Link
Sec C Link
Front
View
Side View
Bottom View
Pri
Sec
Pri
Rx
Pri
Tx
Sec
Rx
Sec
Tx
Notes:
1. Fiber Optic Media Converter may go in position 1, 2, or 3; but is shown mounted in position 2.
2. Fiber Optic cables connect transmit to receive and receive to transmit.
Twisted pair cable
with shielded
connectors
on both ends
Related information
Control Network Specifications
Straight-Through Cable Pin Outs
Environmental Specifications for the DeltaV System
DeltaV Controllers and the Remote Interface Unit
April 2021
D800001X312
318

--- Page 319 ---

E
System Power Supply Specifications
This appendix provides specifications for the system power supplies:
• System Power Supply (AC/DC)
• System Power Supply (Dual DC/DC)
• Intrinsically Safe System Power Supply
E.1
System Power Supply (AC/DC)
Specifications
Table E-1: System Power Supply (AC/DC) Specifications
Item
Specification
Input
100 VAC to 264 VAC, 47 Hz to 63 Hz, single-
phase
Inrush (soft start)
230 VAC input at 35 A peak maximum for one
cycle or less
Output power
25 W total at 60°C
Output voltages (25 W maximum)
•
+12 VDC at 2.1 A maximum
•
+5 VDC at 2.0 A maximum
•
+3.3 VDC at 0.5 A maximum
Combined 5 VDC and 3.3 VDC output = 10 W
maximum
Input protection
Internally fused, non-replaceable fuses
Overvoltage protection
Output protected at 110% to 120%
Hold-up time
Output remains within 5% of nominal at full load
and 115 VAC input for 20 ms.
Mounting
On either slot of 2-wide power/controller carrier
External connectors:
Primary power
AC input, 3-wire
Alarm contacts
2-wire normally open relays; relays are closed
when outputs are within ±4% of nominal; 30
VDC at 2.0 A, 250 VAC at 2.0 A
System Power Supply Specifications
D800001X312 
April 2021
319

--- Page 320 ---

Dimensions
Figure E-1: System Power Supply (AC/DC) Dimensions
Note
Ground connection is not required for the secondary 2-wide power/controller carrier.
System Power Supply Specifications
April 2021
D800001X312
320

--- Page 321 ---

Redundant Connections
Figure E-2: Redundant AC Input Power for System Power Supply (AC/DC)
Isolated
Bus
DC Ground
Chassis
Ground
Enclosure PE Ground Lug
Enclosure Door
Adjacent Enclosure
To DIG
To DIG
AC
Power
Error
Active
Standby
Power
Error
Power
Error
Active
Standby
Power
Error
Fieldbus H1
Interface
Controller
MD Plus
AC/DC
Power Supply
Controller
MD Plus
AC/DC
Power Supply
Power
Error
Active
Standby
Fieldbus H1
Interface
Power
Error
Active
Standby
AI Card
4-20mA
HART
Series 2
Power
Error
Ch. 1
Ch. 2
Ch. 3
Ch. 4
Ch. 5
Ch. 6
Ch. 7
Ch. 8
AO Card
4-20mA
Series 2
Power
Error
Ch. 1
Ch. 2
Ch. 3
Ch. 4
Ch. 5
Ch. 6
Ch. 7
Ch. 8
DI Card
24 VDC
Isolated
Series 2
Power
Error
Ch. 1
Ch. 2
Ch. 3
Ch. 4
Ch. 5
Ch. 6
Ch. 7
Ch. 8
DO Card
24 VDC
Isolated 
Series 2
Power
Error
Ch. 1
Ch. 2
Ch. 3
Ch. 4
Ch. 5
Ch. 6
Ch. 7
Ch. 8
Profibus
DP
Power/Active
Error
Port 1
Series 2 Plus
DeviceNet
Power/Active
Error
Port 1
Series 2
E.2
System Power Supply (Dual DC/DC)
Specifications
Table E-2: System Power Supply (Dual DC/DC) Specifications 
Item
Specifications
Model Number
KJ1501X1-BC1
Model Number
KJ1501X1-BC2
Model Number
KJ1501X1-BC3
Input
•
12 VDC (±5%) at 14.8
A
•
24 VDC (±5%) at 4.0
A
•
12 VDC (±5%) at 14.8
A
•
24 VDC (-15%-+20%)
at 4.0 A
•
12 VDC (-4/+5%) at
14.8 A
•
24 VDC ±20% at 6.1
A
System Power Supply Specifications
D800001X312 
April 2021
321

--- Page 322 ---

Table E-2: System Power Supply (Dual DC/DC) Specifications (continued)
Item
Specifications
Model Number
KJ1501X1-BC1
Model Number
KJ1501X1-BC2
Model Number
KJ1501X1-BC3
Output power
rating -20 to 60°C
•
+12 VDC at 13.0 A
(12 VDC input)
•
+12 VDC at 4.5 A (24
VDC input)
•
+5.1 VDC at 2.0 A
•
+3.4 VDC at 2.0 A
(10.2 W total from +5.1
VDC and +3.4 VDC)
N/A
N/A
Output power
rating -40 to 60°C
N/A
•
+12 VDC at 13.0 A
(12 VDC input)
•
+12 VDC at 4.5 A (24
VDC input)
•
+5.1 VDC at 2.0 A
•
+3.4 VDC at 2.0 A
(10.2 W total from +5.1
VDC and +3.4 VDC)
•
+12 VDC at 13.0 A
(12 VDC input)
•
+12 VDC at 8.0 A (24
VDC input)
•
+5.1 VDC at 2.0 A
•
+3.4 VDC at 2.0 A
(10.2 W total from +5.1
VDC and +3.4 VDC)
Output power
rating 60 to 70°C
N/A
•
+12 VDC at 10. 0 A
(12 VDC input)
•
+12 VDC at 3.0 A (24
VDC input)
•
+5.1 VDC at 2.0 A
•
+3.4 VDC at 2.0 A
(10.2 W total from +5.1
VDC and +3.4 VDC)
•
+12 VDC at 10.0 A
(12 VDC input)
•
+12 VDC at 6.0 A (24
VDC input)
•
+5.1 VDC at 2.0 A
•
+3.4 VDC at 2.0 A
(10.2 W total from +5.1
VDC and +3.4 VDC)
Inrush (soft start)
•
12 A peak maximum for 5 ms over the 12 VDC input range (excluding 12
VDC output)
•
20 A peak maximum for 5 ms over the 24 VDC input range (including 12
VDC outputs)
Input protection
Internally fused, non-replaceable fuses
Overvoltage
protection
Output protected at 110% to 120%
Hold-up time
Output remains within 5% of nominal at full load and minimum input voltage
for 5 ms (excluding 12 VDC current with 12 VDC input)
Mounting
On either slot of the 2-wide power/controller carrier
System Power Supply Specifications
April 2021
D800001X312
322

--- Page 323 ---

Table E-2: System Power Supply (Dual DC/DC) Specifications (continued)
Item
Specifications
Model Number
KJ1501X1-BC1
Model Number
KJ1501X1-BC2
Model Number
KJ1501X1-BC3
External
connectors
•
Primary power: DC input, 2-wire
•
Alarm contacts: 2-wire normally open relays; relays are closed when 3.3
and 5 VDC outputs are within ±4% of nominal
•
Alarm relay contact rating: 30 VDC at 2.0 A; 250 VAC at 2.0 A
Dimensions
Figure E-3: System Power Supply (Dual DC/DC) Dimensions
Warning
Always remove input power to the supply before connecting or disconnecting the input
power connection. The connector should not interrupt current flow and could be
damaged if actuated under a load condition.
System Power Supply Specifications
D800001X312 
April 2021
323

--- Page 324 ---

E.3
Intrinsically Safe System Power Supply
Specifications
Table E-3: I.S. System Power Supply Specifications
Item
Specification
Input
18.5 to 36 VDC (24 VDC nominal)
Output
12 VDC ±5%
Output current
5 A
Input to output isolation
250 VAC rms
Holdup time
1.8 ms
Input protection
Internally fused, non-replaceable fuses
Over voltage protection
110% to 120%
Input power
80 Watts
Mounting
I.S. Power Supply Carrier
External connectors
DC input 2-part screw terminal
Dimensions
Figure E-4: I.S. System Power Supply Dimensions
System Power Supply Specifications
April 2021
D800001X312
324

--- Page 325 ---

F
Workstation and Monitor
Specifications
This section provides information on DeltaV workstations, Multiple Monitors, and Touch
Screens. Refer to the following sources for current DeltaV Workstation configuration
details and for current Ethernet card specifications:
• DeltaV Workstation Product Data Sheets
• The PC manufacturer’s (Dell Computer Corporation) specifications
• Your local Emerson Representative
F.1
Primary and Secondary Channel Ethernet Card
Specifications - Plant LAN Interface Card
The DeltaV system uses Ethernet to create the DeltaV Control Network, both primary and
secondary channels. All network cards used in DeltaV Workstations must be 10/100BaseT
Ethernet network cards.
F.2
Multiple Monitors
The DeltaV system can support up to four monitors that work together like one large
screen and are driven by the same workstation. Multiple monitors can be laid out in a
horizontal orientation (1x2, 1x3, 1x4) or a square orientation (2x2). Other monitor
arrangements are not supported. Refer to the video card manufacturer’s documentation
for information on how to install the video cards and remove any existing video cards. The
NEC MultiSync LCD 2080UX+ is approved for use in a multiple monitor system. Refer to
Books Online for information on installing the driver and video card and setting up the
video card for multiple monitors.
F.3
Touch Screens
Touch screens can be used on single monitors and on multiple monitors.Connect a cable
from any USB connector on the back of the workstation to a touch screen monitor in any
order or sequence. The NEC MultiSync LCD 2080UX with integrated capacitive
touchscreen is approved for use with the DeltaV system. After connecting the touch
screen monitors, refer to the 3M TouchWare™ Software for Windows User Guide for
complete information on calibrating and configuring the touch screens
Workstation and Monitor Specifications
D800001X312 
April 2021
325

--- Page 326 ---

Workstation and Monitor Specifications
April 2021
D800001X312
326