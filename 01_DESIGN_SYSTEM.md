# 01 — Design System

## Intent

This profile amplifies GitHub rather than replacing it. The design ratio is approximately 60% native GitHub surfaces and 40% custom SVG storytelling. GitHub repository history, contribution activity, languages, pinned repositories, stars, forks, and pull requests are primary evidence; the custom layer explains their engineering context.

## Tokens

| Token | Value | Purpose |
| --- | --- | --- |
| Background | `#0D1117` | GitHub dark canvas |
| Surface | `#161B22` | Quiet SVG panels |
| Primary | `#58A6FF` | Structure and connections |
| Success | `#3FB950` | Active, verified work |
| Accent | `#D2A8FF` | Secondary system connection |
| Text | `#F0F6FC` | Primary reading layer |
| Muted | `#8B949E` | Supporting context |

Use GitHub’s native system font stack only: `-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif`.

## Layout and hierarchy

All SVGs use a 1200-unit, twelve-column canvas. Spacing follows 4, 8, 12, 16, 24, 32, 48, 64, 96, and 128. Markdown supplies the page rhythm. SVGs explain one thing at a time and never impersonate an application interface.

The content sequence is Hero → Pinned Repositories → Engineering Signals → Featured Projects → Technology Ecosystem → Architecture → Learning → Open Source → Contact → Footer. Native GitHub profile surfaces should remain visibly configured in GitHub itself.

## Components

Hero, engineering-signal panel, project card, architecture block, timeline node, technology capsule, connection line, status marker, and footer signature share the same dark canvas, one-pixel borders, modest corner radii, and restrained labels.

## Motion

SVG SMIL only. Motion is limited to connection flow, scan, pulse, reveal, or draw. It must be subtle, optional to comprehension, and never use bounce, shake, typing, confetti, floating icons, or continuous spinning.

## SVG rules

Every SVG includes a responsive `viewBox`, `title`, `desc`, logical labelled groups, unique IDs, and high-contrast text. Definitions, symbols, gradients, masks, clips, and filters are used only when they reduce repeated geometry or clarify a visual. No external fonts, raster assets, JavaScript, CSS, or canvases.
