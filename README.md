# Simple Additive FM Synth (JSFX Plugin for Reaper)

This is a simple additive FM synthesizer designed for Reaper, implemented as a JSFX plugin. It provides versatile additive synthesis capabilities, with support for basic FM modulation and envelope shaping. This plugin is suitable for creating rich, harmonically complex sounds and experimenting with FM synthesis techniques.

## Features

- **Additive Synthesis**: Combine up to four harmonics with adjustable levels to create custom timbres.
- **FM Modulation**: Modulate the fundamental and harmonics with flexible FM settings.
- **ADSR Envelope**: Shape the amplitude and FM modulation over time with adjustable attack, decay, sustain, and release parameters.
- **Pitch Bending**: Customize the pitch bend range for expressive control.

## Parameters

### General Controls
- **Volume**: Controls the overall output level of the synthesizer.

### Amplitude Envelope
- **Attack (A)**: Time taken for the amplitude to reach its peak when a note is played.
- **Decay (D)**: Time taken for the amplitude to decrease from the peak to the sustain level.
- **Sustain (S)**: The amplitude level that is maintained while a note is held.
- **Release (R)**: Time taken for the amplitude to fall to zero after the note is released.

### Harmonics
- **Fundamental**: Level of the fundamental frequency (the base pitch of the sound).
- **Harmonic 2**: Level of the second harmonic (2× the fundamental frequency).
- **Harmonic 3**: Level of the third harmonic (3× the fundamental frequency).
- **Harmonic 4**: Level of the fourth harmonic (4× the fundamental frequency).

### FM Modulation
- **FM Env**: Controls how much the ADSR envelope affects the FM modulation level.
- **FM Sub**: Sets the modulation amount for a subharmonic (0.5× the fundamental frequency).
- **FM Harmonic 1**: Sets the modulation amount for the first harmonic.
- **FM Harmonic 2**: Sets the modulation amount for the second harmonic.
- **FM Harmonic 3**: Sets the modulation amount for the third harmonic.

### Pitch Control
- **Pitch Bend Range**: Specifies the range of pitch bending in semitones.

## Installation

1. Download the `.jsfx` file from this repository.
2. Place the file in your Reaper effects folder. On most systems, this is located at:
   ```
   <Reaper resource path>/Effects/
   ```
   You can find the resource path in Reaper by going to `Options > Show REAPER resource path in explorer/finder`.
3. Open Reaper, add the plugin to a track, and start experimenting!

## Usage

- Adjust the amplitude envelope to control the dynamics of the sound.
- Use the harmonic sliders to craft the tonal content.
- Experiment with the FM modulation parameters to create unique timbres.
- Adjust the pitch bend range to suit your performance needs.

## License

This project is dedicated to the public domain under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

Enjoy and happy sound design!
