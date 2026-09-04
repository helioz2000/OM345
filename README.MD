# OM345 replacement
This project (KiCad) is to replace the OM345 RF amlifier module found in various Marconi instruments such as the MI2955.

The project is based on the MAR-7+ from MiniCircuits.
Two different designs have been developed.

**WARNING:** At the writing of this document I have only just ordered the PCBs, actual performance and functionality is yet to be confirmed. 

## OM345A
This design is based on the reference circuit published in the MAR-7+ data sheet. 

Features:

- 2 resistors in parrallel to set the bias current.
- Pi attenuator pad on RF input for gain matching
- De-coupling capacitors on RF in and RF out

## OM345B
This minimal component design serves as a drop-in replacement for OM345s in the MI2955 RF generator (AA04 board). This board provides de-coupling capacitors and the circuit has an ALC to control the gain, so there is no need for exact gain matching of the replacement board and hence no need for a pad.

### Acknowledgement
I'd like to acknowledge the great community group **Marconi-Test-Instruments** located at [groups.io](https://groups.io/g/Marconi-Test-Instruments)
which have been an absolute fountain of knowledge and provided me with lots of help.

My other source of knowledge has come from RFMAN's [YouTube](https://www.youtube.com/@rfmanrfman4536) channel. He provides a lot of useful detail on repairing the MI2955.
