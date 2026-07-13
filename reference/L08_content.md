--- Page 58 ---

• The voltage at the last carrier is greater than 11 volts.
• Bussed field power is 24 VDC or 115/230 VAC as applicable.
For 12 VDC systems with redundant System Power Supplies, remove one power supply
before verifying the voltage.
For 24 VDC systems verify that:
• The voltage at the System Power Supply (Dual DC/DC) is 24.2-24.6 volts.
• The voltage at the last carrier is greater than 11 volts.
• Bussed field power is 24 VDC or 115/230 VAC as applicable.
For 24 VDC systems with redundant System Power Supplies, remove one power supply
before verifying the voltage.
Check output loading and verify that the voltages (where present) are in the proper range
at all associated screw terminal connections. Also, verify that the expected load is within
the capacity of the unit.
Related information
Installation Worksheets
3.1.3
Step 3. Checking the LED Indicators on Each Device
The LED indicators on the system devices show important basic operating data. Following
are tables that describe the LEDs for each hardware component and provide corrective
action for faults.
System Power Supply LEDs
This table describes the LED indicators for the System Power Supply (AC/DC) and the
System Power Supply (Dual DC/DC).
Table 3-1: System Power Supply LEDs
LED
Correct
Operating
Conditions
Fault Indications
Probable Cause
Corrective
Action
Green – Power
On
Off
1. Power is not
supplied to unit.
Possible line
power problem.
1. Check supply
power and
connections.
2. Internal fault
2. Contact
technical support.
Red – Error
Off
On
1. Outputs are
outside of
tolerance.
Verify loading
calculations.
2. Input over
voltage. Unit
shuts down.
2. Check input
supply voltages.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
58

--- Page 59 ---

Controller LEDs
The following table describes the LEDs for the MD Plus, MX, and MQ controllers.
Table 3-2: Controller LEDs
LED
Correct
Operating
Condition
Fault Indication
Probable Cause
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
2. Internal fault
2. Contact
technical support.
Red – Error
Off
On (continuous)
Internal fault
Contact technical
support.
On for one second
followed by all
LEDs on for five
seconds.
Unit went
through RESET
due to an
unrecoverable
software error.
Contact customer
support.
Flashing
The controller is
decommissioned.
Commission the
controller.
Green – Active
On
Off
1. Controller is a
Standby.
1. None - Green
Standby is on.
2. Controller not
commissioned.
2. Commission
controller.
3. Internal fault.
3. Contact
technical support.
Flashing
Controller is not
configured.
Download
controller
configuration.
Green – Standby
Off
On
Controller is a
Standby.
None
Flashing
Controller is not
configured.
Download
controller
configuration.
Yellow - Pri. CN
Communications
attempted and
indicator flashing
Off –
Communications
attempted and
indicator not
flashing.
Controller lacks
active Ethernet
communications
on primary
Control Network
connection.
Check primary
network cable
connections and
switch
connections.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
59

--- Page 60 ---

Table 3-2: Controller LEDs (continued)
LED
Correct
Operating
Condition
Fault Indication
Probable Cause
Corrective
Action
Yellow - Sec. CN
Communications
attempted and
indicator flashing
Off –
Communications
attempted and
indicator not
flashing.
Controller lacks
active Ethernet
communications
on secondary
Control Network
connection.
Check secondary
network cable
connections and
switch
connections.
Remote Interface Unit LEDs
The following table describes the LED indicators for the Remote Interface Unit.
Table 3-3: Remote Interface Unit LEDs
LED
Correct
Operating
Condition
Fault Indication
Probable Cause
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
technical support
Red – Error
Off
On (continuous)
Internal fault.
Contact technical
support
On for one second
followed by all
LEDs on for five
seconds.
Unit went
through RESET
due to an
unrecoverable
software error.
Contact customer
support.
Flashing
The Remote
Interface Unit is
decommissioned.
Commission the
Remote Interface
Unit.
Green – Active
On
Off
1. Remote
Interface Unit is
not
commissioned.
1. Commission
the Remote
Interface Unit.
2. Internal fault.
2. Contact
technical support.
Flashing
Remote Interface
Unit is not
configured.
Download
configuration.
Green – Standby
Off (Redundancy
not supported)
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
60

--- Page 61 ---

Table 3-3: Remote Interface Unit LEDs (continued)
LED
Correct
Operating
Condition
Fault Indication
Probable Cause
Corrective
Action
Yellow - Pri. CN
Communications
attempted and
indicator flashing
Off –
Communications
attempted and
indicator not
flashing.
Remote Interface
Unit lacks active
Ethernet
communications
on primary
Control Network
connection.
Check primary
network cable
connections and
hub connections.
Yellow - Sec. CN
Communications
attempted and
indicator flashing
Off –
Communications
attempted and
indicator not
flashing.
Remote Interface
Unit lacks active
Ethernet
communications
on secondary
Control Network
connection.
Check secondary
network cable
connections and
hub connections.
Media Converter LEDs
The following table describes the LEDs for the Media Converter.
Table 3-4: Media Converter LEDs
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
Power is not
supplied to unit.
Possible line
power problem.
Check power
supply and
connections.
Red – Error
Off
On
Internal fault.
Contact technical
support.
Green – Pri. F Lnk
On
Off
Fiber-optic cable
is incorrectly
connected.
Check fiber-optic
cable connection.
(Connects
transmit to
receive.)
Green – Pri. C Lnk
On
Off
Twisted pair cable
is incorrectly
connected.
Check cable
pinouts.
Green – Sec. F Lnk
On
Off
Fiber-optic cable
is incorrectly
connected.
Check fiber-optic
cable connection.
(Connects
transmit to
receive.)
Green – Sec. C Lnk On
Off
Twisted pair cable
is incorrectly
connected.
Check cable
pinouts.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
61

--- Page 62 ---

DeltaV Fiber Switches LEDs
The following tables describe the LEDs on the Fiber Switches.
Table 3-5: Fiber Switches' Power LEDs
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
unit.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red – Error
Off
On (continuous)
Internal fault.
Contact technical
support.
Table 3-6: Fiber Switches' Twisted Pair Port LEDs
LED
Status
Link Act
    
             
•
On - Link
•
Blinking - Activity
•
Off - No link. Check the cable connection.
FD COL
•
On - Full Duplex
•
Blinking - Collision
•
Off - Half Duplex
100 10
•
On - 100 MHz
•
Off - 10 MHz
LED
Status
Link Act
•
On - Link
•
Blinking - Activity
•
Off - No link.
DeltaV Controller Firewall LEDs
The following tables describe the LEDs on the DeltaV Controller Firewall
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
62

--- Page 63 ---

Table 3-7: DeltaV Controller Firewall Power LEDs
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green – Power
Supply 1 (P1),
Power Supply 2
(P2)
On
Off
System power is
not supplied to
unit or voltage is
less than 9.6 VDC
Check supply
power and
connections.
Red – Fault
Off
On
Internal fault.
Contact technical
support.
Table 3-8: DeltaV Controller Firewall Device Status LEDs
LED
Status
STATUS - Device
status
•
Flashing green - device is initializing
•
Solid green - Device is operational
LED
Status
LS/DA 1, 2, V.24 -
Link status
•
Solid green - valid link
•
Blinking green - port is disabled
•
Running light - initialization phase after a reset
•
Off - no link. Check the cable connection.
AI 8-Channel Card LEDs
The following table describes the LEDs for the pre-Series 2 and Series 2 AI, 8-channel, 4–20
mA card; the AI, 8-channel, 4–20 mA, HART card; and the AI, 8-channel, 1-5 VDC card.
Table 3-9: AI Card LEDs
LED
Correct Operating
Condition
Fault
Indication
Possible Cause
Corrective Action
Green – Power
Green Power/
Active
•
pre-Series 2 - On
•
Series 2 Simplex -
On
•
Series 2
Redundant:
—
Active - On
—
Standby -
Flashing
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
Red-Error
Off
pre-Series 2
and Series 2 On
(continuous)
1. No bussed field
power.
1. Check bussed
field power and
connections.
2. Controller is
not scanning
card.
2. Check
controller
operation.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
63

--- Page 64 ---

Table 3-9: AI Card LEDs (continued)
LED
Correct Operating
Condition
Fault
Indication
Possible Cause
Corrective Action
3. Unit failed self-
test.
3. Contact
technical support.
pre- Series 2
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
card of same type;
contact technical
support.
Redundant
Series 2
Flashing
1. No bussed field
power.
1. Check bussed
field power and
connections. Use
the DeltaV
Diagnostics Clear
Saved Fault
Information
command when
problem fixed.
2.Controller is not
scanning card.
2. Check
controller
operation.
3. Hardware error. 3. Replace card
with known good
card of same type;
contact technical
support.
Simplex Series
2 Flashing
Controller is not
scanning card.
Check controller
operation.
Yellow - Ch.1 to
Ch. 8
On
Off
1. Input is out of
range and
channel is
disabled. (See
specifications in
the "Interface
Specifications"
section.)
1. Check input
source and
connections.
2. No bussed field
power.
2. Check bussed
field power and
connections.
3.Internal fault.
3. Contact
technical support.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
64

--- Page 65 ---

Table 3-9: AI Card LEDs (continued)
LED
Correct Operating
Condition
Fault
Indication
Possible Cause
Corrective Action
Flashing
1. Input is out of
range and
channel is
disabled. (See
specifications in
the "Interface
Specifications"
section.)
1. Check input
source and
connections.
2. No bussed field
power.
2. Check bussed
field power and
connections.
3. Channel is
configured for
HART, but there is
no HART
communication.
3. Check HART
input source and
connections.
4. Channel is
configured for
NAMUR limits and
they have been
exceeded.
4. Check input
levels compared
to NAMUR limits
Refer to the Configuration manual in Books Online or more information on
troubleshooting HART devices.
Related information
Interface Specifications
AI 16-Channel Card LEDs
The following table describes the LED indicators for the Series 2 AI, 16-Channel, 4-20 mA,
HART card in Simplex mode.
Table 3-10: AI 16-Channel Card LEDS
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green-Power
On
Off
1. System power
is not supplied to
unit. Possible line
power problem
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red - Error
Off
On
1. No bussed field
power.
1. Check bussed
field power and
connections.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
65

--- Page 66 ---

Table 3-10: AI 16-Channel Card LEDS (continued)
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
2. Controller is
not scanning
card.
2. Check
controller
operation.
3. Unit failed self-
test.
3. Contact
technical support.
Flashing
1. No bussed field
power.
1. Check bussed
field power and
connections.
2. Controller is
not scanning
card.
2. Check
controller
operation.
3. Hardware error. 3. Replace card
with known good
card of same
type; contact
technical support.
AO 8-Channel Card LEDs
The following table describes the LEDs for the pre-Series 2 and Series 2 AO, 8-channel 4–
20 mA card and the AO, 8-channel, 4-20 mA, HART card.
Table 3-11: AO 8-Channel Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green – Power
Green Power/
Active
•
pre-Series 2 -
On
•
Series 2
Redundant:
•
Active - On
•
Standby -
Flashing
Off
1. System power
is not supplied to
unit. Possible line
power problems.
1. Check supply
power and
connections
2. Internal fault.
2. Contact
technical support.
Red-Error
Off
pre-Series 2 and
Series 2 On
(continuous)
1. Unit failed self-
test.
1. Contact
technical support.
2. Controller is
not scanning
card.
2. Check
controller
operation
pre-Series 2
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
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
66

--- Page 67 ---

Table 3-11: AO 8-Channel Card LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
3. Address
conflict.
3. Replace card
with known good
card of same
type; contact
technical support.
Redundant Series
2 Flashing
1. No bussed field
power.
1. Check bussed
field power and
connections. Use
the DeltaV
Diagnostics Clear
Saved Fault
Information
command when
the problem is
fixed.
2. Controller is
not scanning
card.
2. Check
controller
operation.
3. Hardware error. 3. Replace with
known good card
of same type;
contact technical
support.
Simplex Series 2
Flashing
Controller is not
scanning card.
Check controller
operation.
Yellow - Ch1. to
Ch. 8
On
Off
1. No output
device (load) and
channel is
disabled.
1. Check output
connections.
2. Bussed field
power not
supplied to unit.
2. Check bussed
field power and
communications.
3. Internal fault.
3. Contact
technical support.
Flashing
1. No output
device (load) and
channel is
enabled.
1. Check output
connections.
2. Bussed field
power not
supplied to unit.
2. Check bussed
field power and
connections.
3. Channel is
configured for
HART, but there is
no HART
communication.
3. Check HART
input source and
connections.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
67

--- Page 68 ---

Table 3-11: AO 8-Channel Card LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
4. Internal fault.
4. Contact
technical support.
Refer to the Configuration manual in Books Online for more information on
troubleshooting HART devices.
AS-Interface Card LEDs
Table 3-12: 
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
Yellow – Port 1
and Port 2
On
Off
No
communications.
Check
connections,
cable, and
external device.
Flashing
Communications
error on this port.
Check
connections,
cable, and
external device.
DeviceNet Card LEDs
The following table describes the LEDs for the DeviceNet and Series 2 DeviceNet cards.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
68

--- Page 69 ---

Table 3-13: DeviceNet Card LEDs
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
Yellow - Port 1
Port 2 (reserved)
On
Off
1. No
communications.
1. Check
connections,
cable, and
external device.
2. Port not
enabled
2. Enable port.
3. No
configuration for
this port.
3. Configure port.
Flashing
Communication
error on this port.
Check
connections,
cable, and
external device.
DI 8-Channel Card LEDs
The following table describes the LEDs for the pre-Series 2 and Series 2 8-channel DI cards
(24 VDC isolated and dry contact, and 120/230 VAC isolated and dry contract).
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
69

--- Page 70 ---

Table 3-14: DI 8-Channel Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green - Power
Green Power/
Active
•
pre-Series 2 -
On
•
Series 2 Simplex
-On
•
Series 2
Redundant:
—
Active - On
—
Standby -
Flashing
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
pre-Series 2 and
Series 2 On
(continuous)
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
pre-Series 2 -
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Address
conflict.
2. Replace with
known good card
of same type;
contact technical
support.
Series 2 - Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Hardware error. 2. Replace card
with known good
card of same
type; contact
technical support.
Yellow - Ch.1 to
Ch. 8
•
On = input >
detection level.
•
Off = input <
detection level.
Refer to the
"Interface
Specifications"
section for
detection levels for
each DI card type.
Related information
Interface Specifications
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
70

--- Page 71 ---

DI Mass Connection Board LEDs
The following table describes the LEDs on the Series 2 DI Mass Connection Board and the
Series 2 Plus DI Mass Connection Board.
Table 3-15: DI Mass Connection Board LEDs
Type of LED
Status
Meaning
Power (green)
On (green)
The mass connection board is
receiving power.
Off
The mass connection board is
not receiving power.
Channel (yellow for Series 2;
orange/brown for Series 2 Plus)
On (yellow for Series 2; orange/
brown for Series 2 Plus)
The channel signal is available.
Off
The channel signal is not
available.
DO 8-Channel Card LEDs
Table 3-16: DO 8-Channel Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective Action
Green-Power
Green Power/
Active
•
pre-Series 2 - On
•
Series 2 Simplex -
On
•
Series 2
Redundant:
—
Active - On
—
Standby -
Flashing
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
Red
Off
pre-Series 2 and
Series 2 On
(continuous)
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
pre-Series 2
Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Address
conflict.
2. Replace with
known good card
of same type;
contact technical
support.
Series 2 Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
71

--- Page 72 ---

Table 3-16: DO 8-Channel Card LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective Action
2. Hardware error. 2. Replace with
known good card
of same type;
contact technical
support.
Yellow - Ch. 1
to Ch. 8
Depends on setpoint
and configuration.
DO 32-Channel Card LEDs
The following table describes the LEDs for the DO, 32-channel, 24 VDC, high-side and
Series 2 DO, 32-channel, 24 VDC, high-side cards.
Table 3-17: DO 32-Channel Card LEDs
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green-Power
On
Off
1. Power is not
supplied to unit.
1. Check supply
power and
connections.
2. Internal fault
2. Contact
technical support.
Red - Error
Off
On (continuous)
Communications
error.
Check
connections,
cable, and
external device.
Flashing
Address conflict.
Replace card with
known good card
of same type;
contact technical
support.
DO Mass Connection Board LEDs
Table 3-18: DO Mass Connection Board LEDs
Type of LED
Status
Meaning
Power (green)
On (green)
The mass connection board is
receiving power.
Off
The mass connection board is
not receiving power.
Channel (yellow)
On (yellow)
The channel is turned on.
Off
The channel is turned off.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
72

--- Page 73 ---

Fieldbus H1 Card LEDs
The following table describes the LEDs for the Fieldbus H1 and Series 2 Fieldbus H1 cards.
Table 3-19: Fieldbus H1 Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green-Power
Green Power/
Active
•
pre-Series 2 -
On
•
Series 2
Simplex - On
•
Series 2
Redundant:
—
Active - On
—
Standby -
Flashing
Off
1. System power
is not supplied to
unit. Possible line
power problem.
1. Check supply
power and
connections.
2. Internal fault
2. Contact
technical support.
pre-Series 2 and
Series 2 Flashing
Series 2 Red:
•
Active-
Flashing
•
Stby-Flashing
Incorrect terminal
block for
configured card
type
Install redundant
terminal blocks
for Series 2
redundant cards
and simplex
terminal blocks
for simplex and/or
pre-Series 2 cards.
Red - Error
Off
pre-Series 2 and
Series 2: On
(continuous)
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Unit failed self-
test.
2.Contact
technical support.
pre-Series 2
Flashing
1. Controller is
not scanning
card.
1.Check
controller
operation.
2. Address
conflict.
2. Replace card
with known good
card of same type;
contact technical
support.
Series 2 Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Hardware error. 2. Replace card
with known good
card of same type;
contact technical
support.
Yellow - Port 1
and Port 2
On
Off
1. No
communications.
1. Check
connections,
cable and external
devices.
2. Port not
enabled.
2. Enable port.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
73

--- Page 74 ---

Table 3-19: Fieldbus H1 Card LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
3. Configuration
mismatch. (Such
as redundant card
configured in
database and
simplex card
installed.)
3. Fix
configuration
errors.
Flashing
1.
Communication
error on this port.
1. Check
connections,
cable, and
external device.
2. No
configuration for
this port.
2. Configure port.
Isolated Input Card LEDs
The following table describes the LEDs for the Series 2 Isolated Input card.
Table 3-20: Series 2 Isolated Input Card LEDs
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
On (Continuous)
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
Multifunction Card LEDs
The following table describes the LEDs for the Multifunction card.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
74

--- Page 75 ---

Table 3-21: Multifunction Card LEDs
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
Red - Error
Off
On (continuous)
1. Controller is
not scanning card
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
operation
2. Address
conflict.
2. Replace card
with known good
card of same
type; contact
technical support.
Profibus DP Card LEDs
The following table describes the LEDs for the Profibus DP, Series 2 Profibus DP (Simplex)
and Series 2 Plus Profibus DP (Simplex and Redundant) cards.
Table 3-22: Profibus DP Card LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green -
Power
•
Profibus DP and
Simplex Series 2
Profibus DP- On
•
Series 2 Plus Profibus
DP Redundant:
—
Active - On
—
Standby -
Flashing
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
not scanning card
1. Check
controller
operation.
2. Unit failed self-
test.
2. Contact
technical support.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
75

--- Page 76 ---

Table 3-22: Profibus DP Card LEDs (continued)
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
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
Yellow -
Port 1
Port 2
(reserved)
On
Off
1. No
communications.
1. Check
connections,
cable, and
external device.
2. Port not
enabled.
2. Enable port.
3. No
configuration for
this port.
3. Configure port.
Flashing
Communication
error on this port.
Check
connections,
cable, and
external device.
RTD, ohms and Thermocouple, mV Cards LEDs
The following table describes the LEDs for the RTD, ohms and Thermocouple, mV cards.
Table 3-23: RTD, ohms and Thermocouple, mV Cards LEDs
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
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
76

--- Page 77 ---

Table 3-23: RTD, ohms and Thermocouple, mV Cards LEDs (continued)
LED
Correct
Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
2. Address
conflict.
2. Replace card
with known good
card of same
type; contact
technical support.
Yellow – Ch. 1 to
Ch. 8
On
Off
1. Channel not
configured.
1. Enable channel
and download
card.
2. Internal fault.
2. Contact
technical support.
Flashing
1. Invalid
configuration.
1. Check
configuration.
2. Input is out of
range.
2. Check input
source and
connections.
3. Internal fault.
3. Contact
technical support.
Related information
Interface Specifications
Sequence of Events Card LEDs
The following table describes the LEDs for the Sequence of Events card.
Table 3-24: Sequence of Events Card LEDs
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
1. Power is not
supplied to unit.
1. Check supply
power and
connections.
2. Internal fault.
2. Contact
technical support.
Red - Error
Off
On (continuous)
Communications
error.
Check
connections,
cable, and
external device.
Flashing
Address conflict.
Replace card with
known good card
of same type;
contact technical
support.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
77

--- Page 78 ---

Serial Card, 2 Ports, RS232/RS485 LEDs
Table 3-25: Serial Card, 2 Ports, RS232/RS485 LEDs
LED
Correct Operating
Condition
Fault Indication
Possible Cause
Corrective
Action
Green - Power
Green Power/
Active
•
pre-Series 2 -
On
•
Series 2
Simplex - On
•
Series 2
Redundant
—
Active - On
—
Standby -
Flashing
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
pre-Series 2 and
Series 2 - On
(continuous)
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
pre-Series 2
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
Series 2 Flashing
1. Controller is
not scanning
card.
1. Check
controller
operation.
2. Hardware error. 2. Replace card
with known good
card of same
type; contact
technical support.
Yellow - Port 1
and Port 2
(configured as
Master)
On
Off
No
communications.
Check
connections,
cable, and
external device.
Flashing
Communications
error on this port.
Check
connections,
cable, and
external device.
Checking Out and Troubleshooting Your DeltaV System
April 2021
D800001X312
78

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