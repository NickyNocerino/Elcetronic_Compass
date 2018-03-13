# Elcetronic_Compass
ECE 387 Individual Project
# Periferals:
* -Xilinx PYNQ Board with PMOD Grove Adapter and Shield
* -Grove IMU 9DOF v2.0
* -3 LEDS

# Overview:
The goal of this project Is to create an programable electronic compass thet will always point at the desired 
Lattitde/Longitude coordinates. This is done by using the Xilinx PYNQ Board to control the Grove IMU 9DOF v2.0
chip and webscrape freegeoip.net to find the current board's current location based on IP address. The desired
direction is then convayed to the user Via LEDs.

# Current State:
As of 3/13/18 the compass will point to magnetic north when placed flat or tilted slightly. This is represented
by 3 LEDs that continously update every 2 seconds. One LED will light up when the X axis of the board is within +or-
10 degrees of magnetic north. the other 2 will light up when the x axis is +5 - +35 and -5 - -35 degrees from magnetic
north. 
