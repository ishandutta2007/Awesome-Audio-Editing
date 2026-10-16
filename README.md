# Awesome-Audio-Editing

## Top Audio Editing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Digital Audio Workstations, Waveform Editing & Audio Restoration*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Audio Editing**. These tools enable musicians, podcasters, and audio engineers to record, edit, mix, and master audio—from quick single-file trims to full multitrack productions with virtual instruments and professional effects chains.



**Examples** include Adobe Audition, Avid Pro Tools, Logic Pro, Steinberg Cubase, PreSonus Studio One, FL Studio, Ableton Live, Sound Forge Pro, Reaper, and Acoustica (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, DAW workflows, and open audio editing—ideal for musicians, producers, and audio engineers seeking transparent, vendor-independent tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Digital Audio Workstation (DAW) and audio editing market is valued at approximately **$4.0 billion to $5.5 billion** (projected to reach over $8B to $11B by the mid-2030s at an ~8.5–9.2% CAGR). The sector exhibits **moderate concentration with a bifurcated landscape**: a handful of dominant legacy software/hardware conglomerates (Apple, Avid, Yamaha/Steinberg, Adobe) anchor the high-end studio and post-production industry with strong brand loyalty and ecosystem lock-in, while the broader creator, podcasting, and independent music tiers remain moderately fragmented and fiercely contested by nimble specialist DAWs and browser-based/freemium solutions.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue Scale | Pricing (Starting Tier) | Free Tier / Trial Limits | Key Highlights & Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Logic Pro](https://www.apple.com/logic-pro/)** | Apple Inc. (~$3.5T Market Cap / ~$390B+ Annual Rev) | $199.99 one-time perpetual (or ~$12.99/mo via Apple Creator Studio bundle) | 30-day free trial (fully functional via Apple Creator Studio trial) | Apple's flagship Mac-only DAW featuring Virtual Drummer, Alchemy synthesizer, Spatial Audio mixing, and extensive stock sound libraries. |
| **[Adobe Audition](https://www.adobe.com/products/audition.html)** | Adobe Inc. (~$200B+ Market Cap / ~$21.4B Annual Rev) | $22.99/month (annual plan billed monthly; or $34.49/mo month-to-month) | 7-day free trial (fully functional across all features and audio restoration tools) | Industry standard for audio post-production, podcast mastering, multitrack waveform editing, spectral repair, and seamless Premiere Pro CC integration. |
| **[Steinberg Cubase](https://www.steinberg.net/cubase/)** | Yamaha Corp. (~$4B+ Market Cap / Steinberg ~$35M–$50M Rev) | $99.99 one-time perpetual (Cubase Elements 13) | 60-day free trial (fully functional Pro/Elements trial with zero feature restrictions) | Advanced MIDI sequencing standard with Chord Track, Harmonic Editing, and VariAudio pitch correction; popular among composers and arrangers. |
| **[Avid Pro Tools](https://www.avid.com/pro-tools)** | Avid Technology (~$1.4B Acquisition by STG / ~$400M+ Annual Rev) | $99/year or $9.99/month (Pro Tools Artist) | 30-day free trial (fully functional Pro Tools Ultimate/Studio trial requiring an iLok account) | The commercial studio recording and film post-production standard featuring Dolby Atmos integration, 130+ stock plugins, and track compiling. |
| **[PreSonus Studio One](https://www.presonus.com/products/Studio-One)** | Fender Musical Instruments Corp (~$1B Annual Rev / PreSonus ~$50M Rev) | $19.99/month (Studio One+ subscription) or $199.99 perpetual | 30-day free trial (fully functional Studio One Pro demo) | Streamlined DAW known for drag-and-drop workflow, integrated Melodyne pitch editing, project mastering suite, and live performance view. |
| **[Sound Forge Pro](https://www.magix.com/sound-forge/)** | MAGIX Software / Boris FX (~$30M–$50M Annual Rev) | $24.95/month (or $59.99 one-time for Audio Studio entry tier; $299.95 Pro perpetual) | 15-day free trial (fully functional trial available via Boris FX Hub) | Dedicated stereo and multichannel waveform audio editor focused on audio restoration, mastering, surgical cutting, and 64-bit VST3 processing. |
| **[Ableton Live](https://www.ableton.com/live/)** | Ableton AG (~$270M+ Valuation / ~$75M–$100M Annual Rev) | $99 one-time perpetual (Ableton Live Intro) | 30-day free trial (fully functional trial with unrestricted saving, exporting, and Max for Live) | Dual Session and Arrangement views for live performance and electronic production; known for audio warping and Max for Live device ecosystem. |
| **[FL Studio](https://www.image-line.com/fl-studio/)** | Image-Line (~$50M+ Valuation / ~$30M–$40M Annual Rev) | $99 one-time perpetual (Fruity Edition) | Time-unlimited evaluation (unrestricted features and audio export, but project reopening is locked until licensed) | Pattern-based DAW famous for its step sequencer, piano roll, bundled virtual instruments, and lifetime free updates policy. |
| **[Reaper](https://www.reaper.fm/)** | Cockos Inc. (Private boutique / Estimated $5M–$10M Annual Rev) | $60 one-time discounted personal license ($225 commercial) | 60-day free evaluation (fully functional with all features enabled; displays a brief startup reminder thereafter) | Ultra-lightweight, DRM-free DAW offering extreme customization, portable installation, JSFX scripting, and exceptional stability. |
| **[Acoustica](https://acondigital.com/products/acoustica/)** | Acon Digital (Private micro-entity / Estimated <$5M Annual Rev) | $59.90 one-time perpetual (Standard Edition; $199.90 Premium) | 30-day free trial (fully functional trial for Standard and Premium editions) | High-precision audio editor and post-production suite offering spectral editing, retouching algorithms, surround sound, and mastering tools. |



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
