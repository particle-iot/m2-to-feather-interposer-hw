## M.2 to Feather socket Interposer adapter

### Summary:
Many of our customers have scaled on particle using the feather form factor in order to swap out between Cellular and WiFi products. Unfortunately we are seeing challenges with Cat M1 and the modem sizes that we can offer in the feather form factor. The SA team would like to propose an interposer board between a Particle M.2 Som to an interposer board that can be inserted into a feather socket on a customers PCB.

We recognize our customers may not be able to take advantage of the interposer board if their mechanical assembly does not accommodate the addition Z height and Width required by the addition of an interposer board and an M.2 Som

The interposer board will need to replicate some of the features not found on the M.2 Soms

#### Features:
* Nano SIM Tray
* PMIC, Same PMIC on Boron
* 3.3V@1A Buck regulator like Boron
* Top or Side pressed MODE and RESET buttons
* Enable pin support
* MCO/Board outline is slightly larger than a feather board due to SMT header. 
