# E-SPL
Electronic Shelf price label

## hardware
use something like a CYW20739, a CR2032, and a eink display for price label.

## Updating the SPL
1) The SPL label stores a master BT device code, the Master BT device has a list of .....
2) The SPL label has a IR TX/RX, and is updated via TX/RX signal

## SPL inital setup
The SPL has a "programming pin" which shorts out the programming switch, this allows the prgramming device to load the SPL ID to a blank unit
or update a non blank unit.


## Updating via IR

