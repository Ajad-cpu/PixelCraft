# miniPaint

![miniPaint](https://raw.githubusercontent.com/viliusle/miniPaint/master/docs/logo.png)

> A lightweight, in-browser paint application — forked for easy local development.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Node](https://img.shields.io/badge/node-%3E%3D14-green.svg)](https://nodejs.org/)

---

## 🚀 Quick start — get running in seconds

bash
# 1. Clone the repo
git clone https://github.com/viliusle/miniPaint.git
cd miniPaint

# 2. Install dependencies
npm install

# 3. Run the dev server
npm run dev


Open your browser at http://localhost:3000 (or the port printed by the dev server) and start painting! 🎨

---

## ✨ Why this repo

* Super light-weight paint editor that runs completely in the browser.
* Great for prototyping, demos, or embedding a simple drawing surface in web apps.
* Easy to fork and tweak — perfect for personal projects and learning.

---

## 📦 What’s inside

* Canvas drawing tools (brush, line, shape tools, text)
* Layers and export options
* Built with plain HTML/CSS/JavaScript (no heavy frameworks required)

---

## 🛠 Development notes

* Tested with Node.js 14+ and npm 6+. If you use pnpm or yarn the commands are similar.
* npm run dev starts a local server with live reload.

### Helpful commands

bash
npm install      # install deps
npm run dev      # start development server (live reload)
npm run build    # build production bundle
npm start        # start production server (if configured)


---

## 🎯 Tips & extras (make it yours)

* *Change the port*: If 3000 is taken, set PORT=5173 npm run dev (or modify the dev script in package.json).
* *Add your own theme*: Edit CSS files in src/styles (or css/) to brand the editor.
* *Auto-save*: Hook up localStorage to persist drawings between reloads.
* *Embed*: Use an <iframe> or copy the canvas markup into an existing app to embed the editor.

---

## 🧩 Suggested small customizations (ideas)

* Add an *undo stack* with history snapshots.
* Add *SVG export* alongside PNG for vector-friendly output.
* Integrate *socket.io* to enable collaborative drawing in real-time.

---

## 🐞 Troubleshooting

* **npm run dev fails**: Make sure Node and npm are updated. Delete node_modules and re-run npm install.
* *Blank page*: Open DevTools and check the console for missing file errors. Ensure built assets are being served from the correct folder.
* *Port already in use*: Change the port environment variable or kill the process using that port.

---

## 🤝 Contributing

This fork is meant for experimentation — contributions are welcome!

1. Fork the repo
2. Create a branch: git checkout -b feature/my-cool-tool
3. Commit: git commit -m "feat: add my cool tool"
4. Push & open a PR

Please keep commits tidy and include screenshots or short GIFs for UI changes.

---

## 📸 Screenshots

*Add screenshots to docs/ or the repo root and reference them here.*

md
![editor-screenshot](./docs/screenshot-1.png)


---

## 📜 License

This project uses the original repository license. See LICENSE in the repo for details (typically MIT).

---

## 💬 Feedback / Contact

If you want help customizing this README or adding features (build scripts, CI, Dockerfile, or embeds), ping me and I can generate code/snippets.

Happy painting! 🖌
