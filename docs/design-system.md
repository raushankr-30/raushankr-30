# Engineering Profile Visual System

This identity system is a GitHub-native editorial interface, not a portfolio template. It uses the GitHub dark palette, the platform font stack, a 12-column 1200-unit canvas, and a 4-point spacing rhythm.

## Visual tokens

| Token | Value | Use |
| --- | --- | --- |
| Background | `#0D1117` | Canvas |
| Surface | `#161B22` | Panels and capsules |
| Primary | `#58A6FF` | Structure, links, flow |
| Success | `#3FB950` | Current-state signal |
| Accent | `#D2A8FF` | Secondary system connection |
| Text | `#F0F6FC` | Primary reading layer |
| Muted | `#8B949E` | Supporting context |

## Component grammar

The system repeats a small set of primitives: panel, capsule, node, connection line, process block, and footer signature. Every visual is semantic (`title`, `desc`, labelled groups), responsive via `viewBox`, and limited to native SVG primitives. Motion is reserved for engineering flow and status; it never carries essential information.

## Maintenance

Keep assets self-contained so GitHub can render them. Preserve semantic IDs, avoid duplicate IDs within an SVG, and keep visual assets under the 750 KB aggregate budget. New content must originate from a verified repository artifact or direct owner input.
