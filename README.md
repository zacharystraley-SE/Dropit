<div align="center">

# Dropit

**A compact Mac file converter that keeps your files on your Mac.**

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?style=flat-square)
![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon-8A8A8A?style=flat-square)
![Processing](https://img.shields.io/badge/processing-local-2EA44F?style=flat-square)
![Release](https://img.shields.io/badge/release-v0.1.1-0969DA?style=flat-square)

<img src="docs/dropit-icon.png" width="96" alt="Dropit app icon">

</div>

## Download

Download **[Dropit 0.1.1 for Apple Silicon](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.1)**. It requires macOS 14 or later.

> [!WARNING]
> Dropit 0.1.1 is ad-hoc signed and is not notarized or verified by Apple. Follow the one-time macOS instructions below. Do not disable Gatekeeper or run Terminal commands.

## How to Install Dropit

1. Download the DMG from [GitHub Releases](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.1).
2. Open **Downloads** in Finder and double-click the DMG.
3. Drag **Dropit** into **Applications**, then eject the disk image.
4. Open **Applications** and double-click **Dropit** once.
5. When macOS blocks it, close the warning without moving the app to Trash.
6. Open Apple menu → **System Settings** → **Privacy & Security**.
7. Scroll to **Security** and click **Open Anyway** beside the Dropit message.
8. Authenticate with your Mac login password or Touch ID, then confirm **Open**.
9. This exception is needed only once.

**Open Anyway** appears only after the first launch attempt and remains available for roughly one hour. A managed Mac may require an administrator. See [Apple's official guidance](https://support.apple.com/102445) for details.

## How it works

1. Select files or drag them onto Dropit.
2. Choose a compatible format. On the first conversion, choose a default output folder; the compact 480-point window previews the exact output names before conversion.
3. Convert, then reveal the results in Finder.

The current compact interface keeps **Drop it** centered in the title bar, with a Settings pill at the upper right and the conversion controls arranged beneath the queue. The queue shows the source filenames and planned outputs without extra subtext competing for attention.

Dropit supports ordered batches, collision-safe planned filenames, progress, retrying failed files, clipboard diagnostics, Finder reveal, and combining ordered files into a PDF. Stopping a batch finishes its current file and keeps untouched files staged.

The default destination persists on your Mac until changed in Settings. Settings also offers optional background-only completion notifications and local job history. Completed jobs are kept for one month by default (or 1 week, 3 months, 6 months, 1 year, or never); failed jobs remain until manually removed.

## Supported workflows

| Category | Dropit workflows |
| :--- | :--- |
| **Images** | Convert common still-image formats including PNG, JPEG, HEIC, TIFF, BMP, WebP, GIF, and others supported by macOS. |
| **PDFs** | Create or combine PDFs, make a searchable PDF with OCR, export pages as images or individual PDFs, create multipage TIFFs, and recover text into document formats. |
| **Documents** | Convert Word, OpenDocument, rich text, HTML, plain text, EPUB, Markdown, reStructuredText, LaTeX, and other Pandoc formats. |
| **Spreadsheets** | Convert Excel, OpenDocument Spreadsheet, CSV, TSV, DBF, and PDF workflows. |
| **Presentations** | Convert PowerPoint and OpenDocument Presentation files or export them as PDF. |

Complex Office documents and recovered PDF text are best effort and may not preserve every layout detail.

> [!NOTE]
> Audio and video workflows appear only when FFmpeg is available on the Mac. The current public release does not bundle FFmpeg.

## Privacy

Conversions run locally. Dropit does not upload your files, use external services, or send conversion data off your Mac.

## Feedback

Need a format that is not listed or found a problem? [Open an issue](https://github.com/zacharystraley-SE/Dropit/issues).
