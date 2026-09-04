<div align="center">

# Sieve for Windows

**Paste a link, get the file — then transcode it on your GPU.**

A free desktop downloader and transcoder for Windows, built on yt-dlp + ffmpeg.
8 one-tap download presets over 1,800+ sites · a 52-preset transcode suite with
NVENC hardware encoding · batch + watch-folder modes · VMAF quality scoring ·
channel subscriptions on a schedule. No ads, no accounts, no tracking.

**[⬇ Download the latest release](../../releases/latest)**

</div>

---

## Install

1. Grab `sieve-setup-<version>.exe` from the [Releases](../../releases) page.
2. Run it — one-click, per-user install, no admin needed.
3. Windows SmartScreen may warn about an unsigned installer: choose **More info → Run anyway**.

The installer bundles ffmpeg, ffprobe, and yt-dlp — nothing else to install. The app
keeps its yt-dlp engine fresh with a built-in self-updater (About → Update yt-dlp).

## The Sieve family

- **Sieve for Windows** (this app) — Electron + React desktop app: hardware-encoder
  transcoding, watch folders, subscriptions.
- **[Sieve for Android](https://massivemiike.github.io/sieve-android/)** — native
  Kotlin + Jetpack Compose app with on-device MediaCodec transcoding.

The two are **siblings, not ports** — same name, same philosophy (free and clean,
never monetized), separate codebases with their own feature sets.

More: [michaelwright.work/projects/sieve-windows](https://michaelwright.work/projects/sieve-windows)

## Licenses

Sieve spawns FFmpeg strictly as a separate child process (no linking). FFmpeg is
GPL v3; yt-dlp is Unlicense. Full license texts and the FFmpeg source offer ship
inside the app and are viewable in the About panel.

*This repository hosts release downloads for Sieve for Windows.*
