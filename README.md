# Play Onyx 🎬

**Play Onyx** is a high-performance, browser-based media player designed for seamless audio and video playback. Built with a focus on privacy and speed, it allows users to manage a local media library directly within the browser without uploading files to a server.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-yellow.svg)
![Material Design](https://img.shields.io/badge/UI-Material--3-purple.svg)

**[🔗 Live Demo](https://mainroute-core.github.io/Play-Onyx/)**

---

## ✨ Features

### 📂 Media Management
- **Local Persistence:** Uses **IndexedDB** to store your media files locally in the browser. They remain there even after a page refresh.
- **Unified Library:** Automatically categorizes files into "Audio" and "Video" tabs.
- **Smart Search:** Quickly find tracks or videos with the real-time search bar.
- **Drag & Drop:** Import files by simply dragging them into the interface.

### 🎧 Audio & Visuals
- **Audio Studio:** 3-band Equalizer (Bass, Mids, Treble) with presets (Rock, Pop, Jazz, etc.).
- **Visualizer:** Real-time frequency visualizer powered by the Web Audio API.
- **Speed Control:** Adjust playback speed from 0.5x to 2.0x.

### 📺 Video Enhancements
- **Video Studio:** Real-time filters for Brightness, Contrast, Saturation, and Hue.
- **Subtitles:** Support for external `.srt` and `.vtt` caption files.
- **Picture-in-Picture (PiP):** Multitask while watching your videos.
- **Fullscreen Mode:** Immersive playback experience.

### 🛠 UI/UX
- **Material 3 Design:** A sleek, modern interface following Google's latest design system.
- **Responsive:** Fully optimized for Desktop, Tablet, and Mobile devices.
- **Queue System:** Interactive "Next Up" list with drag-and-drop reordering.
- **Theming:** Toggle between Dark and Light modes.
- **Config Management:** Export and Import your player settings as JSON.

---

## 🚀 Getting Started

Since **Play Onyx** is built with Vanilla JavaScript and HTML5, it requires no installation or build process.

1. **Clone the repo:**
   ```bash
   git clone https://github.com/MainRoute-Core/Play-Onyx.git
   ```
2. **Open the project:**
   Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, or Safari).

---

## 🛠 Technical Stack

- **Frontend:** HTML5, CSS3 (Custom Variables, Grid, Flexbox).
- **Logic:** Vanilla JavaScript (ES6+).
- **Storage:** 
    - `IndexedDB` for storing large media Blobs.
    - `LocalStorage` for user preferences and settings.
- **APIs:** 
    - `Web Audio API` for EQ and Visualizer.
    - `Canvas API` for thumbnail generation and visualizer rendering.
    - `Picture-in-Picture API`.

---

## 🔒 Privacy

**Play Onyx** respects your privacy. 
- No media is ever uploaded to a server.
- All processing, storage, and playback happen locally on your machine.
- No tracking or analytics.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `Arrow Right` | Skip forward 5s |
| `Arrow Left` | Skip backward 5s |
| `Arrow Up` | Increase Volume |
| `Arrow Down` | Decrease Volume |

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

**Developed with ❤️ by [M Ramzan Ch](https://mramzanch.blogspot.com/) & [Pro-Bandey](https://github.com/Pro-Bandey) under [MainRoute Core](https://mainroute-core.github.io/)**