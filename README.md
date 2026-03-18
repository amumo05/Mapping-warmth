# Mapping Warmth: Senior Social Life in Marpole

> A qualitative spatial research website presenting an emotional geography study of senior social activity in the Marpole neighbourhood of Vancouver, BC.

---

## Overview

This project digitizes and visualizes a hand-drawn neighbourhood map created during a qualitative field study. Researchers used color-coded dots, sticky notes, and photographs to document where seniors gather, which spaces feel welcoming, and how emotional geography shapes urban belonging.

---

## Features

- 🗺️ **Interactive SVG map** with toggleable data layers (places, senior gathering spots, warm spaces, cold spaces)
- 💬 **Hover tooltips** revealing field observations for each mapped location
- ✨ **Scroll-triggered animations** throughout all sections
- 🖼️ **Embedded hero illustration** — no external image dependencies
- 📄 **Fully self-contained single HTML file** (no build step, no framework)

---

## Data & Methods

The underlying data comes from a behaviour mapping study using four coding categories:

| Color | Meaning |
|-------|---------|
| 🟠 Orange | Notable places and spatial anchors |
| 🟡 Yellow | Senior social gathering spots |
| 🩷 Pink | Warm / welcoming spaces |
| 🔵 Blue | Cold / unwelcoming spaces |

**Qualitative methods applied:** spatial analysis, thematic coding, behaviour mapping, and emotional geography.

---

## Structure

The site is a single scrollable page with seven sections:

1. **Landing / Overview** — thesis and study introduction
2. **Methodology** — coding scheme and research methods
3. **Interactive Map** — digitized neighbourhood grid with layered data
4. **Key Findings** — five spatial and emotional insights
5. **Activities & Behaviors** — what seniors actually do in these spaces
6. **Reflection & Implications** — urban design and policy takeaways
7. **Footer** — study metadata

---

## Usage

No installation or build step required. Just open the file:

```bash
open marpole-warmth.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/marpole-warmth.html`

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- SVG for the interactive map
- Google Fonts (Playfair Display, Source Serif 4, DM Mono)
- No frameworks, no dependencies, no build tools

---

## Design

Warm editorial aesthetic — parchment palette, serif typography, and a Studio Ghibli-style illustration as the hero background. Designed to feel human and approachable rather than technical, with accessibility and readability as primary constraints.

---

## Context

This project was created as part of a student urban planning / community geography study. It is intended as a research communication tool — translating qualitative fieldwork into an accessible, narrative-driven web format.
