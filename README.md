# Dropit

Dropit is a native macOS file converter designed with simplicity in mind. It processes files entirely on your Mac, eliminating the need to use online file-conversion services.

How many times have you been LOCKED IN on a task, only to hit a bump in the road because your .mp4 needs to be an .mov? Or a .wav needs to be an .mp3? 

With Dropit, simply drag your file(s) to the application window, select your file's output destination and desired format, and voila! That's all there is to it. Need a format that isn't shown? Have a design suggestion? I'd love to hear about it. 



## What it converts

- Images: PNG, JPEG, HEIC, TIFF, BMP, and GIF
- Documents: Word, OpenDocument, EPUB, HTML, Markdown, reStructuredText, Rich Text, LaTeX, and plain text
- Audio: MP3, M4A, AAC, WAV, FLAC, and Opus
- Video: MP4, QuickTime, Matroska, WebM, AVI, and M4V
- Extraction: audio tracks from video

Compatible files can be converted together as a batch. Dropit never overwrites an existing file, shows batch progress, supports cancellation, and can reveal completed files in Finder.


## Why Make this? Aren't there other file-conversion solutions? 

Yes, there are plenty of file‑conversion platforms! However, most are web‑based, so I have no idea where my personal documents go after I upload them for conversion(I'm looking at YOU, CloudConvert). 

Because I do a lot of homelab projects, I'm constantly using websites like CloudConvert. So, I wanted to build a super‑simple app that lives on your desktop, as straightforward in functionality as AirDrop or Blip, and ready to convert your files at a moment's notice.  


## Product Roadmap

Functionality: Additional Support for file extensions to be released soon! Still working on a way to package those libraries so the download isn't 1.5+GB!

Styles/Theming: I plan to add some retro internet‑core themes and an official Dropit theme dedicated to my Chocolate Lab, whom I actually named this app after because I keep telling him to “Drop iiiit!”


## Status

Dropit is in active development for macOS 14 and later on Apple silicon and Intel Macs. The source is proprietary and maintained in a private repository.

Screenshots and signed, notarized DMG downloads will be added here when the first release is ready.

> Complex Office documents may not retain every layout detail because Dropit deliberately does not bundle LibreOffice.
