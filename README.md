# Shorts Zone (desktop app)

The [Shorts Zone](https://shortszone.studio4any.com) editor as a Mac and Windows app. Turn long videos into
shorts on your own computer, with the same account and plan as the website.

- Paste a YouTube link or drop a video file. The app downloads and processes it on your computer; videos are
  not uploaded to our servers.
- Captions are transcribed on your GPU (Metal on Mac, Vulkan or CUDA on Windows), with a CPU fallback.
- Finished shorts are saved straight to a folder (`Movies/Shorts Zone` on Mac, `Videos\Shorts Zone` on Windows).

## Download

- **Mac (Apple Silicon — M1 and later):** [Shorts-Zone-mac-arm64.dmg](https://github.com/elturing/shorts-zone-desktop/releases/latest/download/Shorts-Zone-mac-arm64.dmg)
- **Mac (Intel):** [Shorts-Zone-mac-x64.dmg](https://github.com/elturing/shorts-zone-desktop/releases/latest/download/Shorts-Zone-mac-x64.dmg)
- **Windows:** [Shorts-Zone-Setup.exe](https://github.com/elturing/shorts-zone-desktop/releases/latest/download/Shorts-Zone-Setup.exe)

The app updates itself.

Only import videos you own or have permission to use.

This repository holds release binaries only. The app bundles [yt-dlp](https://github.com/yt-dlp/yt-dlp)
(Unlicense), [FFmpeg](https://ffmpeg.org) (GPL, license file included in the app) and
[whisper.cpp](https://github.com/ggml-org/whisper.cpp) (MIT).
