# Multi-Stage Analog Signal Conditioning Circuit (BJT + RC Filters)

A three-stage analog circuit modelled on the audio section of an AM radio receiver.

*Practical assignment for IE2034 Analog Electronics, SLIIT.*

| Stage | Design |
|---|---|
| 1. High-pass filter | Passive RC, removes noise below about 2 kHz |
| 2. Common-emitter amplifier | BC547 NPN, 9 V supply, theoretical mid-band gain about 175x |
| 3. Low-pass filter | Passive RC, removes noise above about 12 kHz |

Verified by Proteus simulation and on a breadboard, with measurements on a digital oscilloscope.

## Files
Proteus projects (`.pdsprj`): `HPF`, `highpass`, `Amplifier`, `AMP`. Open them with Proteus 8.

## Tech
Proteus, BJT amplifier design, RC filters, oscilloscope measurement

## Authors
Vishmini Michel
