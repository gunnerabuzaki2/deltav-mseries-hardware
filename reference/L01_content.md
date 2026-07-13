--- Page 15 ---

1
Overview
This chapter provides general information on the DeltaV system hardware. Refer to the
appendices for specifications and guidelines.
1.1
The DeltaV System
The DeltaV automation system consists of the following components:
• One or more I/O subsystems that process information from field devices
• One or more controllers that perform local control and manage data and
communications between the I/O subsystem and the Control Network
• Power supplies
• One or more workstations that provide a graphical user interface to the process
• A Control Network that provides communication between system nodes
Figure 1-1 shows an overview diagram of the DeltaV system.
Figure 1-1: DeltaV System Overview Diagram
1.2
DeltaV System Equipment
The DeltaV system uses DIN rail-mounted interconnecting carriers and components that
are designed for installation in an enclosure. The carriers provide power and
communication connections. The I/O subsystem and the controllers are modular; they
simply plug onto the carriers for installation. DeltaV system equipment consists of:
Overview
D800001X312 
April 2021
15

--- Page 16 ---

• Power Controller Carriers and I/O Interface Carriers that mount horizontally or
vertically on DIN rails. The number in the carrier name (such as 8-wide I/O interface
carrier) refers to the number of slots available for connecting the equipment to the
carrier.
• LocalBus that consists of an internal power bus on the Power Controller Carrier, busses
on the associated I/O interface carriers, and connecting cables. The LocalBus supplies
power to the controller and the I/O subsystem and provides communications
connections between cards. System power (12 VDC) can be shared along the length of
the LocalBus. The length of the LocalBus, including all cabling, cannot exceed 6.5 m
(21.3 ft.). The LocalBus at this length can support eight, 8-wide carriers; two, 2-wide
carriers; and, three carrier extenders. The length requirement is the same for vertically
mounted systems.
Figure 1-2: LocalBus
• DeltaV I/O subsystem that includes I/O terminal blocks and I/O cards. Terminal blocks
snap onto the I/O interface carrier to provide screw terminations for field wiring. I/O
cards snap over the I/O terminal block on the carrier and convert field signals to a
digital format for control and communications. You can install the I/O terminal blocks
and connect field wiring before installing the other devices, thus reducing installation
and maintenance costs. Many of the DeltaV Series 2 cards support redundancy. Series
2, redundant capable cards are configured, autosensed, upgraded, and operated just
like the pre-Series 2 cards. Series 2 simplex cards can function as drop-in replacements
for pre-Series 2 simplex cards of the same type.
• DeltaV Controller that performs local control and manages communication between
the I/O subsystem and the Control Network. It mounts on the right slot of the 2-wide
Power Controller carrier for horizontal installations and to the right of a power supply
Overview
April 2021
D800001X312
16

--- Page 17 ---

on the 4-wide Power Controller carrier for vertical installations for M-series carriers. You
can add an additional controller for controller redundancy.
• DeltaV system power. The DeltaV system supports a system power supply (AC/DC)
and a system power supply (Dual DC/DC) as well as an Intrinsically Safe system power
supply.
• DeltaV Workstations that provide graphical user interfaces to help you configure your
system, perform extensive diagnostic checks, operate your process, and gather
reporting and historical data. The DeltaV System Identifier, shipped in your License
Pack, is a connector that plugs into the Universal Serial Bus (USB) on your
ProfessionalPLUS workstation. It gives each DeltaV system a unique identification that
allows you to install or download changes to the system. The system identifier is not
required for the system to continue running or to restart the system after it has been
running.
• Bulk power supplies supply power to the system or to field devices. Power to the
system is isolated from power to field devices.
Related information
I/O Cards
System Power Guidelines
Workstation and Monitor Specifications
DeltaV Controllers and the Remote Interface Unit
DeltaV Legacy Bulk Power Supplies
1.2.1
DeltaV Control Network
The Control Network is an isolated Ethernet local area network (LAN) that provides
communication between the controllers and workstations. It uses standard Ethernet hubs
and switches for communications connections. An optional 10Base-T/100Base-TX switch
can be added for networks with more than 20 controllers and 32 nodes.
The Control Network is dedicated to the DeltaV system. A separate Ethernet interface is
provided via the DeltaV ProfessionalPLUS and Application Station to connect the DeltaV
system to a plant-wide LAN. The primary way to connect a plant LAN to the DeltaV system
is through either or both the ProfessionalPLUS and Application station. The only way to run
non-DeltaV applications (other than Microsoft Excel) is through a DeltaV Application
Station.
 CAUTION
Connecting unapproved non-DeltaV equipment to the DeltaV Control Network can cause
unpredictable operation of the system.
The DeltaV Control Network has been designed to be redundant for communications
reliability. The Control Network is composed of Primary and Secondary communication
channels that are implemented with separate Ethernet NIC cards as well as separate
network hubs and switches for each channel.
Note
Care must be taken when designing your network to not have large amounts of network
traffic running through the area control network across switches which are also used for
Overview
D800001X312 
April 2021
17

--- Page 18 ---

control (for example, controllers and CIOCs). Failing to do so can result in the control
integrity being compromised causing ACN switchovers and device dropouts.
Standard Category 5(e) Screened Twisted Pair (ScTP) cable must be used for Control
Networks with distances of up to 100 meters (328 feet) between Ethernet ports. Refer to
“Ethernet Cable Specifications and Installation Rules” for cable specifications. For
distances of up 2 kilometers (6562 feet) between Ethernet ports, 19 inch rack-mounted
switches with a fiber-optic interface or small form factor switches with fiber-optic ports
can be used. Refer to “DeltaV Fiber Switches” for information on a small form factor switch
with fiber-optic ports. Be sure to specify the fiber-optic option when ordering the 19 inch
rack-mounted switch. Also, fiber-optic communication channels are preferable when:
• Possible electromagnetic noise interference might exist and standard cable does not
provide sufficient protection.
• Ground isolation and protection from near lightning strikes are required for building to
building communication links.
The following sections contain network diagrams that provide an overview of possible
network configurations for DeltaV systems. Refer to Control Network Specifications for
detailed installation diagrams and instructions including requirements for Ethernet shield
orientations, rules for connecting switches in cascade and star topologies, identification of
fiber-optic and twisted pair cable connectors, switch configuration, and other important
installation requirements.
If your DeltaV system consists of one workstation and one controller only, you can connect
the DeltaV network without using a hub. The cable must be routed directly from the
workstation to the controller. Figure 1-3 shows an example of a no hub system. Refer to
Control Network Specifications for the cable pinouts in a no hub system.
Figure 1-3: No Hub System Example
Note
The no-hub cable is for systems with no Control Network Hub. Its wiring is different from
that of the standard Ethernet cables used with DeltaV Control Network Hubs.
Overview
April 2021
D800001X312
18

--- Page 19 ---

Figure 1-4: Control Network Example (2 nodes)
Figure 1-5: Control Network Example (8 nodes)
Related information
Control Network Specifications
Ethernet Cable Specifications and Installation Rules
DeltaV Fiber Switches
Overview
D800001X312 
April 2021
19

--- Page 20 ---

1.2.2
DeltaV Remote Network
The DeltaV Remote Network is an Ethernet 10/100BaseT local area network (LAN) that
provides communications between remote workstations and the DeltaV system. The
DeltaV Remote Network can be a dedicated LAN that contains only DeltaV remote
workstations, or it can be the plant-wide LAN that contains other personal computers or
ethernet devices such as printers. A DeltaV Remote Network uses one or more Ethernet
switches for communications connections. A router must be used to minimize network
traffic between the plant-wide LAN and the DeltaV system.
The DeltaV Remote Network is connected to the DeltaV system through a DeltaV
Application Station or the ProfessionalPLUS workstation running DeltaV Remote Access
Services (RAS) server. To support the engineering applications and the DeltaV Guardian
application on remote workstations and to upload displays from any workstation, the
remote network must also be connected to the ProfessionalPLUS workstation. To support
accessing batch data or to control batches from any workstation, the remote network
must also be connected to the Application station.
Note
The Application Station and ProfessionalPLUS nodes are not automatically designated as
remote servers during the installation process. If you enable remote network redundancy
for your remote nodes when you configure the workstation in DeltaV Explorer, you must
also enable remote network redundancy (in DeltaV Explorer) for the ProfessionalPLUS and
any of the Application Station nodes that are connected to the remote network. If remote
network redundancy is not enabled, you will be unable to view the data remotely if the
Primary network connection is lost.
The DeltaV Remote Network can be simplex or redundant. Additional Ethernet interface
cards, separate from the control network interfaces, can be added to the Application
Station and ProfessionalPLUS workstations to support the DeltaV Remote Network.
The wiring and installation for the remote network should follow the same guidelines as
the control network.
The remote network is also designed to support various network connectivity options,
such as Microwave or leased line type connections as well as standard direct LAN
connections. When using a slow network link option, remote workstations can be
connected through a Remote Application Station. The Remote Application Station is
connected through an Application Station on the DeltaV Control Network. This type of
connection increases communication performance through the slow network link.
There are many possible remote network layouts for various system sizes and connection
options. Figure 1-6 shows a remote network dedicated to the DeltaV system. Both the
Application Station and the ProfessionalPLUS workstation are functioning as RAS servers.
Overview
April 2021
D800001X312
20

--- Page 21 ---

Figure 1-6: Dedicated Remote Network
Remote operator station
Remote operator station
Remote operator station
Pro Plus
Operator
station
Operator
station
App station
Cisco 2950
twisted pair switch
Cisco 2950
twisted pair switch
Cisco 2950
twisted pair switch
Cisco 2950
twisted pair switch
Primary
remote
network
Secondary
control
network
Secondary
remote
network
Primary
control
network
Figure 1-7 shows the use of a router to minimize network traffic between the DeltaV
system and a remote plant LAN. Both the Application Station and the ProfessionalPLUS
workstation are functioning as RAS servers.
Overview
D800001X312 
April 2021
21

--- Page 22 ---

Figure 1-7: Remote Plant-Wide LAN Connected to a DeltaV System
Remote
operator
station
Remote
operator
station
Pro Plus
Operator
station
Operator
station
App station
Cisco 2950
twisted pair switch
Cisco 2950
twisted pair switch
Router
Plant LAN
Secondary
control network
Primary
control
network
Cisco 2950
twisted pair switch
Cisco 2950
twisted pair switch
Related information
Control Network Specifications
Wiring Guidelines
Overview
April 2021
D800001X312
22