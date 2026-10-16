# Awesome-Audio-Editing

# Top Audio Editing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Digital Audio Workstations, Waveform Editing & Audio Restoration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Audio Editing**. These tools enable musicians, podcasters, and audio engineers to record, edit, mix, and master audio—from quick single-file trims to full multitrack productions with virtual instruments and professional effects chains.

**Examples** include Adobe Audition, Avid Pro Tools, Logic Pro, Steinberg Cubase, PreSonus Studio One, FL Studio, Ableton Live, Sound Forge Pro, Reaper, and Acoustica (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, DAW workflows, and open audio editing—ideal for musicians, producers, and audio engineers seeking transparent, vendor-independent tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Audition](https://www.adobe.com/products/audition.html)**
  **The industry standard for audio post-production** with **multi-track editing, spectral editing, and Adobe Premiere Pro integration** . Features **speech-to-text analysis**, **audio restoration**, and **batch processing** . **$19.99/month** for the full Adobe ecosystem .

- **[Avid Pro Tools](https://www.avid.com/pro-tools)**
  **The professional standard for music and post-production** . Features **Dolby Atmos mixing**, **130+ plugins**, **speech-to-text analysis** (2025.6 update), and **track compiling** . **$99/year (Artist)** to **$599/year (Ultimate)** .

- **[Logic Pro](https://www.apple.com/logic-pro/)**
  **Apple's flagship DAW** with **Virtual Drummer**, **Alchemy synthesizer**, and **spatial audio monitoring**. **Mac-only**—the most complete Apple ecosystem audio tool.

- **[Steinberg Cubase](https://www.steinberg.net/cubase/)**
  **Advanced MIDI sequencing** with **Chord Track**, **Harmonic Editing**, and **VariAudio** pitch correction. **The standard for composers and arrangers**.

- **[PreSonus Studio One](https://www.presonus.com/products/Studio-One)**
  **Streamlined DAW with drag-and-drop workflow**, **Melodyne integration**, and **Mastering Suite** . **Pro license $399**; **Studio One+ $19.99/month** .

- **[FL Studio](https://www.image-line.com/fl-studio/)**
  **Pattern-based sequencing** with **Step Sequencer**, **Piano Roll**, and **lifetime free updates**. **The standard for hip-hop and electronic production**.

- **[Ableton Live](https://www.ableton.com/live/)**
  **Session View** for live performance, **Warping** for tempo-flexible playback, and **Max for Live** for custom devices. **The standard for electronic music and live performance**.

- **[Sound Forge Pro](https://www.magix.com/sound-forge/)**
  **The original professional audio editor**—focused on stereo and multichannel editing, restoration, and mastering. **Windows-only**.

- **[Reaper](https://www.reaper.fm/)**
  **The most affordable full DAW**—**$60 single-payment DRM-free license** with **unlimited free updates** . Features **scripting, customizable UI, portable install**, and **light footprint** . **Steep learning curve** but **exceptional value** .

- **[Acoustica](https://acondigital.com/products/acoustica/)**
  **Best paid alternative to Adobe Audition** for **audio restoration and post-production** . **Standard $59.90**; **Premium $199.90** (spectral editing, surround sound) .

## Open-Source GitHub Projects

- **[Audacity](https://github.com/audacity/audacity)**
  **The most widely used open-source audio editor** (GPL-2.0) . **Free, cross-platform (Windows, macOS, Linux)**, with **unlimited tracks**, **41 effects**, **up to 32-bit/384kHz** audio, **dithering**, **batch processing**, and **plugin support** . **Latest updates**: new compressor and limiter, master effects section, **time-stretching loops to tempo with automatic beat detection** . **No multitrack recording** (single-instance limitation), and **mixer view lacks features** compared to DAWs . **Noise reduction is unusually good for a free tool**—a genuine differentiator on spoken-word material . **OpenVINO AI Tools pack** adds **AI noise suppression, stem separation, and speech-to-text** running locally . **The default recommendation** for quick audio projects, podcasts, and sound design .

- **[Ardour](https://github.com/Ardour/ardour)**
  **The most capable open-source DAW** (GPL-2.0) . **Ardour 9.0** (February 2026) adds **Region FX, clip recording, pianoroll windows, clip editing, and touch-sensitive GUI** . Features **unlimited tracks**, **non-destructive editing**, **plugin support (LV2, VST3, AU)**, and **Lua scripting** for automation . **The professional's choice** for Linux audio production—mature, stable, and actively developed .

- **[LMMS](https://github.com/LMMS/lmms)**
  **Open-source music production suite** (GPL-2.0) . Built around **pattern sequencing, synthesis, and beat making** rather than live audio recording . **LMMS 1.3.0-alpha.2** adds **Compressor, Vectorscope, SF3 soundfont support, native Linux VST support, granular pitch shifter, and continuous auto-scrolling** . **The standard open-source alternative to FL Studio** for electronic music . **Audio recording features are weaker than sequencing**—pair with Audacity for recording live instruments .

- **[Qtractor](https://qtractor.org/)**
  **MIDI/Audio multi-track sequencer application** (GPL-2.0) . **The most focused open-source sequencer** for MIDI composition and audio recording. **Active development** with version 1.6.4 in 2026 .

- **[ocenaudio](https://www.ocenaudio.com/)**
  **Free, cross-platform single-file audio editor** . **Streamlined interface for editing and analysing individual audio files** with **real-time effect previews** . **Version 3.22.0** adds **Speech Enhancement (DPDFNet2) AI model**, **explicit routing mode choice (Mono, Stereo, Matrix)**, **FFT engine selection for spectrogram**, and **improved sample rate conversion** . **Best for**: quick single-file edits—"open a file, top and tail it, fix the level, export" .

- **[OpenDaw](https://github.com/glenwrhodes/OpenDaw)**
  **Free, open-source Digital Audio Workstation for Windows** (open-source) . **Qt 6 UI, Tracktion Engine audio, MIDI piano roll, VST3 instruments, built-in effects, and Claude AI assistant** . Features **4 empty audio tracks on launch**, **drag-and-drop audio/MIDI import**, **routing with draggable signal-chain nodes**, **bus creation and effects routing**, and **clip snapping to grid** . **The newest entrant** in open-source DAWs with AI integration .

- **[SoundCraft](https://snapcraft.io/soundcraft)**
  **Open-source, native digital audio workstation** (MIT OR Apache-2.0) . **Record, edit, and mix multitrack audio and MIDI** in Edit and Mix windows . **Part of the ArtCraft "Crafting Apps"**: native Rust application running locally on your files, **driven from CLI, JSON control channel, or MCP server** . **Headless command-line tool available as soundcraft.cli** . **The most modern open-source DAW architecture**—Rust-native with agent-friendly control interfaces .

- **[Tenacity](https://github.com/tenacityteam/tenacity)**
  **Cross-platform multi-track audio editor/recorder** (GPL-2.0) . **Fork of Audacity** with community governance and privacy-focused defaults. **The alternative for users concerned about Audacity's telemetry policies** .

- **[Auto-Editor](https://github.com/WyattBlue/auto-editor)**
  **Automatically edit video and audio** (Unlicense) . **Removes silence, motion, and other segments automatically**—the fastest path to rough cuts for podcasts and interviews .

- **[AudioMass](https://audiomass.co/)**
  **Browser-based open-source audio editor** . **Free, runs in any browser**, with **compression, EQ, reverb, delay, distortion, pitch shift, fade in/out, and MP3 export** . **Works on low-end computers**—no installation required . **Best for**: basic editing on any machine with a browser .

### Additional Strong Open-Source Options

- **[SoX](https://github.com/chirlu/sox)** — Swiss Army knife of sound processing programs (GPL-2.0) . **Command-line audio conversion, effects, and analysis**.
- **[LosslessCut](https://github.com/mifi/lossless-cut)** — Lossless video/audio cutting (GPL-2.0) . **The fastest way to trim without re-encoding**.
- **[audapolis](https://github.com/audapolis/audapolis)** — Editor for spoken-word media with transcription (MIT) . **The most focused open-source tool for podcast editing**.
- **[Kwave](https://github.com/KDE/kwave)** — Sound editor built on KDE Frameworks 5 (GPL-2.0) .
- **[WaveSurfer](https://github.com/katspaugh/wavesurfer.js)** — Tool for sound visualization and manipulation (BSD-3-Clause) .
- **[mhWaveEdit](https://github.com/magnush/mhwaveedit)** — Simple and fast sound editor (GPL-2.0) .
- **[Sweep](https://github.com/mgeier/sweep)** — Audio editor and live playback tool (GPL-2.0) .
- **[MorphEdit](https://github.com/morphedit/morphedit)** — Browser-based desktop audio editor for trimming, effects, mixing (open-source) .
- Community **n8n** workflows for audio processing automation and batch conversion.

**Frameworks for building custom systems**: Combine **Ardour** for multitrack DAW production with **Audacity** for quick editing and restoration, **LMMS** for electronic music production, **ocenaudio** for single-file precision edits, and **Auto-Editor** for automated rough cuts—creating a comprehensive open-source audio production stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Audio editing tools must respect copyright for samples, loops, and recorded material. **Commercial plugin licenses vary**—verify before use in monetized productions.
- **Open-source audio editing is mature and production-ready.** Audacity handles podcasts, restoration, and quick edits with professional-grade noise reduction . Ardour 9.0 provides a full DAW with pianoroll, clip editing, and plugin support . LMMS is the standard for open-source electronic music . **These are genuine alternatives to commercial platforms.**
- **The single-file vs. multitrack distinction is the real dividing line.** Most people who think they need a DAW actually need a good single-file editor, and vice versa . **Choose based on your actual workflow, not feature checklists.**
- **AI is arriving in open-source audio.** Audacity's OpenVINO AI Tools pack adds **noise suppression, stem separation, and speech-to-text** running locally . ocenaudio 3.22.0 adds **Speech Enhancement (DPDFNet2)** . **The gap between open-source and commercial AI features is closing.**
- Self-hosted open-source solutions require proper audio interface configuration and plugin management. **Always monitor levels**—clipping is unrecoverable, and no restoration tool fully recovers a destroyed recording.

---

**Made for musicians, producers, podcasters, and audio engineers building transparent audio editing solutions.**  
Let's make Audio Editing more open, data-driven, and accessible.
