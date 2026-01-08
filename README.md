# Geometric Resonance (Modified)

This is a customised version of **Geometric Resonance**,  created by [Kyler Simzer](https://github.com/kylersimzer/Geometric-Resonance).

It’s a single-file, local-first audio visualizer that runs right in your browser.No installs, no accounts, and definitely no uploading your files to some random server.

This version includes various tweaks and modifications to the original code, but the core soul of the project remains true to Kyler's original vision.

## Quick Start

1.  Download the `index.html` file.
2.  Open it in a modern browser (Chrome or Edge works best).
3.  Load a song (mp3/wav) or hit **Space** to play the included demo.
4.  That’s it.

## Controls

| Key | Action |
| :--- | :--- |
| **Space** | Play / Pause |
| **U** | Hide / Show UI |
| **R** | Randomize Settings |
| **F** | Fullscreen |
| **P** | Presets Menu |
| **1–8** | Switch Tabs |

## Privacy & Local-First

This app is strictly local. When you load an audio file, it stays in your browser's memory. It is **never** uploaded anywhere.

**Note:** By default, this HTML file might load some libraries (like Three.js) or fonts from CDNs. If you need it to be 100% offline or air-gapped:
1.  Download the dependencies locally.
2.  Update the resource links in the HTML to point to your local files.

## Recording

There's a built-in recording feature that captures video (WebM/VP9) + audio. 
*Heads up: Browser support for this API varies. If it behaves strangely in Safari, try Chrome.*

## Demo Audio

This repo includes `demo.mp3` for testing logic.

> **demo.mp3 © 2025 Rhytam Biswas. All rights reserved.**
> The demo audio file is **NOT** covered by the MIT License. It is included for demonstration purposes only. You cannot reuse, sample, or redistribute it without permission.
>
> Contact: weworkfortheo@gmail.com

## License & Credits

The code in this repository is open source under the **MIT License** (see LICENSE).

**Attribution:**
If you build something with this or use it commercially, please respect the original creator's request for credit:

> “Geometric Resonance by Kyler Simzer”

And if you appreciate the modifications in this specific version, a hat tip to this fork is always appreciated as well.

**Original Project:** [Kyler Simzer / Geometric Resonance](https://github.com/kylersimzer/Geometric-Resonance)
**Built with:** three.js & Web Audio API
