<div align="center">

# Dropit

**A compact Mac file converter that keeps your files on your Mac.**

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?style=flat-square)
![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon-8A8A8A?style=flat-square)
![Processing](https://img.shields.io/badge/processing-local-2EA44F?style=flat-square)
![Release](https://img.shields.io/badge/release-v0.1.0-0969DA?style=flat-square)

<img src="docs/dropit-0.1.0.jpg" width="320" alt="Dropit 0.1.0 compact file drop window">

</div>

## Download

Download **[Dropit 0.1.0 for Apple Silicon](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.0)**. It requires macOS 14 or later.

> [!WARNING]
> Dropit 0.1.0 is ad-hoc signed and is not notarized or verified by Apple. Follow the one-time macOS instructions below. Do not disable Gatekeeper or run Terminal commands.

## Install an unsigned copy

1. Download the DMG from [GitHub Releases](https://github.com/zacharystraley-SE/Dropit/releases/tag/v0.1.0).
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
2. Choose a compatible format and output location.
3. Convert, then reveal the results in Finder.

Dropit supports batches, cancellation, progress, collision-safe filenames, and combining ordered files into a PDF.

## Supported workflows

| Category | Dropit 0.1.0 workflows |
| :--- | :--- |
| **Images** | Convert common still-image formats including PNG, JPEG, HEIC, TIFF, BMP, WebP, GIF, and others supported by macOS. |
| **PDFs** | Create or combine PDFs, make a searchable PDF with OCR, export pages as images or individual PDFs, create multipage TIFFs, and recover text into document formats. |
| **Documents** | Convert Word, OpenDocument, rich text, HTML, plain text, EPUB, Markdown, reStructuredText, LaTeX, and other Pandoc formats. |
| **Spreadsheets** | Convert Excel, OpenDocument Spreadsheet, CSV, TSV, DBF, and PDF workflows. |
| **Presentations** | Convert PowerPoint and OpenDocument Presentation files or export them as PDF. |

Complex Office documents and recovered PDF text are best effort and may not preserve every layout detail.

> [!NOTE]
> Audio and video conversion is unavailable in v0.1.0 because FFmpeg is not bundled.

## Privacy

Conversions run locally. Dropit does not upload your files.

## Feedback

Need a format that is not listed or found a problem? [Open an issue](https://github.com/zacharystraley-SE/Dropit/issues).
