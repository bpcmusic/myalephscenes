# myalephscenes

A repository of the scenes that I use with my monome aleph.

Created by: [bpcmusic](https://github.com/bpcmusic)

## versions

* bees: 0.6.2
* aleph-lines: 0.2.4

## scenes

### METRONOMICON

The Metronomicon is a simple patch consisting of 4 CV pulse metronomes that output to the CV outs. Each metronome's tempo is independent and can be adjusted from 30,000 bpm to 7.32 bpm. Adjustments are made using the four rotary encoders. Metronomes can be turned off and on by pressing the corresponding key switch. Optionally, an [ARC4](http://monome.org/docs/arc/) can be connected to control the four metronomes as well. When using the ARC4, note that the Aleph's encoders and the ARC4's encoders are independent; the most recent encoder to move will send its value to the metronome. This allows for rate jumps between the two encoder's settings.

*TEMPO*

* ENC0 and ARC4/0 - Metronome 0 --> CV0
* ENC1 and ARC4/1 - Metronome 1 --> CV1
* ENC2 and ARC4/2 - Metronome 2 --> CV2
* ENC3 and ARC4/3 - Metronome 3 --> CV3

*ENABLE/DISABLE*

* KEY0 - Metronome 0
* KEY1 - Metronome 1
* KEY2 - Metronome 2
* KEY3 - Metronome 3
