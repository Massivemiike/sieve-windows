<div align="center">

# Sieve for Windows

**Paste a link, get the file — then transcode it on your GPU.**

A free desktop downloader and transcoder for Windows, built on yt-dlp + FFmpeg.
8 one-tap download presets over 1,800+ sites · a 52-preset transcode suite with
NVIDIA NVENC, Intel Quick Sync and AMD AMF hardware encoding · batch + watch-folder
modes · VMAF quality scoring · channel subscriptions on a schedule.
No ads, no accounts, no tracking.

**[⬇ Download the latest release](../../releases/latest)**

</div>

---

## Install

1. Grab `sieve-setup-<version>.exe` from the [Releases](../../releases) page.
2. Run it — one-click, per-user install, no admin needed. Updating? Just run the new
   installer; your settings, history and presets carry over.
3. Windows SmartScreen may warn about an unsigned installer: choose **More info → Run anyway**.

The installer bundles everything Sieve needs — yt-dlp, FFmpeg + ffprobe, and Deno
(the JavaScript runtime yt-dlp uses for full YouTube support). Nothing else to install.

## Always current

Sites change all the time, so Sieve keeps its engines up to date on its own:

- It checks once a day for new **yt-dlp**, **FFmpeg** (stable release line) and **Deno**
  builds and shows a one-click **Update now** banner — or turn on
  **Settings → Engine updates → Install automatically**.
- Every update comes straight from its official publisher, is **checksum-verified**,
  and is **tested before it's used** — a build that would break a feature is rejected,
  and your working one is never touched.
- **About → Engines** shows what you're running and lets you update or **roll back**
  each engine. Updates apply to the next job — no restart needed.
- Want site fixes the moment they land? Switch yt-dlp to the **nightly** channel in Settings.

## Works with

Tested end to end with YouTube (videos, Shorts, Music, playlists, channels), Facebook
(reels, watch, fb.watch and share links), LinkedIn posts, SoundCloud, Bandcamp, Mixcloud,
Vimeo, Instagram, TikTok, X/Twitter, Reddit, Bluesky, Twitch, Dailymotion and Pinterest —
plus the rest of yt-dlp's 1,800+ supported sites.

**Signed-in content** (age-restricted, private or members-only videos): sign in to the site
in **Firefox**, then choose Firefox under **Settings → Cookies**. Sieve only uses your
cookies when a site actually asks for a login. Chrome, Edge and Brave lock their cookies
on Windows, so they can't be used for this.

## Requirements

Windows 10 or 11 (64-bit). Hardware encoding is optional and used automatically when
available: NVIDIA (NVENC), Intel (Quick Sync / Arc) or AMD Radeon (AMF). Everything
also works on the CPU.

## The Sieve family

- **Sieve for Windows** (this app) — Electron + React desktop app: hardware-encoder
  transcoding, watch folders, subscriptions.
- **[Sieve for Android](https://massivemiike.github.io/sieve-android/)** — native
  Kotlin + Jetpack Compose app with on-device MediaCodec transcoding.

The two are **siblings, not ports** — same name, same philosophy (free and clean,
never monetized), separate codebases with their own feature sets.

More: [michaelwright.work/projects/sieve-windows](https://michaelwright.work/projects/sieve-windows)

## Licenses

Sieve spawns FFmpeg, yt-dlp and Deno strictly as separate programs (no linking).
FFmpeg is GPL v3, yt-dlp is Unlicense, and Deno is MIT. Full license texts and the
FFmpeg source offer ship inside the app and are viewable in the About panel; FFmpeg
updates installed from within the app come directly from
[BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds), which publishes the
matching source.

*This repository hosts release downloads for Sieve for Windows.*
