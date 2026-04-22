# MIC-Amplifier-2
Prototype test for an amplifier i designed for educational purposes
I used Altium for design and HSpice for simulation
two amplification stages and bufferings (LN pnp CC stage + differential cascode + buffer + CE + buffering) all with active loads and mirrors
closed loop amplifier

theoretical:
Gain = 200dB
bandwidth: 20hz - 100khz

Actual:
Gain: 40dB
bandwidth: 500hz - 7khz
also suffered from noise and instability

Analysis:
~Gain reduction due to no CMFB(common mode feedback) added to the cascode stage and mismatch in components
~Bandwidth reduction because i had to harshly compnsate the circuit due to instability it suffered from

noise and instablility due to:
~very little compensation added
~bad components and parasitics in PCB
~didn't calculate the feedback properly

outcome:
~improved biasing techniques
~deeper analysis and compensation
~more practical understanding of gain, noise and stability
