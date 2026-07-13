--- Page 44 ---

Note
The alarm relay contact is closed during normal operation. The alarm relay is shown
open (unpowered condition) in the following figure.
3. Align the system power supply with the connector on the 2-wide power/controller
carrier and push to attach, as shown in the following figure. Tighten the mounting
screw.
Figure 2-18: System Power Supply Installation
Related information
DeltaV Vertical Carriers
System Power Supply Specifications
Power Guidelines
2.5.11
DeltaV hardware ready for transportation
If you have performed the installation as described in this document, including mounting
the hardware in an enclosure as described, the hardware is ready for transportation.
Additional preparation measures are not recommended and may damage the hardware.
2.5.12
Installing the DeltaV Workstation
To install the DeltaV Workstation, connect the workstation components, install the DeltaV
System Identifier (one per system), install the printer (if used), and install the UPS (if used).
Connect the workstation and its associated peripherals to one power distribution and
system ground.
After hardware installation, refer to the DeltaV media pack installation pamphlet for
information on installing DeltaV software on the workstation.
Installing Your DeltaV System
April 2021
D800001X312
44

--- Page 45 ---

To install the workstation
1. Follow the instructions supplied with your workstation to connect the monitor,
keyboard, and mouse to the central processing unit (CPU). Refer to the
documentation supplied with your workstation for details on the I/O ports
2. If the DeltaV label is not installed on your workstation monitor, apply it to the lower
right corner of the monitor faceplate.
3. Install the system identifier on the Universal Serial Bus (USB).
Figure 2-19: Workstation Installation
4. Refer to the documentation supplied with your printer for hardware installation
information.
2.5.13
Setting up the DeltaV Control Network
The standard Control Network is an isolated Ethernet local area network (LAN) that
provides communication between the controllers and workstations. It uses one or more
Ethernet hubs or switches for communications connections. The Control Network is
dedicated to the DeltaV system; no other devices can be attached. A separate Ethernet
interface is provided through the DeltaV Application Station or ProfessionalPLUS to
connect the DeltaV system to a plant-wide LAN. To minimize the traffic on the plant-wide
LAN, configure a router to filter the IP addresses. Refer to the DeltaV Books Online for
more information on configuring a router.
This section provides basic hub installation examples and includes cable-specific
information and requirements for installing the Control Network. The "Control Network
Specifications" section provides details on cable shield orientations and contains diagrams
that show switches connected in cascade and star topologies, fiber-optic and twisted pair
cable connections, and switch configuration.
To set up the Control Network, install the hub and connect network communication
cables between nodes (controllers and workstations). The hubs can stand alone or can be
linked (cascaded) to other hubs. Each hub is equivalent to a single IEEE 802.3 repeater (1
hop). The number of hops that are allowed and the maximum distance between each hop
varies with the type of hub and whether the link is 10Mbit or 100Mbit. 10Mbit links allow
four hops and 100Mbit links allow two hops.
Installing Your DeltaV System
D800001X312 
April 2021
45

--- Page 46 ---

If your DeltaV system consists of one workstation and one controller only, you can connect
the DeltaV network without using a hub. The cable must be routed directly from the
workstation to the controller. Figure 2-20 shows an example of a no hub system.
Figure 2-20: No Hub System Example
Note
No-hub cable, also called crossover cable, is for systems with no Control Network Hub. Its
wiring is different from that of the straight-through Ethernet cables used with DeltaV
Control Network Hubs.
Related information
Control Network Specifications
Control Network Installation Requirements
The Control Network installer must ensure that the following requirements are met:
• All Cat5-Twisted Pair (TP) and fiber-optic cables should be made, installed, and tested
by an experienced LAN installer.
• A DeltaV system can have a maximum of four repeater hops on the Control Network (a
maximum of four hubs can be linked together in series). 10Mbit networks allow four
repeater hops and 100Mbit networks allow two repeater hops.
• For Cat5 TP cables be sure that:
— All cables are made from screened Category 5 cable with a maximum length of 100
m (328 ft) and an insulated conductor diameter of 0.89 to 0.99 mm (0.035 to 0.040
in).
— Straight-through cables are terminated with RJ45 connectors to EIA/TIA 568B pin-
outs at both ends.
— Crossover cables are terminated with RJ45 connectors to 568B pinouts on one end
and 568A pinouts on the opposite end.
— Cables used to cascade hubs and switches have an unshielded connector on one
end and a shielded connector on the opposite end.
— Unshielded RJ45 connectors are used at all workstation connections.
— Shielded RJ45 connectors are used at all controller connections and all hub and
switch connections to nodes.
— All cables are tested with the Microtest PentaScannerTM testing tool.
— Ethernet wall outlets, punchdown blocks, and patch panels are not supported.
Installing Your DeltaV System
April 2021
D800001X312
46

--- Page 47 ---

Fiber-Optic Cables
For fiber-optic cables, use the cable and connector type specified by the equipment
manufacturer for the fiber-optic ports on their equipment. The type of fiber-optic cable
required could be multimode or single-mode and depends on the equipment's port
specifications, the site's physical layout, and the distance between fiber-optic ports from
device to device. The equipment manufacturer also specifies a fiber-optic loss budget. The
acceptable loss per kilometer for the fiber-optic cable can be determined from the loss
budget so that the overall cable loss does not exceed the equipment’s loss budget. The
loss budget must include all fiber-optic splices and fiber-optic connector losses from end
to end. The following list provides some guidelines for using fiber-optic cable:
• A multimode fiber-optic cable is generally used for 100MB/S 100BASE-FX fiber-optic
communications for up to 2 Kilometers and either 50/125 micron or 62.5/125 micron
multimode fiber can be used depending upon the equipment manufacturer’s
specification for the fiber-optic ports. Refer to the manufacturer's specifications for
cable type and loss budget.
• A single-mode fiber-optic cable is generally used for 1000MB/S 1000BASE-LX/LH
(gigabit) fiber-optic communications for distances beyond 2 Kilometers and 9/125
micron single-mode fiber can be used depending upon the equipment manufacturer’s
specification for the fiber-optic ports. Refer to the manufacturer's specifications for
cable type and loss budget.
• A multimode fiber-optic cable is generally used for 1000MB/S 1000BASE-SX (gigabit)
fiber-optic communications for distances up to approximately 500 meters and 50/125
micron or 62.5/125 micron multimode fiber can be used depending upon the
equipment manufacturer’s specification for the fiber-optic ports. Refer to the
manufacturer's specifications for cable type and loss budget.
• Multimode fiber-optic cable has a Modal Bandwidth specification (MHz/km) which is a
distance limiting factor for gigabit communications on multimode fiber. Refer to the
manufacturer's specifications for distances supported for gigabit communications over
multimode fiber.
• Fiber-optic cables are terminated with ST, SC, MTRJ, or LC connectors depending upon
the physical port that is used on the fiber-optic device. Refer to the manufacturer's
specifications for the fiber-optic port type used on their equipment.
• All fiber-optic links should be tested for attenuation (light loss) with an optical power
meter. The entire link, including all assembled cables, connectors and splices from end
to end should be measured. This measurement should not exceed the equipment
manufacturer's loss budget specification and at least a 3dB margin should be left.
 CAUTION
Substandard cables can create serious communication problems. Make sure all cables
meet the specifications listed in the "Control Network Specifications" section.
Related information
Building Twisted Pair Cable Assemblies
Installing Your DeltaV System
D800001X312 
April 2021
47

--- Page 48 ---

Install the Control Network Cables
1. Make and test the required Control Network cables. See the section, "Control
Network Specifications" for cable guidelines and specifications. Select the
appropriate cable type on the cable test tool and follow the detailed instructions in
the test tool’s manual.
You must connect the test equipment to both ends of the cable to test it properly.
The testing tool checks each cable based on its type and issues a Pass or Fail
reading. Make sure the cable passes each test. The tests supported by the Microtest
PentaScanner testing tool include the following:
• Cable mapping
• Length
• Crosstalk
• Attenuation
• Attenuation-to-crosstalk ratio
• Impedance
• Loop resistance
• Capacitance
 CAUTION
Substandard cables can create serious communication problems. Make sure all
cables meet the specifications listed in the "Control Network Specifications" section.
2. If you have a simplex Control Network, connect the unshielded end of a network
cable to the twisted pair port on the primary Network Interface Card (NIC) and
connect the shielded end of the cable to the primary hub as shown in the following
figure.
Figure 2-21: Simplex Control Network Cable Connections
Shielded 
connector
Unshielded
connector
Installing Your DeltaV System
April 2021
D800001X312
48

--- Page 49 ---

Note
For hub-to-hub connections, one end of the cable must have unshielded
connectors.
For redundant Control Networks, be sure to verify the NIC binding order to
differentiate between the primary and secondary NICs.
3. If you have a redundant Control Network, connect the unshielded end of a network
cable to the twisted pair port on the workstation’s primary NIC and connect the
shielded end of the cable to the primary hub as shown in Figure 2-22. Connect
another cable from the twisted pair port on the workstation’s secondary NIC to the
secondary hub. It is helpful to identify the Control Network cables with color-coded
boots. Emerson recommends the following conventions: a yellow color-coded boot
for the primary Control Network cable and a black color-coded boot for the
secondary Control Network cable.
Note
Make sure you are consistent in your primary and secondary network connections
so they are not crosswired.
Figure 2-22: Redundant Control Network Cable Connections
Shielded 
connector
Primary switch
Secondary switch
Primary NIC
Secondary NIC
unshielded connector
Shielded connector
unshielded 
connector
Note
For hub-to-hub connections, one end of the cable must have unshielded connectors
4. Connect network cables from the hub(s) to the RJ45 connectors on the bottom of
each controller. The front connector is for the primary Control Network and the rear
connector is for the secondary Control Network. Refer to the following figure to
locate the connectors.
Installing Your DeltaV System
D800001X312 
April 2021
49

--- Page 50 ---

Figure 2-23: Control Network Cable Connections for a Simplex Controller
Primary
Secondary
Shielded connectors
Connecting the Control Network to a Plant LAN
A plant LAN can be connected to the DeltaV system through the third Network Interface
Card (NIC) on the Application Station to provide a gateway between the DeltaV Control
Network and other networks. It is highly recommended that you use a firewall such as the
Emerson Smart Firewall to protect the DeltaV network from potential security issues and
to help ensure reliable operations.
To improve the security of the DeltaV system, Emerson recommends that you do not
connect the DeltaV Professional, Operator, and Base workstations to a plant LAN or
gateway. Because the engineering database is on the ProfessionalPLUS station and should
be protected from possible unauthorized external access, Emerson also recommends that
you do not connect the ProfessionalPLUS station to the plant LAN.
The following image shows the recommended network architecture.
Installing Your DeltaV System
April 2021
D800001X312
50

--- Page 51 ---

Figure 2-24: Connecting DeltaV to other networks
DeltaV Smart Switch
DeltaV Smart Switch
DeltaV Smart Switch
Firewall
Firewall
Firewall
Switch
Switch
Switch
Switch
Switch
DeltaV Smart Switch
DeltaV Smart Switch
DeltaV 
Controller 
Firewall
DeltaV 
Controller 
Firewall
DeltaV Smart Switch
DeltaV
Workstations
Host
DeltaV Remote 
Workstations
DeltaV 
Remote Remote 
Workstations
DeltaV Smart Switch
Thin Clients
Field Devices
Field Devices
Field Devices
S-Series 
DeltaV
Controller
M-Series 
DeltaV
Controller
S-Series 
DeltaV
CIOC
Controller
Level 2
DeltaV ACN
Level 2.5
Level 3
Remote Remote Network
Remote Network
Thin Client
Network
Level 1
DeltaV Virtual
Workstations
DeltaV
Smart Switch
optional
Optional, but must 
design systems using 
CIOCs to add this later.
DeltaV
Smart Switch
optional
Emerson
Smart Firewall
recommended
Gigabit
recommended
P-Series 
DeltaV
Controller
Field Devices
2.5.14
Connecting Power to the System
A bulk power supply converts AC or DC power to the power required for the system power
supply and, optionally, for field devices. The method of connecting power to the DeltaV
system depends on your existing power supply, power distribution scheme, and
grounding techniques. Refer to the DeltaV Power and Grounding manual for recommended
power and grounding techniques for a DeltaV system.
The following images show the connections for a Legacy simplex bulk power supply. Refer
to Appendix H for Legacy bulk power supply specifications and dimensions.
Installing Your DeltaV System
D800001X312 
April 2021
51

--- Page 52 ---

Figure 2-25: Simplex Power and Ground Wiring Diagram for Legacy Bulk AC to 12 or
24 VDC Power Supply
G N
L
G N
L
12 VDC or 24 VDC
DC Return (Ground)
Isolated
Common
Ground
Reference
Wire and Connector Legend
A  G Ground (AC)
B  N Neutral (AC)
C  L Line (AC)
Dedicated
Plant Ground
Grid Point
AC Connector
Optional Isolation Transformer
Bulk AC Power
Distribution/UPS
Bulk AC to 12 VDC
or Bulk AC to 24 VDC
Power Supply
L
N
G
Wired to plant power source
Installing Your DeltaV System
April 2021
D800001X312
52

--- Page 53 ---

Figure 2-26: Simplex Power and Ground Wiring Diagram for Legacy Bulk 24 VDC to 12
VDC Power Supply
(-)
(-)
(+)
(-)
(+)
(+)
(-)
(+)
DC Power
Distribution
Bulk 24 VDC to 12 VDC
Power Supply
Dedicated Plant
Ground Grid Point
24 VDC
DC Return Ground
12 VDC
Power Return
Hard Wired to
Plant Power Supply
Isolated
Common
Ground
Reference
Related information
DeltaV Legacy Bulk Power Supplies
System Power Guidelines
Legacy Panel-Mounted Bulk AC to 24 VDC and Bulk AC to 12 VDC
2.5.15
Setting Up the DeltaV Remote Network
Refer to “DeltaV Remote Network” for overview information and to "Control Network
Specifications" for detailed installation information. To set up the Remote Network, install
the switches for the remote network connections and connect the network
communications cables between the remote workstations and the DeltaV RAS
Applications Stations and ProfessionalPLUS workstation.
Users must assign their own PC names and IP addresses to the remote workstations before
installing DeltaV software. If the remote workstation is already on the plant-wide LAN, it
has been assigned a name and IP address that can be used for communications with the
DeltaV system. If you are building a dedicated DeltaV Remote Network, then workstation
node names and IP addresses must be assigned before the workstations are set up in the
DeltaV Explorer. These assigned node names must be used as the workstation names in
Installing Your DeltaV System
D800001X312 
April 2021
53

--- Page 54 ---

the DeltaV Explorer. Refer to the online help for the DeltaV Workstation Configuration
application for information.
Note
If the IP address of either the Remote Network or the DeltaV ACN should change, you
must run Workstation Configuration on all workstations involved in this order:
1. ProfessionalPLUS (only if a download is indicated)
2. The RAS node
3. The Remote Workstations
The cable installation requirements for the DeltaV Remote Network are the same as the
installation requirements for the DeltaV Control Network. Refer to “Control Network
Installation Requirements” for cable requirements and to "Control Network Specifications"
for detailed installation information.
Related information
Control Network Specifications
Control Network Installation Requirements
DeltaV Remote Network
2.5.16
Setting Up a Network Time Server
DeltaV supports GPS Network Time Server equipment. Consult with your Emerson
representative or sales office for current GPS specifications and requirements for use with
DeltaV systems. Refer to the documentation for the GPS network time server for
installation and configuration information. Refer to the next section for the specific
network settings that are required for configuring a GPS network time server for use with a
DeltaV system.
After establishing a serial connection between the setup computer and the GPS network
time server, configure the network and timing parameters. Use the IP addresses and
subnet mask described in the following sections.
IP Addresses
The DeltaV system supports both a primary and an optional backup Network Time Server
on the control network. The Network Time Servers can be attached to either the primary
or the secondary control network. It is recommended that the primary Network Time
Server be attached to the primary control network and the backup Network Time Server
be attached to the secondary control network in a redundant control network system. If
the system is simplex (has only a primary control network) attach both Network Time
Servers to the primary control network.
For the primary Network Time Server use the following IP addresses:
• 10.4.128.1 (for attaching to the primary control network)
• 10.8.128.1 (for attaching to the secondary control network)
For the backup Network Time Server use the following IP addresses:
• 10.4.128.2 (for attaching to the primary control network)
Installing Your DeltaV System
April 2021
D800001X312
54

--- Page 55 ---

• 10.8.128.2 (for attaching to the secondary control network)
The DeltaV system also supports both a primary and backup Network Time Server on the
DeltaV Remote Network. If you are attaching a Network Time Server to a DeltaV Remote
Network, the IP address is not predefined in the DeltaV system. Your network
administrator must assign the Network Time Server a valid IP address for the remote
network segment and this address must be used in the Remote Network properties dialog
box in the DeltaV Explorer.
Subnet Mask
The subnet mask for the Network Time Servers attached to the control network is:
• 255.254.0.0
The subnet mask for the Network Time Servers attached to the remote network(s) must
be assigned by your network administrator.
The route (default gateway for the devices on a different subnet) is not required.
Installing Your DeltaV System
D800001X312 
April 2021
55

--- Page 56 ---

Installing Your DeltaV System
April 2021
D800001X312
56