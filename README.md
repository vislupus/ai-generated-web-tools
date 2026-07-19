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

### N-Body Gravitational Simulation (WebGPU)

GPU n-body gravity simulation:

- WebGPU compute shader (tiled shared memory)
- WebGL2 fallback path
- Multiple scenarios + real-time controls
- Additive glow rendering

**Source:** `/nbody-simulation/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/nbody-simulation/

---

### VOID COMMAND – 2D RTS Space Battle Simulator

Fleet-scale RTS space battle sandbox:

- Configure fighters, tanks, repair and capital ships for each side  
- Formation, targeting and behavior modes (advance, hold, harass, etc.)  
- Batch simulations and simple “training” runs for testing setups  
- Replay bar, minimap and detailed live stats  

**Source:** `/void-command/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/void-command/.

---

### WebGPU Fireworks

High-density WebGPU fireworks show:

- Multiple firework types mapped to number keys (1–0)  
- Auto show with per-type rate sliders  
- Color controls (hue, saturation, intensity)  
- Scene sliders for buildings, density and detail  

**Source:** `/fireworks/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/fireworks/.

---

### Black Hole – Gravitational Lensing

WebGPU black hole visualizer with gravitational lensing:

- Schwarzschild-inspired ray marching around a black hole  
- Adjustable Schwarzschild radius, lensing strength and ray steps  
- Accretion disk with Doppler brightening and falloff  
- Procedural starfield + nebula and cinematic camera mode  

**Source:** `/blackhole/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/blackhole/

---

---

### Abyss Runner

Retro CRT-style underwater shooter with torpedoes, enemy submarines, mines, checkpoints, air, lives and score tracking.

- Arcade action
- Submarine combat
- CRT visuals
- Procedural audio

**Source:** `/abyss-runner/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/abyss-runner/

---

### Abyss Runner — Neural Evolution Lab

A population of autonomous submarines learns to survive the Abyss Runner world through neural networks, selection, crossover and mutation.

- Genetic algorithm
- Neural agents
- Fitness tracking
- Autonomous subs

**Source:** `/abyss-runner-ai/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/abyss-runner-ai/

---

### Murmuration — WebGPU Boids

High-density 3D flocking simulation with up to hundreds of thousands of boids, obstacle avoidance and live behavior controls.

- Massive flocking
- WebGPU compute
- Orbit camera
- Live parameters

**Source:** `/boids-webgpu/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/boids-webgpu/

---

### Bomberman — ROM-Derived Remake

Browser remake and technical study featuring decoded cartridge graphics, live game state, extracted tilesheets and documented 6502 routines.

- Classic gameplay
- Decoded CHR tiles
- 6502 analysis
- Keyboard controls

**Source:** `/bomberman-rom-remake/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/bomberman-rom-remake/

---

### The Math Beauty Gallery

Interactive gallery of roughly 50 chaotic systems, strange attractors, fractals and mathematical visualizations with adjustable parameters.

- Strange attractors
- Live equations
- Curated presets
- PNG export

**Source:** `/chaos-gallery/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/chaos-gallery/

---

### Civilization Simulation

Agent-based civilization sandbox with tribes, settlements, trade, technology, conflict, disease, disasters and evolving traits.

- Agent population
- Settlements
- Trade & conflict
- Dynamic disasters

**Source:** `/civilization-sim/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/civilization-sim/

---

### Computational Imaging Lab

Interactive imaging workstation for HDR fusion, deconvolution, multi-frame night processing, frequency analysis and shader-based experiments.

- HDR fusion
- Deconvolution
- Night stacking
- Frequency analysis

**Source:** `/computational-imaging-lab/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/computational-imaging-lab/

---

### Crystal Druse Generator

Procedural crystal specimen generator with mineral species, host shapes, growth controls, inclusions, optics and material settings.

- Crystal growth
- Host surfaces
- Optical controls
- Procedural parameters

**Source:** `/crystal-druse-generator/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/crystal-druse-generator/

---

### Crystal Wars — Evolution

WebGPU battle lab where two tactical lineages evolve unit mixes, bomber behavior and watchtower placement across generations.

- Co-evolution
- GPU battles
- Tactical genomes
- Fitness history

**Source:** `/crystal-wars-v3/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/crystal-wars-v3/

---

### Digital Holography Console

Digital holography console for recording and reconstructing coherent scenes with wavelength, depth, sensor and reference-angle controls.

- Wave propagation
- Depth control
- Sensor model
- Reconstruction views

**Source:** `/holography/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/holography/

---

### Japan Seismic Simulation

Interactive Japan earthquake model with configurable magnitude, depth and attenuation, MMI intensity mapping and city seismograms.

- Seismic model
- Japan map
- City seismograms
- MMI intensity

**Source:** `/japan-earthquake/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/japan-earthquake/

---

### LiDAR Sensor Simulation

Configurable 2D and 3D LiDAR simulator with scan frequency, angular resolution, noise, dropout, presets and moving objects.

- Ray scanning
- Point clouds
- Scene presets
- Sensor controls

**Source:** `/lidar-sensor-simulation/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/lidar-sensor-simulation/

---

### LiDAR · SLAM Simulation

3D LiDAR SLAM visualization with ground-truth and estimated poses, drift, ICP registration, point clouds and reconstructed mapping.

- SLAM pipeline
- VLP-16 emulation
- Map reconstruction
- Pose drift

**Source:** `/lidar-slam/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/lidar-slam/

---

### Mountain Routes

Map-based mountain route planner with GPX tools, smoothing, simplification, map matching and multi-track centerline merging.

- Trail planning
- Interactive map
- GPX workflow
- Route merging

**Source:** `/mountain-routes/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/mountain-routes/

---

### FIELD/100K — WebGPU Particle Lab

Interactive WebGPU particle field with gravity, repulsion, cursor forces, damping and selectable particle counts.

- 100K+ particles
- WebGPU compute
- Cursor forces
- Physics controls

**Source:** `/particles-webgpu/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/particles-webgpu/

---

### Klondike Solitaire

Self-contained browser version of Klondike Solitaire with move counting, timer, new-game controls and win detection.

- Klondike rules
- Drag-and-drop play
- Timer & moves
- Win detection

**Source:** `/solitaire/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/solitaire/

---

### Procedural Tower Defense

Tower defense game with generated paths, multiple tower types, upgrades, mines, a nuke ability, speed controls and 20 waves.

- Tower building
- 20 waves
- Upgrades
- Active abilities

**Source:** `/tower-defense-procedural/`  
**Live demo:** https://vislupus.github.io/ai-generated-web-tools/tower-defense-procedural/

---

## Structure

Each tool lives in its own folder and opens through that folder’s `index.html`:

```text
/
├─ index.html            # Landing page listing all tools
├─ README.md             # Project overview
├─ abyss-runner/             # Standalone project (index.html)
├─ abyss-runner-ai/          # Standalone project (index.html)
├─ blackhole/                # Standalone project (index.html)
├─ boids-predator-prey/      # Standalone project (index.html)
├─ boids-webgpu/             # Standalone project (index.html)
├─ bomberman-rom-remake/     # Standalone project (index.html)
├─ chaos-gallery/            # Standalone project (index.html)
├─ civilization-sim/         # Standalone project (index.html)
├─ computational-imaging-lab/ # Standalone project (index.html)
├─ crystal-druse-generator/  # Standalone project (index.html)
├─ crystal-wars-v3/          # Standalone project (index.html)
├─ drone-light-show/         # Standalone project (index.html)
├─ fireworks/                # Standalone project (index.html)
├─ holography/               # Standalone project (index.html)
├─ japan-earthquake/         # Standalone project (index.html)
├─ jp-text-highlighter/      # Standalone project (index.html)
├─ lidar-sensor-simulation/  # Standalone project (index.html)
├─ lidar-slam/               # Standalone project (index.html)
├─ localnotes/               # Standalone project (index.html)
├─ lunar_miner/              # Standalone project (index.html)
├─ micro-rts/                # Standalone project (index.html)
├─ mountain-routes/          # Standalone project (index.html)
├─ n5-kanji-drill/           # Standalone project (index.html)
├─ nbody-simulation/         # Standalone project (index.html)
├─ particles-webgpu/         # Standalone project (index.html)
├─ sheetclone/               # Standalone project (index.html)
├─ solitaire/                # Standalone project (index.html)
├─ tower-defense-procedural/ # Standalone project (index.html)
└─ void-command/             # Standalone project (index.html)
```
