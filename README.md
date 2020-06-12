# Voltage Defusal Module

## Goal

The defusor has to tell the expert voltage levels between two testpoints.
The expert looks up the next voltage to meassure or tell to press a button to defuse the module.

## Description

This module consists of:
- 6 testpoints for "meassuring"
- background that show the connection between testpoints
- a voltage display
- a button
- two test leads

## Function

The two leads are not used to actually meassure anything. They are just connected to each other. When inserted into testpoints, the mcu will deteremine which testpoints are now connected and display a predetermined voltage on the display. 

When the button is pressed the mcu checks if the correct testpoints are connected and that the button was pressed when the voltage display is showing the correct voltage.  

If that's the case this modules is successfully disarmed. Otherwise it counts as a failed attempt.

## Build the module

- Print out a conduits background and glue it onto your module
- Drill holes at the black circles for the testpoints

TODO finish build instructions

TODO add arduino sources

TODO add circuit diagram

TODO link to main project


