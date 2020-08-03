# Teensy polyBLEP Oscillator

A quasi-bandlimited oscillator for the Teensy Audio Library 

Usage: 
This Software only works together with the Teensy Audio Library.
In your Arduino Sketch, #include "polyBlepOscillator.h" and use as an Audio Object.

Inputs:
0 - Frequency Modulation for Oscillator 1
1 - Pulse Width Modulation for Oscillator 1
2 - Frequency Modulation for Oscillator 2
3 - Pulse Width Modulation for Oscillator 2
4 - Frequency Modulation for Oscillator 3
5 - Pulse Width Modulation for Oscillator 3

Outputs:
0 - Output Oscillator 1
1 - Output Oscillator 2
2 - Output Oscillator 3

Functions: 
When setting the parameters, the first argument is the oscillator
(1, 2 or 3), the second the parameter. 
Further details can be seen in the header file.
