<div align="center">

# Dropit

**A native macOS file converter that never touches the internet.**

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?style=flat-square)
![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon%20%7C%20Intel-8A8A8A?style=flat-square)
![Processing](https://img.shields.io/badge/processing-100%25%20local-2EA44F?style=flat-square)
![Status](https://img.shields.io/badge/status-in%20development-D97706?style=flat-square)

</div>

---

<!-- Screenshot goes here once the first release is ready -->
<!-- <div align="center"><img src="docs/screenshot.png" width="700" alt="Dropit main window"></div> -->

## Overview

Dropit converts files entirely on your Mac. No uploads, no accounts, no queue, and no wondering where your documents ended up.

How many times have you been **locked in** on a task, only to hit a bump because your `.mp4` needs to be a `.mov`, your `.wav` needs to be an `.mp3`, or several scans need to become one PDF? Dropit is built to make that interruption as short as possible.

## How it works

1. Drag one or more files onto the Dropit window.
2. Pick an output format and destination.
3. Convert.

That's all there is to it.

## What it converts

The first release is being validated with the following core format set:

| Category | Formats |
| :--- | :--- |
| **Images** | PNG, JPEG, HEIC, TIFF, BMP, GIF |
| **Documents** | Word, OpenDocument, EPUB, HTML, Markdown, reStructuredText, Rich Text, LaTeX, plain text |
| **Audio** | MP3, M4A, AAC, WAV, FLAC, Opus |
| **Video** | MP4, QuickTime, MKV (Matroska), WebM, AVI, M4V |
| **Extraction** | Audio tracks pulled from video |

Compatible files can convert together as a batch. Dropit shows progress, supports cancellation, reveals finished files in Finder, and never overwrites an existing file.

> [!NOTE]
> Format support is finalized only after it passes conversion tests on both Apple silicon and Intel Macs. Complex Office and PDF-to-editable conversions are best effort and may not preserve every layout detail.

## Privacy by design

Conversions stay on your Mac. Dropit has no accounts, uploads, telemetry, conversion history, or remote document processing. Bundled conversion engines run locally alongside native macOS frameworks.

## Why build this? Aren't there other file-conversion solutions?

Yes, there are plenty. Most are web-based, though, so I have no idea where my personal documents go after I upload them for conversion. I'm looking at you, CloudConvert.

I do a lot of homelab projects, which means I'm constantly reaching for conversion sites. I wanted a simple app that lives on the desktop—something as straightforward as AirDrop or Blip, ready at a moment's notice.

## Roadmap

- [ ] **Broader format support.** PDF creation, merging, text recovery and OCR; Office documents, spreadsheets and presentations; more image, media, subtitle and ebook formats.
- [ ] **Native releases.** Separate signed and notarized downloads for Apple silicon and Intel so nobody has to carry two copies of the bundled conversion engines.
- [ ] **Themes.** Retro internet-core themes, plus an official Dropit theme dedicated to my chocolate Lab, who I named the app after because I keep telling him to *“Drop iiiit!”*

## Status

Dropit is in active development for macOS 14 and later on Apple silicon and Intel Macs. The source is proprietary and maintained in a private repository.

Screenshots and separate signed, notarized DMG downloads will be posted once the first release is ready.

## Feedback

Need a format that isn't listed? Have a design suggestion? Open an issue or reach out directly. I'd love to hear about it.
