# Instrument Interface

**Please note that this is an unofficial project page, the official one is [here](http://www.befaco.org/en/instrument-interface/).**

Sometimes interaction between a modular system and other musical instruments
(electronic or acoustic) is needed. With an envelope follower circuit we can achieve a direct
control of the amplitude of the signal. It will produce a control voltage proportional to the
amplitude, allowing true communication between our system and the external sound source.

The Instrument Interface module has the following blocks:

## PREAMP
With two audio inputs (6.5 jack and minijack/banana), input amplification is controlled with
the “GAIN” pot, controlling the amplitude of the envelopes that will be generated. The minimum signal
required to generate the maximum envelope is 200mV peak and allows up to 5v input.

## BPF
The signal will pass thru a band pass filter with cutoff frequency and band width control via
“FREQ” and “WIDTH” pots. This way we will select the frequency range that will generate our
control signal. After this stage the signal will be output with synth level via “AUDIO OUT”.

## ENV.FOLLOWER
After filtering the signal it will feed the “RESPONSE” stage, that will determine envelope follower
response velocity. It features a “HIGH”, “MEDIUM” and “LOW” selector switch to get an optimal
envelope for different kind of signals. “FOLLO OUT” will output the envelope extracted and show
us its level via a LED. Green: Medium level, Orange: High level and Red: Max. level.

## ENV.REGENERATOR
“REGE OUT” is a re-generated envelope that will allow controlling the rise of the envelope with
“ATTACK” and the fall with “DECAY”, making them longer or shorter. It features a LED indicator
for the regenerated envelope level. Green: Medium level, Orange: High level, Red: Max. level.

## TRIG.EXTRACTOR
With the “THRESHOLD” pot we control the level of a comparator that determines when "GATE OUT" and
"TRIGG OUT" outputs will be activated. "GATE OUT" will be at high level while the envelope is
above the threshold we set, while "TRIGG OUT" is present just when the threshold is passed.
Indication LEDS will show when the outputs are active.

## Specs
* Eurorack compatible
* Power supply: +/-12V.
* Current: +12V: 40mA -12V: 35mA.
* Banana or mini-jack connectors available
* 11 HP. 45 mm depth.
