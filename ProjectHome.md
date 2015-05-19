Device uses a CM8870 DTMF decoder chip and a few small parts to interface with an Arduino UNO board and an LCD display.

DTMF tones are input either via a telephone or can be input from a PC sound card or radio or TV audio.

Tones are decoded and displayed on an LCD, up to 40 digits.  At the 41st digit, the device resets and starts all over again.

Device takes care of validating tones and only displaying one tone no matter how long the duration.

Some other decoders on the Internet have a problem with the digits being repeated rapidly if the dial pad key or recorded tone is more than a fraction of a second.

This is done by only displaying tone after the tone has ended.