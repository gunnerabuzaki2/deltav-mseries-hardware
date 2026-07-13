--- Page 443 ---

J
System Power Guidelines
This section contains important information about DeltaV system power. Refer to the
DeltaV Power and Grounding manual for additional information.
J.1
System Power Supply (AC/DC)
One System Power Supply (AC/DC) is sufficient for many small systems. The power supply
provides 1.25 A of LocalBus power, enough for:
• 8 discrete I/O cards
or
• 8 analog I/O cards
or
• 4 serial I/O cards
or
• 4 Series 2 H1 cards
Refer to the installation worksheets for complete information on calculating system power
for all I/O card combinations.
For systems that require additional power, use another System Power Supply (AC/DC) for
load sharing. For systems that require redundant power, connect a second System Power
Supply (AC/DC).
Other options for systems that require additional power are the System Power Supply
(Dual DC/DC) with a bulk power supply. These options do not require an additional two-
wide carrier and are good choices when future expansion is anticipated.
Related information
Installation Worksheets
J.2
System Power Supply (Dual DC/DC)
When it is operated on 12 VDC, the System Power Supply (Dual DC/DC) is rated for a
maximum of 13 A of LocalBus power which is sufficient for most large DeltaV systems.
When it is operated on 24 VDC, the System Power Supply (Dual DC/DC) is rated for a
maximum of 8 A (4.5 A for older models) of LocalBus power. For systems that require
additional power, use another System Power Supply (Dual DC/DC). For systems that
require redundant power, use a second System Power Supply (Dual DC/DC).
System Power Guidelines
D800001X312 
April 2021
443

--- Page 444 ---

Figure J-1: Simplex dual DC/DC system power supply with 12 VDC input
Top View
Carrier
Terminal Strip
Notes:
1
Dual DC/DC
System Power
Supply
From DC/DC
Power Supply 
or AC/DC Bulk 
Power Supply
12 VDC
Return
12 VDC
1
A fuse block and fuse are optional. If you are providing DC power to several DC/DC
passthrough system power supplies by the same bulk power supply, fuse the line to 
each supply.
.
Always use pre-formed metal shorting bars to ensure a good connection. Do not use individual
jumper wires.
Fuse
Block
12 VDC
12 VDC Return
(Ground)
DIN rail mounted
DC Power Bus (+)
2
2
DIN rail mounted
DC Return Bus (−)
System Power Guidelines
April 2021
D800001X312
444

--- Page 445 ---

Figure J-2: Redundant dual DC/DC system power supply with 12 VDC input
Top View
Carrier
Terminal Strip
Notes:
Use separate DC power busses as shown. Then, for optimum power redundancy, connect
each system power supply to separate DC bulk power supplies.
Always use pre-formed metal shorting bars to ensure a good connection. Do not use
individual jumper wires.
1
Primary Dual
DC/DC System
Power Supply
Secondary Dual
DC/DC System
Power Supply
12 VDC
Return
12 VDC
12 VDC
12 VDC Return
(Ground)
From DC Bulk
Power Supply
Fuse
Block
12 VDC
From DC Bulk
Power Supply
12 VDC
Return
DIN rail mounted
DC Power Bus (+)
1
1
2
2
2
DIN rail mounted
DC Return Bus (−)
System Power Guidelines
D800001X312 
April 2021
445

--- Page 446 ---

Figure J-3: Simplex dual DC/DC system power supply with 24 VDC input
Top View
Carrier
Terminal Strip
Notes:
1
Dual DC/DC
System Power
Supply
From DC
Bulk Power
Supply
24 VDC
Return
24 VDC
2
2
Use the left-hand terminal screw only.
A fuse block and fuse are optional. If you are providing DC power to several DC/DC passthrough system power
supplies by the same bulk power supply, it is recommended that you fuse the line to each supply.
Always use pre-formed metal shorting bars to ensure a good connection. Do not use individual jumper wires.
Fuse
Block
24 VDC
24 VDC Return
(Ground)
DC
Return
Reference
Ground
1
To DC Gnd Bus
in enclosure
DIN rail mounted
DC Power Bus (+)
3
3
DIN rail mounted
DC Return Bus (−)
System Power Guidelines
April 2021
D800001X312
446

--- Page 447 ---

Figure J-4: Redundant dual DC/DC system power supply with 24 VDC input
To DC Gnd Bus
in Enclosure
Notes:
Use separate sets of DC power busses as shown. Then, for optimum power redundancy, connect each system
power supply to separate DC bulk power supplies.
Use the left-hand terminal screw only. Only one ground wire is necessary because the return side of both DC
power supplies is internally connected to the ground terminal of either terminal strip.
Always use pre-formed metal shorting bars to ensure a good connection. Do not use individual jumper wires.
1
2
DC
Return
Reference
Ground
3
Top View
Carrier
Terminal Strip
Primary Dual
DC/DC System
Power Supply
Secondary Dual
DC/DC System
Power Supply
24 VDC
Return
24 VDC
From DC Bulk
Power Supply
Fuse
Block
24 VDC
From DC Bulk
Power Supply
24 VDC
Return
DIN rail mounted
DC Power Bus (+)
1
1
2
DIN rail mounted
DC Return Bus (−)
3
3
24 VDC
24 VDC Return
(Ground)
J.3
100-240 VAC to 12 VDC 15 A DeltaV Bulk Power
Supply
Installation notes
• The following information applies only to part number KJ1503X1-BA1. For other DeltaV
bulk power supplies with similar characteristics, you can obtain documentation from
Emerson Global Support Center at 800-833-8314.
• Install this bulk power supply on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
System Power Guidelines
D800001X312 
April 2021
447

--- Page 448 ---

50% of the rated power. Increase this clearance to 15 mm if the adjacent device is a
heat source such as another power supply.
Specifications
Table J-1: 100-240 VAC to 12 VDC 15 A DeltaV Bulk Power Supply
Item
Specification
Output voltage
12 VDC
Output adjustment range
12-15 VDC
Output current
•
15-13.5 A continuous
•
22.5-20.3 A for 4 seconds (typical)
Output power
•
180 W continuous at 12 VDC
•
270 W for 4 seconds at 12 VDC (typical)
Output ripple
< 50 mV peak-to-peak at 20 Hz to 20 MHz
Output holdup time
AC input
•
72 ms typical at 100 VAC, 12 V, 7.5 A
•
31 ms typical at 100 VAC, 12 V, 15 A
•
72 ms typical at 120 VAC, 12 V, 7.5 A
•
32 ms typical at 120 VAC, 12 V, 15 A
•
72 ms typical at 230 VAC, 12 V, 7.5 A
•
32 ms typical at 230 VAC, 12 V, 15 A
DC input
•
31 ms typical at 110 VDC
Operational temperature range
-25°C to + 70°C
Output derating at higher temperature
5 W/°C at +60°C to +70°C
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
AC input voltage
•
100-240 VAC ± 15%
•
110-150 VDC -20%/+25%
AC mains frequency
50-60 Hz ± 6%
AC input current
•
1.65 A at 120 VAC
•
0.93 A at 230 VAC
AC power factor
•
0.98 at 120 VAC
•
0.92 at 230 VAC
System Power Guidelines
April 2021
D800001X312
448

--- Page 449 ---

Table J-1: 100-240 VAC to 12 VDC 15 A DeltaV Bulk Power Supply (continued)
Item
Specification
AC inrush current
•
10 A peak maximum at 100 VAC over entire
temperature range
•
5 A peak typical at 100 VAC over entire
temperature range
•
10 A peak maximum at 120 VAC over entire
temperature range
•
4 A peak typical at 120 VAC over entire
temperature range
•
10 A peak maximum at 230 VAC over entire
temperature range
•
7 A peak typical at 230 VAC over entire
temperature range
AC efficiency
•
91.5% at 120 VAC
•
91.8% at 230 VAC
AC losses
•
16.7 W at 120 VAC
•
16.1 W at 230 VAC
DC input voltage
100-300 VDC ±20%
DC input current
1.78 A at 110 VDC
DC power factor
1 or N/A at 110 VDC
DC inrush current
•
10 A peak maximum
•
5 A peak typical
DC efficiency
91% at 110 VDC
DC losses
17.8 W at 110 VDC
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 6 cm (2.4 inches)
Depth: 11.7 cm (4.6 inches)
Terminals and wiring
Bistable, quick-connect spring-clamp terminals with IP20 finger safe construction are
used. The terminals are shipped in the open position and are suitable for field installation.
Use wire that complies with local codes and regulations.
Wire type
Input spring-clamp
terminals
Output spring-clamp
terminals
DC-OK-Signal spring-
clamp terminals
Solid wire
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
Stranded wire
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
System Power Guidelines
D800001X312 
April 2021
449

--- Page 450 ---

Connectors and LEDs
The following image shows the connectors and LEDs on the bulk power supply. The labels
on the input and output terminals are self-explanatory (Neutral (-), Line (+), protective
earth ( ), positive (+) and negative (-) output). Additional information about the relay
contact operation follows the image. Refer to the Related information section for
information on the LEDs.
Figure J-5: Connectors and LEDs on the 100-240 VAC to 12 VDC 15 A DeltaV Bulk
Power Supply
Output terminals
Output voltage potentiometer 
(factory set at 12 VDC)
DC OK LED (green)
Input terminals
Overload LED (red)
DC OK relay contact
DC OK Relay Contact operation
The DC OK relay contact monitors the bulk power supply's output voltage. It is
synchronized with the DC OK LED.
• Closed contact: the output voltage has reached the adjusted output voltage level.
• Open contact: voltage has dipped to more than 10% below the adjusted output
voltage. Short dips are extended to a signal length of 250 ms. Dips shorter than 1 ms
are ignored.
• Reclosed contact: the output voltage has exceeded 90% of the adjusted voltage.
• Contact ratings maximum resistive load: 60 VDC at 0.3 A, 30 VDC at 1 A, 30 VAC at 0.5
A
• Contact ratings minimum permissible load: 1 mA at 5 VDC
System Power Guidelines
April 2021
D800001X312
450

--- Page 451 ---

J.4
100-240 VAC to 24 VDC 5 A DeltaV Bulk Power
Supply
Installation notes
• The following information applies only to part number KJ1503X1-BB1. For other DeltaV
bulk power supplies with similar characteristics, you can obtain documentation from
Emerson Global Support Center at 800-833-8314.
• Install this bulk power supply on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated power. Increase this clearance to 15 mm if the adjacent device is a
heat source such as another power supply.
Specifications
Table J-2: 100-240 VAC to 24 VDC 5 A DeltaV Bulk Power Supply
Item
Specification
Output voltage
24 VDC
Output adjustment range
24-28 VDC
Output current
•
5-4.5 A continuous
•
7.5-6.7 A for 4 seconds (typical)
Output power
•
120 W continuous
•
180 W for 4 seconds (typical)
Output ripple
< 50 mV peak-to-peak at 20 Hz to 20 MHz
Output holdup time
AC input
•
66 ms typical at 100 VAC, 24 V, 2.5 A
•
34 ms typical at 100 VAC, 24 V, 5 A
•
66 ms typical at 120 VAC, 24 V, 2.5 A
•
34 ms typical at 120 VAC, 24 V, 5 A
•
127 ms typical at 230 VAC, 24 V, 2.5 A
•
65 ms typical at 230 VAC, 24 V, 5 A
DC input
•
34 ms at 110 VDC (typical)
Operational temperature range
-25°C to + 70°C
Output derating at higher temperature
3 W/°C at +60°C to +70°C
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
System Power Guidelines
D800001X312 
April 2021
451

--- Page 452 ---

Table J-2: 100-240 VAC to 24 VDC 5 A DeltaV Bulk Power Supply (continued)
Item
Specification
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
AC input voltage
•
100-240 VAC +10% /-15%
•
110-300 VDC ± 20%
AC mains frequency
50-60 Hz ± 6%
AC input current
•
1.10 A at 120 VAC
•
0.62 A at 230 VAC
AC power factor
•
0.99 at 120 VAC
•
0.91 at 230 VAC
AC inrush current
•
15 A peak maximum at 100 VAC over entire
temperature range
•
8 A peak typical at 100 VAC over entire
temperature range
•
15 A peak maximum at 120 VAC over entire
temperature range
•
9 A peak typical at 120 VAC over entire
temperature range
•
15 A peak maximum at 230 VAC over entire
temperature range
•
11 A peak typical at 2300 VAC over entire
temperature range
AC efficiency
•
91% at 120 VAC
•
92.7% at 230 VAC
AC losses
•
11.0 W at 120 VAC
•
9.4 W at 230 VAC
DC input voltage
110 to 300 VDC ±20%
DC input current
1.19 A 110 VDC
DC power factor
1 or N/A at 110 VDC
DC inrush current
•
15 A peak maximum
•
8 A peak typical
DC efficiency
91% at 110 VDC
DC losses
11.9 W at 110 VDC
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 4 cm (1.6 inches)
Depth: 11.7 cm (4.6 inches)
System Power Guidelines
April 2021
D800001X312
452

--- Page 453 ---

Terminals and wiring
Bistable, quick-connect spring-clamp terminals with IP20 finger safe construction are
used. The terminals are shipped in the open position and are suitable for field installation.
Use wire that complies with local codes and regulations.
Wire type
Input spring-clamp
terminals
Output spring-clamp
terminals
DC-OK-Signal spring-
clamp terminals
Solid wire
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Stranded wire
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
2.5 mm2; 14 AWG
Maximum wire gauge:
2.5 mm2; 14 AWG
Connectors and LEDs
The following image shows the connectors and LEDs on the bulk power supply. The labels
on the input and output terminals are self-explanatory (Neutral (-), Line (+), protective
earth ( ), positive (+) and negative (-) output). Additional information about the relay
contact operation follows the image. Refer to the Related information section for
information on the LEDs.
Figure J-6: Connectors and LEDs on the 100-240 VAC to 24 VDC 5 A DeltaV Bulk Power
Supply
Output
terminals
DC OK
relay contact
Output voltage potentiometer 
(factory set at 24.1 VDC)
DC OK LED (green)
Overload LED (red)
Input terminals
System Power Guidelines
D800001X312 
April 2021
453

--- Page 454 ---

DC OK Relay Contact operation
The DC OK relay contact monitors the bulk power supply's output voltage. It is
synchronized with the DC OK LED.
• Closed contact: the output voltage has reached the adjusted output voltage level.
• Open contact: voltage has dipped to more than 10% below the adjusted output
voltage. Short dips are extended to a signal length of 250 ms. Dips shorter than 1 ms
are ignored.
• Reclosed contact: the output voltage has exceeded 90% of the adjusted voltage.
• Contact ratings maximum resistive load: 60 VDC at 0.3 A, 30 VDC at 1 A, 30 VAC at 0.5
A
• Contact ratings minimum permissible load: 1 mA at 5 VDC
J.5
100-240 VAC to 24 VDC 10 A DeltaV Bulk Power
Supply
Installation notes
• The following information applies only to part number KJ1503X1-BB2. For other DeltaV
bulk power supplies with similar characteristics, you can obtain documentation from
Emerson Global Support Center at 800-833-8314.
• Install this bulk power supply on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated power. Increase this clearance to 15 mm if the adjacent device is a
heat source such as another power supply.
Specifications
Table J-3: 100-240 VAC to 24 VDC 10 A DeltaV Bulk Power Supply
Item
Specification
Output voltage
24 VDC
Output adjustment range
24-28 VDC
Output current
•
10-9 A continuous
•
15-13.5 A for 4 seconds (typical)
Output power
•
240 W continuous
•
360 W for 4 seconds (typical)
Output ripple
< 50 mV peak-to-peak at 20 Hz to 20 MHz
System Power Guidelines
April 2021
D800001X312
454

--- Page 455 ---

Table J-3: 100-240 VAC to 24 VDC 10 A DeltaV Bulk Power Supply (continued)
Item
Specification
Output holdup time
AC input
•
51 ms typical at 100 VAC, 24 V, 5 A
•
26 ms typical at 100 VAC, 24 V, 10 A
•
53 ms typical at 120 VAC, 24 V, 5 A
•
27 ms typical at 120 VAC, 24 V, 10 A
•
55 ms typical at 230 VAC, 24 V, 5 A
•
28 ms typical at 230 VAC, 24 V, 10 A
DC input
•
26 ms typical at 110 VDC
Operational temperature range
-25°C to + 70°C
Output derating at higher temperature
6 W/°C at +60°C to +70°C
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
AC input voltage
•
100-240 VAC ±15%
AC mains frequency
50-60 Hz ± 6%
AC input current
•
2.22 A at 120 VAC
•
1.22 A at 230 VAC
AC power factor
•
0.98 at 120 VAC
•
0.92 at 230 VAC
AC inrush current
•
10 A peak maximum at 100 VAC over entire
temperature range
•
5 A peak typical at 100 VAC over entire
temperature range
•
10 A peak maximum at 120 VAC over entire
temperature range
•
4 A peak typical at 120 VAC over entire
temperature range
•
10 A peak maximum at 230 VAC over entire
temperature range
•
7 A peak typical at 230 VAC over entire
temperature range
AC efficiency
•
92.6% at 120 VAC
•
93.5% at 230 VAC
System Power Guidelines
D800001X312 
April 2021
455

--- Page 456 ---

Table J-3: 100-240 VAC to 24 VDC 10 A DeltaV Bulk Power Supply (continued)
Item
Specification
AC losses
•
19.1 W at 120 VAC
•
16.7 W at 230 VAC
DC input voltage
110 to 150 VDC -20%/+25%
DC input current
2.37 A at 110 VDC
DC power factor
1 or N/A at 110 VDC
DC inrush current
•
10 A peak maximum
•
5 A peak typical
DC efficiency
91.8% at 110 VDC
DC losses
21.4 W at 110 VDC
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 6 cm (2.3 inches)
Depth: 11.7 cm (4.6 inches)
Terminals and wiring
Bistable, quick-connect spring-clamp terminals with IP20 finger safe construction are
used. The terminals are shipped in the open position and are suitable for field installation.
Use wire that complies with local codes and regulations.
Wire type
Input spring-clamp
terminals
Output spring-clamp
terminals
DC-OK-Signal spring-
clamp terminals
Solid wire
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
Stranded wire
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Connectors and LEDs
The following image shows the connectors and LEDs on the bulk power supply. The labels
on the input and output terminals are self-explanatory (Neutral (-), Line (+), protective
earth ( ), positive (+) and negative (-) output). Additional information about the relay
contact operation follows the image. Refer to the Related information section for
information on the LEDs.
System Power Guidelines
April 2021
D800001X312
456

--- Page 457 ---

Figure J-7: Connectors and LEDs on the 100-240 VAC to 24 VDC 10 A DeltaV Bulk
Power Supply
Output terminals
Output voltage potentiometer 
(factory set at 24.1 VDC)
DC OK LED (green)
Input terminals
Overload LED (red)
DC OK relay contact
DC OK Relay Contact operation
The DC OK relay contact monitors the bulk power supply's output voltage. It is
synchronized with the DC OK LED.
• Closed contact: the output voltage has reached the adjusted output voltage level.
• Open contact: voltage has dipped to more than 10% below the adjusted output
voltage. Short dips are extended to a signal length of 250 ms. Dips shorter than 1 ms
are ignored.
• Reclosed contact: the output voltage has exceeded 90% of the adjusted voltage.
• Contact ratings maximum resistive load: 60 VDC at 0.3 A, 30 VDC at 1 A, 30 VAC at 0.5
A
• Contact ratings minimum permissible load: 1 mA at 5 VDC
System Power Guidelines
D800001X312 
April 2021
457

--- Page 458 ---

J.6
100-240 VAC to 24 VDC 20 A DeltaV Bulk Power
Supply
Installation notes
• The following information applies only to part numbers 1X00781H01L and KJ1503X1-
BB3. For other DeltaV bulk power supplies with similar characteristics, you can obtain
documentation from Emerson Global Support Center at 800-833-8314.
• Install this bulk power supply on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated power. Increase this clearance to 15 mm if the adjacent device is a
heat source such as another power supply.
Specifications
Table J-4: 100-240 VAC to 24 VDC 20 A DeltaV Bulk Power Supply
Item
Specification
Output voltage
24 VDC
Output adjustment range
24-28 VDC
Output current
•
20-17 A continuous
•
30-26 A for 4 seconds (typical)
Output power
•
480 W continuous
•
720 W for 4 seconds (typical)
Output ripple
< 100 mV peak-to-peak at 20 Hz to 20 MHz
Output hold-up time
•
64 ms typical at 100 VAC, 24 V, 10 A
•
32 ms typical at 100 VAC, 24 V, 20 A
•
64 ms typical at 120 VAC, 24 V, 10 A
•
32 ms typical at 120 VAC, 24 V, 20 A
•
99 ms typical at 230 VAC, 24 V, 10 A
•
51 ms typical at 230 VAC, 24 V, 20 A
Operational temperature range
-25°C to + 70°C
Output derating at higher temperature
12 W/°C at +60°C to +70°C
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
AC input voltage
•
100-240 VAC ±15%
System Power Guidelines
April 2021
D800001X312
458

--- Page 459 ---

Table J-4: 100-240 VAC to 24 VDC 20 A DeltaV Bulk Power Supply (continued)
Item
Specification
AC mains frequency
50-60 Hz ± 6%
AC input current
•
4.56 A at 120 VAC
•
2.48 A at 230 VAC
AC power factor
•
0.95 A at 120 VAC
•
0.90 a at 230 VAC
AC inrush current
•
13 A peak maximum at 100 VAC
•
11 A peak typical at 100 VAC
•
13 A peak maximum at 120 VAC
•
9 A peak typical at 120 VAC
•
13 A peak maximum at 230 VAC
•
7 A peak typical at 230 VAC
AC efficiency
•
92.4% at 120 VAC
•
93.9% at 230 VAC
AC losses
•
39.6 W at 120 VAC
•
31.4 W at 230 VAC
DC input voltage
110-150 VDC -20%/+25%
DC input current
4.6 A at 110 VDC
DC power factor
1 or N/A at 110 VDC
DC inrush current
•
13 A peak maximum
•
10 A peak typical
DC efficiency
92% at 110 VDC
DC losses
41.8 W at 110 VDC
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 8.2 cm (3.2 inches)
Depth: 12.7 cm (5 inches)
Terminals and wiring
Bistable, quick-connect spring-clamp terminals with IP20 finger safe construction are
used. The terminals are shipped in the open position and are suitable for field installation.
Use wire that complies with local codes and regulations.
Wire type
Input spring-clamp
terminals
Output spring-clamp
terminals
DC-OK-Signal spring-
clamp terminals
Solid wire
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
Maximum wire gauge:
6 mm2; 10 AWG
System Power Guidelines
D800001X312 
April 2021
459

--- Page 460 ---

Wire type
Input spring-clamp
terminals
Output spring-clamp
terminals
DC-OK-Signal spring-
clamp terminals
Stranded wire
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Maximum wire gauge:
4 mm2; 11 AWG
Connectors and LEDs
The following image shows the connectors and LEDs on the bulk power supply. The labels
on the input and output terminals are self-explanatory (Neutral (-), Line (+), protective
earth ( ), positive (+) and negative (-) output). Additional information about the relay
contact operation follows the image. Refer to the Related information section for
information on the LEDs.
Figure J-8: Connectors and LEDs on the 100-240 VAC to 24 VDC 20 A DeltaV Bulk
Power Supply
Output voltage potentiometer 
(factory set at 24.1 VDC)
DC OK LED (green)
Overload LED (red)
Input terminals
Output terminals
DC OK relay contact
DC OK Relay Contact operation
The DC OK relay contact monitors the bulk power supply's output voltage. It is
synchronized with the DC OK LED.
• Closed contact: the output voltage has reached the adjusted output voltage level.
System Power Guidelines
April 2021
D800001X312
460

--- Page 461 ---

• Open contact: voltage has dipped to more than 10% below the adjusted output
voltage. Short dips are extended to a signal length of 250 ms. Dips shorter than 1 ms
are ignored.
• Reclosed contact: the output voltage has exceeded 90% of the adjusted voltage.
• Contact ratings maximum resistive load: 60 VDC at 0.3 A, 30 VDC at 1 A, 30 VAC at 0.5
A
• Contact ratings minimum permissible load: 1 mA at 5 VDC
J.7
100-240 VAC to 24 VDC 40 A DeltaV Bulk Power
Supply
Installation notes
• The following information applies only to part numbers 1X00797H01L and KJ1503X1-
BB4. For other DeltaV bulk power supplies with similar characteristics, you can obtain
documentation from Emerson Global Support Center at 800-833-8314.
• Install this bulk power supply on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated power. Increase this clearance to 15 mm if the adjacent device is a
heat source such as another power supply.
Specifications
Table J-5: 100-240 VAC to 24 VDC 40 A DeltaV Bulk Power Supply
Item
Specification
Output voltage
24 VDC (nominal)
Output adjustment range
24-28 VDC
Output current
•
40-34.3 A continuous
•
60-51.5 A short term (4 seconds)
Output power
•
960 W continuous
•
1440 W short term (4 seconds)
Output ripple
< 100 mV peak-to-peak at 20 Hz to 20 MHz
Output hold-up time
•
54 ms typical at 100 VAC, 24 V, 20 A
•
27 ms typical at 100 VAC, 24 V, 40 A
•
54 ms typical at 120 VAC, 24 V, 20 A
•
27 ms typical at 120 VAC, 24 V, 40 A
•
54 ms typical at 230 VAC, 24 V, 20 A
•
27 ms typical at 230 VAC, 24 V, 40 A
Operational temperature range
-25°C to + 70°C
System Power Guidelines
D800001X312 
April 2021
461

--- Page 462 ---

Table J-5: 100-240 VAC to 24 VDC 40 A DeltaV Bulk Power Supply (continued)
Item
Specification
Output derating at higher temperature
24 W/°C at +60°C to +70°C
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
AC input voltage
100-240 VAC -15%/+10%
AC mains frequency
50-60 Hz ± 6%
AC Input current
•
8.6 A at 120 VAC
•
4.5 A at 230 VAC
AC power factor
•
0.99 at 120 VAC
•
0.99 at 230 VAC
AC Inrush current
•
25 A peak maximum at 100 VAC
•
18 A peak typical at 100 VAC
•
22 A peak maximum at 120 VAC
•
16 A peak typical at 120 VAC
•
16 A peak maximum at 230 VAC
•
9 A peak typical at 230 VAC
AC efficiency
•
93.6 % at 120 VAC
•
94.6 % at 230 VAC
AC losses
•
65.6 W at 120 VAC
•
54.8 W at 230 VAC
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 12.5 cm (4.92 inches)
Depth: 12.7 cm (5 inches)
Terminals and wiring
Screw terminals with IP20 finger safe construction are used. The terminals are suitable for
field and factory wiring. Use wire that complies with local codes and regulations.
Wire type
Input screw terminals
Output screw terminals
DC-OK spring-clamp
terminals
Solid wire
Maximum wire gauge: 6
mm2; 10 AWG
Maximum wire gauge: 16
mm2; 6 AWG
Maximum wire gauge: 1.5
mm2; 16 AWG
Recommended tightening
torque: 1 N · m; 9 lb. · in.
Recommended tightening
torque: 2.3 N · m;
20.5 lb. · in.
System Power Guidelines
April 2021
D800001X312
462

--- Page 463 ---

Wire type
Input screw terminals
Output screw terminals
DC-OK spring-clamp
terminals
Stranded
wire
Maximum wire gauge: 4
mm2; 12 AWG
Maximum wire gauge: 10
mm2; 8 AWG
Maximum wire gauge: 1.5
mm2; 16 AWG
Recommended tightening
torque: 1 N · m; 9 lb. · in.
Recommended tightening
torque: 2.3 N · m;
20.5 lb. · in.
Connectors and LEDs
The following image shows the connectors and LEDs on the bulk power supply. The labels
on the input and output terminals are self-explanatory (Neutral, Line, protective earth,
positive (+) and negative (-) output). Additional information about the relay contact, shut
down and remote control operations, and the parallel and single use selector follows the
image. Refer to the Related information section for information on the LEDs.
Figure J-9: Connectors and LEDs on the 100-240 VAC to 24 VDC 40 A DeltaV Bulk
Power Supply
Output
Terminals
Parallel use and 
single use selector 
Output voltage potentiometer 
(factory set at 24.1 VDC)
DC OK LED (green)
Overload LED (red)
DC OK relay contact
Shut down and remote 
control input
Input
terminals
System Power Guidelines
D800001X312 
April 2021
463

--- Page 464 ---

DC OK Relay Contact operation
The DC OK relay contact monitors the bulk power supply's output voltage. It is
synchronized with the DC OK LED.
• Closed contact: the output voltage has reached the adjusted output voltage level.
• Open contact: voltage has dipped to more than 10% below the adjusted output
voltage. Short dips are extended to a signal length of 250 ms. Dips shorter than 1 ms
are ignored.
• Reclosed contact: the output voltage has exceeded 90% of the adjusted voltage.
• Contact ratings maximum resistive load: 60 VDC at 0.3 A, 30 VDC at 1 A, 30 VAC at 0.5
A
• Contact ratings minimum permissible load: 1 mA at 5 VDC
Shut down and remote control input operation
The shut down feature enables a signal switch or an external voltage to switch the power
supply output off. The shutdown occurs immediately; the restart is delayed for up to 350
ms. In a shutdown condition, the output voltage is < 2 VDC and the output power is < 0.5
W. The voltage between different minus pole output terminals must be below 1 VDC
when units are connected in parallel. The following image shows the various wiring
options. When multiple power supplies are connected in series, only wiring option A with
individual signal switches is allowed. Option C requires that the voltage source has current
sink capability. Do not use a blocking diode.
Parallel and single use selector
Set the jumper to Parallel Use mode when power supplies are connected in parallel to
increase the output power. In order to share the load current between the individual
power supplies, parallel use regulates the output voltage such that the voltage at no load
is approximately 4% higher than at nominal load. A missing jumper is the same as Single
Use mode.
J.8
12-48 VDC 20 A DeltaV Bulk Power Supply
Redundancy Module
Installation notes
• The following information applies only to part numbers 1X00924H01L and KJ1503X1-
BC1. For other DeltaV redundancy modules with similar characteristics, you can obtain
documentation from Emerson Global Support Center at 800-833-8314.
System Power Guidelines
April 2021
D800001X312
464

--- Page 465 ---

• Install this redundancy module on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom,
5 mm on the left and right sides when the device is loaded permanently with more
than 50% of the rated output current. Increase the side clearance to 15 mm if the
adjacent device is a heat source such as a power supply.
• This redundancy module can be used in one-to-one and n-to-one redundant systems.
Use diodes or other switching arrangements to isolate the redundant power supply
outputs from each other.
• Connect the two input channels to the 100-240 VAC to 24 VDC 10 A DeltaV Bulk Power
Supply for redundant applications.
Specifications
Table J-6: 12-48 VDC 20 A DeltaV Bulk Power Supply Redundancy Module
Item
Specification
Input voltage
12-48 VDC ±25%
Input voltage range
9-60 VDC
Input current
•
2x 0-10 A continuous
•
2x 0-16 A for 5 seconds
Output current
•
0-20 A continuous
•
20-32 A for 5 seconds
•
25 A at continuous overload/short circuit
Input to output voltage drop
•
0.78 VDC at 2x 5 A input (typical)
•
0.85 VDC at 1x 10 A input (typical)
•
0.85 VDC at 2x 10 A input (typical)
Power losses
•
0 W at no load (typical)
•
7.8 W at 2x 5 A input (typical)
•
8.5 W at 1x 10 A input (typical)
•
17 W at 2x 10 A input (typical)
Temperature range
-40°C to +70°C operational
Relative humidity
5 to 95%, non-condensing
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
Derating
0.5 A /°C at +60°C to +70°C
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 3.2 cm (1.25 inches)
Depth: 10.2 cm (4.0 inches)
System Power Guidelines
D800001X312 
April 2021
465

--- Page 466 ---

Terminals and wiring
Bistable, quick-connect spring-clamp terminals with IP20 finger safe construction are
used. The terminals are shipped in the open position and are suitable for field installation.
Use wire that complies with local codes and regulations.
Wire type
Input and output spring-clamp terminals
Solid wire
Maximum wire gauge: 6 mm2; 10 AWG
Stranded wire
Maximum wire gauge: 4 mm2; 11 AWG
Connectors
Figure J-10: Connectors on the 12-48 VDC 20 A DeltaV Bulk Power Supply Redundancy
Module
Input 1
Input 2
Chassis ground 
(optional)
Output
terminals
Wiring for redundancy
The 12-48 VDC 20 A DeltaV Bulk Power Supply Redundancy Module can be used in one-to-
one and n-to-one applications.
Note
For both one-to-one redundancy and n-to-one redundancy, it is recommended that, if
possible, you use separate mains systems for each power supply.
System Power Guidelines
April 2021
D800001X312
466

--- Page 467 ---

Figure J-11: Wiring for one-to-one redundancy at up to 10 A
L
N
PE
N
L
PE
Optional
10A
Load
Faliure
Monitor
Figure J-12: Wiring for n-to-one redundancy at up to 30 A
Optional
Optional
PE
L
N
60A
Load
Faliure
Monitor
System Power Guidelines
D800001X312 
April 2021
467

--- Page 468 ---

J.9
12-24 VDC 40 A DeltaV Bulk Power Supply
Redundancy Module
Installation notes
• The following information applies only to part number KJ1503X1-BD1. For other
DeltaV redundancy modules with similar characteristics, you can obtain
documentation from Emerson Global Support Center at 800-833-8314.
• Install this redundancy module on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated output current. Increase the side clearance to 15 mm if the adjacent
device is a heat source such as a power supply.
• This redundancy module can be used in one-to-one and n-to-one redundant systems.
Use diodes or other switching arrangements to isolate the redundant power supply
outputs from each other.
• Connect the two input channels to the 100-240 VAC to 24 VDC 20 A DeltaV Bulk Power
Supply for redundant applications.
Specifications
Table J-7: 12-24 VDC 40 A DeltaV Bulk Power Supply Redundancy Module
Item
Specification
Input voltage
12-28 VDC ±30%
Input voltage range
16.8-36.4 VDC
Input current
•
2x 0-20 A continuous
•
2x 20-32.5 A for 5 seconds
Output current
•
0-40 A continuous
•
40-65 A for 5 seconds
•
65 A at continuous overload/short circuit
Input to output voltage drop
•
72 mV at 2x 10 A input (typical)
•
112 mV at 1x 20 A input (typical)
•
140 mV at 2x 20 A input (typical)
Power losses
•
700 mW at no load (typical)
•
2.15 W at 2x 10 A input (typical)
•
2.65 W at 1x 20 A input (typical)
•
6.3 W at 2x 20 A input (typical)
Temperature range
-40°C to +70°C operational; no derating required
Relative humidity
5 to 95%, non-condensing
System Power Guidelines
April 2021
D800001X312
468

--- Page 469 ---

Table J-7: 12-24 VDC 40 A DeltaV Bulk Power Supply Redundancy Module (continued)
Item
Specification
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 3.6 cm (1.4 inches)
Depth: 12.7 cm (5.0 inches)
Terminals and wiring
Screw terminals with IP20 finger safe construction are used. The terminals are suitable for
field and factory wiring. Use wire that complies with local codes and regulations.
Wire type
Input screw terminals
Output screw terminals
Solid wire
Maximum wire gauge: 6 mm2; 10
AWG
Maximum wire gauge: 16 mm2; 6
AWG
Recommended tightening torque:
0.8 N · m; 7 lb. · in.
Recommended tightening torque: 1.2
N · m; 10.6 lb. · in.
Stranded wire
Maximum wire gauge: 4 mm2; 12
AWG
Maximum wire gauge: 10 mm2; 8
AWG
Recommended tightening torque:
0.8 N · m; 7 lb. · in.
Recommended tightening torque:
1.2 N · m; 10.6 lb. · in.
System Power Guidelines
D800001X312 
April 2021
469

--- Page 470 ---

Connectors
Figure J-13: Connectors on the 12-24 VDC 40 A DeltaV Bulk Power Supply Redundancy
Module
Input 2
Input 1
Chassis ground 
(optional)
Output terminals
Wiring for redundancy
The 12-24 VDC 40 A DeltaV Bulk Power Supply Redundancy Module can be used in one-to-
one and n-to-one applications.
Note
For both one-to-one redundancy and n-to-one redundancy, it is recommended that, if
possible, you use separate mains systems for each power supply.
System Power Guidelines
April 2021
D800001X312
470

--- Page 471 ---

Figure J-14: Wiring for one-to-one redundancy at up to 20 A
N
L
PE
Faliure
Monitor
20A
Load
Figure J-15: Wiring for n-to-one redundancy at up to 60 A
N
L
PE
Faliure
Monitor
20A
Load
System Power Guidelines
D800001X312 
April 2021
471

--- Page 472 ---

J.10
12-24 VDC 80 A DeltaV Bulk Power Supply
Redundancy Module
Installation notes
• The following information applies only to part number KJ1503X1-BD2. For other
DeltaV redundancy modules with similar characteristics, you can obtain
documentation from Emerson Global Support Center at 800-833-8314.
• Install this redundancy module on a horizontally oriented DIN rail with the label text
right-side up.
• Keep the following installation clearances: 40 mm on top, 20 mm on the bottom, 5
mm on the left and right sides when the device is loaded permanently with more than
50% of the rated output current. Increase the side clearance to 15 mm if the adjacent
device is a heat source such as a power supply.
• This redundancy module can be used in one-to-one and n-to-one redundant systems.
Use diodes or other switching arrangements to isolate the redundant power supply
outputs from each other.
• Connect the two input channels to the 100-240 VAC to 24 VDC 40 A DeltaV Bulk Power
Supply for redundant applications.
Specifications
Table J-8: 12-24 VDC 80 A DeltaV Bulk Power Supply Redundancy Module
Item
Specification
Input voltage
12-28 VDC ±30%
Input voltage range
16.8-36.4 VDC
Input current
•
2x 0-40 A continuous
•
2x 40-65 A for 5 seconds
Output current
•
0-80 A continuous
•
80-130 A for 5 seconds
•
130 A at continuous overload/short circuit
Input to output voltage drop
•
50 mV at 2x 20 A input (typical)
•
85 mV at 1x 40 A input (typical)
•
95 mV at 2x 40 A input (typical)
Power losses
•
700 mW at no load (typical)
•
2.7 W at 2x 20 A input (typical)
•
3.6 W at 1x 40 A input (typical)
•
8.3 W at 2x 40 A input (typical)
Temperature range
-40°C to +70°C operational; no derating required
Relative humidity
5 to 95%, non-condensing
System Power Guidelines
April 2021
D800001X312
472

--- Page 473 ---

Table J-8: 12-24 VDC 80 A DeltaV Bulk Power Supply Redundancy Module (continued)
Item
Specification
Shock
15 g half sine wave for 6 ms, 10 g half sine wave
for 11 ms
Vibration
1.6 mm peak to peak from 2 to 17.8 Hz, 2 g
from 17.8 to 500 Hz
Dimensions
Height: 12.4 cm (4.9 inches)
Width: 4.6 cm (1.8 inches)
Depth: 12.7 cm (5.0 inches)
Terminals and wiring
Screw terminals with IP20 finger safe construction are used. The terminals are suitable for
field and factory wiring. Use wire that complies with local codes and regulations.
Wire type
Input screw terminals
Output screw terminals
Solid wire
Maximum wire gauge: 16 mm2; 6
AWG
Maximum wire gauge: 35 mm2; 2
AWG
Recommended tightening torque:
1.2 N · m; 10.6 lb. · in.
Recommended tightening torque: 2.5
N · m; 22 lb. · in.
Stranded wire
Maximum wire gauge: 10 mm2; 8
AWG
Maximum wire gauge: 35 mm2; 2
AWG
Recommended tightening torque:
1.2 N · m; 10.6 lb. · in.
Recommended tightening torque: 2.5
N · m; 22 lb. · in.
System Power Guidelines
D800001X312 
April 2021
473

--- Page 474 ---

Connectors
Figure J-16: Connectors on the 12-24 VDC 80 A DeltaV Bulk Power Supply Redundancy
Module
Chassis ground 
(optional)
Output terminals
Input 1
Input 2
Wiring for redundancy
The 12-24 VDC 80 A DeltaV Bulk Power Supply Redundancy Module can be used in one-to-
one and n-to-one applications.
Note
For both one-to-one redundancy and n-to-one redundancy, it is recommended that, if
possible, you use separate mains systems for each power supply.
System Power Guidelines
April 2021
D800001X312
474

--- Page 475 ---

Figure J-17: Wiring for one-to-one redundancy at up to 40 A
N
L
PE
40A
Load
Faliure
Monitor
Figure J-18: Wiring for n-to-one redundancy at up to 120 A
L
PE
N
120A
Load
Faliure
Monitor
J.11
Sizing the I.S. System Power Supply
The I.S. System Power Supply accepts locally available 24 VDC (nominal) power and
converts it to 12 VDC for powering I.S. I/O cards. Each I.S. power supply is rated at 5 A and
can power from eight to fifteen cards depending upon the type and mix of cards. You can
have up to ten I.S. power supplies and add an additional power supply for redundancy.
(The total number of I.S. power supplies for a redundant system is eleven.) When using
multiple I.S. system power supplies, intersperse the power supplies among the cards.
Note
The I.S. Power Supply supplies 60 W and draws 80 W for 24 VDC bulk power supply
calculations at the rated load.
System Power Guidelines
D800001X312 
April 2021
475

--- Page 476 ---

J.12
Legacy Bulk Power Supplies for System Power
The legacy bulk AC to 12 VDC and 24 VDC to 12 VDC power supplies provide 12 VDC
power to the System Power Supply (Dual DC/DC) for one or more controllers and their
associated I/O subsystems. However, if you are using the bulk power supply to provide
power for more than one DeltaV system or for other equipment, refer to the I/O card
specifications or use the simplified calculations in the installation worksheet to determine
if there is sufficient capacity.
Related information
I/O Cards
Installation Worksheets
J.13
Sizing the Legacy Bulk Power Supply for Bussed
Field Power and System Power
The legacy bulk AC to 24 VDC power supply provides power to field devices and System
Power Supplies (Dual DC/DC). In general, AI cards, AO cards, and dry contact DI cards use
small amounts of current. Thus, the legacy bulk AC to 24 VDC power supply provides
enough power for approximately 40 of these types of I/O cards.
If you are supplying power to DO cards with high side switches, you must evaluate the
power requirements carefully. Refer to the manufacturer’s specifications for your field
devices to determine the load.
J.14
Using Multiple System Power Supplies
There are three reasons to use more than one power supply for a system application:
• To provide load sharing if more than 100 percent of the output of a single supply is
required
• To supply separate power supplies for redundant equipment
• To provide a backup for one or more power supplies in a system
Do not use different product types in multiple system power supply applications. Use the
same product type with the same input voltage (12 VDC or 24 VDC) for either load sharing
applications or redundant applications that use multiple system power supplies.
Note
Your individual requirements for system availability determine where to provide
redundancy in a system. Corporate/plant standards or “Hazardous Operations
Procedures” for your site often provide guidelines.
The system power supplies provide OR-ing diodes to isolate faults on one supply from the
output provided by the other supply.
Different system constraints apply to each type of DeltaV Power Supply. The following
sections discuss considerations for each type of power supply.
System Power Guidelines
April 2021
D800001X312
476

--- Page 477 ---

J.14.1
System Power Supply (AC/DC)
The System Power Supply (AC/DC) converts AC input power to 12 VDC for the I/O
subsystem (I/O power is expressed as LocalBus power in the power calculation
worksheets). In addition, it converts some input power to supply the requirements of the
controller if it is mounted directly to the left of the controller or on the right slot of a
second 2-wide power/controller carrier.
Note
The left slot of the second 2-wide power/controller carrier will NOT provide power to the
controller, only to the I/O subsystem.
Supplying System Power to the I/O
For some system sizes, I/O power requirements cannot be met by a single supply. In these
cases, you must use multiple supplies for load sharing. By adding a second system power
supply (or more) and additional carriers, you can increase the power available for the I/O.
You may need as many as four supplies for a full system of analog I/O cards.
For load sharing, mount the second supply in either slot of the second power/controller
carrier. Additional supplies mount to the left of the second supply or on a third power/
controller carrier, if needed. The following figure shows an example of four system power
supplies used for load sharing.
System Power Guidelines
D800001X312 
April 2021
477

--- Page 478 ---

Figure J-19: System Power Supply Mounting for Load Sharing with a Simplex
Controller
Note
In an application requiring redundant power to the controller rather than load sharing, the
second system power supply in Figure J-1 would provide only 15 W to the I/O and 10 W to
the controller. Refer to “Supplying Redundant System Power to the Controller”. Refer also
to Table J-9 for information on LocalBus current provided to the I/O in various controller/
power redundancy situations.
Extending System Power to the I/O
The LocalBus power is specified and limited to 8 A. Some cards consume up to 0.5 A of
system power each. Because of this, a system with several cards such as AS-Interface,
Profibus, DeviceNet, and Fieldbus cards can exceed the ratings.
Note
The 8-wide carriers must be left-aligned when using 1-wide extenders.
The following image shows power injected for two system power supplies mounted on the
2-Wide Horizontal Power Carrier. The power is supplied to the left 1-Wide Horizontal
Carrier Extender positive and negative (+ and -) screw terminals with the jumper removed.
System Power Guidelines
April 2021
D800001X312
478

--- Page 479 ---

In addition to supplying DC power, the system power supplies on the 2-Wide Horizontal
Carrier provide additional filtering for the local extended railbus.
Figure J-20: Extended Power Diagram
CB1
CB1
CB1
CB1
CB1
CB1
CB1
CB1
Primary
AC
Secondary
AC
Chassis
Ground
Enclosure PE Ground Lug
Enclosure Door
Adjacent Enclosure
To DIG
To DIG
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Fuse
Isolated
Bus
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
Field Power
System 
Power Supply 
Controller
System 
Power Supply 
Controller
System 
Power Supply 
System 
Power Supply 
Shield Bar Jumper Wire
Shield Bar Jumper Wire
Shield Bar Jumper Wire
Jumper
Jumper
Shield Bar Jumper Wire
DC Ground
System Power Guidelines
D800001X312 
April 2021
479

--- Page 480 ---

Supplying Redundant System Power to the Controller
To provide redundant power to the controller, install a secondary system power supply in
the right slot of the second power/controller carrier, as shown in the following figure. You
must mount the secondary supply in the right slot of the second carrier to provide power
to the controller.
Figure J-21: System Power Supply Mounting for Redundant Controller Power
If you require redundant power to the controller and additional system power supplies for
I/O load sharing, you must mount the secondary system power supply for the controller in
the right slot of the second carrier, as shown in Figure J-3.
LocalBus Current Provided to the I/O Based on Controller/Power Redundancy
The following table shows the LocalBus current provided to the I/O based on the number
of System Power Supplies (AC/DC) and the controller/power redundancy used in the
configuration.
Table J-9: LocalBus Current Provided to the I/O
Number of System
Power Supplies
(AC/DC)
Controller/Power Redundancy
Simplex Controller
and Simplex Power
Simplex Controller
and Redundant
Power
Redundant Controller
and Redundant
Power
1
1.25 A
N/A
N/A
System Power Guidelines
April 2021
D800001X312
480

--- Page 481 ---

Table J-9: LocalBus Current Provided to the I/O (continued)
Number of System
Power Supplies
(AC/DC)
Controller/Power Redundancy
Simplex Controller
and Simplex Power
Simplex Controller
and Redundant
Power
Redundant Controller
and Redundant
Power
2
3.35 A
1.25 A
1.25 A
3
5.45 A
3.35 A
2.50 A
4
7.55 A
5.45 A
4.6 A
5
9.65 A; current limited
to 8.0 A due to carrier
limitations
7.55 A
6.7 A
6
11.75 A; current
limited to 8.0 A due to
carrier limitations
9.65 A; current limited
to 8.0 A due to carrier
limitations
8.8 A; current limited
to 8.0 A due to carrier
limitations
Related information
Installation Worksheets
Using OR-ing Diodes with Legacy Bulk Power Supplies
J.14.2
System Power Supply (Dual DC/DC)
The System Power Supply (Dual DC/DC) provides 12 VDC LocalBus power to the I/O
subsystem when it is operated on either 12 VDC or 24 VDC input power. In addition, it
converts some input power to supply the requirements of the controller if it is mounted
directly to the left of the controller or on the right slot of a second 2-wide power/controller
carrier.
Supplying System Power to the I/O
You can add a second system power supply to provide I/O power redundancy. The second
supply mounts in the right slot of the second 2-wide power/controller carrier, as shown in
the following figure. Power this supply from a separate bulk power supply to provide
power if the primary bulk supply fails.
System Power Guidelines
D800001X312 
April 2021
481

--- Page 482 ---

Figure J-22: System Power Supply (Dual DC/DC) Mounting for Redundant Power
Supplying Redundant Power to the Controller
To provide redundant power to the controller, install a secondary system power supply in
the right slot of the second power/controller carrier as shown in the preceding image. You
must mount the secondary supply in the right slot to provide power to the controller.
The power conversion from 12 VDC is done inside of the system supply. Because of this,
you could decide that it is acceptable to supply power to both system supplies from a
single bulk supply if your application can support that single point of failure.
J.15
Using Multiple Legacy Bulk Power Supplies for
Redundancy and Load Sharing
The legacy Bulk AC to 24 VDC and Bulk AC to 12 VDC power supplies are available as both
DIN rail and panel-mounted units. Both types of power supplies can be used in redundant
systems and the legacy DIN rail-mounted supply can be used in systems requiring load
sharing as well as redundancy. The legacy DIN rail-mounted supply contains an integrated
OR-ing diode to isolate power supply faults. Refer to “OR-ing Diodes” for usage
information. The legacy panel-mounted power supply cannot be used in systems that
require load sharing.
System Power Guidelines
April 2021
D800001X312
482

--- Page 483 ---

If you have redundant system power supplies, connect the redundant legacy Bulk AC to 12
VDC power supplies to different System Power Supplies (Dual DC/DC) on each controller
and I/O subsystem.
The legacy DIN rail-mounted Bulk AC to 24 VDC power supply provides 24 VDC power to
field devices and System Power Supplies (Dual DC/DC). This power supply provides
enough power for approximately 40 AI, AO, and dry contact DI cards.
J.15.1
Using OR-ing Diodes with Legacy Bulk Power Supplies
The legacy DIN rail-mounted Bulk Power Supplies have an integrated OR-ing diode to
isolate power supply faults and are set at 12.3 or 24.6 VDC. If the legacy DIN rail-mounted
Bulk Power Supply is used in a system that requires redundancy or load sharing, connect
the SHARE terminals on the top of the power supplies to terminal strips or bus bars. One or
both of the VOUT (+) and RTN (-) connections must go to the same location.
Figure J-23: Connecting the Legacy DIN Rail-Mounted Bulk Power Supply for
Redundancy or Load Sharing
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
+
share
share
share
To terminal strips or
        bus bars
Connect one or both 
+ and - to the 
same location
If the legacy panel-mounted Bulk Power Supply or a bulk power supply without OR-ing
diodes from another manufacturer is used in a system that requires redundant power, use
external OR-ing diodes (such as the Weidmuller USA #998786 dual rectifier diode module)
to isolate power supply faults. Because an external OR-ing diode has a nominal .7 V drop,
the output of each supply must be adjusted to account for the drop or the voltage to the
carriers might be too low. The recommended adjustments, after the OR-ing diodes, are:
• 12.3 VDC for a 12 VDC bulk power supply
• 24.6 VDC for a 24 VDC bulk power supply
System Power Guidelines
D800001X312 
April 2021
483

--- Page 484 ---

Verify these voltages with one bulk power supply disabled to ensure operation in a fault
condition.
Note
The system power supply shuts down if the input power exceeds 12.6 V. Do not adjust a
12 V bulk power supply to more than 12.3 V at the input to the system power supply.
If additional 12 VDC power is required for a carrier that is powered by a bulk power supply
without integrated OR-ing diodes, connect the primary and secondary bulk power
supplies through OR-ing diodes with the output going only to the extender cable, not to
the system power supplies as shown in Figure J-26.
The following table shows the current provided to the system based on the number of
legacy DIN rail-mounted Bulk Power Supplies (AC to 12 and 24 VDC) and whether simplex
or redundant power is used in the configuration. Figure J-24 shows the connections for
four DIN rail-mounted Bulk Power Supplies. A fifth supply can be connected in the same
manner for redundancy.
Table J-10: Bulk Power Provided to the System
Number of legacy Bulk Power
Supplies (AC to 24 VDC and
AC to 12 VDC)
System Current Provided by
Simplex Power
System Current Provided by
Redundant Power
1
12 A
N/A
2
24 A
12 A
3
36 A
24 A
4
48 A
36 A
5
N/A
48 A
System Power Guidelines
April 2021
D800001X312
484

--- Page 485 ---

Figure J-24: Connecting Multiple Legacy DIN Rail-Mounted Bulk Power Supplies
+
share
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
share
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
share
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
share
AC+ AC
RTN
VOUT
Bulk AC to 12 or 24 VDC
power supply
+ +
share
Terminal
strips or bus bars 
Figure J-25 shows power and grounding for an AC System Power Supply and DeltaV bulk
power supplies. Note that the 2-wide carrier must be connected to the DC Ground.
System Power Guidelines
D800001X312 
April 2021
485

--- Page 486 ---

Figure J-25: Power and Grounding for an AC System Power Supply
Isolated
Bus
To DIG
DC Ground
Chassis
Ground
Enclosure PE Ground Lug
Enclosure Door
Adjacent Enclosure
AC
To DIG
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
– + + –
– + + –
Figure J-26 shows power and grounding for a 12 VDC System Power Supply (Dual DC/DC)
used with legacy bulk power supplies. Note that the 2-wide carrier is not connected to
ground because the legacy 12 VDC Bulk Power Supplies are connected to the isolated
common ground reference or to the DeltaV instrumentation ground.
Figure J-26 also shows:
• How to provide redundant 24 VDC bussed field power
• The recommended method for connecting 12 VDC redundant legacy bulk power
supplies to redundant system power supplies
• How to extend 12 VDC bulk power to the carriers
Providing Redundant 24 VDC Bussed Field Power
In Figure J-26, the legacy 24 VDC Bulk Power Supplies are connected together to provide
the redundant bussed field power. The OR-ing diodes are integrated into the power
supply.
Connecting Redundant 12 VDC Legacy Bulk Power to Redundant System Power
Supplies
As shown in Figure J-26, the recommended method for connecting redundant legacy bulk
power supplies to redundant system power supplies is to connect the primary legacy bulk
power supply directly to the primary system power supply and to connect the secondary
legacy bulk power supply directly to the secondary system power supply. Do not connect
the legacy bulk power supplies together because a single high-voltage failure in either bulk
power supply could cause both system power supplies to reset which in turn causes both
controllers to reset. OR-ing diodes are not required in this situation.
System Power Guidelines
April 2021
D800001X312
486

--- Page 487 ---

Extending 12 VDC Legacy Bulk Power to the Carriers
Also shown in Figure J-26 are OR-ing diodes used for extending 12 VDC power to the
carrier when OR-ing diodes are not integrated into the bulk power supply. The primary and
secondary legacy bulk power supplies are connected through OR-ing diodes with the
output going to the extender cable not to the system power supply.
Figure J-26: Power and Grounding for a 12 VDC System Power Supply (Dual DC/DC)
with Legacy Bulk Power Supplies
AC+ AC
RTN
VOUT
+
+
+
+
+
+
+
AC+ AC
RTN
VOUT
+
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
AC+ AC
RTN
VOUT
+
+
AC+ AC
RTN
VOUT
+
+
+
+
+
+
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
24 VDC
bussed
field power
1-Wide carrier 
extender
share
share
2-Wide carrier
share
share
8 DC cards
8-Wide carrier
Carrier
shield bar
Isolated local
ground reference
To isolated common ground reference
or DeltaV instrumentation ground (DIG)
DC reference
ground
OR-ing diodes 
(only required if not
integrated into power 
supply)
Bulk AC to 12 VDC
power supply
Bulk AC to 12 VDC
power supply
Bulk AC to 24 VDC
power supply
Bulk AC to 24 VDC
power supply
24 VDC
bussed
field power
Figure J-27 shows power and grounding for a 24 VDC System Power Supply (Dual DC/DC)
used with legacy bulk power supplies. It also shows connections for providing 24 VDC
bussed field power. In Figure J-27. The legacy bulk power supplies are connected together
to provide power to the system power supplies and to provide bussed field power. The OR-
ing diodes are integrated into the legacy bulk power supply. Note that in Figure J-27 the 2-
wide carrier is connected to the isolated common ground reference or to the DeltaV
instrumentation ground.
System Power Guidelines
D800001X312 
April 2021
487

--- Page 488 ---

Figure J-27: Power and Grounding for a 24 VDC System Power Supply (Dual DC/DC)
with Legacy Bulk Power Supplies
AC+ AC
RTN
VOUT
Bulk AC to 24 VDC
power supply
+
+
+
+
AC+ AC
RTN
VOUT
Bulk AC to 24 VDC
power supply
+
+
+
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
8 DC cards
8-Wide carrier
To isolated common ground reference
or DeltaV instrumentation ground (DIG)
Isolated local
ground reference
DC
reference
ground
24 VDC bussed
field power
share
share
2-Wide carrier
Carrier
shield
bar
1-Wide carrier 
extender
1-Wide
carrier 
extender
For grounding information for DeltaV Bulk Power supplies refer to Figure J-20.
.
System Power Guidelines
April 2021
D800001X312
488