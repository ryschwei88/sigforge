# SigForge ⚡
### AI-Powered Animated Forum Signature Generator

> *Bringing back the lost art of the 2000s GFX forum signature.*

SigForge is a browser-based tool that generates animated forum signatures in the style of early-2000s GFX communities — complete with smudge effects, particle systems, glowing text, scanline sweeps, lightning bolts, and more. Powered by AI (Claude) to suggest era-accurate taglines and style notes.

No installs. No Photoshop. Just open it and go.

---

## ✨ Features

- **8 Animation Modes** — Pulse Glow, Scanline Sweep, Particle Drift, Text Shimmer, Fire Flicker, Matrix Rain, Lightning, and ALL OUT mode
- **6 Style Presets** — Dark Grunge, Neon Cyber, Anime/Soft, Fire/Energy, Chrome Metal, Galaxy/Space
- **6 Text Effects** — Chrome, Glow, Fire, Gradient, Outlined, Drop Shadow
- **7 Color Schemes** — Blue Electric, Red/Fire, Green Matrix, Purple Dark, Gold Royal, Ice/White, Rainbow
- **AI Tagline Generation** — Claude suggests 2000s-accurate taglines if you leave the field blank
- **Download as Animated GIF** — export a real `.gif` you can drop into any forum
- **Download as PNG** — static snapshot for forums that don't support GIFs
- **Variations** — generate 4 alternate versions of your signature
- **100% client-side** — single HTML file, no backend required

---

## 🚀 Live Demo

👉 **[Try it here](https://yourusername.github.io/sigforge)**

*(Replace with your actual GitHub Pages URL after deploying)*

---

## 🛠 How to Use

**Option 1 — Use the live site**
Just visit the GitHub Pages link above. Nothing to install.

**Option 2 — Run locally**
```bash
git clone https://github.com/yourusername/sigforge.git
cd sigforge
# Open index.html in any browser — that's it
```

**Option 3 — Download the file**
Grab `index.html` from this repo, open it in your browser.

---

## 📁 Project Structure

```
sigforge/
├── index.html        # The entire app — self-contained
├── README.md         # This file
├── presets/          # Community-submitted style presets (JSON)
│   └── example-preset.json
└── screenshots/      # Preview images for the README
```

---

## 🗺 Roadmap

- [ ] phpBB / MyBB plugin integration
- [ ] SMF (Simple Machines Forum) mod
- [ ] Custom font upload
- [ ] Save signature to browser (localStorage)
- [ ] Community preset submissions
- [ ] More animation types (aurora, glitch, neon flicker)
- [ ] Animated text entrance effects
- [ ] Mobile layout improvements
- [ ] Optional image/render upload as background layer

---

## 🤝 Contributing

Contributions are welcome. The easiest way to contribute is to submit a new **style preset** — no deep code knowledge needed, just a JSON file in the `/presets` folder.

For bigger changes, open an issue first so we can discuss it.

---

## 💡 The Idea

Between roughly 2002 and 2010, forum signature art was its own subculture. Communities like GFXForum, Signature-Resource, and dozens of others were full of people learning Photoshop CS2, sharing renders and stock textures, and competing to make the most elaborate 400×150px animated GIF they could. It was a genuine creative ecosystem that basically vanished when social media killed the forum era.

SigForge is a small attempt to make that accessible again — for older folks who remember it, and younger people who never got to experience it.

---

## 📄 License

MIT — do whatever you want with it.

---

*Built with HTML5 Canvas, gif.js, and the Claude API.*
