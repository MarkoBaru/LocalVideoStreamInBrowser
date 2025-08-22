# 🎬 Autoplay Video Tab (HTML-only)

This project provides a simple HTML5 page that plays a local video automatically in the browser – fullscreen, without requiring any web server or external player.

## ✅ Features

- ✅ Autoplay video on page load (muted, fullscreen)
- ✅ Resume playback when switching back to the tab
- ✅ Infinite loop – video restarts when it ends
- ✅ 100% offline and local
- ✅ Pure HTML, CSS, and JavaScript

## 🧰 Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- An HTML file (`index.html`)
- A local MP4 video file (e.g., `video.mp4`)
- Both files must be in the same folder

## 🚀 How to Use

1. Place `index.html` and your `video.mp4` file in the same folder.
2. Open `index.html` in your browser (double-click or use "Open With...").
3. The video will:
   - start automatically (muted)
   - enter fullscreen (if allowed)
   - loop infinitely
   - resume playback when the tab is revisited

## ⚠️ Notes

- Most browsers block autoplay with sound. This setup uses `muted` autoplay to ensure smooth behavior.
- Fullscreen must sometimes be user-initiated. Clicking on the video will trigger fullscreen if needed.

## 📁 Folder Structure

```
my-video-tab/
├── index.html
└── video.mp4
```

## 📷 Preview

A fullscreen video experience, ideal for:
- Digital signage
- Kiosk displays
- Interactive installations
- Local media playback

No internet connection required – runs entirely from your local machine.

---

**Made with ❤️ for smooth, fullscreen, looped video experiences.**
