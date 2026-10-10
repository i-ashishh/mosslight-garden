# Mosslight Garden 🌿

A cozy, top-down pixel-art backyard you can explore in your browser. The scene is drawn with HTML Canvas and runs as a self-contained page, with no build step or external JavaScript libraries.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, or Safari).
3. Use the keyboard or on-screen controls to explore.

No installation or local server is required for the current prototype.

## Controls

| Input | Action |
| --- | --- |
| `W A S D` or arrow keys | Move; steer when driving |
| `E` | Interact, enter/exit a truck, or sit/stand near the picnic table |
| `Space` | Wave |
| Click/tap the garden | Walk toward a destination |
| On-screen arrows | Touch-friendly movement |

## What's inside

- A small house, garden gate, fruit grove, vegetable beds, flowers, bicycle, and dustbin
- A circular picnic area with food and drinks
- Three mini trucks with basic driving controls
- A customizable player name and outfit colour
- Local wandering characters and browser-based interactions

## Current limitations

This is a local single-player prototype. The garden visitors are simulated sprites, not other people connected online. Live multiplayer needs a shared server and network synchronization. The current project has no user accounts, database, or hosted game backend.

## Publish with GitHub Pages

1. Create a new GitHub repository named `mosslight-garden`.
2. Add `index.html` and `README.md` to the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. After GitHub finishes deploying, the Pages address will appear in the same section.

### Push with Git on Windows

Open PowerShell or Terminal in this folder after creating an empty repository on GitHub, then run:

```powershell
git init
git add index.html README.md .gitignore
git commit -m "Build Mosslight Garden pixel world"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/mosslight-garden.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If Git asks you to identify yourself, configure your Git name and email with `git config --global user.name` and `git config --global user.email`.

## Making it your own

The HTML contains the page markup, styling, canvas drawing, movement logic, and interactions. Start with small, understandable changes: rename the world, adjust the palette, add a new flower or garden prop, then test in the browser and commit the change. Be ready to explain which parts you built or modified if you present the project as portfolio work.

This prototype was created with AI assistance from the project owner's design brief. Update this section as your own implementation, testing, and design work grows. No external image or code libraries are required by the current page.
