# VOID STRIKE

**Deep Space Combat Squadron** — a 3D space shooter that runs entirely in your browser. No install, no downloads.

## Play

Open `index.html` (or the live GitHub Pages site) and press **Start**.

## Controls

| Input | Action |
|-------|--------|
| `W` `A` `S` `D` / Arrow keys | Move |
| Mouse | Aim |
| Left mouse button | Fire |
| `Space` | Boost up |
| `Shift` | Dive down |
| `Esc` | Release the mouse (click to resume) |

## Gameplay

- Survive wave after wave of enemies and rack up score and combos.
- Spend points between waves on ship upgrades.
- Keep an eye on your health, shields, and the radar.

## Tech

- [Three.js](https://threejs.org/) (r128, loaded from cdnjs)
- Plain HTML, CSS, and JavaScript — no build step
- Font: [Orbitron](https://fonts.google.com/specimen/Orbitron) (Google Fonts)

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page markup and game code |
| `style.css` | All styling (title screen, HUD, menus) |
| `index.md` | This documentation |

## Deploy to GitHub Pages

1. Create a new repository and upload these three files to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`.
