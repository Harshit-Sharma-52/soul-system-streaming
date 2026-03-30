# 🎶 Soul System Streaming  
*A custom music player app for the upcoming instrumental album **Soul System***  

---

## 📖 Overview  
Soul System Streaming is a **React + Tailwind CSS** powered music player built to showcase the *Soul System* album.  
It features a custom design inspired by the album visuals, responsive layouts, and support for streaming across desktop, tablet, and mobile.  

The app is lightweight, deployable to **Vercel**, and portfolio-ready.  

---

## ✨ Features  
- 🎧 **Custom Music Player**  
  - Play / Pause, Skip, Seek  
  - Shuffle and Repeat modes (Off → One → All)  
  - Loop back to the first track when skipping forward past the last track  

- 🕑 **Track Durations**  
  - Real durations auto-fetched from audio metadata  
  - Displayed in the tracklist, styled consistently with current/idle states  

- 🔊 **Volume + Mute Controls**  
  - Smooth slider styled in brand colors  
  - Mute toggle with contextual icon state  

- 🖼 **Responsive Layout**  
  - Desktop: split album art + player/tracklist columns  
  - Tablet: balanced layout with scaling  
  - Mobile: stacked layout with compact controls  

- 🎨 **Theming + Branding**  
  - Gradient header with logo + album name  
  - **Platform links row** directly under logo/title (Spotify, Apple Music, Bandcamp)  
  - Background image overlay + subtle noise texture  
  - Color palette drawn from album visuals (`#f5b14b`, `#cfa56a`, `#7a5cff`)  

- 🔗 **Platform Links**  
  - Buttons auto-generate only if a link exists in `ALBUM.links`  
  - Uses official platform brand colors for Spotify, Apple Music, Bandcamp  
  - Easily extendable for YouTube, Tidal, SoundCloud  

- 🚀 **Deployment Ready**  
  - Built for **Vite + React + Tailwind**  
  - `/public` folder handles all album assets (images + audio)  
  - Vercel config ensures audio streaming (`Accept-Ranges: bytes`)  

---

## 📂 Project Structure
/public
/audio # Album MP3 files (01.mp3 … 13.mp3)
/img # Album cover, logo, promo art, noise texture
/src
App.jsx # Main entry point
PlayerUI.jsx # Player + UI layout

---

## 🚀 Setup & Run
```bash
# Install dependencies
npm install

# Run locally
npm run dev

# Build for production
npm run build

---
Deploy by connecting your repo to Vercel.



📌 Case Study Notes

Problem: Needed a branded, mobile-friendly streaming experience for the Soul System album.

Solution: Built a responsive React + Tailwind player with custom branding and streaming features.

Result: Polished, feature-complete music player ready for album launch and portfolio showcase.
