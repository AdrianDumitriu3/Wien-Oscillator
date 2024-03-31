# Wien-Oscillator
Designed Wien Oscillator using OrCAD Capture CIS and Allegro PCB Editor, incorporating three amplifying stages: a power-saving differential stage, a common emitter amplifying stage, and a class A output stage for optimal signal fidelity. 
The circuit is composed of 3 amplifying stages :
•The differential stage: Uses microampere currents to command the transistors, saving power.
•The amplifying stage: Based on a common emitter configuration.
•The output stage: I chose a class A block in order to have as few as possible distortions of the signal.

The layout of the circuit was made considering :
•Heat dissipation that could affect the differential stage
•Proper routes diameter for the used currents
•IPC Standards
•Dividing the schematic into functional blocks

The technical Parameters of the circuit are:
•Adjustable oscillation frequency in the range: 4kHz-24 kHz
•Output load RL = 8kΩ
•Automatic control of oscillation amplitude with TEC-J;
•Oscillation amplitude Vo = 1.66 V (With Automatic Gain Control)
•Operating temperature range: -20°C to 120°C (verifiable through temperature testing);
•Indication of power supply presence with LED diode.
