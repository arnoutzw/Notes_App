# Notes App

A Progressive Web App inspired by Obsidian, built as a single HTML file with a dark zinc/amber terminal-inspired theme.

## Features

- **Markdown Editor** — Split-view editor with live preview, syntax-highlighted code blocks, `[[wiki-links]]`, `#tags`, and table support
- **File Tree** — Left sidebar with folder hierarchy, create/delete notes, and real-time search
- **Graph View** — Full-screen D3.js force-directed graph showing note connections via wiki-links
- **Backlinks** — Right sidebar showing which notes reference the current note
- **Tags** — Auto-extracted from note content with filtering
- **Outline** — Table of contents generated from headings
- **Firebase Sync** — Real-time Firestore persistence with offline localStorage fallback
- **PWA** — Installable, offline-capable progressive web app

## Getting Started

1. Open `index.html` in your browser — or visit the deployed GitHub Pages site
2. On first launch, optionally configure Firebase (or skip to use local storage)
3. Start writing notes!

## Firebase Setup (Optional)

1. Create a project at [Firebase Console](https://console.firebase.google.com)
2. Enable Firestore Database
3. Click the settings gear in the app and enter your Firebase config

## Tech Stack

Single HTML file — no build step, CDN only:

- **Tailwind CSS** — Utility-first styling
- **marked.js** — Markdown parsing
- **highlight.js** — Code syntax highlighting
- **D3.js** — Interactive graph visualization
- **Firebase** — Cloud persistence
- **Lucide Icons** — UI iconography

## License

MIT
