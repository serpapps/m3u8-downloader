# M3U8 Downloader (Browser Extension)

> Detect and download HLS/M3U8 streams from supported websites and save them as MP4 files.

M3U8 Downloader is a browser extension built for users who need a site-agnostic HLS workflow instead of a single-site downloader. It monitors supported media requests in your browser, detects M3U8/HLS streams and related video sources, and helps you export them into standard MP4 files without relying on command-line tools.

- Detect HLS/M3U8 streams from supported sites
- Save compatible streams as MP4 files
- Review multiple available stream variants and qualities
- Download media from browser-visible streaming sessions
- Use a browser workflow instead of FFmpeg or manual playlist extraction

## Links

- 🚀 Get it here: [M3U8 Downloader](https://serp.ly/m3u8-downloader)
- 🆕 Latest release: [GitHub Releases](https://github.com/serpapps/m3u8-downloader/releases/latest)
- ❓ Help center: [SERP Help](https://help.serp.co/en/)
- 🐛 Report bugs: [GitHub Issues](https://github.com/serpapps/m3u8-downloader/issues)
- 💡 Request features: [Feature Requests](https://github.com/serpapps/m3u8-downloader/issues)

## Preview

![M3U8 Downloader workflow preview](assets/workflow-preview.svg)

## Table of Contents

- [Why M3U8 Downloader](#why-m3u8-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download HLS Streams](#step-by-step-tutorial-how-to-download-hls-streams)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [About M3U8 / HLS](#about-m3u8--hls)

## Why M3U8 Downloader

HLS streams are not ordinary downloadable files. They are delivered through playlist manifests and media segments, which means right-click saving does not work and generic downloader tools often miss the real stream behind the page player. For many users, the alternatives are either fragile websites or technical command-line workflows.

M3U8 Downloader is built for that protocol-level use case. It watches browser-visible media requests, detects compatible stream sources, and gives you a cleaner way to export supported HLS media into a single local file.

## Features

- Automatic detection of compatible M3U8/HLS streams from browser activity
- Support for related direct video formats where exposed by the page
- MP4 export for compatible HLS workflows
- Quality and stream-variant selection where multiple options exist
- Download progress tracking for active exports
- Browser-based workflow without requiring FFmpeg commands
- Support for login-gated browser sessions when the stream is already available in the page context
- Cross-browser support for Chrome, Edge, Brave, Opera, Firefox, Whale, and Yandex

## How It Works

1. Install the extension from the latest release.
2. Open a supported website with an HLS or compatible media player.
3. Start playback so the browser loads the stream requests.
4. Open the extension popup to review detected streams.
5. Choose the stream or quality you want.
6. Download the media and save the final MP4 file locally.

## Step-by-Step Tutorial: How to Download HLS Streams

1. Install M3U8 Downloader from the latest GitHub release.
2. Navigate to a supported page that uses an HLS or related streaming player.
3. Press play so the stream manifest and segments start loading.
4. Click the extension button in your browser toolbar.
5. Review the detected media sources and available quality variants.
6. Select the stream you want to keep.
7. Start the download and wait for the MP4 export to complete.
8. Open the saved file from your Downloads folder.

## Supported Formats

- Input: M3U8 / HLS streams
- Input: Related compatible media sources where exposed by the page
- Output: MP4

The final export is designed to turn stream-based playback into a single easier-to-use local video file.

## Who It's For

- Users downloading HLS streams from supported sites
- Testers and QA users capturing browser-visible stream outputs
- Creators archiving their own streamed media
- Students or researchers preserving permitted streaming content for offline access
- Anyone who wants a browser-based HLS workflow instead of terminal tools

## Common Use Cases

- Save a compatible HLS stream from a supported site
- Export browser-visible M3U8 playback into a local MP4
- Review multiple quality variants before downloading
- Keep a local copy of content you are permitted to access
- Capture a stream that other generic downloaders fail to detect

## Troubleshooting

**The extension is not detecting the stream**  
Press play first and wait a few seconds so the manifest and segments start loading.

**No quality options are listed**  
Some players expose only one active stream variant.

**The site requires login**  
The extension only works on media you can already access in your current browser session.

**The stream still does not appear**  
Refresh the page, replay the media, and try again once the player is fully loaded.

**The page uses DRM**  
DRM-protected content is outside the supported scope of normal HLS capture workflows.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/m3u8-downloader](https://serp.ly/m3u8-downloader)

## Installation Instructions

1. Open the latest release page:
   [https://github.com/serpapps/m3u8-downloader/releases/latest](https://github.com/serpapps/m3u8-downloader/releases/latest)
2. Download the extension build for your browser.
3. Install the extension.
4. Open a supported page with streaming media.
5. Use the extension popup to detect and download the stream.

## FAQ

**What does this extension download?**  
Compatible HLS/M3U8 streams and related media sources that are visible to the browser on supported pages.

**Does it save videos as MP4?**  
Yes. Compatible stream workflows are exported as MP4 files.

**Do I need FFmpeg or terminal commands?**  
No. Everything runs through the browser extension workflow.

**Why do I have to press play first?**  
Because the stream usually is not exposed until the player actually starts loading media.

**Does it work on every streaming site?**  
No. It depends on the actual browser-visible media workflow and whether the stream is compatible with this extension’s detection path.

## Notes

- Only download content you own or have explicit permission to save
- The extension only works when the stream is already accessible in your browser session
- DRM-protected media is outside the normal supported workflow
- Quality depends on what the player exposes for that stream

## About M3U8 / HLS

M3U8 and HLS are stream delivery formats used by many modern video players. They are excellent for adaptive playback, but awkward for ordinary users who want a local file because the media is split into playlists and segments rather than exposed as a single downloadable video. M3U8 Downloader simplifies that workflow in a browser-first way.
