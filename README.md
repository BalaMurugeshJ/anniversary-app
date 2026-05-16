# 💕 Happy 2nd Anniversary — Memory App

> A heartfelt, browser-based anniversary gift built with pure HTML, CSS, and JavaScript.
> Hosted on GitHub Pages — no installs, no frameworks, just love.

🌐 **Live Site:** [balamurugeshj.github.io/anniversary-app](https://balamurugeshj.github.io/anniversary-app/)

---

## ✨ What It Does

Every time the **"Reveal a Memory"** button is clicked:

- A random **photo** appears in a **polaroid-style frame** with a shimmer while it loads
- A random **sweet saying** fades in beneath it
- Sayings **never repeat** until all 20 have been shown — then they reshuffle
- Romantic **background music** starts softly on the first click
- A **♪ button** (bottom-right corner) lets you mute/unmute anytime
- Soft **floating hearts** drift across the background continuously

---

## 📁 Complete File & Folder Structure

```
anniversary-app/                 ← your GitHub repository (root)
│
├── index.html                   ← Full app (HTML + CSS + JS in one file)
├── sayings.txt                  ← Comma-separated list of cute sayings
├── music.mp3                    ← Romantic background music
├── README.md                    ← This file
│
└── images/                      ← All anniversary photos
      1.jpg
      2.jpg
      3.jpg
      4.jpg
      5.jpg
      6.jpg
      7.jpg
      8.jpg
      9.jpg
      10.jpg
      11.jpg
      12.jpg
      13.jpg
      14.jpg
      15.jpg
```

> ⚠️ Photo names must be exactly `1.jpg`, `2.jpg` etc. — no spaces, no capitals.

---

## 🚀 Full Feature List

| Feature | Details |
|---|---|
| 🖼️ Polaroid photo frame | Slightly rotated white-bordered frame for each photo |
| ✨ Fade-in animation | Photo and text slide up and fade in on every reveal |
| ⏳ Shimmer loading | Pink shimmer placeholder shown while image loads |
| 💬 No-repeat sayings | All 20 sayings shown before any repeat (Fisher-Yates shuffle) |
| 🎵 Background music | Starts softly on first button click, loops continuously |
| 🔇 Mute button | Fixed ♪ button in bottom-right corner to toggle sound |
| 🌸 Floating hearts | ❤️ 🩷 💕 💗 💖 🌸 drift upward in the background |
| ⚡ Image preloading | All 15 photos loaded silently on page open for instant clicks |
| 📱 Responsive | Works on mobile, tablet, and desktop |
| 🔤 Custom fonts | Playfair Display (headings) + Lato (body) via Google Fonts |

---

## 🛠️ How to Update Things

All edits are done in the **GitHub Web UI** — no terminal needed.

### ➕ Add a new saying
1. Click `sayings.txt` → pencil icon to edit
2. Add your new saying at the end, separated by a comma
3. Commit changes

### 🖼️ Add or replace a photo
1. Rename your photo (e.g. `16.jpg`) before uploading
2. Go to repo → **"Add file"** → **"Upload files"** → type `images/` in the path box
3. Upload the photo and commit
4. Open `index.html`, find the `imageNames` array and add `'16.jpg'`
5. Commit

### 🎵 Change the music
1. Rename your new song file to `music.mp3`
2. In the repo, click the old `music.mp3` → three dots `...` → **Delete file** → commit
3. Go back to repo root → **"Add file"** → **"Upload files"** → upload the new `music.mp3`
4. Commit — no code changes needed

### 🎨 Change the accent colour
Open `index.html`, press **Ctrl+H** (find & replace) and replace all instances of `#e8315a` with your new colour hex code.

---

## ⚡ Performance Tips

| Tip | Tool | Impact |
|---|---|---|
| Compress photos | [squoosh.app](https://squoosh.app) | 🔥 Biggest improvement |
| Compress music | [mp3smaller.com](https://www.mp3smaller.com) | ⚡ Faster audio load |
| Keep images named simply | Rename before uploading | ✅ Avoids broken links |

---

## 🎵 Audio Notes

- Browsers **block true autoplay** — music starts on the **first button click**, not page load
- The ♪ button in the bottom-right corner toggles mute/unmute at any time
- Volume is set to `0.35` (35%) by default — change it in `index.html` if needed
- Free romantic music: [pixabay.com/music](https://pixabay.com/music) → search **"romantic piano"**

---

## 🏗️ Tech Stack

- **HTML5** — structure
- **CSS3** — animations, polaroid frame, shimmer, floating hearts, responsive layout
- **Vanilla JavaScript** — shuffle logic, image preloading, audio control, DOM updates
- **Google Fonts** — Playfair Display + Lato
- **GitHub Pages** — free hosting, zero configuration

No build tools. No npm. No frameworks. Just three files, a folder, and a song. 💛

---

## 💌 Made with love

Built as a 2nd anniversary gift.
Every click is a little reminder of how far we've come. 🥂

---

*Last updated: May 2026*
