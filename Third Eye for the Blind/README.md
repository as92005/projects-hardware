Third Eye for the Blind Summary-
This project is a wearable assistive device that helps visually impaired individuals detect nearby obstacles using an ultrasonic sensor, providing real-time feedback through vibration and sound. The closer the person is to an object, the stronger the vibration and the faster the beeping.

How It Works:-
- The ultrasonic sensor measures distance using echo timing.
- A digital integrator reads the Echo pulse and converts its length into a binary value using a four-bit counter and FSM logic.
- This value is stored using JK Flip-Flops, then passed through a Digital-to-Analog Converter (DAC).
- The analog signal controls:
   - A tone generator for audio feedback (faster beeps = closer object).
   - A motor control circuit for vibration feedback (stronger vibration = closer object).

Key Subcircuits:-
- Schmitt Trigger Oscillator: Triggers ultrasonic pulses at regular intervals.
- Digital Integrator & FSM: Detects pulse length and translates it into a digital signal.
- JK Flip-Flops: Hold the distance data until updated by a new reading.
- DAC: Converts stored digital values into analog voltages.
- Tone Generator: Produces beeps at varying frequencies based on distance.
- Motor Circuit: Controls vibration intensity based on proximity.

Notable Design Choices:-
- Used FSMs and custom logic for precise timing and state transitions.
- Added buffers and inverters to isolate circuits and preserve signal integrity.
- Mapped input voltages (0–8V) to match the motor’s operating range (0–4.2V) using op-amp scaling.

<img width="200" height="350" alt="image" src="https://github.com/user-attachments/assets/08349c97-325e-4c29-8c52-8d9460af21fa" />


Overall Ciruit:
![ECE198 final project](https://github.com/user-attachments/assets/d1ab3b84-5ced-4623-9f06-6744a3080653)

