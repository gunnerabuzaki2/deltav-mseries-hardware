--- Page 57 ---

3
Checking Out and Troubleshooting
Your DeltaV System
This chapter provides guidelines to help ensure that your system is installed properly and
to help you troubleshoot hardware problems. The System Administration and
Maintenance manual in Books Online and the Release Notes KBA provide updated
maintenance and troubleshooting information.
After installing, it is recommended that you check out the hardware to ensure a smooth
startup.
After checkout, start up the DeltaV software following the instructions in the manual
Getting Started with Your DeltaV Software. You can then verify and troubleshoot your
hardware installation by using:
• DeltaV Explorer to view the overall structure and layout of your system
• Diagnostics utilities to check workstation hardware
• DeltaV Diagnostics to view diagnostics data for DeltaV hardware
3.1
Checking Out Your System
Follow these steps to check out your system after installing the hardware:
• Check the cable connections for all cables.
• Check the power supply voltages.
• Check the LED indicators on devices and I/O cards.
• Test the field wiring connections.
3.1.1
Step 1. Checking the Cable Connections
Verify that all power, ground, and carrier connections are correctly installed and that all
network cables are correctly installed. For network cables, use the Microtest PentaScanner
cable testing tool to test all cables to the specifications in the "Control Network
Specifications" section. The test equipment must be connected to both ends of the cable.
Make sure all cable passes each test.
Related information
Control Network Specifications
3.1.2
Step 2. Checking the Power Supply Voltages
Check power supplies and connections and check power supply voltages. Verify that the
voltages are in the proper range at all associated screw terminal connections.
For 12 VDC systems verify that:
• The voltage at the System Power Supply (Dual DC/DC) is 12.1-12.3 volts.
Checking Out and Troubleshooting Your DeltaV System
D800001X312 
April 2021
57

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