# Eutropia III (2025)

**For flute and live-electronics**

Pure Data patches/abstractions and score for _Eutrópia III_ (2025), for flute and live-electronics.

A binaural recording is available **[here](https://github.com/oviniciuscesar/EutropiaIII_2025/releases/download/recording/EutropiaIII.wav)**

Score is available **[here](https://github.com/oviniciuscesar/EutropiaIII_2025/releases/download/recording/EutropiaIII_2026.score.pdf)**

---

## Technical Requirements

### Software

- **Pure Data** 0.56-1 or higher
- **Required externals:**
  - [conTorchionist](https://github.com/ecrisufmg/contorchionist)
  - [timberID](https://github.com/wbrent/timbreIDLib)
  - [tresf](https://github.com/zepadovani/tresf)
  - [cyclone](https://github.com/porres/pd-cyclone)
  - [else](https://github.com/porres/pd-else)
  - [Pd Spectral Toolkit](https://github.com/cooperbaker/Pd-Spectral-Toolkit)
  - [ceammc](https://github.com/ceammc/ceammc.github.io)
  - [gaitacol~](https://github.com/oviniciuscesar/gaitacol)

### Hardware

- **Audio Interface:** Minimum 2 inputs and 4 outputs
- **MIDI Controller:** Fader controller with at least 8 faders for output level control
- **Microphone:** 1 small diaphragm condenser microphone
- **Speakers:** 4 speakers positioned around the audience
  - The spatialization system uses ambisonics and is adaptable to other speaker configurations

---

## Repository Structure

## Repository Structure

eutropia_III/
├── audio/ # Audio samples and recordings
├── data/ # Score and configuration data
│ └── score/ # Performance score files
├── patches/ # Pure Data patches and abstractions
├── EutropiaIII_2026.pdf # Score PDF
└── EutropiaIII.wav # Recording
