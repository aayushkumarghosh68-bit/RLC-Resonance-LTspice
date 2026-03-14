Objective

To simulate and analyze the behavior of a series RLC circuit and observe voltage waveforms across resistor, inductor, and capacitor.

Software Used

LTspice

Circuit Description

The circuit consists of a voltage source connected in series with a resistor (R), inductor (L), and capacitor (C). The source provides a sinusoidal input signal.

Component Values

R = 100 Ω
L = 10 mH
C = 1 µF

Input Source: SINE(0 5 1k)

Simulation

Transient analysis was performed to observe the voltage waveforms across each element.

Simulation Command:
.tran 0 10m 0 1u

Results

The voltage across R, L, and C are sinusoidal.
However, each waveform has a different phase relative to the input signal.

Conclusion

The simulation demonstrates the phase relationship between voltage and current in a series RLC circuit and shows the fundamental behavior of resonance in AC circuits.