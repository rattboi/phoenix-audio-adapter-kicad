# Copyright and Disclaimer
Original - Copyright: René Richard

This Version - Copyright: Jacob Proctor

This documentation describes Open Hardware and is licensed under the
CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions

# Phoenix Audio Adapter
This is a modification of the original board which allows a stereo headphone jack (Digikey# CP1-3523N-ND) to be interfaced to a standard 5pin 3.5mm Phoenix connector.

# Output Differences
The Extron Audio output wiring is different than the input wiring. There are 2 PCBs in this project. Be sure to use the output PCB for your outputs!

## Phoenix Input 
This folder contains a PCB which connects L- and R-. You "can" use this PCB for all your needs, provided you cut the R- and L- traces for outputs. If you forget to cut the traces it's probably not a big deal since there is internal resistance (50 ohms or so) in line which each output. Obviously best if they are cut, but not catastrophic by any means.

## Phoenix Output
This folder contains a PCB which leaves L- and R- floating.

# Changelog

## 0.1
Initial commit. Uses the CP1-3523N-ND part. Future revisions may use a different part.

## 0.2
Fixed an incorrect plated slot that did not load correctly in OSHPark. The board should still show an error for "unsupported drill holes"
but OSHPark should produce it correctly and the preview appears correct.