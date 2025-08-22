# 🎬 Autoplay Video Tab (HTML-only)

This project provides a simple HTML5 page that plays a local video automatically in the browser – fullscreen, without requiring any web server or external player.

## ✅ Features

- ✅ Autoplay video on page load (muted, fullscreen)
- ✅ Resume playback when switching back to the tab
- ✅ No VLC or third-party software needed
- ✅ 100% offline and local
- ✅ Pure HTML, CSS, and JavaScript

## 🧰 Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- An HTML file (`index.html`)
- A local MP4 video file (e.g., `video.mp4`)
- Both files must be in the same folder

## 🚀 How to Use

1. Place one of the `index.html` (`ENG_index.html` or `GER_index.html`) and your `video.mp4` file in the same folder.
2. Open `index.html` in your browser (double-click or use "Open With...").
3. The video will:
   - start automatically (muted)
   - enter fullscreen (if allowed)
   - resume playback when the tab is revisited

## ⚠️ Notes

- Modern browsers block autoplay with sound. This setup uses `muted` autoplay to ensure it works smoothly.
- Fullscreen must be user-initiated in some browsers. A click anywhere on the video will re-trigger fullscreen if needed.

## 📁 Folder Structure

