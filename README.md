# Expedition

_Expedition_ is a collection of electronic music composed and
performed with [Tidal](http://tidal.lurk.org), a
live-coding and algorithmic music pattern environment in the Haskell
programming language.

## Tracks

Code for the tracks is located in the `tracks/` folder.

1. Surface Transmission Decoding
2. Escape Burn
3. Slipstream Jump
4. Termination Shock Transition
5. Ring Surfing
6. Encrypted Message From Home
7. Repeating Distress Beacon
8. Galactic Alpaca
9. Atmospheric Probe Malfunction
10. Humans Riding on Bicycles Taking Selfies
11. Species / Anti-Species Annihilation
12. Sorting Through Wreckage

## License and Audio Samples

_Expedition_ is released under the Creative Commons
Attribution-ShareAlike license. You may use the material
found in this repository (including any audio samples) by
attributing the source work and keeping the license intact;
please refer to the license details at
[creativecommons.org/licenses/by-sa/4.0](http://creativecommons.org/licenses/by-sa/4.0/).

Samples are located in the `samples/` folder.

Except for the drum breaks on _Selfies_, all sampled audio in this repository was originally produced by [kindohm](http://github.com/kindohm)
using FL Studio softsynths and hardware synthesizers. If you're
interested in how all sounds were produced in the studio, check out
the [for-audio-nerds](production/for-audio-nerds.md) doc for detailed
audio production info.

Drum breaks on _Selfies_ are sourced from:

- Dave Akuma, who has made his breaks available for free use
- The _Think_ break, in the public domain

## Release

_Expedition_ will be released digitally at
[kindohm.bandcamp.com](http://kindohm.bandcamp.com) at a future date.

## Running the Code in Tidal

You must have Tidal installed. If you are not familiar with Tidal,
refer to the [Tidal docs](http://tidal.lurk.org) for installation instructions
and usage.

All tracks are in the `tracks/` folder. Make sure to eval the custom
functions in 00-boot.tidal first before executing any of the other
Tidal files.

Most tracks use the Dirt sample synthesizer that pairs with Tidal.
Two tracks use the MIDI capabilities of Tidal: _Humans Riding
on Bicycles Taking Selfies_ and _Sorting Through Wreckage_.
