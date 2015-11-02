# Expedition

_Expedition_ is a collection of electronic music composed and
performed with [Tidal](http://tidal.lurk.org), a
live-coding and algorithmic music pattern environment in the Haskell
programming language.

<ul>
  <li><a href="#tracks">Track List</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#release">Release(s)</a></li>
  <li><a href="#running-the-code">Running the code in Tidal</a>
    <ul>
      <li><a href="#midi">MIDI</a></li>
    </ul>
  </li>
  <li><a href="#sampledetail">Samples and Stems</a></li>
</ul>

![Cover art created by Chris LeBlanc](https://github.com/kindohm/expedition/blob/master/cover.jpg?raw=true)

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

#<a name="license"></a>License

_Expedition_ is released under the Creative Commons
Attribution-ShareAlike license. You may use the material
found in this repository (including any audio samples) by
attributing the source work and keeping the license intact;
please refer to the license details at
[creativecommons.org/licenses/by-sa/4.0](http://creativecommons.org/licenses/by-sa/4.0/).

Except for the drum breaks on _Selfies_, all sampled audio in this
repository was originally produced by
[Mike Hodnick](http://kindohm.com)
using FL Studio softsynths, hardware synthesizers, and smart phone apps.

Drum breaks on _Selfies_ are sourced from:

- Dave Akuma, who made his breaks available for free use at [dogsonacid.com/threads/new-breaks-for-download.225872/](http://www.dogsonacid.com/threads/new-breaks-for-download.225872/)
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

#<a name="sampledetail"></a>Samples and Stems

Samples are located in the `samples/` folder. Stems are located
at [this shared folder](https://drive.google.com/open?id=0B2CY0DSY3mxgfjF5T09SZUpxRXBKby1ZZjJKTzNsMjRlNHNSLUxYVXdGZDFwSVVDcThxSlE).

Almost all tracks use samples in the `samples/` folder. There are a couple
of exceptions: _Selfies_ has a bass stem track and _Wreckage_ has stems for
bass, pads, and drums.

Below is a listing of the sample names/folders used on each track.

<ol>
  <li>Surface Transmission Decoding
    <ul>
      <li>trans1</li>
    </ul>
  </li>
  <li>Escape Burn
    <ul>
      <li>electrowave</li>
      <li>fk</li>
      <li>pockch</li>
      <li>pockcp</li>
      <li>pocks</li>
    </ul>
  </li>
  <li>Slipstream Jump
    <ul>
      <li>b18b</li>
      <li>kit2</li>
      <li>kit3</li>
      <li>kit4</li>
      <li>kit5</li>
      <li>kit6</li>
      <li>kit7</li>
      <li>slipcy</li>
      <li>slipk</li>
      <li>teks</li>
      <li>ulh</li>
    </ul>
  </li>
  <li>Termination Shock Transition
    <ul>
      <li>bit1</li>
      <li>b18b</li>
      <li>kit3</li>
      <li>kit5</li>
      <li>kit7</li>
    </ul>
  </li>
  <li>Ring Surfing
    <ul>
      <li>gli1</li>
      <li>peri</li>
      <li>ringh</li>
      <li>ringk</li>
      <li>ringkit</li>
      <li>ringpad</li>
      <li>rings</li>
      <li>vocad</li>
    </ul>
  </li>
  <li>Ecrypted Message From Home
    <ul>
      <li>fall</li>
      <li>fall2</li>
    </ul>
  </li>
  <li>Repeating Distress Beacon
    <ul>
      <li>alonevox</li>
      <li>b18b</li>
      <li>beacch</li>
      <li>beack</li>
      <li>beakr</li>
      <li>beacsub</li>
      <li>defdo</li>
      <li>fk</li>
      <li>monst</li>
      <li>nau</li>
      <li>teks</li>
    </ul>
  </li>
  <li>Galactic Alpaca
    <ul>
      <li>alpch</li>
      <li>alpkeys</li>
      <li>alps</li>
      <li>d4</li>
      <li>fk</li>
      <li>peri</li>
      <li>sea</li>
    </ul>
  </li>
  <li>Atmospheric Probe Malfunction
    <ul>
      <li>keys2</li>
    </ul>
  </li>
  <li>Humans Riding Bicycles Taking Selfies
    <ul>
      <li><em>also uses a stem track for the bass</em></li>
      <li>akuma3</li>
      <li>akuma4</li>
      <li>akuma5</li>
      <li>fk</li>
      <li>fur1</li>
      <li>fur2</li>
      <li>fur3</li>
      <li>funky</li>
      <li>ion1</li>
      <li>ion2</li>
      <li>ion3</li>
      <li>ion4</li>
      <li>melt</li>
      <li>selffx</li>
      <li>selfcpr</li>
      <li>selfs</li>
      <li>teeny2</li>
      <li>teeny3</li>
      <li>teeny4</li>
      <li>teeny1</li>
      <li>think</li>
    </ul>
  </li>
  <li>Species / Anti-Species Annihilation
    <ul>
      <li>alps</li>
      <li>bit1</li>
      <li>electrowave</li>
      <li>fk</li>
      <li>laz</li>
      <li>teks</li>
    </ul>
  </li>
  <li>Sorting Through Wreckage
    <ul>
      <li><em>no samples used. uses stems for bass, pads, and drums</em></li>
    </ul>
  </li>
</ol>
