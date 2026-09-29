# Parkoid — downloads

Mono FM synth plugin (VST3/Standalone) by DRELVA, for hypnotic techno, built around two signature
sounds: ELASTIC (rubbery "boing" pitch sweeps with a spring bounce) and BLEEPS (short, bright, resonant
FM blips through a saturated ping-pong delay). Phase-modulation FM, anti-aliased wavefolder, MS-20-style
filter, analog envelopes and drift, a 16-step sequencer with slide, probability and scale-aware
generator, or play it straight from MIDI.

This repo hosts only the downloads — no source code (that lives in a private repo).

See the [Releases](../../releases) tab for the Windows installer (`.exe`), the macOS installer (`.pkg`)
and the PDF manual.

| Version | What's in it |
|---|---|
| **v0.3.0** | modulation matrix: 8 slots, any parameter as destination, full length or chosen steps (parameter locks), MOD A/B step lanes, LFOs, random, envelopes; right-click any knob to modulate; sound generator RND / VARY / UNDO in 4 styles |
| **v0.2.0** | ELASTIC + BLEEPS: rebuilt DSP (2x/4x oversampling, drive, bass comp, mono low end), MIDI play mode with legato/glide, pitch CURVE + BOUNCE (+/-48 st), per-step slide + probability, GEN in a scale, dotted/triplet ducked ping-pong, 19 categorised presets + user presets, interactive UI, Windows + macOS installers, PDF manual |
| **v0.1.0** | first release: FM voice, MS-20 filter, tape delay + space, 16-step sequencer with GEN / MUT, 6 factory presets, Windows + macOS installers, PDF manual |

The installers are unsigned/not notarised: on first run, right-click → Open (Mac) or click
"More info" → "Run anyway" (Windows SmartScreen) to bypass the unknown-publisher warning.
