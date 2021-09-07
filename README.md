# NOTE Waiting on PCBS to arrive to test, use at your own risk
# K64F_CAN_SHIELD

A CAN shield for the Freedom K64F FRDM-K64F. This should be compatible with other arduino header compatible boards, you might have to use the additional CAN RX and CAN TX header.


## Solder Bridges

The board has two solder bridges which allow the user some control over how the board functions:

- Power solder bridge: Use of one these two solder bridges to select the supply voltage for the CAN transceiver. This can be 5V or 3V3. 
- CAN solder bridge: These solder bridges are used to connect/disconnect the CAN TX & CAN RX to pin 1 and pin 2 of J1. Usually you will want to have these two soldered, but if you are using a different board which doesn't have CAN TX and CAN RX on the same pins you will want to leave the solder bridges open and use the provided CAN RX/TX Header.


# References and Acknowledgment

Design rules for the proyect were taken from [ayberkozgur](https://github.com/ayberkozgur) [JLCPCB Design rules Stackup](https://github.com/ayberkozgur/jlcpcb-design-rules-stackups)

Thanks to Gonzalo Julian Reina Kiperman ([greinak](https://github.com/greinak)) for the help with designing and reviewing the board