# Chaptor 02 - Wireless transmission

## Frequencies

electro-magnetic waves

all we see are electro-magnetic waves

* lambda = c / f, [wave length](https://en.wikipedia.org/wiki/Wavelength) (lambda)
* speed of light c ~ 3 x 10^8m/s
* [frequency](https://en.wikipedia.org/wiki/Frequency)

## Frequencies and regulations

Divide the spectrum in to bands

Country dependend

different technologies (cellular networks, cordless phones, wlan)

rough devision in three regions:

* Europe
* USA
* Japan

Frequency range is call
[spectrum](https://en.wikipedia.org/wiki/Spectrum#Electromagnetic_spectrum)

In Europe regulation was done by the state. In the USA there was a market driven
approache.

[3GPP](http://www.3gpp.org/) is involved in the standardization process.

## Signals

* amplitude
* phase (shift)
* frequency

We can influence all three to transmit data.

## Fourier representation of periodic signals

each signal is a composition (sum) of many sine waves.

Antennas, obstacles etc. limit frequencies etc. Real world limits the signals we
can transmit

Our receivers limit the signal to a specific spectrum.

We can transmit/receive super low frequencies, super high frequencies

Why can we see through a window but not see through e.g. concrete?

[Fourier series](https://en.wikipedia.org/wiki/Fourier_series)

## Signals II

We can represent signals in atleast three ways:

* amplitude (amplitude domain)
* frequency (frequency domain)
* [constellation diagram](https://en.wikipedia.org/wiki/Constellation_diagram) (amplitude M and phase foo in polar coordinates)

We have to represent bits e.g. by shifting the phase. Constellation diagram is
useful to show these shifts?

[Keying](https://en.wikipedia.org/wiki/Keying_%28telecommunications%29)

Modulation is the general technique of shaping a signal to convey information.

## Antennas: isotropic radiator

We have to some how send a signal

Heinrich Hertz was the first to tansmit a signal

We have antennas to emit signals. They emit and receive signals.

In the ideal world we have point and this point emits signals in all directions
equally. It's a theoretical (ideal) reference antenna.

Real antennas always have a directive effect.

Radiation pattern: we can measure a radiation pattern for an antenna

[isotropic radiator](https://en.wikipedia.org/wiki/Isotropic_radiator)

## Antennas: simple dipoles

[dipol](https://en.wikipedia.org/wiki/Dipole_antenna)

Hertzian dipol

We have different antennas for different frequencies with different radiation
patterns.

Each antenna has a [main lobe](https://en.wikipedia.org/wiki/Main_lobe).
It's the direction in which the antenna emits most of it's energie/power.

## Antennas: directed and sectorized

[Sectorization](https://en.wikipedia.org/wiki/Sector_antenna#Use)

TODO I don't get the definition for sectorized antenna. Is it really an antenna
feature?

## Antennas: [diversity](https://en.wikipedia.org/wiki/Antenna_diversity)

Grouping of two or more antennas.

Antenna selection (selection diversity), select antenna with best output

Use diversity combining to produce a stronger signal.

## MIMO

Stands for multiple input multiple output.

Use several antennas at receiver and transmitter to e.g. increase data rates by
using antennas in parallel

[Beamforming](https://en.wikipedia.org/wiki/Beamforming) can be used to maximize
signal power at receiver antenna. Change direction of the antenna (main lobe).

Signals can cancel each other out if e.g. the frequencies overlap by a multiple
of the wave length. Might happen but not such a big problem with high
frequencies and longer distances.

[Spatial multiplexing](https://en.wikipedia.org/wiki/Spatial_multiplexing) split
high-rate signal into lower rate streams and transmit over different antennas

[Diversity coding]()

## Signal propagation ranges

Transmission ranges is the range in which we can actually communicate.

Detection range is the range in which we can atleast detect the signal.

Interference range is the range where we can even detect the signal and the
signal becomes part of the background noise.

## Signal propagration

In free space electro magnetic waves travel in "straight" lines. (Ideal view, in
reality they bend and do whatever).

Receiving power ist influenced by various things:

* [fading](https://en.wikipedia.org/wiki/Fading)
* shadowing
* reflection at large obstacles
* refraction depending on the density of a medium
* scattering
* diffraction

## Real world examples

Some nice pictures ^^

Can be simulated by ray tracing (because signals travel in straight lines).

## Multipath propagation

Signals can take different paths from transmitter to receiver. There is an
infinite amount of paths between transmitters/receivers.

All paths have different characteristics.

The signal dispersed over time (time dispersion).
The signal can shift on the path.

Line of Sight (LoS) is the shortest direct path between sender and receiver.

## Effects of mobility

Power over time can change because of location changes. We can e.g. change the
output power based on our location.

Long term fading: slow changes in the power received (distances change)

Short term fading: quick changes in the power received

## Multiplexing

We want to support multiple users (multiple users for the shared medium). 
Therefore we use multiplexing in four dimensions (space, time, frequency, code).

## Frequency multiplexing

We can assign each user a frequency for exclusive use. Every participant get's a
part of the spectrum.

Static assignment is a waste of bandwith/spectrum e.g. if one user does not use
the assigned frequency.

## Time multiplexing

User gets the whole spectrum for a certain amount of time.

## Time and frequency multiplexing

Combination of both technics.

## Code multiplexing

Next time...


