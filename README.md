# Tiny Web Tools (AI-Assisted)

A small collection of simple web apps and experiments.  
Most projects were created with the assistance of AI, primarily **Claude**, with occasional help from other models.

This repo is a personal sandbox where I quickly build ideas, test concepts, and collect small tools in one place.

---

## Projects

### JLPT N5 Kanji Drill

Kanji practice tool for N5 learners.  

- Beginner-friendly JLPT N5 kanji practice
- Instant search and filter by kanji or reading
- Designed for short daily drill sessions
- Works entirely in the browser, no backend
- Good for revising before mock tests or real JLPT
- Helps connect kanji shapes with readings and meaning

**Source:** `/n5-kanji-drill/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/n5-kanji-drill/.

---

### Boids + Predator–Prey Simulation

Interactive simulation combining classic boids flocking behavior with predator–prey dynamics:

- Flocking rules: separation, alignment, cohesion
- Predators chasing and eating boids
- Reproduction and starvation mechanics
- Real-time controls in a side panel

**Source:** `/boids-predator-prey/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/boids-predator-prey/.

---

### LocalNotes – Notion-like Editor

A lightweight local note-taking app inspired by Notion, featuring:

- Block-based editing (paragraphs, headings, lists, todos, quotes, code, etc.)
- Slash commands (`/`) to change block type
- Multiple choice question blocks
- Math equations via KaTeX
- Light/dark theme toggle
- LocalStorage persistence

**Source:** `/localnotes/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/localnotes/.

---

### JP Text Highlighter – Furigana & Romaji

A Japanese text study helper that lets you:

- Toggle between kanji + furigana view and pure romaji view  
- Highlight parts of the text in different colors (1–0 as shortcuts)  
- Save and load your highlight sets as JSON  

**Source:** `/jp-text-highlighter/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/jp-text-highlighter/

---

### SheetClone – Mini Spreadsheet

A small spreadsheet-like web app with:

- Multiple sheets, resizing rows/columns, context menus  
- Formatting (bold, italic, colors, borders, alignment)  
- Formulas (`=SUM(A1:A5)` etc.)  
- Clipboard support (cut/copy/paste)  
- Chart creation (bar, line, scatter) using selected ranges  

**Source:** `/sheetclone/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/sheetclone/

---

### Lunar Miner

A p5.js arcade-style lunar mining experiment:

- Randomly generated lunar terrain and tunnels  
- Keyboard-based movement (arrows, jump, dig)  
- Crystal collection and collapsing tiles  
- Score based on survival time and resources collected  

**Source:** `/lunar_miner/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/lunar_miner/

---

### Drone Light Show

A Babylon.js 3D drone light show:

- Adjustable number of drones  
- Formation animations (sequences, timing, transitions)  
- Playback controls (play, pause, next formation)  
- Smooth cinematic camera movement  
- Neon HUD-style UI  

**Source:** `/drone-light-show/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/drone-light-show/

---

### MicroRTS game – Age of Empires Inspired

A tiny RTS prototype made in pure HTML/JS:

- Villagers, resource gathering and drop-off
- Buildings, unit training queues, population cap (houses)
- Minimap, pause + game speed controls
- Runs fully in the browser, no backend

**Source:** `/micro-rts/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/micro-rts/

---

## Structure

Each tool lives in its own folder:

```text
/
├─ index.html            # Landing page listing all tools
├─ n5-kanji-drill/       # JLPT N5 Kanji drill tool
├─ boids-predator-prey/  # Boids + predator–prey simulation
├─ localnotes/           # Notion-like editor
├─ jp-text-highlighter/  # Japanese text highlighter with furigana/romaji
├─ sheetclone/           # Spreadsheet-like app
├─ lunar_miner/          # Lunar Miner
├─ micro-rts/            # MicroRTS game
└─ drone-light-show/     # Drone Light Show
