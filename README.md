# PixelCraft


> PixelCraft — a lightweight, privacy-first in-browser image editor. No uploads, no accounts, just fast local editing with layers, brushes and basic filters.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) \[![Static Site](https://img.shields.io/badge/static-HTML%2FCSS%2FJS-orange.svg)]

---

## 🚀 Quick start — get running in seconds

```bash
# 1. Clone the repo
git clone https://github.com/Ajad-cpu/PixelCraft.git
cd PixelCraft

# 2. (Optional) Install dependencies if you want to use the dev/build scripts
npm install

# 3a. Open locally (no Node required)
# Just open index.html in your browser, OR run a tiny static server:
# Using npm
npx serve .
# Or Python 3 built-in server
python -m http.server 8000

# 3b. If the repo uses a dev script (for local tooling)
npm run dev
```

Open `http://localhost:8000` (or the port printed by your server) and start editing! 🎨

---

## ✨ About PixelCraft

PixelCraft is a small, open-source image editor built to run entirely in the browser — no uploads, no telemetry. It's perfect for quick edits, prototyping, teaching, or embedding a simple canvas editor inside another web app.

**Key features**

* Layers and basic layer controls
* Brush / paint tools and shape tools
* Basic filters and adjustments
* Drag-and-drop and clipboard paste support
* Offline-friendly: service worker and static assets included

---

## 📂 Repo structure (high level)

* `index.html` — single-page entry and demo UI
* `dist/` — built assets (if available)
* `images/` — screenshots and demo assets
* `examples/` — example files and demos
* `package.json` & `webpack.config.js` — dev/build scripts

---

## 🛠️ Development notes

* The repo already contains static assets and a working `index.html`, so you can run it without Node.
* If you want to modify build tooling, run `npm install` then `npm run build` (if present). You can also run `npm run dev` during active development if a dev script exists.

**Helpful commands**

```bash
npm install      # install deps
npm run dev      # start development server (if provided)
npm run build    # build production assets (if provided)
```

---

## 🎯 Tips & customizations

* Change UI styles by editing the CSS files in the repo.
* Add auto-save using `localStorage` to persist canvases between reloads.
* Export enhancements: add SVG export or better PNG metadata.
* Add collaborative drawing with WebSockets (`socket.io`).

---

## 🐞 Troubleshooting

* **Blank page**: Open DevTools → Console. Make sure `index.html` can load `bundle.js` (if present) and assets from the correct relative path.
* **`npm run dev` not found**: The repo is primarily static; you can use a static server (see Quick start) or add a dev toolchain.
* **Port already in use**: change the port when running the server: `python -m http.server 9000` or `npx serve -p 9001`.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-cool-tool`
3. Commit: `git commit -m "feat: add <feature>"`
4. Push & open a PR

Please add screenshots or short GIFs for any UI changes.

---



```md
![editor-screenshot](./images/preview.png)
```

---

## 📜 License

PixelCraft is released under the MIT License. See `LICENSE` for details.

---

## 💬 Contact

If you want help customizing this README or adding deployment (GitHub Pages / GitHub Actions), CI, or a Dockerfile, email: **[azadsinghdinkar@gmail.com](mailto:azadsinghdinkar@gmail.com)**.

Happy pixel-crafting! 🖌️
