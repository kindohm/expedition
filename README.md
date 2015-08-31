# Expedition

_Expedition_ is a collection of electronic and algorithmic music. 
It was composed and performed with [Tidal](http://tidal.lurk.org), a 
live-coding and algorithmic music pattern environment in the Haskell 
programming language. It was produced August and September 2015.

Except for the drum breaks on _Selfies_, all audio was originally 
produced by [kindohm](http://github.com/kindohm) 
using FL Studio softsynths and hardware synthesizers. If you're 
interested in how all sounds were produced in the studio, check out the 
[for-audio-nerds](production/for-audio-nerds.md) doc for detailed
audio production info.

_Expedition_ is released under the Creative Commons 
Attribution-ShareAlike license. You may use the audio and material
found in this repository by keeping the license intact; please
refer to the license details at 
[creativecommons.org/licenses/by-sa/4.0](http://creativecommons.org/licenses/by-sa/4.0/). 

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

Some tracks use the MIDI capabilities of Tidal. The track _Humans Riding
on Bicycles Taking Selfies_ requires a MIDI device listening on port 16.
The track _Sorting Through Wreckage_ requires MIDI devices on port
0 (drum machine with 12 notes), port 15 (synth) and port 16 (synth).

## Samples and Stems

Most tracks use the Dirt sample synthesizer that pairs with Tidal.

Samples will be made a part of this repository very soon.

Track stems will become available for the MIDI/synth tracks in the
near future.