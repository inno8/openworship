---
layout: default
title: Home
nav_order: 1
description: "Open Worship - Free, open-source church presentation software"
permalink: /
---

# Open Worship
{: .fs-9 }

Free, open-source church presentation software for worship lyrics.
{: .fs-6 .fw-300 }

[<i class="fa-solid fa-download"></i> Download Now](https://github.com/inno8/open-worship/releases){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[<i class="fa-solid fa-book"></i> Read the Docs](getting-started){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## <i class="fa-solid fa-star"></i> Features

<div class="features-grid" markdown="1">

| | Feature | Description |
|:--|:--------|:------------|
| <i class="fa-solid fa-music fa-lg" style="color: #8b5cf6;"></i> | **Song Library** | Organize, search, and manage your worship songs |
| <i class="fa-solid fa-list-check fa-lg" style="color: #8b5cf6;"></i> | **Service Schedules** | Build setlists ahead of time or on-the-fly |
| <i class="fa-solid fa-display fa-lg" style="color: #8b5cf6;"></i> | **Multi-Display** | Project lyrics to any connected screen |
| <i class="fa-solid fa-video fa-lg" style="color: #8b5cf6;"></i> | **NDI & OBS** | Overlay lyrics on livestreams with transparency |
| <i class="fa-solid fa-rotate fa-lg" style="color: #8b5cf6;"></i> | **API Sync** | Connect to external systems via REST API |
| <i class="fa-solid fa-keyboard fa-lg" style="color: #8b5cf6;"></i> | **Keyboard Shortcuts** | Fast navigation during live services |

</div>

---

## <i class="fa-solid fa-images"></i> Screenshots

### <i class="fa-solid fa-tv"></i> Presenter View
Control your service with real-time preview and live output.

![Presenter View](assets/screenshots/presenter.png)

### <i class="fa-solid fa-folder-open"></i> Song Library
Organize, search, and manage your worship song collection.

![Library View](assets/screenshots/library.png)

### <i class="fa-solid fa-gear"></i> Settings
Customize fonts, colors, NDI output, and more.

![Settings](assets/screenshots/settings.png)

---

## <i class="fa-solid fa-rocket"></i> Quick Start

### 1. <i class="fa-solid fa-download"></i> Download

| Platform | Download |
|:---------|:---------|
| <i class="fa-brands fa-windows"></i> **Windows** | [Open-Worship-Setup.exe](https://github.com/inno8/open-worship/releases) |
| <i class="fa-brands fa-apple"></i> **macOS** | [Open-Worship.dmg](https://github.com/inno8/open-worship/releases) |
| <i class="fa-brands fa-linux"></i> **Linux** | [Open-Worship.AppImage](https://github.com/inno8/open-worship/releases) |

### 2. <i class="fa-solid fa-plus"></i> Add Songs

1. Open the **Library** tab
2. Click **+ Add Song**
3. Enter the title and lyrics
4. Use markers like `[Verse 1]`, `[Chorus]`, `[Bridge]` to organize sections

### 3. <i class="fa-solid fa-calendar-days"></i> Build a Schedule

1. Go to **Present** tab
2. Click **Back to Schedules**
3. Create a new schedule and add songs

### 4. <i class="fa-solid fa-play"></i> Go Live

1. Select a song from your schedule
2. Click a verse to preview it
3. Press **Enter** or click **→ LIVE** to send to output
4. Use **Space** or arrow keys to navigate

---

## <i class="fa-solid fa-book"></i> Documentation

| | Guide | Description |
|:--|:------|:------------|
| <i class="fa-solid fa-flag-checkered"></i> | [Getting Started](getting-started) | Installation and first launch |
| <i class="fa-solid fa-graduation-cap"></i> | [User Guide](user-guide) | Complete feature guide |
| <i class="fa-solid fa-broadcast-tower"></i> | [NDI & OBS Setup](ndi-obs-setup) | Livestream integration |
| <i class="fa-solid fa-keyboard"></i> | [Keyboard Shortcuts](keyboard-shortcuts) | Quick reference |
| <i class="fa-solid fa-circle-question"></i> | [FAQ](faq) | Common questions |

---

## <i class="fa-solid fa-code"></i> For Developers

### Tech Stack

| | Component | Technology |
|:--|:----------|:-----------|
| <i class="fa-solid fa-desktop"></i> | Desktop | Electron + React + TypeScript |
| <i class="fa-solid fa-server"></i> | Backend | Django + REST Framework |
| <i class="fa-solid fa-database"></i> | Database | SQLite |
| <i class="fa-solid fa-network-wired"></i> | NDI | koffi bindings |

### Build from Source

```bash
git clone https://github.com/inno8/open-worship.git
cd open-worship/desktop
npm install
npm run dev
```

<i class="fa-brands fa-github"></i> See the [GitHub repository](https://github.com/inno8/open-worship) for full build instructions.

---

## <i class="fa-solid fa-scale-balanced"></i> License

MIT License — free for personal and commercial use.
