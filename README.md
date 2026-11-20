# YouTube DJ

**A free DJ performance, sampling, and resampling device for Ableton Live and Max for Live.**

**Current Release: v1.1**

YouTube DJ combines YouTube video playback, DJ mixing, cue and loop controls, sample decks, audio recording, resampling, and waveform editing in a single Max for Live device.

Designed for DJ practice, creative performance, sound experimentation, and music production, YouTube DJ brings video-based DJ workflows and local audio sampling together inside Ableton Live.

It provides an expandable DJ interface with 2-deck and 4-deck modes, sample pads, effects, MIDI mapping, and dedicated audio waveform editing tools.

**YouTube DJ is free to use and independently developed.**

---

## ☕ SUPPORT YOUTUBE DJ — BUY ME A COFFEE

**YouTube DJ is developed, maintained, and distributed free of charge by an independent developer.**

Development involves interface design, audio processing, Max for Live programming, compatibility improvements, debugging, and ongoing maintenance.

**If you enjoy using YouTube DJ or find it useful for your music production, please consider supporting its development.**

Your support helps make future improvements, new features, and compatibility updates possible.

### ☕ **[BUY ME A COFFEE — SUPPORT YOHsUKE NAKANO](https://buymeacoffee.com/yohsukenak)**

**Every contribution is appreciated. Thank you for supporting independent Max for Live development!**

---

## What's New in v1.1

Version 1.1 focuses on waveform interaction, sample playback, DJ workflow improvements, and interface refinement.

### Waveform Scrub and Scratch

- WAVE SCRUB mode for supported local audio.
- Click the waveform to move the playback cursor.
- Drag across the waveform to perform scratch-style playback.
- Control the playback position directly from the stereo waveform display.
- Switch between scrubbing and other waveform editing modes.

### Loop Range Editing

- Create loop regions directly on the waveform.
- Adjust loop start and end points by dragging their boundaries.
- Drag the interior of an existing loop to reposition the entire region.
- Maintain loop duration when moving the region.
- Improved interaction between loop editing and other waveform modes.

### Trim and Sample Assignment

- Create trim ranges using waveform gestures.
- Create sample assignment ranges from recorded or imported audio.
- Assign selected audio regions to sample pads.
- Edit source material using the waveform display.
- Support stereo waveform visualization.

### Sample Pad Improvements

- Sample pads with individual play, pause, stop, and loop controls.
- Independent sample level and mute controls.
- File-based samples and assigned waveform regions.
- Improved separation between waveform editing and sample pad controls.
- Improved sample pad metering for 2-deck and 4-deck layouts.
- Updated source selection and sample management interfaces.

### Interface and Workflow Improvements

- Improved sample pad settings modal.
- More consistent deck-specific colors.
- Distinct visual states for empty and assigned sample pads.
- Updated drag-and-drop indicators.
- Improved waveform interaction and mouse event handling.
- General stability and usability improvements.

**Note:** v1.1 includes changes to complex Max for Live interaction and audio-routing code. Development and static checks do not guarantee identical behavior in every Live installation. Please report any remaining problems through GitHub Issues.

---

## Main Features

### YouTube DJ Decks

Two independent YouTube playback decks:

- Deck A — YouTube player
- Deck B — YouTube player

Each deck includes:

- Independent video display
- Playback controls
- Cue controls
- Hot cues
- Loop controls
- Pitch adjustment where supported
- Playlist management
- Playback history
- Mixer channel controls

YouTube playback capabilities are subject to the restrictions of the embedded YouTube player.

### 2-Deck and 4-Deck Modes

**2-Deck Mode**

- Deck A — YouTube playback and associated sample pads
- Deck B — YouTube playback and associated sample pads
- Two main mixer channels
- Integrated sample playback and mixing

**4-Deck Mode**

- Deck C — Sample deck
- Deck A — YouTube deck
- Deck B — YouTube deck
- Deck D — Sample deck

Additional sample decks provide independent mixer controls for creative layering and live performance.

The interface rearranges the mixer according to the selected deck configuration.

### DJ Mixer

- Channel volume faders
- Master volume control
- Crossfader
- Low, Mid, and High EQ
- Filter
- Delay
- Reverb
- Phaser
- Flanger
- Channel gain
- Level meters
- Mute controls
- Cue monitoring controls
- Transition effects

Audio routing and monitoring capabilities depend on the available Ableton Live configuration.

### Sample Pads

Each main deck provides eight sample pad slots.

Features include:

- Audio file assignment
- Import from selected Ableton Live audio clips
- Assignment from recorded or resampled material
- Play, pause, and stop
- Individual loop controls
- Volume adjustment
- Mute controls
- Playback position and duration indicators
- Sample source information
- Sample management settings

Sample pads can be used for drum loops, vocal samples, effects, musical phrases, transitions, and other audio material.

**The intended workflow allows sample pad playback while editing waveform regions.** If your system exhibits a conflict between waveform editing and pad playback, please report it.

### Audio File Import

YouTube DJ provides several methods for working with local audio:

- Load audio files
- Import compatible selected Live audio clips
- Assign local audio to sample pads
- Use recorded or resampled material
- Create sample assignment ranges from waveform selections

Supported import operations depend on the file format, Max for Live environment, and Live API capabilities.

**Important:** Drag-and-drop behavior may vary depending on the operating system and the source application. A visible drop indicator does not always guarantee that an audio file has been received successfully.

If drag-and-drop fails, try **LOAD FILE** or **IMPORT SELECTED CLIP** from the sample pad settings.

### Recording and Resampling

- Record audio within the supported routing configuration
- View recorded audio in the waveform editor
- Play and pause recorded audio
- Set cue points
- Create loop ranges
- Adjust supported tempo and pitch parameters
- Apply audio effects
- Save recorded audio as WAV
- Send supported recorded material to Ableton Live audio tracks
- Assign recorded material to sample pads

Recording and resampling are intended for creative audio workflows inside Ableton Live.

### Waveform Editor

The waveform section provides:

- Stereo waveform display
- Playback position cursor
- Wave scrub controls
- Scratch-style waveform interaction
- Loop range editing
- Trim range creation
- Trim undo
- Sample assignment range creation
- Visual waveform navigation

Different editing modes determine how mouse gestures are interpreted.

**WAVE SCRUB:** Click to seek or drag to scratch.

**ADJUST LOOP:** Adjust loop boundaries or move an existing loop range.

**CREATE TRIM RANGE:** Select a region for trimming.

**CREATE ASSIGN RANGE:** Select a region for sample assignment.

These features operate on supported local audio or recorded material, not directly on unrestricted YouTube audio streams.

### MIDI Mapping

MIDI Learn allows supported controls to be assigned to compatible MIDI controllers.

Mapping support includes selected controls for:

- Deck playback
- Cue operations
- Mixer controls
- Channel volume
- Crossfader
- Effects
- Sample pads
- Other supported performance parameters

Available mappings depend on device implementation and controller compatibility.

### Playlists and History

Each YouTube deck provides playlist and playback history tools.

- Independent playlists for Deck A and Deck B
- Playback history
- Video management
- Deck-specific navigation
- Playlist selection
- Support for DJ practice workflows

### Multilingual Interface

YouTube DJ supports seven interface languages:

- Japanese
- English
- German
- French
- Spanish
- Portuguese
- Italian

The interface language can be selected during initial setup and changed later through the settings.

---

## Requirements

- Ableton Live with Max for Live support
- A compatible Max for Live runtime
- Internet connection for YouTube playback
- YouTube DJ `.amxd` device file
- Audio output configured in Ableton Live

**Primary development environment:**

- Windows 11
- Ableton Live 12.3
- Max for Live

**macOS compatibility has not been verified.**

Behavior on other operating systems, Ableton Live versions, and Max versions may differ.

Some embedded-browser or audio-import features may depend on operating-system capabilities and available Max objects.

---

## Installation

1. Download the latest YouTube DJ `.amxd` file.
2. Open Ableton Live.
3. Load YouTube DJ onto an audio track.
4. Open the main YouTube DJ interface.
5. Select your preferred interface language when prompted.
6. Configure audio routing as required.
7. Load videos into Decks A and B.
8. Select 2-deck or 4-deck mode.
9. Use the mixer, cue, loop, sample, and recording controls.

YouTube DJ is distributed as a Max for Live device.

Additional setup may be necessary for specific audio-routing or monitoring configurations.

---

## Getting Started with Sample Pads

1. Open the sample pad settings.
2. Select Deck A or Deck B.
3. Choose a sample pad slot.
4. Use **LOAD FILE** to import a compatible audio file.
5. Alternatively, select an audio clip in Ableton Live and choose **IMPORT SELECTED CLIP**.
6. Use **TEST** to preview the assigned sample.
7. Close the settings modal.
8. Trigger the sample using the corresponding sample pad controls.

Recorded or resampled audio can also be assigned to supported sample slots.

When using waveform range assignments, select the desired region before assigning it to a pad.

---

## Important: YouTube Login and Advertisements

**Signing in to a YouTube account is not supported in YouTube DJ due to the embedded playback implementation and its technical restrictions.**

Account-specific features, including YouTube Premium benefits, should not be assumed to apply inside this device.

**YouTube advertisements may play before or during video playback.**

Advertisement delivery, playback restrictions, interruptions, and video availability are controlled by YouTube and are outside the control of YouTube DJ.

**YouTube DJ does not block, skip, remove, or bypass YouTube advertisements.**

Please keep the following limitations in mind:

- Ads may interrupt video playback.
- Internet connectivity can affect playback stability.
- Some videos may prohibit embedded playback.
- Regional restrictions may prevent access.
- Video availability may change.
- Uninterrupted or gapless playback cannot be guaranteed.
- YouTube playback does not necessarily provide unrestricted tempo, audio capture, or pitch manipulation.

**For performances requiring reliable, uninterrupted playback, use appropriately licensed local audio and a suitable DJ or DAW playback configuration.**

---

## Important: Audio Recording and Sampling

Recording, sampling, and resampling capabilities depend on the available audio sources, Ableton Live routing, and permissions associated with the material.

**YouTube DJ does not grant permission to record, copy, extract, redistribute, or commercially exploit copyrighted content.**

Users must ensure that their use of recorded or sampled material complies with applicable laws, licenses, and platform terms.

---

## Known Limitations

- YouTube playback is subject to embedded player restrictions.
- YouTube account login is not supported.
- YouTube advertisements cannot be controlled by the device.
- Some playback operations are limited by the YouTube player.
- File drag-and-drop support may vary by platform and source application.
- Certain Live API operations depend on the Live and Max runtime.
- Importing selected Live clips may use the original audio file rather than Live's Warp or clip-trim settings.
- macOS compatibility has not yet been verified.
- Some functionality may require additional testing on different Live versions or systems.

**If drag-and-drop displays a target but does not load the audio, use LOAD FILE or IMPORT SELECTED CLIP and report the issue.**

---

## Troubleshooting

### No Audio from Sample Pads

- Confirm that an audio source is assigned.
- Check the sample pad volume.
- Check the pad mute state.
- Check the deck channel fader.
- Check master volume and audio routing.
- Test the sample from the sample settings modal.

### Waveform Scrub Does Not Respond

- Confirm that audio has been loaded.
- Enable WAVE SCRUB mode.
- Click or drag within the waveform display.
- Check whether another waveform editing mode is active.
- Report unexpected behavior with reproduction steps.

### Unable to Import Audio

- Verify the file format.
- Try LOAD FILE.
- Try IMPORT SELECTED CLIP.
- Verify the selected Live clip references an accessible audio file.
- Check the Max Console for relevant error messages.

### YouTube Video Does Not Play

- Check the internet connection.
- Check whether the video allows embedding.
- Try another video.
- Check whether advertisements or playback restrictions are interfering.

---

## Copyright and Responsible Use

**YouTube DJ is a playback and creative-performance tool. It does not grant any license or permission to use copyrighted music or videos.**

- All rights to YouTube videos, recordings, compositions, artwork, and other third-party content remain with their respective copyright owners.
- Users are responsible for complying with applicable copyright laws, YouTube's Terms of Service, and relevant license conditions.
- Public performances, livestreams, DJ mix recordings, broadcasting, redistribution, sampling, and remixing may require separate permissions or licenses.
- Recording or sampling music through YouTube DJ or Ableton Live does not automatically grant permission to publish, share, sell, or reuse it.
- Use original works, properly licensed material, or content for which you have the required permissions.
- Availability on YouTube does not imply that content is licensed for other uses.

YouTube DJ is an independent third-party project.

**It is not affiliated with, endorsed by, or sponsored by YouTube, Google, or Ableton.**

All respective trademarks and product names remain the property of their owners.

---

## Feedback and Bug Reports

YouTube DJ is an independently developed Max for Live project.

Bug reports, compatibility feedback, and suggestions are welcome.

When reporting an issue, please include:

- Operating system and version
- Ableton Live version
- Max version, if available
- YouTube DJ version
- Steps to reproduce the problem
- Screenshots or relevant Max Console messages

Please submit reports through GitHub Issues.

Reports involving audio routing, waveform interaction, sample pad playback, and file import are especially helpful for improving compatibility.

---

## License and Distribution

YouTube DJ is provided free of charge.

Refer to the `LICENSE` file included in the repository, if present, for the terms governing modification, redistribution, and reuse.

If no license is provided, copyright remains with the author, and publication of the repository does not automatically grant permission for modification or redistribution.

The software's availability does not grant any rights to third-party music, video, images, or other copyrighted content.

---

## ☕ SUPPORT THE PROJECT — BUY ME A COFFEE

**YouTube DJ is free because I want to make creative DJ tools more accessible to Ableton Live users.**

Maintaining an independent Max for Live project takes time, especially when implementing audio processing, playback systems, MIDI integration, waveform editing, and compatibility improvements.

**If YouTube DJ helps with your DJ practice, live performance, or music production, please consider supporting future development.**

Your contribution helps sustain the project and encourages continued improvements.

### ☕ **[BUY ME A COFFEE — SUPPORT YOHsUKE NAKANO](https://buymeacoffee.com/yohsukenak)**

**Thank you for using YouTube DJ and supporting independent music software development!**

---

**Developer:** Yohsuke Nakano  
**Project:** YouTube DJ for Max for Live  
**Version:** v1.1  
**Platform:** Ableton Live / Max for Live  
**Primary Tested Environment:** Windows 11 / Ableton Live 12.3  
**Support:** https://buymeacoffee.com/yohsukenak
