# ⬡ NEXUS — Mission Control

> A futuristic productivity dashboard that doesn't look like every other to-do app.

![Dark Mode](https://img.shields.io/badge/theme-dark%20%2F%20light-00d4ff?style=flat-square)
![Vanilla JS](https://img.shields.io/badge/built%20with-vanilla%20js-f59e0b?style=flat-square)
![No Framework](https://img.shields.io/badge/framework-none-7c3aed?style=flat-square)
![LocalStorage](https://img.shields.io/badge/storage-localStorage-10b981?style=flat-square)

---

## What is this?

NEXUS is a browser-based productivity app styled like a mission control dashboard. No React, no Vue, no build step — just HTML, CSS, and JavaScript running straight in your browser.

---

## Features

**Greeting & Clock**
- Live clock with seconds, auto-updating date
- Context-aware greeting (Good Morning / Afternoon / Evening / Night)
- Day progress bar showing how far through the day you are

**Focus Timer**
- Pomodoro-style timer with animated SVG ring
- Switch between Focus and Break modes
- Start, pause, resume, reset
- Session dot tracker — fills up every 4 completed sessions
- Fully customizable duration from settings

**Mission Queue (Tasks)**
- Add tasks with Low / Mid / High priority
- Color-coded priority indicator on each task
- Filter by All, Active, Done, or High priority
- Inline edit and delete
- Purge all completed tasks at once
- Everything persists in LocalStorage

**Quick Portals (Links)**
- Save shortcuts to your favorite websites
- Custom name + emoji icon per link
- Opens in new tab, delete on hover
- Saved to LocalStorage

**Mission Stats**
- Total tasks, completed count, focus sessions, day streak
- Animated completion rate progress bar

**Settings Panel**
- Set your operator name (shows in greeting)
- Customize focus and break duration
- Toggle dark / light mode

---

## Tech Stack

| Layer | Choice |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, glassmorphism, keyframe animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | Browser LocalStorage API |
| Fonts | Space Grotesk + Space Mono (Google Fonts) |
| Dependencies | **Zero** |

---

## Getting Started

No install. No build. Just open it.

```bash
# clone the repo
git clone https://github.com/your-username/nexus.git

# open in browser
open index.html
```

Or just double-click `index.html`.

---

## Project Structure

```
nexus/
├── index.html
├── css/
│   └── style.css
└── js/
    └── app.js
```

---

## Design

Dark space aesthetic with neon cyan and purple accents, glassmorphism cards, and a three-column mission control layout. Light mode available via the settings panel.
