# 🎵 BardBox

<p align="center">
  <strong>Currently in private development</strong>
</p>
<p align="center">
  <strong>https://www.bardbox.app/</strong>
</p>

<p align="center">
<img width="1284" height="1031" alt="image" src="https://github.com/user-attachments/assets/75b1b9c8-c4a2-452c-b971-ac6248cd64e2" />
</p>

<p align="center">
  <strong>Bring your D&D games to life with immersive audio</strong>
</p>

## About

A tool that allows Dungeon Masters to bring their D&D games to life by organising music and sound effects, building soundscape presets, and triggering audio instantly - without breaking the flow of a session.

---

## Features

- **📁 Folder-based Audio Management** — Pick a single folder once; BardBox remembers it and asks for permission once per session via the File System Access API
- **▶️ Music Player** — Full playback controls with track progress, loop toggle, and volume
- **🔊 SFX Board** — Per-track play/stop, loop toggle, volume control, and Stop All
- **📋 Sortable Track Lists** — Drag to reorder music and SFX tracks; order is persisted across sessions
- **🎭 Scenes** — Build named scenes (e.g. "Tavern", "Combat") that save a music track and a set of SFX with their volume and loop state. Grouped into colour-coded scene groups
- **🎨 Scene Groups** — Organise scenes into named colour-coded groups shown in a collapsible sidebar
- **🎵 Scene Playback** — Selecting a scene activates a banner showing the assigned music track; scene play/stop triggers can drive audio automatically
- **✨ Animations** — Subtle Framer Motion transitions throughout
- **🌙 Dark Mode** — Full light/dark theme support
- **💾 Persistent Storage** — Tracks, file handles, and scene groups all survive page refresh via IndexedDB

---

## 🗺️ Planned Features

### Playback & Controls
- **⌨️ Keyboard Shortcuts** — Space to play/pause, number keys to trigger SFX slots, `L` to toggle loop
- **🔀 Random / Shuffle Mode** — Randomise playback within a tag or playlist
- **⏭️ Auto-advance** — Automatically play the next music track when one ends

### UX & Polish
- **📊 Visual Playback Feedback** — Pulsing indicator on active SFX, waveform or progress bar on music
- **🧭 Onboarding** — Empty-state guidance and a first-run walkthrough for new users

### Power User Options
- **🏷️ Track Tagging** — Tag tracks with labels like "combat", "ambient", "suspense" for quick filtering
- **🎛️ Customisable Layout** — Resize or rearrange panels; choose number of SFX columns
- **📤 Import / Export** — Export a scene pack (track metadata + settings) to share between machines
- **🔍 Search & Filter** — Live search across all tracks by name or tag

---

## 🛠️ Tech Stack

- **React 19** with TypeScript
- **Vite** — build tooling
- **Tailwind CSS** — utility-first styling
- **shadcn/ui** — component library (MIT licensed)
- **Radix UI** — accessible component primitives
- **Framer Motion** — animations
- **dnd-kit** — drag-to-reorder
- **IndexedDB (idb)** — local persistence
- **File System Access API** — native file handle storage
- **Vitest + React Testing Library** — unit testing

---

## 🔒 Code Quality

- **ESLint** — linting
- **Husky** — pre-commit hooks
- **Gitleaks** — secret detection
- **SonarCloud** — code quality analysis

---

<p align="center">
  Made with ❤️ for the TTRPG community
</p>
