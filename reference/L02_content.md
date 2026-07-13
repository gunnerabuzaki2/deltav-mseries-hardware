--- Page 23 ---

2
Installing Your DeltaV System
This chapter provides detailed instructions and diagrams for system installation. It
includes recommendations for planning the installation and provides a brief overview of
the steps required for system installation.
This chapter describes installations that are mounted vertically on horizontal carriers.
For Class I Division 2 installations, refer to the document DeltaV Scalable Process System,
Class I Division 2 Installation Instructions, (12P1293) on the DeltaV Documentation Library
DVD.
For Zone 2 installations, refer to the document DeltaV Scalable Process System, Zone 2
Installation Instructions, (12P2046) on the DeltaV Documentation Library DVD.
For NAMUR NE 21 installations, refer to the document DeltaV Digital Automation System
Namur NE 21 Installation Instructions, (12P2822) on the DeltaV Documentation Library
DVD.
For Marine Certified DeltaV installations, refer to the following installation requirements.
These requirements allow the DeltaV system to support the reduced EMC interference
requirements at the Marine Navigation Frequencies. Marine certification is approved for
24 V powered systems only. For additional requirements and for a list of the specific
DeltaV equipment that is approved for marine installation, refer to the specific certifying
agency.
For all exposed deck locations:
• Install the DeltaV system in an IP66/NEMA 4 enclosure with EMC-reduction shielding
(15 dB minimum) such as the Stahl Series 8125/8126 enclosures. The Stahl Series
8125/8126 enclosures are Emerson Alliance Program products.
• The door of the enclosure must remain closed during normal operation. Opening the
door defeats EMC-reduction shielding and protection from electrostatic discharge.
Open the door only for maintenance and repair performed by certified, trained
personnel.
• Include an EMC power line filter such as a Tyco S series or equivalent on all DC input
leads at the DeltaV system's enclosure with the filter grounded at the enclosure.
For non-exposed deck locations:
• Install the DeltaV system in an enclosure suitable for your environment with EMC-
reduction shielding (15 dB minimum).
• The door of the enclosure must remain closed during normal operation. Opening the
door defeats EMC-reduction shielding and protection from electrostatic discharge.
Open the door only for maintenance and repair performed by certified, trained
personnel.
• Include an EMC power line filter such as a Tyco S Series or equivalent on all DC input
leads at the DeltaV system's enclosure with the filter grounded at the enclosure.
Note
All electrical installations must conform to applicable federal, state, and local codes and
regulations. All installation and maintenance procedures described in this document must
Installing Your DeltaV System
D800001X312 
April 2021
23

--- Page 24 ---

be performed by qualified personnel and all equipment must be used only for the
purposes described. If the equipment is used in a manner not specified, the protection
provided by the equipment may be impaired.
Related information
DeltaV Vertical Carriers
2.1
CE Statement
Note
This manual describes installation and maintenance procedures for products that have
been tested to be in compliance with appropriate CE directives. To maintain compliance,
these products must be installed and maintained according to the procedures described in
this document. Failure to follow the procedures may compromise compliance.
2.2
China RoHS
DeltaV products manufactured on or after 1 July 2016 and shipped by Emerson into China
will be China RoHS compliant. For more information, refer to the following URL:
http://www2.emersonprocess.com/en-US/brands/deltav/documentation/Pages/Product-
Certificates.aspx
2.3
Important Information about Hazardous Live
Voltages
Warning
The AC input and output I/O cards and carriers may have hazardous live voltages present
on the input or output terminals. These devices switch or sense the presence of 120 VAC
or 250 VAC field power. Ensure that proper safety precautions, such as de-energizing field
power, are observed during installation, maintenance, or any time wiring changes are
made to any of the following devices:
• KJ4001X1-BE1: 8-Wide I/O Interface Carrier
• KJ4002X1-BA1 and BB1: Left and Right 8-Wide Legacy Vertical Carriers
• KJ4003X1- BA1 and BB1: Left and Right VerticalPLUS Carriers
• KJ3207X1: Series 2 AC input Cards
• KJ3209X1 and KJ3210X1: Series 2 AC output cards
• KJ4001X1-CA1: I/O Terminal Block
• KJ4001X1-CB1: Fused I/O Terminal block
2.4
Installation Planning
The appendices in this manual contain reference information to help you plan system
installation.
Installing Your DeltaV System
April 2021
D800001X312
24

--- Page 25 ---

• Appendix A Environmental Specifications
• Appendix B Carrier Specifications
• Appendix C Interface Specifications
• Appendix D Controller Specifications
• Appendix E System Power Supply Specifications
• Appendix F Workstation and Server Specifications
• Appendix G Control Network Specifications
• Appendix H Bulk Power Supply Specifications
• Appendix I Enclosure and Power Dissipation Guidelines
• Appendix J System Power Guidelines
• Appendix K Bussed Field Power Guidelines
• Appendix L Controller Redundancy
• Appendix M DeltaV Vertical Carriers
• Appendix N Installation Worksheets
• Appendix O Intrinsically Safe I/O
2.4.1
Tools Required for Installation
You need the following tools to install a DeltaV system:
• Standard electrical tools (voltmeter, wire cutter, wire stripper, pliers, screwdriver)
• Standard installation tools (screwdrivers, drill with standard bits)
• Ethernet cable tools (crimper, cable tester)
Please see the workstation instructions for information on the tools needed to install the
workstation and its peripherals.
2.4.2
Site Preparation
Properly designed and installed power distribution, ground networks, and signal wiring are
part of site preparation and are extremely important for optimum DeltaV system
operation. Even the best control system can only perform as well as the electrical
foundation on which it is built. Clean input power, single-point grounding, and adequate
shielding from outside electrical interference are a must.
Power distribution, ground networks, and signal wiring should be installed before the
system is installed. Use the manual, DeltaV Power and Grounding, as your resource for
proper site preparation.
Note
Some images in this manual show bullet style wiring connections. This style is used for
reference only and splicing wires into wires to emulate bullet connections is never
recommended by Emerson. Always use terminal-to-terminal wiring.
Installing Your DeltaV System
D800001X312 
April 2021
25

--- Page 26 ---

2.4.3
Wiring Guidelines
The power and grounding terminals and field termination points on the I/O subsystem and
the system power supplies are designed to accept 2.5 mm2 (14 AWG) stranded or solid
wire. To select wire, calculate the maximum current limit expected for each wire. Local
electrical codes define the wire size required for a specific current.
Shielded twisted pair wiring is recommended for low-level signal wiring to reduce
susceptibility to noise. You can order an I/O carrier with a shield bar (to terminate the
shields from field wiring) or without a shield bar (where termination is not necessary).
2.4.4
Power Guidelines
The removable connectors on the System Power Supplies and legacy Bulk Power Supplies
are not designed to interrupt current flow in circuits under load and can be damaged if
used for this purpose. If you need to disconnect power, use a separate component such as
a knife blade fuse terminal block or breaker that is designed for this purpose. Multiple
manufacturers make knife blade fuse terminal blocks that provide a disconnect function
and fusing for the supply. If you use a fuse or breaker in the disconnect circuit, size it
appropriately for the load.
2.4.5
Torque Limits
When you install the DIN rails and DeltaV equipment, do not exceed the maximum torque
limits for the mounting screws.
Table 2-1: Maximum Torque Limits on Mounting Screws
Item
Torque Limit on Mounting Screw(s)
Bulk power supply 2.84 Nm (25 in-
lb)
2.84 Nm (25 in-lb)
DIN rail latching
1.32 Nm (12 in-lb)
DIN rail stop
0.9 Nm (8 in-lb)
I/O terminal block field terminations
0.45 Nm (4 in-lb)
I/O terminal block protection cover
0.11 Nm (1 in-lb)
I/O card
0.11 Nm (1 in-lb)
Controller
0.11 Nm (1 in-lb)
Media Converter
0.11 Nm (1 in-lb)
System Power Supply
0.11 Nm (1 in-lb)
2.4.6
Getting Started with DeltaV Hardware
This section provides a brief description of the steps required for system installation.
Specific information on installation steps 1–7 is included in this chapter. Specific
information on step 8 is included in the topic "Checking Out and Troubleshooting Your
DeltaV System". The appendices in this manual include product specifications and detailed
information.
Installing Your DeltaV System
April 2021
D800001X312
26

--- Page 27 ---

The following steps for installation are listed in the most common order. You can elect to
perform these steps in another order that is more convenient for your project.
 CAUTION
The DeltaV I/O Cards and Controller must be mounted vertically on the horizontal carrier
for cooling purposes.
1. Install the DIN rails and DeltaV Carriers.
a) Install the DIN rails.
b) Install the power/controller carrier and I/O interface carrier on the DIN rails.
2. Install the DeltaV I/O Interface.
a) Check the key settings on the I/O terminal blocks and install them on the I/O
interface carrier.
b) Connect field wiring.
c) Install the I/O cards on the I/O interface carrier.
3. Install the DeltaV Controller.
a) Install the controller on the power/controller carrier.
4. Install the DeltaV System Power Supply.
a) Install the system power supply on the power/controller carrier.
b) Connect the supply inputs.
5. Install the DeltaV Workstation and Servers.
a) Follow the instructions supplied with your workstation and Server.
b) Install the system identifier.
c) Follow the instructions supplied with your printer and UPS
6. Set up the DeltaV Control Network.
a) Install the hub or switch.
b) Install the network cables between nodes.
7. Connect power to the system and power up.
a) Install the bulk power supply and connect the supply inputs.
b) Power up the system.
8. Check out the installation.
a) Check cable connections.
b) Check power supply voltages.
c) Check indicators on the devices and cards.
d) Test field wiring connections.
Installing Your DeltaV System
D800001X312 
April 2021
27