# Batphone: Ultrasonic Microphones for Animal Recordings and Research

## Please read through before you go ahead with the microphone. Use it under your own risk. 

I developed this microphone to record ultrasonic soundwaves emitted by bio sonar from bats. 

The quick specifications:

| Specification             | Nominal   | Min                         | Max                         |
| ------------------------- | --------- | --------------------------- | --------------------------- |
| Operating Voltage (V)     | 5         | Minimum of the LDO or opamp | Maximum of the opamp or LDO |
| Frequency Range (Hz)      | 1 - 100K  | 1                           | ∞                           |
| Signal Output Voltage (V) | 0.5 - 3.3 | 0.5                         | 3.3                         |


The microphone itself has very low gain so in order to increase it, you will need to turn the potentiometer.

Design of the microphone mainly relies on the Knowle's FG sensor. This sensor is rather pricey, going in the ranges for ~$25 USD. The microphones integrity has been tested against a GRAS standard microphone (Unknown model) that displayed a flat frequency response between 1 Hz- 200 kHz with -1db trailing near the end. 
![FFT comparison between GRAS and Batphone](figures\fft.png)

My microphone that I have developed is not designed to be used as an replacement microphone for standard microphones but a portable, cheaper, and smaller alternative to the commercial ultrasonic microphones aimed at researches alike.

I thank Dr. Rolf Müeller for overseeing the project and research for his Bat bio-sonar research. 

If you have any questions, please email me at lucasmun@vt.edu. 