# 💕 Happy 2nd Anniversary — Memory App

> A heartfelt, browser-based anniversary gift built with pure HTML, CSS, and JavaScript. Hosted on GitHub Pages — no installs, no frameworks, just love.

🌐 **Live Site:** [balamurugeshj.github.io/anniversary-app](https://balamurugeshj.github.io/anniversary-app/)

---

## ✨ What It Does

Every time the **"Reveal a Memory"** button is clicked:

- A random **photo** from the `images/` folder appears in a **polaroid-style frame**
- A random **sweet saying** is shown beneath it
- Sayings never repeat until all 20 have been shown (then they reshuffle)
- Soft **floating hearts** drift across the background
- Everything **fades in** smoothly with a staggered animation

---

## 📁 File Structure

```
anniversary-app/
├── index.html        ← Full app (HTML + CSS + JS in one file)
├── sayings.txt       ← Comma-separated list of cute sayings
├── README.md         ← This file
└── images/           ← All anniversary photos
      1.jpg
      2.jpg
      ...
      15.jpg
```

---

## 🚀 Features

| Feature | Details |
|---|---|
| 🖼️ Polaroid photo frame | Slightly rotated white-bordered frame for each photo |
| 💬 No-repeat sayings | Fisher-Yates shuffle — all 20 sayings shown before any repeat |
| 🌸 Floating hearts | Animated background — ❤️ 🩷 💕 💗 💖 🌸 drift upward continuously |
| ✨ Fade-in animation | Photo and text slide up and fade in on every reveal |
| ⚡ Image preloading | All 15 photos silently preloaded on page load for faster clicks |
| 📱 Responsive | Works on mobile, tablet, and desktop |
| 🔤 Custom fonts | Playfair Display (headings) + Lato (body) via Google Fonts |

---

## 🛠️ How to Update

All edits are done directly in the **GitHub Web UI** — no terminal needed.

### Add or change a saying

1. Click `sayings.txt` in the repo
2. Click the **pencil icon** to edit
3. Add your new saying separated by a comma
4. Click **Commit changes**

### Add or replace a photo

1. Rename your photo to the next number (e.g. `16.jpg`)
2. Click **"Add file" → "Upload files"** in the repo
3. Type `images/` in the path box
4. Drag and drop your photo
5. Open `index.html`, find the `imageNames` array and add `'16.jpg'` to it
6. Commit both changes

### Change the image count in the code

Open `index.html` and find this line:

```js
const imageNames = [
    '1.jpg','2.jpg','3.jpg','4.jpg','5.jpg',
    '6.jpg','7.jpg','8.jpg','9.jpg','10.jpg',
    '11.jpg','12.jpg','13.jpg','14.jpg','15.jpg'
];
```

Add or remove filenames to match what's in your `images/` folder.

---

## ⚡ Performance Tips

Photos loading slowly? Here's what helps most:

1. **Compress images** using [squoosh.app](https://squoosh.app) — reduces file size by up to 90% with no visible quality loss
2. **Rename before uploading** — keep names simple: `1.jpg`, `2.jpg`, etc.
3. The app already **preloads all images** silently on page load — so after the first visit everything is instant

---

## 🎨 Customisation

| What to change | Where to find it |
|---|---|
| Page title | `<title>` tag and `<h1>` in `index.html` |
| Button text | `<button>` tag in `index.html` |
| Accent colour | Search `#e8315a` in `index.html` and replace all |
| Heart emojis | `heartEmoji` array in the JS section |
| Animation speed | `floatUp` and `fadeUp` keyframes in the CSS section |

---

## 🏗️ Tech Stack

- **HTML5** — structure
- **CSS3** — animations, polaroid frame, floating hearts, responsive layout
- **Vanilla JavaScript** — shuffle logic, image preloading, DOM updates
- **Google Fonts** — Playfair Display + Lato
- **GitHub Pages** — free hosting, zero configuration

No build tools. No npm. No frameworks. Just three files and a folder. 💛

---

## 📸 Screenshot

> *A photo from the live site — floating hearts, polaroid frame, and a sweet saying.*

![App Screenshot](screenshot.png)

---

## 💌 Made with love

Built as a 2nd anniversary gift. Every click is a little reminder of how far we've come. 🥂

---

*Last updated: May 2026*
