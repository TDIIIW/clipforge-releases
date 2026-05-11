<div align="center">

<img src="logo.svg" alt="ClipForge" width="320" style="margin-top: 40px;" />

<br/>
<br/>

**Turn your stream recordings into polished short-form clips — in minutes, not hours.**

[![Platform](https://img.shields.io/badge/platform-Windows-blue?style=flat-square)](#download)
[![Built with Electron](https://img.shields.io/badge/built%20with-Electron-47848F?style=flat-square)](https://www.electronjs.org/)

</div>

---

## What is ClipForge?

ClipForge is a **desktop app for streamers** that takes your horizontal gameplay recordings and reformats them into vertical short-form videos — ready to drop straight onto TikTok, YouTube Shorts, or Instagram Reels.

No subscriptions. No uploading footage to a cloud. Everything runs **locally on your machine**, processes in seconds with GPU acceleration, and outputs broadcast-quality video.

---

## The Problem It Solves

You just played a great session. You clipped the best moment. Now you need it vertical for Shorts — but your webcam is in the corner, your gameplay fills the frame, and you've got overlays all over the place.

Most tools make you crop blindly or pay for an AI editor that still gets it wrong. ClipForge lets you **see exactly what you're cutting**, place every element where you want it, and export in one click.

---

## Features

**Import**
- Drag-and-drop any video file (MP4, MKV, MOV, and more)
- Trim to your exact in/out point using a visual filmstrip timeline
- Prepend or append intro/outro clips automatically

**Regions**
- Draw boxes around any element you want to isolate — webcam, minimap, health bar, kill feed, anything
- Resize, reposition, and rename each region
- Choose the shape: rectangle, rounded, or circle mask
- Add a background effect behind each region: blur, solid colour, or none

**Compose**
- Drag your regions into a live 9:16 canvas preview
- Set your gameplay position and size independently
- Multiple layout presets (full, top 60%, top 50%, centered)

**Export & Process**
- Desktop track (original horizontal, cleaned up)
- TikTok / YouTube Shorts vertical track
- Individual isolated region tracks (great for facecam-only cuts)
- Automatic GPU encoder detection — uses NVIDIA NVENC, AMD AMF, or Intel Quick Sync if available, falls back to CPU
- Progress tracking per job with overall percentage

**Twitch Clips**
- Browse and download your Twitch clips directly inside the app

---

## How It Works

```
Your recording
      │
      ▼
  [ Import ]  ─── trim start / end point
      │
      ▼
  [ Regions ] ─── draw boxes around overlays
      │
      ▼
  [ Compose ] ─── arrange into 9:16 layout
      │
      ▼
  [ Export ]  ─── choose output tracks
      │
      ▼
  [ Process ] ─── ffmpeg renders everything locally
      │
      ▼
  Your folder: clip_name YYYY-MM-DD/
    ├── short.mp4        ← vertical TikTok/Shorts
    ├── desktop.mp4      ← original horizontal
    └── webcam.mp4       ← isolated region (optional)
```

All processing happens on your machine using a bundled ffmpeg binary. Nothing leaves your computer.

---

## Output Quality

- H.264 encoding (GPU-accelerated when available)
- Lossless region extraction — no double-compression on cropped areas
- Shape masks (circle, rounded rect) applied cleanly at render time
- Background blur / solid fill rendered directly in the ffmpeg filter graph

---

## Download

ClipForge is currently in private early access. If you'd like to try it, reach out directly:

📧 [tdiiw@proton.me](mailto:tdiiw@proton.me)

---

## Follow

Stay up to date and catch clips that were made with ClipForge:

[![Twitch](https://img.shields.io/badge/Twitch-tdiiw-9146FF?style=flat-square&logo=twitch&logoColor=white)](https://www.twitch.tv/tdiiw)
[![YouTube](https://img.shields.io/badge/YouTube-@tdiiw-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@tdiiw)
[![TikTok](https://img.shields.io/badge/TikTok-@tdiiw__-000000?style=flat-square&logo=tiktok&logoColor=white)](https://www.tiktok.com/@tdiiw_)

---

## Who Is This For?

- **Streamers** who want to repurpose VODs into TikTok/Shorts without paying for cloud editors
- **Clip makers** who need precise control over what goes where in a vertical layout
- **Content teams** processing multiple clips in a consistent format

---
