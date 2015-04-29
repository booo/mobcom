# Chaptor 03 -

## time and frequency multiplexing

Mechanism to seperate users over time and frequency etc.

[time devision multiplexing](https://en.wikipedia.org/wiki/Time-division_multiplexing)

## cognitive radio

detected unused spectrum by listening to the medium. spectrum sensing CR.
Avoid interference by listening for other participants.

Find the best available spectrum automatically.

Seperate spectrum users into primary users (PU) and secondary users (SU).

[cognitive radio](https://en.wikipedia.org/wiki/Cognitive_radio)

## code multiplexing

Use same spectrum at the same time. We can code the signals.

[spread-spectrum technology](https://en.wikipedia.org/wiki/Spread_spectrum)

[code devision multiple access](https://en.wikipedia.org/wiki/Code_division_multiple_access)

## Modulation

translate digital data into an analog signal by changing one or more properties
of a periodic waveform.

Carrier signal is the periodic waveform.

Three examples of modulation: ASK, FSK, PSK

There is digital and analog modulation.

## Example MSK

In the real world we should avoid sudden changes of the phase.

Lookup table for even and odd bits of the data stream.

## Example quadrature amplitude modulation

...

## spread spectrum technology

Frequency dependent fading can wipe out narrow band signals. Narrow band signal can
be canceld out.

Instead of using a narrow signal with high power we spread the spectrum to a
broader frequency range and use less power.

## effects of spreading and interference

1. Spread narrow signal.
2. interference with narrowand broad signals
3. de-spread the signal
4. remove uninteresting frequency ranges

## spreading and frequenc selective fading

One channel becomes unusable because of narrowband interference.

## DSSS (Direct Sequence Spread Spectrum) I

* chipping sequence
* Spreading factor

xor data stream with chipping sequence. chipping sequence known by the sender
and receiver.

You can use spreading to "hide" the signal in the noise floor. Keep the key
(chipping sequence) a secret and use xor as cipher.

## FHSS (Frequency Hopping Spread Spectrum) II

Jump through channels.

[frequency hopping spread spectrum](https://en.wikipedia.org/wiki/Frequency-hopping_spread_spectrum)

## Software defined radio

It would be nice to change the many parameters like modulation, carrier
frequency, coding in software.

Examples: Joint Tactical Radio System, GNU Radio, URSP

## cell structures

...
