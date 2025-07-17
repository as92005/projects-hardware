Adjustable Sine Wave Generator Summary- 
This project involved designing a circuit that outputs a sine wave with adjustable amplitude (10–12 Vpp), frequency (400–800 Hz), and independent top/bottom clipping.

Key Features
- 555 Timer in astable mode generates a square wave with variable frequency using a potentiometer.
- 4 Low-Pass Filters smooth the square wave into a sine wave, with cutoff frequency designed below the 400 Hz minimum.
- Op-Amp Amplifier (LM358) boosts the signal amplitude; gain is adjustable via potentiometers.
- Integrated Clipping is achieved by limiting the op-amp's supply voltages using voltage dividers and buffer op-amps, allowing independent control of the clipping thresholds.

The final output met all the requirements: clean sine wave, tunable frequency and amplitude, and adjustable clipping.

Design Highlights
Adjustability: Real-time control of frequency, amplitude, and clipping using potentiometers.
Efficient Design: Combined amplification and clipping into one stage to simplify the circuit.

<img width="320" height="500" alt="image" src="https://github.com/user-attachments/assets/f7353488-54f9-478a-a55f-7c64a5d351b8" />

