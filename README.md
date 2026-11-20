# YouTube DJ

**A free, work-in-progress DJ device for Ableton Live and Max for Live.**

YouTube DJ brings YouTube video playback, DJ-style mixing controls, sample decks, cue and loop tools, recording, and resampling into a single Max for Live device. It is designed for experimenting, practicing, and building creative DJ workflows inside Ableton Live.

> **Development status: v1.0 (work in progress)**  
> This project is **not finished or fully tested**. Some controls, audio-import paths, and Live integrations may be incomplete or unreliable. Features and behavior may change as development continues. Please do not rely on the current build for critical or uninterrupted live performances.

## ☕ SUPPORT DEVELOPMENT — BUY ME A COFFEE

**YouTube DJ is developed independently and offered for free. If you find it useful, please consider supporting continued development, bug fixes, and new features.**

### **☕ [BUY ME A COFFEE — Support YouTube DJ](https://buymeacoffee.com/yohsukenak)**

Your support helps keep this project moving forward. Thank you!

## Features

- **Two YouTube decks (A/B):** Video playback with independent deck controls and a DJ-oriented interface.
- **2-deck / 4-deck layouts:** A/B are YouTube playback decks; the additional C/D decks are designed for sample playback.
- **Mixer controls:** Channel faders, crossfader, EQ, and effects controls, subject to the limitations of the available audio paths.
- **Cue and loop tools:** Cue points, hot cues, loop controls, and timeline interaction.
- **Sample pads:** Assign and play audio material using dedicated pads, with individual playback and level controls.
- **Recording and resampling:** Record material and work with it in a waveform-oriented playback/editor section.
- **Audio import tools:** File import, drag-and-drop, and Ableton Live clip integration are being developed and refined.
- **MIDI Learn:** Mapping of supported controls to external MIDI controllers is under development.
- **Playlists and history:** Deck-oriented browsing, playlists, and playback-history functions.
- **Multilingual interface:** Language selection and translated controls, with coverage still being refined.

**Important:** These describe the project's intended and partially implemented feature set, not a guarantee that every feature is complete or works reliably in the current build.

## Requirements

- Ableton Live with **Max for Live** support.
- A computer with an internet connection for YouTube playback.
- A current `.amxd` build of YouTube DJ.

Development has primarily taken place on **Windows 11 with Ableton Live 12.3**. **macOS compatibility has not yet been verified.** Other Live versions and system configurations may behave differently.

## Getting Started

1. Download the available YouTube DJ `.amxd` build from this repository when published.
2. Load the device onto an audio track in Ableton Live.
3. Click **OPEN** to access the main DJ interface.
4. Select an interface language when prompted.
5. Choose videos for Deck A and Deck B and explore the available mixer, cue, loop, and sample controls.
6. Use the 4-deck layout to access the additional sample decks when available.

For now, save your Live Set before testing experimental features.

## YouTube Login and Advertising — Important Limitation

**YouTube account login is not supported in YouTube DJ because of the embedded playback implementation and its technical restrictions.** You cannot assume that account-based features or YouTube Premium benefits will be available inside this device.

**YouTube advertisements may appear before or during video playback.** Ads, interruptions, playback availability, and player behavior are controlled by YouTube, not by YouTube DJ. The device does **not** provide an ad blocker or a method to bypass YouTube advertising.

**Plan your mixing and transitions with advertising in mind.** Playback may be interrupted or delayed, so seamless cueing and uninterrupted DJ sets cannot be guaranteed. Video availability may also depend on region, embedding permissions, or other YouTube restrictions.

## Copyright, Content Rights, and Responsible Use

**YouTube DJ does not grant permission to use, record, remix, distribute, broadcast, or publicly perform copyrighted material.**

- Rights to YouTube videos, music, images, and other third-party content remain with their respective owners.
- You are responsible for complying with applicable copyright laws, licensing requirements, and YouTube's terms and policies.
- Public performances, livestreams, recordings, remixes, sampled material, and redistributed audio/video may require separate permission or licenses, even when a video is available to watch on YouTube.
- Recording or sampling content inside Ableton Live does **not** automatically grant rights to publish or reuse that content.
- Use your own material, properly licensed material, or material for which you otherwise have the necessary rights.

This project is an independent third-party tool and is **not affiliated with, endorsed by, or sponsored by YouTube, Google, or Ableton**. All relevant names and trademarks belong to their respective owners.

## Current Development Priorities

The following areas remain under active development and testing:

- More reliable cue/loop range dragging and waveform interaction.
- Audio-file drag-and-drop and selected Live-clip loading.
- Sample assignment, playback state, and buffer management.
- Recording, resampling, and waveform editing.
- Send to Live, audio-track detection, and other Live integrations.
- 2/4-deck switching, MIDI mapping, layout responsiveness, and multilingual consistency.

Please report reproducible bugs through GitHub Issues, including your OS, Ableton Live version, steps to reproduce, and screenshots when appropriate.

## License and Distribution

A source-code license has **not yet been specified**. Public access to a repository does not, by itself, grant permission to redistribute or modify its contents. Check this repository for updated licensing information before reusing the code or assets.

## ☕ Help Keep YouTube DJ Free

If this device is useful to you—or you would like to help improve it—**supporting its development is greatly appreciated**:

### **[☕ Buy Me a Coffee — Yohsuke Nakano](https://buymeacoffee.com/yohsukenak)**

**Developer:** Yohsuke Nakano  
**Project:** YouTube DJ for Max for Live  
**Version:** v1.0 (work in progress)
