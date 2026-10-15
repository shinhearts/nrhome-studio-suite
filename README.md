# nrHome Studio Suite

**Vibe coded from the heart.** Created by Drew Shinhearts.

A little more personal computing. A little less noise.

nrHome is a collection of retro desktop tools for watching, listening, recording and making music. Floating vintage hardware, familiar controls, and shelves for the things you want to keep—while leaving the rest of your desktop available.

| App | What it does |
| --- | --- |
| **nrVIEW** | A television and media player with video tapes, game cartridges, and storage shelves. |
| **nrTUBE** | A radio receiver and cassette player for stations, personal audio, and virtual mixtapes. |
| **nrRACK** | A floating music studio with instruments, pedals, mixing, loopers, MIDI routing, and recording. |
| **nrMONOLOG** | A quick microphone/interface voice recorder with a cassette shelf and customizable global hotkeys. |

nrFACE is a separate project and is not included in this suite.

## Get the Windows beta

**Release preparation is underway.** The app downloads will appear on the Releases page when the beta is published.

Download the official files from [Releases](https://github.com/shinhearts/nrhome-studio-suite/releases). Choose **Part1**, **Part2**, and **Setup-nrHome-Beta-1.cmd**, keeping all three in the same folder. Run the setup file to verify/extract both parts and create the four desktop shortcuts. Alternatively, extract both ZIPs into the same destination and run `Create-Desktop-Shortcuts.cmd` inside the suite folder.

This beta targets **Windows x64**. The desktop runtimes are included: no Node.js installation, earlier nrHome app, or older patch is required. Keep each app beside its supplied resources and runtime files. GitHub's automatic **Source code** archive contains repository documentation, not the runnable apps.

The download is free. If you'd like to support the project, you can [leave an optional tip on Ko-fi](https://ko-fi.com/drewshinhearts). Payment is not required for the supplied features. I'm a one-person operation, and support helps me keep building tools and games.

## Your desktop, your collection

Launch the app you want from its hardware icon. nrMONOLOG's keyboard button opens global-hotkey settings. nrRACK's home mount opens its instrument/effect inventory. See `START-HERE.txt` and the included documentation for setup and testing.

The suite can be carried on a USB drive. Preferences and internal libraries currently stay on the Windows computer; export creations you want to take elsewhere. Moving the suite folder or changing the USB drive letter requires recreating its desktop shortcuts.

## Beta notes

- Back up important recordings and configurations. Device compatibility and live-performance reliability need continued testing across more machines.
- Windows may identify the apps as coming from an unrecognized publisher. Check the official download source and supplied SHA-256 checksums; do not disable Windows security protections.
- Online radio, streaming, and first-time emulator/component downloads need internet. Third-party services, streams, and protected playback can change and are not guaranteed.
- Emulator setup currently needs internet on a fresh PC. Supplied homebrew games are distinct from commercial ROMs. Only import or share media you have rights to use.
- Linux and macOS releases will be listed when complete tested builds are available.

## Feedback

[Report an issue](https://github.com/shinhearts/nrhome-studio-suite/issues) with the app/version, Windows version, steps to reproduce, expected result, and actual result. Mention your sound device or controller when relevant. Please do not post passwords, private recordings, or personal identifiers.

## Terms and credits

This repository contains public distribution information and support materials. Original application development sources are not published in this repository. Electron apps contain the scripts and resources needed to run; this is not a promise of source-code secrecy.

See [TERMS.txt](TERMS.txt) for the original app distribution terms. Bundled third-party components and media retain their own licenses and required notices, included with each download. Your original recordings and creations remain yours.

nrHome is not affiliated with hardware manufacturers or third-party streaming services.
