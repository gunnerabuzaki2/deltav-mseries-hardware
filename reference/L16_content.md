--- Page 380 ---

Figure G-65: 100Mbit Twisted Pair Cascaded Network with Cisco 3750 Switches
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 1
ProPLUS
station
Management
station
Operator
stations
Controllers
Cisco Catalyst 3750-24TS
Switch 2
Operator stations
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 3
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 4
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 5
Controllers
Cisco Catalyst 3750-24TS
Switch 6
4
4
3
3
4
3
7
7
7
5
5
5
8
4
3
7
5
8
4
3
7
5
8
4
3
7
5
8
8
8
6
1,2
1,2
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends.
4
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
April 2021
D800001X312
380

--- Page 381 ---

Callout
Description
5
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the Cisco documentation for web management
information. A dedicated non-DeltaV PC is required for switch management.
6
The Management station has special hardware and software requirements. Refer to
the related topics for information on the management station before connecting
the station to the DeltaV Control Network.
7
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex.
8
The switch is equipped with two gigabit slots that require a fiber-optic or twisted
pair small form factor pluggable (SFP) module (not used in the preceding network
drawing ). These slots always operate at 1000Mbit (gigabit) full duplex when fitted
with the SFP module.
Related information
Ethernet Cable Specifications and Installation Rules
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
The Management Station
Connecting the Management Station
G.5.9
Gigabit Twisted Pair Network Cascade
This network example shows a twisted pair cascaded network with Cisco 3750 switches.
Gigabit twisted pair small form factor pluggable (SFP) modules are used in this network.
Control Network Specifications
D800001X312 
April 2021
381

--- Page 382 ---

Figure G-66: Gigabit Twisted Pair Network Cascade with Cisco 3750 Switches
Controllers
Controllers
Controllers
Switch 2
Switch 5
Switch 3
Cisco Catalyst
3750-24TS
Cisco Catalyst
3750-24TS
Cisco Catalyst
3750-24TS
Switch 6
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Operator stations
Operator
stations
ProPLUS
station
Management
station
Operator stations
Controllers
Operator stations
Controllers
Operator stations
Operator stations
Controllers
Cisco Catalyst
3750-24TS
Cisco Catalyst
3750-24TS
Cisco Catalyst
3750-24TS
Switch 1
Switch 4
Cisco
Gigabit
Twisted Pair
SFP Module
Cisco
Gigabit
Twisted Pair
SFP Modules
Cisco
Gigabit
Twisted Pair
SFP Module
Cisco
Gigabit
Twisted Pair
SFP Modules
Cisco
Gigabit
Twisted Pair
SFP Modules
Cisco
Gigabit
Twisted Pair
SFP Modules
4
4
4
3
3
3
3
7
7
7
7
7
5
5
5
5
5
5
8
8
8
3
3
7
8
8
8
4
4
4
6
1,2
1,2
1,2
1,2
1,2
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
4
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
April 2021
D800001X312
382

--- Page 383 ---

Callout
Description
5
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
6
The Management station has special hardware and software requirements. Refer to
the related topics for information on the management station before connecting
the station to the DeltaV Control Network.
7
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex.
8
The switch is equipped with two gigabit slots that require a fiber-optic or twisted
pair small form factor pluggable (SFP) module. The twisted pair gigabit module is
shown in the preceding figure. These slots always operate at 1000Mbit (gigabit) full
duplex when fitted with the SFP module.
G.5.10
Gigabit Fiber-Optic Network Cascade
Figure G-67 shows a fiber-optic cascaded network with Cisco 3750 switches. Gigabit fiber-
optic small form factor pluggable (SFP) modules are used in this network.
Control Network Specifications
D800001X312 
April 2021
383

--- Page 384 ---

Figure G-67: Gigabit Fiber-Optic Network Cascade with Cisco 3750 Switches
Controllers
Controllers
Controllers
Switch 2
Switch 5
Switch 3
Switch 6
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Management
station
Cisco Catalyst
3750-24TS
Cisco
Gigabit
Fiber Optic
SFP Module
Operator stations
Switch 1
Operator stations
Switch 4
Operator
stations
ProPLUS
station
Cisco Catalyst
3750-24TS
Cisco
Gigabit
Fiber Optic
SFP Modules
Cisco Catalyst
3750-24TS
Controllers
Controllers
Cisco Catalyst
3750-24TS
Cisco
Gigabit
Fiber Optic
SFP Modules
Cisco Catalyst
3750-24TS
Cisco
Gigabit
Fiber Optic
SFP Modules
Cisco Catalyst
3750-24TS
Cisco
Gigabit
Fiber Optic
SFP Module
Cisco
Gigabit
Fiber Optic
SFP Modules
Operator stations
Controllers
Operator stations
4
4
4
4
3
8
3
3
3
5
5
5
5
5
5
5
2
2
2
2
2
2
6
6
6
6
6
4
4
6
1,7
1.7
1,7
1,7
1,7
1,7
Callout
Description
1
The SFP slots can be fitted with any combination of the SX or LH fiber-optic
transceiver modules. The SX module supports up to 550 meters of Multimode Fiber
and the LH module supports up to 10 kilometers of Single Mode Fiber. Fiber-optic
splices, patch panels, and connector losses reduce these overall distances. The SFP
slots and transceivers operate at 1000Mb (gigabit) full duplex only.
2
Each SFP transceiver module has a transmit port and a receive port. An LC type
duplex fiber-optic connector is required on the end of the fiber-optic cable pair. The
fiber-optic switch-to-switch connection is a crossover where the transmit on one
end is connected to the receive on the other end.
3
For Multimode Fiber on the SX type module, a 62.5/125 micron or 50/125 micron
fiber can be used. For Single Mode fiber on the LH module, a 9 micron fiber can be
used.
4
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
Control Network Specifications
April 2021
D800001X312
384

--- Page 385 ---

Callout
Description
5
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
6
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex
7
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
8
The Management station has special hardware and software requirements. Refer to
the related topics for information on the management station before connecting
the station to the DeltaV Control Network.
Related information
Fiber-Optic Cable Specifications
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
The Management Station
Connecting the Management Station
G.5.11
Gigabit Fiber-Optic Network Star with Cisco 3750
Switches
Figure G-68 shows a fiber-optic network star with Cisco 3750 switches. Gigabit fiber-optic
small form factor pluggable (SFP) modules are used in this network.
Control Network Specifications
D800001X312 
April 2021
385

--- Page 386 ---

Figure G-68: Gigabit Fiber-Optic Network Star with Cisco 3750 Switches
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
Catalyst 3750
ProPLUS
station
Management
station
Operator
stations
Operator stations
Controllers
Controllers
Cisco Catalyst 3750-24TS
Cisco Catalyst 3750G-12S
Switch 2
Cisco Catalyst 3750-24TS
Switch 3
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 4
Switch 1
Stacking
cable (rear)
Operator
stations
Cisco Catalyst 3750-24TS
Switch 5
Typical Remote Leg of Star
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 6
Operator stations
Controllers
Cisco Catalyst 3750-24TS
Switch 7
Remote Leg of Star with Additional Switch
Daisy-chained
Central Area of Network Star
Cisco
Gigabit
Fiber Optic
SFP Modules
Cisco
Gigabit
Fiber Optic
SFP Module
Cisco
Gigabit
Fiber Optic
SFP Module
Cisco
Gigabit
Fiber Optic
SFP Module
Cisco
Gigabit
Fiber Optic
SFP Module
Cisco
Gigabit
Fiber Optic
SFP Modules
4
5
4
5
8
3
3
3
3
5
5
5
5
5
2
2
2
2
2
2
6
9
6
6
4
4
4
6
6
6
1,7
1,7
1,7
1,7
1,7
1,7
1,7
Callout
Description
1
The SFP slots can be fitted with any combination of the SX or LH fiber-optic
transceiver modules. The SX module supports up to 550 meters of Multimode Fiber
and the LH module supports up to 10 kilometers of Single Mode Fiber. Fiber-optic
splices, patch panels, and connector losses reduce these overall distances. The SFP
slots and transceivers operate at 1000Mb (gigabit) full duplex only.
2
Each SFP transceiver module has a transmit port and a receive port. An LC type
duplex fiber-optic connector is required on the end of the fiber-optic cable pair. The
fiber-optic switch-to-switch connection is a crossover where the transmit on one
end is connected to the receive on the other end.
3
For Multimode Fiber on the SX type module, a 62.5/125 micron or 50/125 micron
fiber can be used. For Single Mode fiber on the LH module, a 9 micron fiber can be
used.
4
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends.
Control Network Specifications
April 2021
D800001X312
386

--- Page 387 ---

Callout
Description
5
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
6
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex
7
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
8
The Management station has special hardware and software requirements. Refer to
the related topics for information on the management station before connecting
the station to the DeltaV Control Network.
9
A Cisco stacking cable is included with the switch and can be used to connect two
3750-series switches together to form a single switch that can be managed with one
IP address.
Related information
Fiber-Optic Cable Specifications
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
The Management Station
Connecting the Management Station
G.5.12
100Mb Fiber-Optic Star
Figure G-69 shows a 100Mbit Fiber-Optic Star with Cisco 2950C and 3750 Switches.
Control Network Specifications
D800001X312 
April 2021
387

--- Page 388 ---

Figure G-69: 100Mb Fiber-Optic Star with Cisco 2950C and 3750 Switches
Catalyst 3750
Catalyst 3750
ProPLUS
station
Management
station
Operator
stations
Operator stations
Controllers
Controllers
Cisco Catalyst 3750-24TS
Cisco Catalyst 3750-24FS
Switch 2
Cisco Catalyst 2950C-24
Switch 3
Operator stations
Controllers
Cisco Catalyst 2950C-24
Switch 4
Switch 1
Stacking
cable (rear)
Operator
stations
Cisco Catalyst 2950C-24
Switch 5
Typical Remote Leg of Star
Operator stations
Controllers
Cisco Catalyst 2950C-24
Switch 6
Operator stations
Controllers
Cisco Catalyst 2950C-24
Switch 7
Remote Leg of Star with Additional Switch
Daisy-chained
Central Area of Network Star
4
4
6
5
6
5
5
9
6
5
6
6
8
1
8
1
7
7
7
7
10
2
8
3
4
8
3
8
3
4
6
7
7
5
6
8
3
8
3
Callout
Description
1
The SFP slots (not used in the preceding image ) can be fitted with any combination
of the SX or LH fiber-optic transceiver modules. The SX module supports up to 550
meters of Multimode Fiber and the LH module supports up to 10 kilometers of
Single Mode Fiber. Fiber-optic splices, patch panels, and connector losses reduce
these overall distances. The SFP slots and transceivers operate at 1000Mb (gigabit)
full duplex only.
2
All MTRJ fiber-optic ports on this switch have been preconfigured by Emerson to
100BASE-FX full duplex operation in order to meet the most typical network
configuration requirements. It is good practice to check each port's duplex setting
before connecting to them since it is also possible to configure each of these ports
to half duplex operation. Half duplex operation is not recommended for switch-to-
switch connections. Check both ends of the link and ensure that they are both
configured to full duplex operation or a duplex mismatch, which can cause serious
communications problems, could occur.
3
The two MTRJ ports on this switch are set by Cisco to 100BASE-FX full duplex
operation. Neither the speed nor duplex can be changed. Ensure that all devices
attached to these ports are properly configured for 100BASE-FX full duplex
operation before making the connection.
Control Network Specifications
April 2021
D800001X312
388

--- Page 389 ---

Callout
Description
4
2 km (max) full duplex Mulimode Fiber with MTRJ connectors.
5
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
6
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
7
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex.
8
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
switch-to-switch links. Refer to "Managing Cisco Switches" in Books Online for
information. Refer to the list of reserved IP addresses that are allowed for switches
on DeltaV systems. Refer to the Cisco documentation for web management
information. A dedicated non-DeltaV PC is required for switch management.
9
The Management station has special hardware and software requirements. Refer to
the related topics for information on the management station before connecting
the station to the DeltaV Control Network.
10
A Cisco stacking cable is included with the switch and can be used to connect two
3750-series switches together to form a single switch that can be managed with one
IP address.
Related information
Fiber-Optic Cable Specifications
Building Twisted Pair Cable Assemblies
The Management Station
Connecting the Management Station
Reserved DeltaV IP Addresses
G.5.13
100Mbit Twisted Pair Cascaded Network
Figure G-70 shows a 100Mbit Twisted Pair Cascaded Network with Cisco 2960 switches.
Control Network Specifications
D800001X312 
April 2021
389

--- Page 390 ---

Figure G-70: 100Mbit Twisted Pair Cascaded Network with Cisco 2960 Switches
4
4
4
4
3
3
3
3
3
3
4
4
1,2
1,2
7
7
7
7
7
7
8
Cisco Catalyst
2960-24TT-L Switch
Operator station
Operator station
Operator station
Operator station
Operator station
Operator station
Switch 
management station
Controllers
Controllers
Controllers
Controllers
Controllers
Controllers
ProPlus station
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-48TT-L Switch
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-8TC-L Switch
5,6
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
4
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
April 2021
D800001X312
390

--- Page 391 ---

Callout
Description
5
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
6
The Management station has special hardware and software requirements. Refer to
the related topics for information before connecting the station to the DeltaV
Control Network.
7
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, could occur. Always
allow the switch to auto-sense speed and auto-negotiate duplex.
8
The Cisco 2960-8TC-L is equipped with one gigabit port either as a RJ45 or a SFP slot.
The SFP slot requires a fiber-optic or twisted pair small form factor pluggable (SFP)
module. This slot operates at 1000Mbit (gigabit) full duplex when fitted with the
gigabit SFP module. If fitted with a 100BASE-FX SFP module (GLC-FE-100FX) it
operates at 100Mbit. This port is not used in this example.
Related information
Ethernet Cable Specifications and Installation Rules
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
Connecting the Management Station
The Management Station
G.5.14
Gigabit Twisted Pair Cascaded Network
Figure G-71 shows a gigabit twisted pair cascaded network with Cisco 2960 switches.
Control Network Specifications
D800001X312 
April 2021
391

--- Page 392 ---

Figure G-71: Gigabit Twisted Pair Cascaded Network with Cisco 2960 Switches
4
4
4
4
3
3
3
3
3
3
4
4
1,2
1,2
7
7
7
7
7
7
8
Cisco Catalyst
2960-24TT-L Switch
Operator station
Operator station
Operator station
Operator station
Operator station
Operator station
Switch 
management station
Controllers
Controllers
Controllers
Controllers
Controllers
Controllers
ProPlus station
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-48TT-L Switch
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-24TT-L Switch
Cisco Catalyst
2960-8TC-L Switch
5,6
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
4
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
April 2021
D800001X312
392

--- Page 393 ---

Callout
Description
5
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
6
The Management station has special hardware and software requirements. Refer to
the information in the related topics before connecting the station to the DeltaV
Control Network. before
7
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, could occur. Always
allow the switch to auto-sense speed and auto-negotiate duplex.
8
The Cisco 2960-8TC-L is equipped with one gigabit port either as a RJ45 or a SFP slot.
The SFP slot requires a fiber-optic or twisted pair small form factor pluggable (SFP)
module. This slot operates at 1000Mbit (gigabit) full duplex when fitted with the
gigabit SFP module. If fitted with a 100BASE-FX SFP module (GLC-FE-100FX) it
operates at 100Mbit. This port is not used in this example.
Related information
Ethernet Cable Specifications and Installation Rules
Building Twisted Pair Cable Assemblies
Connecting the Management Station
The Management Station
Reserved DeltaV IP Addresses
G.5.15
Gigabit Fiber-Optic Cascaded Network
Figure G-72 shows a gigabit fiber-optic cascaded network with Cisco 2960 switches.
Control Network Specifications
D800001X312 
April 2021
393

--- Page 394 ---

Figure G-72: Gigabit Fiber-Optic Cascaded Network with Cisco 2960 Switches
5
5
5
5
6
6
6
4
4
4
4
4
4
5
5
7,8
6
6
6
Cisco Catalyst
2960-24TC-L Switch
Operator station
Operator station
Operator station
Operator station
Operator station
Operator station
Switch 
management station
Controllers
Controllers
Controllers
Controllers
Controllers
Controllers
ProPlus station
Cisco Catalyst
2960-24TC-L Switch
Cisco Catalyst
2960-48TC-L Switch
Cisco Catalyst
2960-24TC-L Switch
Cisco Catalyst
2960-24TC-L Switch
Cisco Catalyst
2960-8TC-L Switch
1,2,9
1,2,9
1,2,9
1,2,9
1,2,9
1,2,10
2,3
2,3
Cisco
GLC-FE-100FX
SFP Module
Callout
Description
1
The SFP slots can be fitted with any combination of the SX or LH fiber-optic
transceiver modules. The SX module supports up to 550 meters of Multimode Fiber
and the LH module supports up to 10 kilometers of Single Mode Fiber. Fiber-optic
splices, patch panels, and connector losses reduce these overall distances. The SFP
slots and transceivers operate at 1000Mb (gigabit) full duplex only.
2
Each SFP transceiver has a transmit port and a receive port. An LC type duplex fiber-
optic connector is required on the end of the fiber-optic cable pair. The fiber-optic
switch-to-switch connector is a crossover cable where the transmit on one end is
connected to the receive on the other end.
3
For Multimode Fiber on the SX type module, 62.5/125 micron or 50/125 micron
fiber can be used. For Single Mode fiber on the LH module, a 9/125 micron fiber can
be used.
Control Network Specifications
April 2021
D800001X312
394

--- Page 395 ---

Callout
Description
4
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
5
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
6
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, could occur. Always
allow the switch to auto-sense speed and auto-negotiate duplex.
7
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
8
The Management station has special hardware and software requirements. Refer to
the related topics for information before connecting the station to the DeltaV
Control Network. Refer to the Cisco documentation for web management
information. A dedicated non-DeltaV PC is required for switch management.
9
Optionally, the fiber-optic link can be 100Mbit with a GLC-GE-100FX 100BASE-FX
SFP module in the Cisco 2960-24TC-L and the Cisco 2960-48TC-L switches.
10
Optionally, the fiber-optic link can be 100Mbit with a GLC-FE-100FX 100BASE-FX SFP
module in the Cisco 2960-8TC-L switch.
G.5.16
Gigabit Fiber-Optic Network Star
Figure G-73 shows a gigabit fiber-optic network star with Cisco 2960 and 3750 switches.
Control Network Specifications
D800001X312 
April 2021
395

--- Page 396 ---

Figure G-73: Gigabit Fiber-Optic Network Star with Cisco 2960 Switches
Operator station
Operator station
Operator station
Operator station
Cisco
GLC-FE-100FX
SFP Module
5
5
4
5
5
4
4
4
5
1,2,9
2,3
7,8
1,2,9
1,2,9,10
1,2,9,10
1,2,9
1,2,10
11
6
6
6
6
Controllers
Controllers
Controllers
Controllers
Cisco Catalyst
2960-48TC-L Switch
Cisco Catalyst
2960-48TC-L Switch
Cisco Catalyst
2960-48TC-L Switch
Cisco Catalyst
2960-8TC-L Switch
Cisco
Catalyst
3750-24TS 
Switch
CENTER AREA
OF THE STAR
Cisco
Catalyst
3750G-12S 
Switch
ProPLUS
station
Application
station
Switch Mgt.
station
Callout
Description
1
The SFP slots can be fitted with any combination of the SX or LH fiber-optic
transceiver modules. The SX module supports up to 550 meters of Multimode Fiber
and the LH module supports up to 10 kilometers of Single Mode Fiber. Fiber-optic
splices, patch panels, and connector losses reduce these overall distances. The SFP
slots and transceivers operate at 1000Mb (gigabit) full duplex only.
2
Each SFP transceiver has a transmit port and a receive port. An LC type duplex fiber-
optic connector is required on the end of the fiber-optic cable pair. The fiber-optic
switch-to-switch connector is a crossover cable where the transmit on one end is
connected to the receive on the other end.
3
For Multimode Fiber on the SX type module, 62.5/125 micron or 50/125 micron
fiber can be used. For Single Mode fiber on the LH module, a 9/125 micron fiber can
be used.
Control Network Specifications
April 2021
D800001X312
396

--- Page 397 ---

Callout
Description
4
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
5
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
6
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, could occur. Always
allow the switch to auto-sense speed and auto-negotiate duplex.
7
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
8
The Management station has special hardware and software requirements. Refer to
the related topics for information before connecting the station to the DeltaV
Control Network. Refer to the Cisco documentation for web management
information. A dedicated non-DeltaV PC is required for switch management.
9
Optionally, the fiber-optic link can be 100Mbit with a GLC-GE-100FX 100BASE-FX
SFP module in the Cisco 3750G-12S and the Cisco 2960-24TC-L switches.
10
Optionally, the fiber-optic link can be 100Mbit with a GLC-GE-100FX 100BASE-FX
SFP module in the Cisco 3750G-12S switch and a GLC-FE-100FX SFP module in the
Cisco 2960-8TC-L switch.
11
A Cisco stacking cable is included with the switch and can be used to connect two
3750-series switches together to form a single switch that can be managed with one
IP address.
Related information
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
Connecting the Management Station
The Management Station
G.5.17
100Mbit Fiber-Optic Network Star
Figure G-74 shows a 100Mbit fiber-optic network star with Cisco 2960 and 2950 switches.
Control Network Specifications
D800001X312 
April 2021
397

--- Page 398 ---

Figure G-74: 100Mbit Fiber-Optic Network Star with Cisco 2950 and 2960 Switches
Operator station
Operator station
2 Cisco
GLC-GE-100FX
SFP Modules
100BASE FX
Fiber
100BASE FX
Fiber
NOTE:
Only the GLC-GE-100 FX 
100BASE FX SFP module can be 
used in the Cisco 2960-48TC-L switch.
2
2
2
3
3
1
1
4,5
6
Controllers
Controllers
Cisco Catalyst
2950C Switch
Cisco Catalyst
2960-48TC-L Switch
Cisco Catalyst
2950C Switch
ProPLUS
station
Application
station
Switch
Management
station
7
7
Callout
Description
1
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
2
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on either switch and not on the PC.
3
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, will occur. Always allow
the switch to auto-sense speed and auto-negotiate duplex.
Control Network Specifications
April 2021
D800001X312
398

--- Page 399 ---

Callout
Description
4
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
5
The Management station has special hardware and software requirements. Refer to
the related topics for inforamtion before connecting the station to the DeltaV
Control Network. Refer to the Cisco documentation for web management. A
dedicated non-DeltaV PC is required for switch management.
6
For a 100Mbit fiber-optic link, use only a GLC-GE-100FX 100BASE-FX SFP module in
the Cisco 2960-48TC-L switch.
7
The 100BASE-FX fiber-optic link has duplex LC connectors at the GLC-GE-100FX SFP
and RTMJ connectors at the Cisco 2950C switch.
Related information
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
Connecting the Management Station
The Management Station
G.5.18
100Mbit Multimode Fiber-Optic Network
Figure G-75 shows a 100Mbit multimode fiber-optic network with Cisco 2950 and 2960
switches.
Control Network Specifications
D800001X312 
April 2021
399

--- Page 400 ---

Figure G-75: 100Mbit Multimode Fiber-Optic Network with Cisco 2950 and 2960
Switches
6
7
3
3
1
1
1
2
2
4,5
Cisco Catalyst
2960-24TC-L Switch
Cisco Catalyst
2960-8TC-L Switch
Cisco Catalyst
2950C Switch
Operator station
Operator station
Controllers
Controllers
Controllers
Switch 
management
station
ProPlus
station
Operator
station
Cisco
GLC-FE-100FX
SFP Module
100BASE FX
Fiber
Cisco
GLC-GE-100FX
SFP Module
NOTE:
Only the GLC-FE-100 FX 
100BASE FX SFP module can be 
used in the Cisco 2960-8TC-L switch.
NOTE:
Only the GLC-GE-100 FX  
100BASE FX SFP module can be 
used in the Cisco 2960-24TC-L switch.
2
3
8
Callout
Description
1
100 m (max) straight-through cable. The shield on the controller's RJ45 connector
connects only to a Faraday cage in the controller; not to the controller's DC ground.
Therefore, the RJ45 connectors are floating and the single point of ground is made
at the hub or switch to which the controller is connected. Build this cable assembly
with a shielded, metal-enclosed RJ45 connector on both ends .
2
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on either switch and not on the PC.
3
All twisted pair ports are configured to auto-sense speed and auto-negotiate
duplex. Do not hard-configure speed or duplex on the twisted pair switch ports or
duplex mismatches, which create communications failures, could occur. Always
allow the switch to auto-sense speed and auto-negotiate duplex.
Control Network Specifications
April 2021
D800001X312
400

--- Page 401 ---

Callout
Description
4
If switch management is to be used over the network via telnet or a web browser, be
aware that access privileges and port configuration requirements exist for the
twisted pair switch-to-switch links. Refer to "Managing Cisco Switches" in Books
Online for information. Refer to the list of reserved IP addresses that are allowed for
switches on DeltaV systems. Refer to the Cisco documentation for web
management information. A dedicated non-DeltaV PC is required for switch
management.
5
The Management station has special hardware and software requirements. Refer to
the related topics for information before connecting the station to the DeltaV
Control Network. Refer to the Cisco documentation for web management. A
dedicated non-DeltaV PC is required for switch management.
6
For a 100Mbit fiber-optic link, use only a GLC-GE-100FX 100BASE-FX SFP module in
the Cisco 2960-24TC-L switch.
7
For a 100Mbit fiber-optic link, use only a GLC-FE-100FX 100BASE-FX SFP module in
the Cisco 2960-8TC-L switch.
8
The 100BASE-FX fiber-optic link has duplex LC connectors on all SFP modules and
MTRJ connectors on the Cisco 2950C switch.
Related information
Building Twisted Pair Cable Assemblies
Reserved DeltaV IP Addresses
Connecting the Management Station
The Management Station
G.6
Example Networks with DeltaV Smart Switches
The following set of network drawings provide examples of more complex networks that
use DeltaV Smart Switches in 10/100Mbit twisted pair and fiber-optic segments. These
examples are intended to help you visualize some of the possibilities for control network
expansion and growth. Each example contains a network drawing with callouts and a table
that explains each callout.
G.6.1
DeltaV Smart Switches in a Twisted Pair Network with a
Twisted Pair Uplink
Figure G-76 shows DeltaV RM100 and FP20 Smart Switches in a twisted pair network with
a twisted pair uplink.
Control Network Specifications
D800001X312 
April 2021
401

--- Page 402 ---

Figure G-76: DeltaV RM100 and FP20 Switches in Twisted Pair Network with Twisted
Pair Uplink
1,2,9
1,2,9
1,2,12
3,12
3,12
1,2,12
1,2,12
1,2,12
4,12
3,12
7
7
8
8
5
5
11
11
10
10
8,6
8,6
3,12
DeltaV Operator Stations and ProPlus
DeltaV Redundant Controllers
RM100
Primary
RM100
Secondary
To additional
RM100 switch
To additional
RM100 switch
To additional
FP20 switch
FP20-6TX2TX
To additional
FP20 switch
DeltaV
Redundant
Controllers
with Redundant
Network
Secondary
Primary
Shield
Ground
Shield
Ground
To additional
FP20 switch
To additional
FP20 switch
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through or crossover cable. The shield on the controller's RJ45
connector connects only to a Faraday cage in the controller; not to the controller's
DC ground. Therefore, the RJ45 connectors are floating and the single point of
ground is made at the hub or switch to which the controller is connected. Build this
cable assembly with a shielded, metal-enclosed RJ45 connector on both ends.
4
100 m (max) straight-through or crossover cable. To prevent ground loops, build
this cable assembly with a shielded, metal-enclosed RJ45 connector on one end and
an isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
April 2021
D800001X312
402

--- Page 403 ---

Callout
Description
5
Use a ring tongue terminal to connect the ground screw of the switch to a suitable
shield ground. This connection provides a ground for the twisted pair Ethernet
shielded connectors.
6
The type of uplink ports on this switch are determined by the switch part number. In
this example, all FP20 switches have 8 10/100Mbit/sec twisted pair ports and any
number of them can be used for uplinks to other switches. Other uplink port types
are available in fixed hardware configurations. SFP ports are not available on this
switch and this switch has no gigabit capable ports.
7
This switch has two fixed 10/100/1000Mbit/sec uplink ports and two SFP uplink
ports. The SFP ports can be fitted with optional fiber-optic SFP transceivers for long
distance communications. Only two uplinks can be active at a time in any
combination of twisted pair and SFP. Refer to the ordering information for the
available SFP transceivers.
8
All twisted pair ports are configured to auto-sense speed, auto-negotiate duplex,
and auto-detect polarity. Do not hard-configure speed or duplex on the twisted pair
switch ports or duplex mismatches, which create communications failures, could
occur. Always allow the switch to auto-sense speed and auto-negotiate duplex. All
unused ports of the switch can be deactivated (locked down) by a software
command from the DeltaV station after all initial connections are made to the
switch. If additional controllers or workstations need to be connected to unused
ports after the initial lock down, an additional software command from the DeltaV
station is required to unlock the ports. After the final connections are made, the lock
down command should be reissued to the switch to lock down any remaining
unused ports. Once the ports are in a lock down state, only the original device can
communicate on its original port.
9
If more than one RM100 switch is required to increase port count in an area, use any
of the gigabit uplink ports for the switch-to-switch connection to provide ample
performance headroom on these aggregating links. 100Mbit/sec links can also be
used for this purpose but normally these links are reserved for single devices on the
edge of the network such as controllers and workstations that require much less
bandwidth than switch-to-switch links.
10
The serial port is not required for process communications; it is used only for
occasional out-of-band switch setup and management.
11
This connector is used for a +24VDC power supply input and relay contacts.
12
This is a 10/100Mbit/sec twisted pair link.
Related information
Building Twisted Pair Cable Assemblies
Ethernet Cable Specifications and Installation Rules
G.6.2
DeltaV Smart Switches in Twisted Pair Network with SFP
and Fiber-Optic Uplinks
Figure G-77shows DeltaV RM100 and FP20 Smart Switches in a twisted pair network with
SFP and fiber-optic uplinks.
Control Network Specifications
D800001X312 
April 2021
403

--- Page 404 ---

Figure G-77: DeltaV RM100 and FP20 Twisted Pair Network with SFP and Fiber-Optic
Uplinks
FAULT
USB
V.24
1.1
2.1
2.3
2.5
2.7
2.2
2.4
2.6
2.8
1
3
5
7
2
4
6
8
1.2
Network Switch RM100
RM100 Base Module
RUN
LOCK
P
Network Switch RM100
RM100-EM-8TX
1
3
5
7
2
4
6
8
Network Switch RM100
RM100-EM-8MM-FX
3,13
3,13
14
6
11
5
5
11
10
8
8
9,12
9,12
1,2,13
1,2,13
4,13
3,13
7
7
8
6
10
8
14
DeltaV Operator Stations and ProPlus
DeltaV Redundant Controllers
RM100
Secondary
To additional
FP20 switch
DeltaV
Redundant
Controllers
with Redundant
Network
Secondary
Primary
Shield
Ground
Shield
Ground
To additional
FP20 switch
To additional
FP20 switch
To additional
FP20 switch
RM100
Primary
To additional
RM100 switch
To additional
RM100 switch
3,13
FP20
FP20
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through or crossover cable. The shield on the controller's RJ45
connector connects only to a Faraday cage in the controller; not to the controller's
DC ground. Therefore, the RJ45 connectors are floating and the single point of
ground is made at the hub or switch to which the controller is connected. Build this
cable assembly with a shielded, metal-enclosed RJ45 connector on both ends.
4
100 m (max) straight-through or crossover cable. To prevent ground loops, build
this cable assembly with a shielded, metal-enclosed RJ45 connector on one end and
an isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
5
Use a ring tongue terminal to connect the ground screw of the switch to a suitable
shield ground. This connection provides a ground for the twisted pair Ethernet
shielded connectors.
Control Network Specifications
April 2021
D800001X312
404

--- Page 405 ---

Callout
Description
6
The type of uplink ports on this switch are determined by the switch part number. In
this example, all FP20 switches have two 100Mbit/sec full duplex multimode fiber-
optic uplink ports. Other uplink port types are available in fixed hardware
configurations. SFP ports are not available on this switch and this switch has no
gigabit capable ports.
7
This switch has two fixed 10/100/1000Mbit/sec uplink ports and two SFP uplink
ports. The SFP ports can be fitted with optional fiber-optic SFP transceivers for long
distance communications. Only two uplinks can be active at a time in any
combination of twisted pair and SFP. Refer to the ordering information for the
available SFP transceivers.
8
All twisted pair ports are configured to auto-sense speed, auto-negotiate duplex,
and auto-detect polarity. Do not hard-configure speed or duplex on the twisted pair
switch ports or duplex mismatches, which create communications failures, could
occur. Always allow the switch to auto-sense speed and auto-negotiate duplex. All
unused ports of the switch can be deactivated (locked down) by a software
command from the DeltaV station after all initial connections are made to the
switch. If additional controllers or workstations need to be connected to unused
ports after the initial lock down, an additional software command from the DeltaV
station is required to unlock the ports. After the final connections are made, the lock
down command should be reissued to the switch to lock down any remaining
unused ports. Once the ports are in a lock down state, only the original device can
communicate on its original port.
9
If more than one RM100 switch is required to increase port count in an area, use any
of the gigabit uplink ports for the switch-to-switch connection to provide ample
performance headroom on these aggregating links. 100Mbit/sec links can also be
used for this purpose but normally these links are reserved for single devices on the
edge of the network such as controllers and workstations that require much less
bandwidth than switch-to-switch links.
10
The serial port is not required for process communications; it is used only for
occasional out-of-band switch setup and management.
11
This connector is used for a +24VDC power supply input and relay contacts.
12
In this example, an SFP transceiver is used for the connection to the next switch. The
SFP module type must be matched to the type of fiber-optic cable that is installed.
Single mode and multimode fiber-optic cable in various core/cladding diameters
which contribute to the overall distance limit, can be used with specific SFP
modules.
13
This is a 10/100Mbit/sec twisted pair link.
14
This is a 100Mbit/sec full duplex multimode fiber-optic link. Distances up to 5 km
can be achieved depending upon the fiber-optic port option ordered and the
number of intermediate splices and patch panels used.
Related information
Building Twisted Pair Cable Assemblies
Ethernet Cable Specifications and Installation Rules
Control Network Specifications
D800001X312 
April 2021
405

--- Page 406 ---

G.6.3
DeltaV Smart Switches with Fiber and Twisted Pair
Uplinks
Figure G-78 shows DeltaV RM100 Smart Switches with single mode fiber-optic uplinks and
FP20 switches with single mode fiber-optic and twisted pair uplinks.
Figure G-78: RM100s with Fiber Uplinks and FP20s with Fiber and Twisted Pair
Uplinks
FAULT
USB
V.24
1.1
2.1
2.3
2.5
2.7
2.2
2.4
2.6
2.8
1.2
Network Switch RM100
RM100 Base Module
RUN
LOCK
P
1
3
5
7
2
4
6
8
Network Switch RM100
RM100-EM-8MM-FX
1
3
5
7
2
4
6
8
Network Switch RM100
RM100-EM-8MM-FX
FAULT
USB
V.24
1.1
2.1
2.3
2.5
2.7
2.2
2.4
2.6
2.8
1.2
Network Switch RM100
RM100 Base Module
RUN
LOCK
P
1
3
5
7
2
4
6
8
Network Switch RM100
RM100-EM-8MM-FX
1
3
5
7
2
4
6
8
Network Switch RM100
RM100-EM-8MM-FX
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
Network Switch
FP20
FAULT
FAULT
LOCK
0V
+24V(P1)
P
RUN
LS
1
2
DA
LS
DA
USB
V.24
+24V(P2)
0V
1   2
3   4
5   6
1,2,12
1,2,12
1,2,12
1,2,12
7,9
8,12
6
8
6
8
6
8
6
8
6
8
6
8
6
8
6
8
4,12
13
13
7,9
8
5
5
8
8
3
10
11
10
11
DeltaV Operator Stations and ProPlus
RM100
Primary
Primary FP20
Primary
Primary
Primary
Ground
Shield
Ground
Shield
Secondary FP20
Secondary
Secondary
Secondary
To additional
FP20 switch
RM100
Secondary
To additional
FP20 switch
To additional
FP20 switch
To additional
FP20 switch
To additional
FP20 switch
To additional
FP20 switch
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
Control Network Specifications
April 2021
D800001X312
406

--- Page 407 ---

Callout
Description
3
100 m (max) straight-through or crossover cable. The shield on the controller's RJ45
connector connects only to a Faraday cage in the controller; not to the controller's
DC ground. Therefore, the RJ45 connectors are floating and the single point of
ground is made at the hub or switch to which the controller is connected. Build this
cable assembly with a shielded, metal-enclosed RJ45 connector on both ends.
4
100 m (max) straight-through or crossover cable. To prevent ground loops, build
this cable assembly with a shielded, metal-enclosed RJ45 connector on one end and
an isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
5
Use a ring tongue terminal to connect the ground screw of the switch to a suitable
shield ground. This connection provides a ground for the twisted pair Ethernet
shielded connectors.
6
The type of uplink ports on this switch are determined by the switch part number. In
this example, all FP20 switches have one 100Mbit/sec full duplex single mode fiber-
optic uplink ports. Other uplink port types are available in fixed hardware
configurations. SFP ports are not available on this switch and this switch has no
gigabit capable ports.
7
This switch has two fixed 10/100/1000Mbit/sec uplink ports and two SFP uplink
ports. The SFP ports can be fitted with optional fiber-optic SFP transceivers for long
distance communications. Only two uplinks can be active at a time in any
combination of twisted pair and SFP. Refer to the ordering information for the
available SFP transceivers.
8
All twisted pair ports are configured to auto-sense speed, auto-negotiate duplex,
and auto-detect polarity. Do not hard-configure speed or duplex on the twisted pair
switch ports or duplex mismatches, which create communications failures, could
occur. Always allow the switch to auto-sense speed and auto-negotiate duplex. All
unused ports of the switch can be deactivated (locked down) by a software
command from the DeltaV station after all initial connections are made to the
switch. If additional controllers or workstations need to be connected to unused
ports after the initial lock down, an additional software command from the DeltaV
station is required to unlock the ports. After the final connections are made, the lock
down command should be reissued to the switch to lock down any remaining
unused ports. Once the ports are in a lock down state, only the original device can
communicate on its original port.
9
If more than one RM100 switch is required to increase port count in an area, use any
of the gigabit uplink ports for the switch-to-switch connection to provide ample
performance headroom on these aggregating links. 100Mbit/sec links can also be
used for this purpose but normally these links are reserved for single devices on the
edge of the network such as controllers and workstations that require much less
bandwidth than switch-to-switch links.
10
The serial port is not required for process communications; it is used only for
occasional out-of-band switch setup and management.
11
This connector is used for a +24VDC power supply input and relay contacts.
12
This is a 10/100Mbit/sec twisted pair link.
13
This is a 100Mbit/sec full duplex single mode fiber-optic link. Distances up to 40 km
can be achieved depending upon the fiber-optic port option ordered and the
number of intermediate splices and patch panels used.
Control Network Specifications
D800001X312 
April 2021
407

--- Page 408 ---

Related information
Building Twisted Pair Cable Assemblies
Ethernet Cable Specifications and Installation Rules
G.6.4
RM104 Smart Switch network with fiber-optic and
twisted-pair uplinks
Figure G-79: DeltaV RM104s and RM100s with fiber-optic and twisted-pair uplinks
1
1
RM104
RM104
RM100
RM100
Pro+
OP/APP
Workstation
OP/APP
Workstation
OP/APP
Workstation
CIOC
DeltaV Redundant Controller
Protected by optional DeltaV Firewall IPD
Up to 8 controllers per firewall.
CIOC
Not protected by optional
DeltaV Firewall IPD
DeltaV Redundant Controller
+24 VDC In
+24 VDC In
1
1
4
4
4
3
3
3
3
7
7
7
6
7
6
6
6
5
5
5
5
4
2
5
5
8
Optional
DeltaV
Firewall
IPD
Optional
DeltaV
Firewall
IPD
Switch
Switch
Control Network Specifications
April 2021
D800001X312
408

--- Page 409 ---

Callout
Description
1
Fiber-optic cable is supplied by the end user or the installer. The type of fiber-
optic cable that can be used depends on the type of optional fiber-optic
transceivers that are selected at time of sale. The transceivers that are available
are single mode and multimode, and they support various fiber diameters such as
62.5/125 micron, 50/125 micron in multimode, and 9 micron in single mode. Use
information in pre-sales literature to determine cabling distances supported by
the various types of fiber optic transceivers.
2
The ProfessionalPLUS is connected to any RM104 port in this case so that there is
a gigabit link between the ProfessionalPLUS and the switch. Alternately, the
ProfessionalPLUS could be connected to any 100 mb/s port on the RM100
switches, or to one of the two gigabit ports available on the RM100. Initially
selecting a gigabit port for the ProfessionalPLUS connection on any of the Smart
Switches provides the most available bandwidth.
3
This is a 100 meter (maximum) straight-through or crossover cable. To prevent
ground loops, build this cable assembly with a shielded, metal-enclosed RJ45
connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly must be placed on the
switch and not on the PC. Refer to Building twisted pair cable assemblies in the
DeltaV Hardware Installation manual for more information.
4
The RM104 and RM100 Smart Switches contain these combination ports. When
there is a fiber-optic SFP slot next to a twisted-pair slot as highlighted for this
note, one or the other in that pair can be used simultaneously, but not both. For
the RM104, there are 4 combination ports, up to 4 ports in this grouping can be
used, but never two directly adjacent ports. For the RM100, there are 2
combination ports, up to 2 ports in this grouping can be used, but never two
directly adjacent ports.
5
This is a 100 m (maximum) straight-through or crossover cable. The shield on the
CIOC and Controller's RJ45 connector connects only to a Faraday cage in the CIOC
or Controller; not to the CIOC or Controller's DC ground. Therefore, the RJ45
connectors are floating and the single point of ground is made at the switch to
which the CIOC or Controller is connected. Build this cable assembly with a
shielded, metal-enclosed RJ45 connector on both ends. Refer to Building twisted
pair cable assemblies in the DeltaV Hardware Installation manual for more
information.
6
Ground screw must be attached to a suitable ground for the shielding.
7
This is a 100 meter (maximum) straight-through or crossover cable. To prevent
ground loops, build this cable assembly with a shielded, metal-enclosed RJ45
connector on the end that goes to the Smart Switch, and the plastic-enclosed
RJ45 connector on the end that goes to the firewall IPD.
8
This example shows that when Controllers and CIOCs are directly connected to
the same switch as the workstations, they are not protected by a firewall IPD. The
firewall IPD is an option that allows additional security; however, it is not required
for normal DeltaV operation.
G.6.5
DeltaV Smart Switches in a Twisted Pair Network
The following two images show DeltaV RM100, FP20, and MD30 Smart Switches in a
twisted pair network. There can be no more than six switches in series between any two
devices in any path in this type of network.
Control Network Specifications
D800001X312 
April 2021
409

--- Page 410 ---

Figure G-80: DeltaV Smart Switches in a Twisted Pair Network, Example 1
1,2,9
1,2,9
1,2,6,8
1,2,6,8
3,12
3,12
3,12
7
7
8
8
5
4,12
5
8
8
10,11
10,11
DeltaV Operator Stations and ProPlus
DeltaV Redundant Controllers
RM100
Primary
Primary
MD30 Switch
Secondary
MD30 Switch
RM100
Secondary
To additional
RM100 switch
To additional
RM100 switch
DeltaV
Redundant
Controllers
with Redundant
Network
Shield
Ground
Shield
Ground
The following figure shows a maximum of four switches in series between two devices
Control Network Specifications
April 2021
D800001X312
410

--- Page 411 ---

Figure G-81: DeltaV Smart Switches in a Twisted Pair Network, Example 2
1,2,9
1,2,9
1,2,6,8
1,2
1,2
1,2
1,2
1,2,6,8
3,12
3,12
3,12
7
7
8
8
5
4,12
8
8
5
10,11
10,11
DeltaV Operator Stations and ProPlus
DeltaV Redundant Controllers
RM100
Primary
Primary
MD30 Switch
FP20
Switch
FP20
Switch
Secondary
MD30 Switch
RM100
Secondary
To additional
RM100 switch
To additional
RM100 switch
DeltaV
Redundant
Controllers
with Redundant
Network
Shield
Ground
Shield
Ground
Callout
Description
1
100 m (max) straight-through or crossover cable. Cat. 5(e) Screened Twisted Pair
cable is required between switches.
2
To prevent ground loops, build this cable assembly with a shielded, metal-enclosed
RJ45 connector on one end and an isolated, plastic-enclosed RJ45 connector on the
other end. The metal connector end of this cable assembly/link can be placed on
either switch.
3
100 m (max) straight-through or crossover cable. The shield on the controller's RJ45
connector connects only to a Faraday cage in the controller; not to the controller's
DC ground. Therefore, the RJ45 connectors are floating and the single point of
ground is made at the hub or switch to which the controller is connected. Build this
cable assembly with a shielded, metal-enclosed RJ45 connector on both ends.
4
100 m (max) straight-through or crossover cable. To prevent ground loops, build
this cable assembly with a shielded, metal-enclosed RJ45 connector on one end and
an isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
D800001X312 
April 2021
411

--- Page 412 ---

Callout
Description
5
Use a ring tongue terminal to connect the ground screw of the switch to a suitable
shield ground. This connection provides a ground for the twisted pair Ethernet
shielded connectors.
6
The type of uplink ports on this switch are determined by the optional modules
chosen. In this example, all MD30 switches have a gigabit module installed on the
left side of the switch that used for the uplink to the RM100 switch. This module
contains two, 10/100/1000 twisted pair ports and two gigabit SFP slots for various
types of optional SFP transceivers. Only two ports on this module can be used
simultaneously in any mix. The SFP transceivers are available in singlemode and
multimode fiber-optic versions. Each of the remaining six port modules on the right
side of the switch have four 10/100Mbit/sec twisted pair ports for a total of 24 ports
and any combination of ports can be used for 10/100Mbit/sec uplinks to other
switches or for edge devices such as workstations and controllers.Other modules
are available in 100Mbit/sec only communications in single and multimode fiber-
optic versions.
7
The type of uplink ports on this switch consists of two fixed 10/100/1000Mbit/sec
ports and two SFP ports. The SFP ports can be fitted with optional fiber-optic SFP
transceivers for long distance communications. Only two uplinks can be active at a
time in any combination of twisted pair and SFP. Refer to the ordering information
for the available SFP transceivers.
8
All twisted pair ports are configured to auto-sense speed, auto-negotiate duplex,
and auto-detect polarity. Do not hard-configure speed or duplex on the twisted pair
switch ports or duplex mismatches, which create communications failures, could
occur. Always allow the switch to auto-sense speed and auto-negotiate duplex. All
unused ports of the switch can be deactivated (locked down) by a software
command from the DeltaV station after all initial connections are made to the
switch. If additional controllers or workstations need to be connected to unused
ports after the initial lock down, an additional software command from the DeltaV
station is required to unlock the ports. After the final connections are made, the lock
down command should be reissued to the switch to lock down any remaining
unused ports. Once the ports are in a lock down state, only the original device can
communicate on its original port.
9
If more than one RM100 switch is required to increase port count in an area, use any
of the gigabit uplink ports for the switch-to-switch connection to provide ample
performance headroom on these aggregating links. 100Mbit/sec links can also be
used for this purpose but normally these links are reserved for single devices on the
edge of the network such as controllers and workstations that require much less
bandwidth than switch-to-switch links.
10
The serial port is not required for process communications; it is used only for
occasional out-of-band switch setup and management.
11
The power connector (not shown) is used for a +24VDC power supply input and
relay contacts.
12
This is a 10/100Mbit/sec twisted pair link.
Related information
Ethernet Cable Specifications and Installation Rules
Building Twisted Pair Cable Assemblies
Control Network Specifications
April 2021
D800001X312
412

--- Page 413 ---

G.7
DeltaV Controller Firewall
The DeltaV Controller Firewall is designed to protect DeltaV controllers from Denial of
Service (DoS) attacks originating from DeltaV workstations or other computers on the
DeltaV Control Network.
Important
The DeltaV system requires a specific hardware and software version of the firewall IPD
and a special configuration that includes the packet inspection rules and packet rate limits
that have been tested with the DeltaV system. Firewall IPDs ordered from Emerson
Automation Solutions are shipped with the supported software and are pre-configured to
operate properly with the DeltaV system. To ensure that you have the proper firewall IPD
configuration and the correct hardware and software versions, you must purchase the
firewall IPD through normal Emerson channels.
A detachable screw terminal block is used to supply the required 24 VDC system power to
the firewall IPD. The firewall IPD is installed close to the controllers on the DIN rail and can
use the same system power supply as the controllers. To more tightly control physical
access to the firewall IPD, it can be installed on a DIN rail with a 24 VDC power supply in the
equipment room. A set of normally closed, potential-free relay contacts, also supplied on
the detachable terminal block, monitor proper device functioning.
The ground screw connects to an instrumentation ground to provide a shield ground for
the controller and firewall IPD communications cables.
The 10/100 BASE-T Ethernet port labeled Workstations is for DeltaV workstations only.
Typically, the workstations are connected to a managed switch such as the DeltaV RM100
Smart Switch, and the switch is connected to the workstation port of the firewall IPD. The
10/100 BASE-T Ethernet port labeled Controllers is for DeltaV controllers only. Typically,
the controllers are connected to a managed switch such as the DeltaV RM100 Smart
Switch, and the switch is connected to the controller port of the firewall IPD. For
controllers that are distributed over wider geographic areas, consider using one firewall
IPD for each controller. This is a more secure arrangement because it eliminates the
possibility of open switch ports on the controller side.
Table G-26: DeltaV Firewall IPD specifications
Item
Specification
Input voltage
24 VDC nominal (12-48 VDC)
Input current
TX/TX
•
410 mA at 12 VDC
•
110 mA at 48 VDC
TX/FX
•
450 mA at 12 VDC
•
120 mA at 48 VDC
Twisted-pair ports: controller (protected) and
workstation (unprotected)
10/100 BASE-T Ethernet; 100 meters maximum
Category 5(e) Screened Twisted Pair (ScTP)
Fiber-optic ports: controller (protected) and
workstation unprotected
100 BASE-FX
Control Network Specifications
D800001X312 
April 2021
413

--- Page 414 ---

Table G-26: DeltaV Firewall IPD specifications (continued)
Item
Specification
Link budget
•
Multimode 50/125 µm - max attenuation 8
dB
•
Multimode 62.5/125 µm - max attenuation
11 dB
•
Wavelength 1300 nM
•
Single mode 9/125 µm - max attenuation
16dB
•
Wavelength 1300 nM
Alarm contacts
Normally closed. Configurable to opened if:
•
Redundant power supply fails
•
Cables on either or both ports are
disconnected
Controllers supported
Eight (8)
If more than 8 controllers require protection,
add more firewall IPDs in parallel to share the
communications load.
Workstations supported
All combinations of workstations up to normal
DeltaV limits for workstations. Refer to the
System Capacities table in DeltaV Books Online
for complete information on workstation limits
Dimensions
Height: 13 cm (5.12 inches)
Width: 4.52 cm (1.78 inches)
Depth: 12.06 cm (4.75 inches)
Mounting
DIN rail. The firewall IPD can be mounted on the
same DIN rail as the controller.
Control Network Specifications
April 2021
D800001X312
414

--- Page 415 ---

Figure G-82: Firewall IPD with one twisted-pair port and one fiber-optic port
Power/relay
connectors
Status LEDs
Twisted-pair
controller port
Power/relay
connection
wiring diagram
Ground screw
for RJ45 shield
Bypass
pushbutton
Serial port
USB port
Bypass
contacts
Fiber-optic
workstation port
Figure G-83: Firewall IPD with two twisted-pair ports
Bypass
pushbutton
Power/relay
connectors
Status LEDs
Twisted-pair
controller port
Power/relay
connection
wiring diagram
Ground screw
for RJ45 shield
Serial port
USB port
Bypass
contacts
Twisted-pair
workstation port
The firewall IPD must be installed on the Primary and Secondary Control Networks to
provide protection on both access ports of the controllers. Among the things to consider
when determining the best location in which to install the firewall IPD are:
Control Network Specifications
D800001X312 
April 2021
415

--- Page 416 ---

• Power and grounding requirements
• Cable shielding requirements
• Securing access to the firewall IPD
Note
Do not connect a workstation to the controller side of the firewall IPD and do not connect
a controller to the workstation side of the firewall IPD. Incorrect connections will
completely bypass firewall IPD protection for controllers.
Refer to DeltaV Firewall IPD Network Examples for examples of how to use the firewall IPD
in a Control Network.
The firewall IPD can be managed from a Management station. Refer to the Managing the
DeltaV Firewall IPD topic in DeltaV Books Online.
Related information
Connecting the Management Station
The Management Station
G.7.1
DeltaV Firewall IPD Network Examples
The following four network drawings show examples of how the DeltaV Firewall IPD can be
used in Control Networks. In all figures, Firewall refers to the firewall IPD. The examples
begin with simple networks and end with more complex networks.
DeltaV Firewall IPD with Single Controllers and Switches
The following figure shows DeltaV Firewall IPDs in a network with single controllers and
three-port switches.
Control Network Specifications
April 2021
D800001X312
416

--- Page 417 ---

Figure G-84: DeltaV Firewall IPDs with Single Controllers and Switches
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
Switch
Building A
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
Firewall
Building B
Building C
Operator stations
ProPLUS station
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
+24 (p1)
+24 (p2)
Firewall
Firewall
Firewall
Firewall
Firewall
Switch
Switch
Switch
Switch
Switch
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
+24 (p1)
+24 (p2)
Primary switch
Secondary switch
Protected side
Protected side
Protected
side
Rack room
1
2
3
4
6
5
3
The information in the following table applies to both the primary and secondary
connections between all components.
1
100 m (max) straight-through Category 5e Screened Twisted Pair (ScTP) cable. The
shield on the controller's RJ45 connector connects only to a Faraday cage in the
controller; not to the controller's DC ground. Therefore, the RJ45 connectors are
floating and the single point of ground is made at the switch to which the controller
is connected. Build this cable assembly with a shielded, metal-enclosed RJ45
connector on both ends.
2
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the mini-switch and not on the
firewall IPD port.
3
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the firewall IPD port.
4
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the workstation.
Control Network Specifications
D800001X312 
April 2021
417

--- Page 418 ---

5
On the mini-switch, attach a separate ground wire to the terminal block screw that
is labeled with the ground symbol and connect this wire to a suitable
instrumentation ground.
6
On the firewall IPD, attach a separate ground wire to the front panel screw that is
labeled with the ground symbol and connect this wire to a suitable instrumentation
ground.
DeltaV Controller Firewall with Single Controllers and the
Single Port Fiber Switch
Figure G-85: DeltaV Controller Firewall with Single Controllers and the Single Port
Fiber Switch
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
Firewall
Building A
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
Building B
Building C
Operator stations
ProPLUS station
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
+24 (p1)
+24 (p2)
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
Switch
Firewall
Firewall
Firewall
Firewall
Firewall
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
+24 (p1)
+24 (p2)
Primary switch
Secondary switch
Protected side
Protected side
Protected side
Rack room
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
Power
Error
Port 1
Port 4
Port 2
Port 5
Port 3
1
2
3
4
5
6
3
The information in the following table applies to both the primary and secondary
connections between all components.
1
100 m (max) straight-through Category 5e Screened Twisted Pair (ScTP) cable. The
shield on the controller's RJ45 connector connects only to a Faraday cage in the
controller; not to the controller's DC ground. Therefore, the RJ45 connectors are
floating and the single point of ground is made at the switch to which the controller
is connected. Build this cable assembly with a shielded, metal-enclosed RJ45
connector on both ends.
Control Network Specifications
April 2021
D800001X312
418

--- Page 419 ---

2
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the mini-switch and not on the
firewall port.
3
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the firewall port.
4
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the workstation.
5
On the mini-switch, attach a separate ground wire to the terminal block screw that
is labeled with the ground symbol and connect this wire to a suitable
instrumentation ground.
6
On the firewall, attach a separate ground wire to the front panel screw that is
labeled with the ground symbol and connect this wire to a suitable instrumentation
ground.
DeltaV Firewall IPD with Multiple Controllers
A firewall IPD supports a maximum of eight controllers.
Control Network Specifications
D800001X312 
April 2021
419

--- Page 420 ---

Figure G-86: Firewall IPD with Eight Controllers
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
01
03
04
02
05
07
08
06
Firewall
Primary switch
Secondary switch
Pri MD
Smart Switch
Firewall
Sec MD
Smart Switch
Operator stations
ProPLUS station
1
2
3
4
5
Rack room
The following figure shows firewall IPDs in a network with more than eight controllers. Add
firewall IPDs to share the communications load if the number of controllers requiring
protection exceeds eight.
Control Network Specifications
April 2021
D800001X312
420

--- Page 421 ---

Figure G-87: Firewall IPDs with more than Eight Controllers
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
P1
2
1
2
Fault
Status
LSDA
V24
Default
Controllers
Workstations
IP Address
V.24
+24 (p1)
+24 (p2)
OV
01
03
04
02
05
07
08
06
09
11
12
10
13
15
16
14
Firewall
Primary switch
Firewall
Secondary switch
Pri MD
Smart Switch
Firewall
Firewall
Sec MD
Smart Switch
Operator stations
ProPLUS station
Rack room
Pri MD
Smart Switch
Sec MD
Smart Switch
The information in the following table applies to both the primary and secondary
connections between all components.
1
100 m (max) straight-through Category 5e Screened Twisted Pair (ScTP) cable. The
shield on the controller's RJ45 connector connects only to a Faraday cage in the
controller; not to the controller's DC ground. Therefore, the RJ45 connectors are
floating and the single point of ground is made at the switch to which the controller
is connected. Build this cable assembly with a shielded, metal-enclosed RJ45
connector on both ends.
2
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the mini-switch and not on the
firewall IPD port.
Control Network Specifications
D800001X312 
April 2021
421

--- Page 422 ---

3
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the firewall IPD port.
4
100 m (max) straight-through ScTP cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the rack room switch and not on
the workstation.
5
Attach a separate ground wire to the front panel screw that is labeled with the
ground symbol and connect this wire to a suitable instrumentation ground.
G.8
The Management Station
A Management station is a qualified PC that can be user-installed with web-based
interfaces for DeltaV Smart Switches, management software for the DeltaV Firewall IPD,
and web-based switch management software for Cisco switches. A PC is qualified when it
has been certified for use with the DeltaV system. Any PC connected to the DeltaV Control
Network must follow the same hardware installation rules as DeltaV workstations even if
the PC is not installed with the DeltaV software. For example, the PC must use Category 5e
Screened 4 Twisted-Pair Cable (ScTP) and cable lengths cannot exceed 100 meters (328
feet).
Qualified PCs for use as Management stations can be ordered from Emerson; however,
Emerson does not install the management software. Users must install the management
software on the Management station. Switch management software and firewall IPD
management software are supported only on Management stations, not on DeltaV
workstations.
If a Management station connected to the DeltaV Control Network is also connected to
another network for plant area access outside of the DeltaV system, it is imperative that
the Management station is properly maintained with the latest Microsoft security patches
and virus software. This ensures that the Management station does not become infected
with viruses that could affect the operation of the DeltaV control system equipment. Like
other DeltaV stations, the Management station’s outside network connection, which is
usually a third NIC card in the PC, must be isolated via a router to other local area networks
and a firewall to the wide area network or internet. If you do not have the resources or
expertise to connect to the outside world using a properly configured router and firewall,
then do not attach the Management station to both the DeltaV Control Network and other
networks outside the DeltaV control system. This way, the Management station will have
the same protection as the ProfessionalPLUS and Operator Stations.
A TFTP server application can be installed on the Management station. A TFTP server can
be used to flash Ethernet switches or archive Ethernet switch configurations. Do not
confuse a Management station with a Simple Network Management Protocol (SNMP)
station that contains additional network management software. The Management station
is a basic PC with a web browser that can access the switch or firewall using its IP address
and is capable of displaying graphics, switch network statistics, bar and line graphs, and
firewall logs.
Control Network Specifications
April 2021
D800001X312
422

--- Page 423 ---

To manage switches and the firewall using traditional management software from third
parties, you must install Java software on the Management station. DeltaV workstations,
including the Management station, that are connected to a DeltaV Control Network
should never make connections to the Internet. To install Java on a Management station,
you must download Java from the Internet to a USB flash drive or other media on a
computer that is not connected to the DeltaV Control Network and then install Java from
the USB flash drive to the Management station. Refer to “Downloading Java Software for
use on a Management Station” in DeltaV Books Online for information on how to
download Java from the Internet to a USB flash drive.
Refer to KBA NK-1600-0290 for information about managing the firewall IPD using
HiView.
Emerson cannot be responsible for the operation of a DeltaV system if these requirements
for a Management station are not strictly followed.
G.8.1
Connecting the Management Station
Connect the Management station to the Primary and Secondary Control Networks with
shielded twisted pair cable as shown in the figures in this chapter. This enables the
Management station to access any switch or DeltaV Firewall IPD on the network and
creates one central location for switch and/or firewall management.
Qualified Ethernet cables that are described in all DeltaV network figures in this section
must be used to connect a Management station to the DeltaV Control Network. When
considering cable shielding, treat the Management station like a DeltaV device.
Additionally for switches, the Management station can be connected to the switch
through the “Comm Port” of the Management station and the “Console Port” of the
switch. The Console Port of the switch is a low-speed serial connection. This port is used to
set up the switch for Telnet and web management and to give the switch an IP address,
name, and password protection. However, the Network Device Management Center
(NDCC) can also perform these functions when the switch is connected to one of the
supported networks.
When not using NDCC switch management from the DeltaV console, the switch needs an
IP address to be managed from anywhere on the network using the Management station’s
web browser or Telnet. Optionally, the serial connection can be kept intact and the link
can be used to observe network statistics, configure ports, and save switch data to the
Management station. The disadvantage of serial port management is that the
Management station must be physically moved from switch to switch to make the
physical connections to each switch’s Console port.
G.9
Managing Switches and the DeltaV Firewall IPD
DeltaV Smart Switches, Cisco switches, and the DeltaV Firewall IPD can be managed from
the Management station to monitor general network health or for troubleshooting
purposes.
Refer to DeltaV Books Online for information on:
• Using Telnet and Web-based switch management for DeltaV Smart Switches
• Command line, Telnet, and Web-based switch management for Cisco switches
Control Network Specifications
D800001X312 
April 2021
423

--- Page 424 ---

• Configuring Cisco switches for use with the DeltaV system
• Managing the firewall IPD
Related information
Connecting the Management Station
The Management Station
G.10
Reserved DeltaV IP Addresses
The DeltaV system automatically assigns IP addresses to the DeltaV nodes. In addition,
there are reserved IP addresses that can be used on the DeltaV system for optional
equipment. The first table shows the IP addresses that are reserved for external Network
Time Protocol Servers. The second table shows the IP addresses that are reserved for
switches and the DeltaV Firewall IPD. You can copy and keep these tables for your records.
Be sure to read the important information following the second table.
Note
If the Network Time Protocol Server is a DeltaV workstation, it is automatically assigned an
IP address.
Table G-27: Reserved IP Addresses for the Network Time Protocol Server
Primary Network Ethernet
Reservations
Secondary Network Ethernet
Reservations
Server
Address
Server
Address
Primary NTP
server
10.4.128.1
Primary NTP
server
10.8.128.1
Backup NTP
server
10.4.128.2
Backup NTP
server
10.8.128.2
Table G-28: Reserved IP Addresses for Switches and the DeltaV Firewall IPD
Checklist
Primary Ethernet Reservation
Secondary Ethernet
Reservation
Pri.
Sec.
IP Address
Device name
IP Address
Device name
10.4.128.16
10.8.128.16
10.4.128.17
10.8.128.17
10.4.128.18
10.8.128.18
10.4.128.19
10.8.128.19
10.4.128.20
10.8.128.20
10.4.128.21
10.8.128.21
10.4.128.22
10.8.128.22
10.4.128.23
10.8.128.23
10.4.128.24
10.8.128.24
10.4.128.25
10.8.128.25
Control Network Specifications
April 2021
D800001X312
424

--- Page 425 ---

Table G-28: Reserved IP Addresses for Switches and the DeltaV Firewall IPD
(continued)
Checklist
Primary Ethernet Reservation
Secondary Ethernet
Reservation
Pri.
Sec.
IP Address
Device name
IP Address
Device name
10.4.128.26
10.8.128.26
10.4.128.27
10.8.128.27
10.4.128.28
10.8.128.28
10.4.128.29
10.8.128.29
10.4.128.30
10.8.128.30
10.4.128.31
10.8.128.31
10.4.128.32
10.8.128.32
10.4.128.33
10.8.128.33
10.4.128.34
10.8.128.34
10.4.128.35
10.8.128.35
10.4.128.36
10.8.128.36
10.4.128.37
10.8.128.37
10.4.128.38
10.8.128.38
10.4.128.39
10.8.128.39
10.4.128.40
10.8.128.40
10.4.128.41
10.8.128.41
10.4.128.42
10.8.128.42
10.4.128.43
10.8.128.43
10.4.128.44
10.8.128.44
10.4.128.45
10.8.128.45
10.4.128.46
10.8.128.46
10.4.128.47
10.8.128.47
10.5.128.16
10.9.128.16
10.5.128.17
10.9.128.17
10.5.128.18
10.9.128.18
10.5.128.19
10.9.128.19
10.5.128.20
10.9.128.20
10.5.128.21
10.9.128.21
10.5.128.22
10.9.128.22
10.5.128.23
10.9.128.23
10.5.128.24
10.9.128.24
Control Network Specifications
D800001X312 
April 2021
425

--- Page 426 ---

Table G-28: Reserved IP Addresses for Switches and the DeltaV Firewall IPD
(continued)
Checklist
Primary Ethernet Reservation
Secondary Ethernet
Reservation
Pri.
Sec.
IP Address
Device name
IP Address
Device name
10.5.128.25
10.9.128.25
10.5.128.26
10.9.128.26
10.5.128.27
10.9.128.27
10.5.128.28
10.9.128.28
10.5.128.29
10.9.128.29
10.5.128.30
10.9.128.30
10.5.128.31
10.9.128.31
10.5.128.32
10.9.128.32
10.5.128.33
10.9.128.33
10.5.128.34
10.9.128.34
10.5.128.35
10.9.128.35
10.5.128.36
10.9.128.36
10.5.128.37
10.9.128.37
10.5.128.38
10.9.128.38
10.5.128.39
10.9.128.39
10.5.128.40
10.9.128.40
10.5.128.41
10.9.128.41
10.5.128.42
10.9.128.42
10.5.128.43
10.9.128.43
10.5.128.44
10.9.128.44
10.5.128.45
10.9.128.45
10.5.128.46
10.9.128.46
10.5.128.47
10.9.128.47
Emerson recommends that 10.4.128.17 and 10.8.128.17 be assigned to a TFTP server
and/or an Ethernet Management station. (A TFTP server and an Ethernet Management
station can be created on the same device.) A TFTP server can be used to flash Ethernet
switches or archive Ethernet switch configurations. Refer to “Managing Cisco Switches” in
Books Online for more information. It is recommended that the remaining addresses in
this block be assigned to the managed Ethernet switches.
Control Network Specifications
April 2021
D800001X312
426

--- Page 427 ---

G.11
DeltaV Zones
DeltaV Zones is a combination of hardware and software for connecting separate DeltaV
systems or Zones. An Inter-Zone Server (IZS) must be installed in each DeltaV system to
implement zones. The Inter-Zone Servers are connected by an Inter-Zone Control Network
(IZCN). The only function of the Inter-Zone Servers and the Inter-Zone Control Network is
to communicate inter-zone operating data between systems. Refer to DeltaV Books
Online for complete information on implementing zones, zone-to-zone data
communication, and security considerations.
The following figure shows a simple Inter-Zone Control Network in which two DeltaV
systems are connected. It shows how the Inter-Zone Servers connect to the DeltaV
network and to each other.
Figure G-88: Simple Inter-Zone Control Network
Inter-Zone
Server A
Inter-Zone
Server B
ProPLUS 
Station A
Operator
Station A
Zone A
Primary
Primary
Secondary
Primary
ProPLUS
Station B
Operator
Station
Zone B
Secondary
Inter-Zone
Control
Network
 B
Controller A
Controller B
Secondary
1
2
2
1
1
1
1
1
1
1
1
1
1
1
1
1
2
1
100 m (max) straight-through cable. To prevent ground loops, build this cable
assembly with a shielded, metal-enclosed RJ45 connector on one end and an
isolated, plastic-enclosed RJ45 connector on the other end. The metal connector
end of this cable assembly/link must be placed on the switch and not on the PC.
Control Network Specifications
D800001X312 
April 2021
427

--- Page 428 ---

2
100 m (max) straight-through cable. The shield on the controller’s RJ45 connector
connects only to a Faraday cage in the controller; not to the controller’s DC
ground. Therefore, the RJ45 connectors are floating and the single point of ground
is made at the hub or switch to which the controller is connected. Build this cable
assembly with a shielded, metal-enclosed RJ45 connector on both ends.
G.12
1420 Wireless Gateway
The 1420 Wireless Gateway integrates signals from HART wireless devices into the DeltaV
system. Refer to the documentation that ships with the 1420 Wireless Gateway for
specifications and information on how to properly mount the Gateway and connect it to
the DeltaV system.
Control Network Specifications
April 2021
D800001X312
428