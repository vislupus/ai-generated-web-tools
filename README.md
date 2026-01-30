# Tiny Web Tools (AI-Assisted)

A small collection of simple web apps and experiments.  
Most projects were created with the assistance of AI, primarily **Claude**, with occasional help from other models.

This repo is a personal sandbox where I quickly build ideas, test concepts, and collect small tools in one place.

---

## Live Demos (GitHub Pages)

Once GitHub Pages is enabled for this repo, the projects will be available here:

- **Main landing page:**  
  `https://vislupus.github.io/ai-generated-web-tools/`

- **JLPT N5 Kanji Drill:**  
  `https://vislupus.github.io/ai-generated-web-tools/n5-kanji-drill/`

- **Boids + Predator–Prey Simulation:**  
  `https://vislupus.github.io/ai-generated-web-tools/boids-predator-prey/`

- **LocalNotes – Notion-like Editor:**  
  `https://vislupus.github.io/ai-generated-web-tools/localnotes/`

---

## Projects

### JLPT N5 Kanji Drill

Simple kanji practice tool for N5 learners.  
Features basic search, drill/quiz-style interaction, and a minimal UI.  
**Source:** `/n5-kanji-drill/`  
**Live demo:** see link above.

---

### Boids + Predator–Prey Simulation

Interactive simulation combining classic boids flocking behavior with predator–prey dynamics:
- Flocking rules: separation, alignment, cohesion
- Predators chasing and eating boids
- Reproduction and starvation mechanics
- Real-time controls in a side panel

**Source:** `/boids-predator-prey/`  
**Live demo:** see link above.

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
**Live demo:** see link above.

---

## Structure

Each tool lives in its own folder:

```text
/
├─ index.html            # Landing page listing all tools
├─ n5-kanji-drill/       # JLPT N5 Kanji drill tool
├─ boids-predator-prey/  # Boids + predator–prey simulation
└─ localnotes/           # Notion-like editor
