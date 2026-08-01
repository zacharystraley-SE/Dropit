 +<div align="center">
     2 +
     3 +# Dropit
     4 +
     5 +**A native macOS file converter that never touches the internet.**
     6 +
     7 +![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?style=flat-square)
     8 +![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon%20%7C%20Intel-8A8A8A?style=flat-square)
     9 +![Processing](https://img.shields.io/badge/processing-100%25%20local-2EA44F?style=flat-square)
    10 +![Status](https://img.shields.io/badge/status-in%20development-D97706?style=flat-square)
    11 +
    12 +</div>
    13 +
    14 +---
    15 +
    16 +<!-- Screenshot goes here once the first release is ready -->
    17 +<!-- <div align="center"><img src="docs/screenshot.png" width="700" alt="Dropit main window"></div> -->
    18 +
    19 +## Overview
    20 +
    21 +Dropit converts files entirely on your Mac. No uploads, no accounts, no queue, and no wondering where your documents ended up.
    22 +
    23 +How many times have you been **locked in** on a task, only to hit a bump because your `.mp4` needs to be a `.mov`, your `.wav` nee
        ds to be an `.mp3`, or several scans need to become one PDF? Dropit is built to make that interruption as short as possible.
    24 +
    25 +## How it works
    26 +
    27 +1. Drag one or more files onto the Dropit window.
    28 +2. Pick an output format and destination.
    29 +3. Convert.
    30 +
    31 +That's all there is to it.
    32 +
    33 +## What it converts
    34 +
    35 +The first release is being validated with the following core format set:
    36 +
    37 +| Category | Formats |
    38 +| :--- | :--- |
    39 +| **Images** | PNG, JPEG, HEIC, TIFF, BMP, GIF |
    40 +| **Documents** | Word, OpenDocument, EPUB, HTML, Markdown, reStructuredText, Rich Text, LaTeX, plain text |
    41 +| **Audio** | MP3, M4A, AAC, WAV, FLAC, Opus |
    42 +| **Video** | MP4, QuickTime, MKV (Matroska), WebM, AVI, M4V |
    43 +| **Extraction** | Audio tracks pulled from video |
    44 +
    45 +Compatible files can convert together as a batch. Dropit shows progress, supports cancellation, reveals finished files in Finder,
        and never overwrites an existing file.
    46 +
    47 +> [!NOTE]
    48 +> Format support is finalized only after it passes conversion tests on both Apple silicon and Intel Macs. Complex Office and PDF-t
        o-editable conversions are best effort and may not preserve every layout detail.
    49 +
    50 +## Privacy by design
    51 +
    52 +Conversions stay on your Mac. Dropit has no accounts, uploads, telemetry, conversion history, or remote document processing. Bundl
        ed conversion engines run locally alongside native macOS frameworks.
    53 +
    54 +## Why build this? Aren't there other file-conversion solutions?
    55 +
    56 +Yes, there are plenty. Most are web-based, though, so I have no idea where my personal documents go after I upload them for conver
        sion. I'm looking at you, CloudConvert.
    57 +
    58 +I do a lot of homelab projects, which means I'm constantly reaching for conversion sites. I wanted a simple app that lives on the
        desktop—something as straightforward as AirDrop or Blip, ready at a moment's notice.
    59 +
    60 +## Roadmap
    61 +
    62 +- [ ] **Broader format support.** PDF creation, merging, text recovery and OCR; Office documents, spreadsheets and presentations;
        more image, media, subtitle and ebook formats.
    63 +- [ ] **Native releases.** Separate signed and notarized downloads for Apple silicon and Intel so nobody has to carry two copies o
        f the bundled conversion engines.
    64 +- [ ] **Themes.** Retro internet-core themes, plus an official Dropit theme dedicated to my chocolate Lab, who I named the app aft
        er because I keep telling him to *“Drop iiiit!”*
    65 +
    66 +## Status
    67 +
    68 +Dropit is in active development for macOS 14 and later on Apple silicon and Intel Macs. The source is proprietary and maintained i
        n a private repository.
    69 +
    70 +Screenshots and separate signed, notarized DMG downloads will be posted once the first release is ready.
    71 +
    72 +## Feedback
    73 +
    74 +Need a format that isn't listed? Have a design suggestion? Open an issue or reach out directly. I'd love to hear about it.
