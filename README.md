# Simple-VOR
Beautified version of a VOR Decoder built to solve CTS challenge 8.7 and 8.8 at RC3 2021

This is a simple implementation of a "VHF omni-directional range (VOR)" decoder.
Requires a complex baseband as input and returns the radial (magnetic north, as per definition).
Additionally (if the proper magnetic declination at the VOR station is given) it calculates the angle for "true north".
<br>
The graph uses only complex math, FIR filters, delays, DC-blocker and "moving average" to implement the decoder. No fancy extra blocks or libraries are required.
<br>
GUI elements are realized using QT-Blocks.
