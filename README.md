# 🐍 Jim's Snake Adventure

A neon-retro Snake game where **Jim** the snake eats **Jannat**, **Shova**, and **HSTU** — with swipe/tilt controls and 8 progressive difficulty levels.

## 🎮 Features
- **JIM** written letter-by-letter across the snake's body
- 3 named foods: **JANNAT** (+10pts), **SHOVA** (+15pts), **HSTU** (+25pts)
- 8 speed levels that increase as you eat more
- Swipe gestures (mobile), gyroscope tilt, WASD/Arrow keys (desktop)
- Particle burst effects on eating
- Persistent high score (localStorage)
- Neon grid aesthetic with scanline overlay

## 🚀 Deploy to Vercel (3 steps)

### Step 1 — Push to GitHub
```bash
git init
git add .
git commit -m "Jim's Snake Adventure 🐍"
git remote add origin https://github.com/YOUR_USERNAME/jim-snake.git
git push -u origin main
```

### Step 2 — Connect to Vercel
1. Go to [vercel.com](https://vercel.com) → **New Project**
2. Import your GitHub repo
3. Framework: **Other** (it's a static HTML file)
4. Click **Deploy**

### Step 3 — Play!
Vercel gives you a live URL like `https://jim-snake.vercel.app`

## 🕹 Controls
| Control | Action |
|---|---|
| Swipe ← → ↑ ↓ | Move Jim |
| WASD / Arrow Keys | Move Jim |
| Tilt phone | Move Jim (gyroscope) |
| Tap screen | Pause / Resume |
| P key | Pause / Resume |

## 📁 File Structure
```
jim-snake/
├── index.html     ← The entire game (single file)
├── vercel.json    ← Vercel deployment config
└── README.md      ← This file
```
