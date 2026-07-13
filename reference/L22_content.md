--- Page 543 ---

O
Intrinsically Safe I/O
The DeltaV system includes the following Intrinsically Safe I/O components:
• I/O cards
— I.S. DI, 16-Channel
— I.S. DO, 4-Channel
— I.S. AI, 8-Channel, 4-20, mA HART
— I.S AO, 8-Channel, 4-20 mA and I.S AO, 8-Channel, 4-20 mA HART
• Terminal Blocks
— I.S. 8-Channel terminal block
— I.S. 16-Channel terminal block
• I.S. Power Supply
• I.S. LocalBus Isolator
• Right and left hand carrier extenders
• Carriers
— I.S. 8-Wide carrier
— Power Supply carrier
— Isolator carrier
Warning
Be sure that your I.S. I/O cards and terminal blocks are compatible before plugging in I/O
cards. Card damage can result if an I/O card and terminal block are incompatible.
Warning
In any hazardous area installation it is important to read and follow the device
manufacturer's design and installation documents. Failure to follow the documentation
could result in an unapproved and unsafe application. Additionally, in hazardous locations
follow your plant's procedures for making the area safe during installation and
maintenance operations.
You can use both I.S. and non-I.S. I/O cards within one DeltaV system. However, you must
separate the I.S. cards from the non-I.S. cards with a LocalBus Isolator to protect the I.S.
cards from damaging voltages. Only one LocalBus Isolator can be used in the DeltaV
system. Plan your I/O subsystem carefully because you cannot add non-I.S. cards beyond
the LocalBus Isolator. If you use multiple I.S. system power supplies, intersperse the power
supplies among the cards. Refer to DeltaV™ Scalable Process System with Zone 0 Field Circuits
Installation Instructions (Part Number - 12P1990) for detailed information on wiring
multiple I.S. system power supplies. This manual is on the DeltaV Documentation Library
DVD. The following figure shows a LocalBus Isolator separating non-I.S. and I.S. cards.
Intrinsically Safe I/O
D800001X312 
April 2021
543

--- Page 544 ---

Figure O-1: DeltaV Intrinsically Safe I/O Overview
System Power
Supply
Controller
Non-IS I/O Cards
(Gray Terminal Blocks)
IS I/O Cards
(Blue Terminal Blocks)
Localbus
Isolator
IS I/O Cards
IS I/O Cards
IS I/O Cards
RH Carrier
Extender
LH Carrier
Extender
Non-IS
IS
IS
Power Supply
Important
Field power is provided by the I.S. I/O cards. Do not connect to the connectors on the top
of the I.S. 8-wide carrier.
The following figure shows the grounding requirements for an I.S. I/O subsystem.
Intrinsically Safe I/O
April 2021
D800001X312
544

--- Page 545 ---

Figure O-2: Grounding Requirements for I.S. I/O
Dedicated
Plant Ground
Grid Point
Isolated
Common Ground
Reference
Carrier Shield Bar
IS
Power
Supply
Localbus
Isolator
Several documents pertaining to Hazardous Area installations are on the DeltaV
Documentation Library DVD.
Related information
Intrinsically Safe I/O Interface Keying
Hazardous Area Installation Manuals, NAMUR Installation Manuals, and ATEX Instruction
Sheets
O.1
Intrinsically Safe LocalBus Isolator
The I.S. LocalBus Isolator separates non-I.S. components such as I/O cards and controllers
from I.S. components. The following figure shows the I.S. LocalBus Isolator dimensions.
Table O-1: I.S. LocalBus Isolator Specifications
Item
Specification
Input
12 V @ 60 mA maximum
Output
12 V @ 60 mA maximum
Power dissipation within module
1.2 W maximum
Mounting
LocalBus Isolator carrier
The controller is non-I.S. You must always use an I.S. LocalBus Isolator to isolate the
controller from I.S. cards.
Intrinsically Safe I/O
D800001X312 
April 2021
545

--- Page 546 ---

Figure O-3: I.S. LocalBus Isolator Dimensions
O.2
Intrinsically Safe Carrier Extenders
I.S. carrier extenders bridge two I.S. carriers to make one complete I.S. system. I.S. carrier
extenders can be used to build a system around obstacles such as cabinet walls or pipes.
Intrinsically Safe I/O
April 2021
D800001X312
546

--- Page 547 ---

Figure O-4: Right and Left I.S. Carrier Extenders
Intrinsically Safe I/O
D800001X312 
April 2021
547

--- Page 548 ---

Intrinsically Safe I/O
April 2021
D800001X312
548