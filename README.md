# All Plugins
To collect the latest release version of every plugin I make

## Roadmap
### Effects
- [ ] Volume
- [ ] Util
- [ ] [Clip](../../clip) `fp001` `stoej-fp001-clip`
- [ ] Texture `fp000` `stoej-fp000-text`
- [ ] Distortion: a VA guitar distortion builder
- [ ] Vibe Machine: a weird delay effect
- [ ] FFT Freeze: spectral freeze effect
- [ ] Hysteresis: VA tape emulation
- [ ] Stochastic: stochastic bit-crushing
- [ ] Eraser: slew-limiting distortion
- [ ] Buffer Ops: buffer mangling toy box
- [ ] Glitch Pitch: a deliberately terrible pitch shifter

### Synths
- [ ] Micro: ultra basic subtractive synth, implemented with outdated digital synthesis techniques for a crunchy aliased sound and super low CPU usage
- [ ] Synth A: fully featured VA synth, with some weird idiosyncrasies
- [ ] Synth D: fully featured unapologetically digital synth
- [ ] Granary: mixing wavetable synthesis with granular synthesis

## Tech Stack
Top to bottom (abstraction wise)

- DevOps: Github Actions, clap-validator, custom Python build automaticion
- GUI: Vizia
- DSP: FunDSP
- VST3/CLAP Framework: NIH-plug
- Programming Language: Rust
