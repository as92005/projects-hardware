**Superheterodyne AM Radio Receiver**-

We constructed a Superheterodyne AM Radio Receiver that would take a modulated AM signal from an antenna as input, process it through analog stages, and deliver clear audio through a speaker.

<img width="1375" height="324" alt="image" src="https://github.com/user-attachments/assets/1dcdcfa9-2829-4391-808c-a3aed13f03cb" />







How It Works:-

The receiver takes in a modulated AM signal from the antenna. This signal contains the high-frequency carrier with the embedded audio message. Since directly filtering and demodulating such high frequencies is difficult, the superheterodyne architecture is used:
- The antenna and RF module pick up the broadcast AM signal.
- A local oscillator and mixer shift the incoming signal to a fixed Intermediate Frequency (IF = 14 kHz).
- A IF filter (band-pass filter) removes everything except the desired IF channel.
- The IF amplifier boosts the filtered signal.
- An envelope detector extracts the audio from the modulated carrier.
- An audio amplifier further boosts the recovered message signal, which is then played through a speaker. 
