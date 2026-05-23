# 🏎️ Turbo Rush — 3D Car Racing Game

A browser-based 3D car racing game built with **HTML**, **CSS**, and **Three.js**.  
Avoid traffic, survive as long as you can, and beat your best score!

## 🎮 How to Play

| Key | Action |
|-----|--------|
| ← → Arrow Keys | Change lanes (left / right) |
| ↑ Arrow Key | Accelerate |
| ↓ Arrow Key | Brake |

- Dodge the oncoming traffic cars
- Speed and difficulty increase over time
- The game ends if you crash into another car

## 🚀 Play Online

👉 **[Play on GitHub Pages](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**  
*(Replace with your actual GitHub Pages link after deploying)*

## 📁 Project Structure

```
racing-game/
├── index.html    ← Main HTML file (game canvas + UI screens)
├── style.css     ← Styling for HUD, start/gameover screens
├── game.js       ← All game logic (Three.js 3D scene)
└── README.md     ← This file
```

## 🛠️ Technologies Used

- **HTML5** — Structure and canvas container
- **CSS3** — UI styling and overlays
- **JavaScript (ES6)** — Game logic
- **[Three.js r128](https://threejs.org/)** — 3D rendering (loaded via CDN)

## 🏗️ How to Run Locally

Just open `index.html` in any modern web browser — no server or installation needed!

```bash
# If you have Python installed, you can also run a local server:
python -m http.server 8000
# Then open http://localhost:8000
```

## 📦 How to Deploy on GitHub Pages

1. Create a new **public** repository on GitHub
2. Upload all files (`index.html`, `style.css`, `game.js`, `README.md`)
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save** — your game will be live in ~1 minute!

---

Made with ❤️ using Three.js
