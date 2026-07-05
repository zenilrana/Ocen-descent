# The Descent — an ocean in depth

A single-page parallax scrolling experience that takes you from the sunlit ocean surface down to the floor of the Mariana Trench, using scroll-linked motion to actually represent depth rather than as decoration.

## Concept

Parallax only earns its place when it means something. Here, each of the six zones is based on a real ocean depth band (sunlit, twilight, midnight, abyss, trench), and elements closer to the "camera" move faster than distant ones as you scroll — the same visual cue used to judge depth in real life.

## Features

- **Six depth zones**, each with its own color palette that darkens as you descend, from bright surface cyan to near-black abyss
- **Multi-layer parallax** — background, creature, and foreground layers move at different scroll speeds within each zone
- **Live depth gauge** (fixed UI element) — a dive-computer-style readout showing meters descended and atmospheres of pressure, calculated from real ocean physics (~1 ATM per 10m) and synced to scroll position
- **Ambient motion** — rising bubbles near the surface, flickering bioluminescent particles in the dark zones, drifting fish, jellyfish, anglerfish, and a giant squid silhouette in the trench
- Fully responsive, and respects `prefers-reduced-motion`
- No frameworks, no build step — plain HTML, CSS, and vanilla JavaScript

## Ocean zones featured

| Zone | Depth | 
|---|---|
| Sunlit zone | 0–200m |
| Twilight zone | 200–1,000m |
| Midnight zone | 1,000–4,000m |
| The abyss | 4,000–6,000m |
| The trench | 6,000–11,000m |

## Tech stack

- HTML5 / CSS3 (gradients, keyframe animation, `transform`-based parallax)
- Vanilla JavaScript — scroll-linked parallax engine, procedurally scattered creatures/particles, live depth gauge
- Fonts: Fraunces, Inter, IBM Plex Mono (Google Fonts)

## Running locally

No build step required — clone and open directly in a browser:

\`\`\`bash
git clone https://github.com/zenilrana/Ocen-descent.git
cd Ocen-descent
open index.html
\`\`\`

## Live demo

*[add your GitHub Pages link here once enabled, e.g. https://zenilrana.github.io/Ocen-descent/]*
