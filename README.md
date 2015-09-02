# Expedition

_Expedition_ is a collection of electronic music composed and
performed with [Tidal](http://tidal.lurk.org), a
live-coding and algorithmic music pattern environment in the Haskell
programming language.

<ul>
  <li><a href="#tracks">Tracks</a></li>
  <li><a href="#license">License and Audio Samples</a></li>
  <li><a href="#release">Release(s)</a></li>
  <li><a href="#running-the-code">Running the code in Tidal</a>
    <ul>
      <li><a href="#midi">MIDI</a></li>
    </ul>
  </li>
</ul>

#<a name="tracks"></a>Tracks

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

#<a name="license"></a>License and Audio Samples

_Expedition_ is released under the Creative Commons
Attribution-ShareAlike license. You may use the material
found in this repository (including any audio samples) by
attributing the source work and keeping the license intact;
please refer to the license details at
[creativecommons.org/licenses/by-sa/4.0](http://creativecommons.org/licenses/by-sa/4.0/).

Samples are located in the `samples/` folder.

Except for the drum breaks on _Selfies_, all sampled audio in this
repository was originally produced by
[kindohm](http://github.com/kindohm)
using FL Studio softsynths and hardware synthesizers.

Drum breaks on _Selfies_ are sourced from:

- Dave Akuma, who has made his breaks available for free use
- The _Think_ break, in the public domain

#<a name="release"></a>Release(s)

_Expedition_ will be released digitally at
[kindohm.bandcamp.com](http://kindohm.bandcamp.com) at a future date.

#<a name="running-the-code"></a>Running the Code in Tidal

You must have Tidal installed. If you are not familiar with Tidal,
refer to the [Tidal docs](http://tidal.lurk.org) for installation
instructions and usage.

All tracks are in the `tracks/` folder. Once you get Tidal up and
running you can "run" the tracks as you would any other `.tidal` file.
Make sure to eval the custom functions in
<a href="tracks/00-boot.tidal">00-boot.tidal</a> first
before executing any other Tidal files. If you don't do this
then some of the tracks won't work.

Most tracks use the Dirt sample synthesizer that pairs with Tidal.
Run `dirt` so that it picks up the `samples/` folder in this repo.

##<a name="midi"></a>MIDI
Two tracks use the MIDI capabilities of Tidal: _Humans Riding
on Bicycles Taking Selfies_ and _Sorting Through Wreckage_.

The MIDI configuration is highly customized for
<a href="//github.com/kindohm">kindohm's</a> studio and instruments.

The MIDI configuration is booted in
<a href="tracks/00-boot.tidal">00-boot.tidal</a>
and depends on 16 channels being used. During production, a drum
machine was used on channels 1-12, and synths were used on channels
15 and 16.

Synth code on channels 15 and 16 could easily be played on a more
simple setup with a single channel.
