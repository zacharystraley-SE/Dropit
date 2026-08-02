<div align="center">

# Dropit

**A compact Mac file converter that keeps your files on your Mac.**

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?style=flat-square)
![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon-8A8A8A?style=flat-square)
![Processing](https://img.shields.io/badge/processing-local-2EA44F?style=flat-square)
![Release](https://img.shields.io/badge/release-v0.1.1-0969DA?style=flat-square)

<img src="docs/dropit-icon.png" width="96" alt="Dropit app icon">

</div>

Dropit is a native macOS utility for quick, private file conversion. Its compact window keeps the queue, output format, progress, and results in one focused place without uploading files or requiring an account.

![Dropit interface](docs/dropit-interface.jpg)

## Download

Download **[Dropit 0.1.1 for Apple Silicon](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.1)**. Dropit requires macOS 14 or later and an Apple Silicon Mac.

> [!WARNING]
> The current release is ad-hoc signed and is not notarized by Apple. Do not disable Gatekeeper or run Terminal commands to install it.

## Install

1. Download `Dropit-0.1.1-macOS-arm64-unsigned.dmg` from the [v0.1.1 release](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.1).
2. Open the DMG, drag **Dropit** to **Applications**, and eject the disk image.
3. Open **Dropit** once from **Applications**. If macOS blocks it, close the warning without deleting the app.
4. Open **System Settings → Privacy & Security**, select **Open Anyway** beside Dropit, authenticate, and confirm **Open**.

That exception is required only once. See [Apple's official guidance](https://support.apple.com/102445) for details.

## The conversion flow

1. Drop files onto the compact window or choose them with **Choose Files…**.
2. Select the output format. On the first conversion, choose a default destination folder; Dropit uses it for future conversions until you change it in Settings.
3. Review the planned output names, then select **Convert**.
4. Watch determinate progress, retry failures when needed, and reveal completed files in Finder.

The window keeps the app title **Drop it** centered, with Settings available at the upper right. The queue shows the source filenames and planned outputs without distracting secondary copy.

## Settings and history

- Change the default destination for all future conversions.
- Enable background-only notifications when a conversion finishes. Dropit does not notify while you are actively using the app.
- Review local job history, reveal an output in Finder, remove individual records, or clear all history.
- Choose completed-job retention: **1 week, 1 month, 3 months, 6 months, 1 year, or Never**. The default is **1 month**. Failed jobs remain until you remove them manually.

## Supported workflows

Dropit uses native macOS image and PDF APIs, with Pandoc and LibreOffice available for document, spreadsheet, and presentation workflows when installed. FFmpeg-backed audio and video formats appear only when FFmpeg is available.

It supports ordered batches, collision-safe output names, progress, stop-after-current cancellation, retries, diagnostics, Finder reveal, and combining ordered files into a PDF. Complex Office documents and recovered PDF text are best effort and may not preserve every layout detail.

## Privacy

Conversions run locally. Dropit does not upload your files, use external conversion services, or send conversion data off your Mac.

## Feedback

Need a format that is not listed or found a problem? [Open an issue](https://github.com/zacharystraley-SE/Dropit/issues).
