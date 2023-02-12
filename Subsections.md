## Control Modules
* Power Distribution Module (1)
* Pneumatics Control Module (2)

## Chassis

### Main Chassis (Can 4 - 7)

CAN ID: rightFront (4)

CAN ID: leftFront (5)

CAN ID: rightBack (6)

CAN ID: leftBack (7)

Motors: 4

Speed Controllers: 4

### "Secret" Drive Train (Can 8 & 9)

CAN ID: front (8)

CAN ID: back (9)

Motors: 2

~~Back follows front.~~

Front Module #:

Back Module #:


Speed Controllers: 2
	
The "Secret" Drive Train will also contain 2 double pneumatics (2 double solenoids) that will do the same thing at the same time. The two solenoids drive four pistons.


## Elevator System (Can 10)

CAN ID: elevCan (10)

Motors: 1

Module #:

Module #:

Speed Controllers: 1

Limit Switches: 

	We will most likely have 2 position sensors, one on the top and bottom of 
	the elevator system in addition 1 limit switches that would trigger the
	switchable output on the power distribution hub.
	
	The Elevator System will also have 1 double solenoid valve.

## Arm (Can 20 & 21)

CAN ID: armRight (20)

CAN ID: armLeft (21)

Motors: 2

	Right follows left.

Limit Switches: 1

	In order to limit the upward travel and possibly the downward travel.

### Intake (Can 30 & 31)

CAN ID: rightIN (30)

CAN ID: leftIN (31)

	The Intake will have 2 NEO 550s. Of the 2, one will be used for the Cube
	intake and both will be used for the Cone intake.
	
	We will also need to set the amount of current limiting.
