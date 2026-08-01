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

Dropit converts files entirely on your Mac. No uploads, no queue, no wondering where your documents ended up.

How many times have you been LOCKED IN on a task, only to hit a bump in the road because your `.mp4` needs to be a `.mov`? Or a `.wav` needs to be an `.mp3`?

## How it works

1. Drag your file or files onto the Dropit window.
2. Pick an output destination and a format.
3. Voila.

That's all there is to it.

## What it converts

| Category | Formats |
| :--- | :--- |
| **Images** | PNG, JPEG, HEIC, TIFF, BMP, GIF |
| **Documents** | Word, OpenDocument, EPUB, HTML, Markdown, reStructuredText, Rich Text, LaTeX, plain text |
| **Audio** | MP3, M4A, AAC, WAV, FLAC, Opus |
| **Video** | MP4, QuickTime, MKV (Matroska), WebM, AVI, M4V |
| **Extraction** | Audio tracks pulled from video |

**Batch behavior:** compatible files convert together as a batch. Dropit shows batch progress, supports cancellation, and can reveal finished files in Finder. It never overwrites an existing file.

> [!NOTE]
> Complex Office documents may not retain every layout detail. Dropit handles them locally with LibreOffice, but those conversions are still best effort.

## Why build this? Aren't there other file-conversion solutions?

Yes, there are plenty of file-conversion platforms. Most of them are web-based, though, so I have no idea where my personal documents go after I upload them for conversion. (I'm looking at YOU, CloudConvert.)

I do a lot of homelab projects, which means I'm constantly hitting sites like that. I wanted a super simple app that lives on your desktop, as straightforward as AirDrop or Blip, ready to convert files at a moment's notice.

## Roadmap

- [ ] **More formats.** PDF creation, merging, text recovery and OCR; Office documents, spreadsheets and presentations; plus more image, media, subtitle and ebook formats. Separate Apple silicon and Intel builds keep all those bundled libraries from turning into one giant download.
- [ ] **Themes.** Retro internet-core themes, plus an official Dropit theme dedicated to my chocolate Lab, who I actually named this app after because I keep telling him to *"Drop iiiit!"*

## Status

Dropit is in active development for macOS 14 and later on Apple silicon and Intel Macs. The source is proprietary and maintained in a private repository.

Screenshots and signed, notarized DMG downloads will be posted here once the first release is ready.

## Feedback

Need a format that isn't listed? Have a design suggestion? I'd love to hear about it. Open an issue or reach out directly.
