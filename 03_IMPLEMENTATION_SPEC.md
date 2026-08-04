# 03 — Implementation Specification

## Repository structure

```text
README.md
01_DESIGN_SYSTEM.md
02_PROFILE_CONTEXT.md
03_IMPLEMENTATION_SPEC.md
assets/
  hero.svg
  dashboard.svg
  projects.svg
  architecture.svg
  timeline.svg
  tech.svg
  opensource.svg
  footer.svg
  patterns/components.svg
  icons/system.svg
  dividers/line.svg
.github/workflows/svg-quality.yml
```

## GitHub compatibility

Use standard Markdown and self-contained SVGs only. Do not use JavaScript, CSS, canvas, external fonts, raster media, Lottie, or third-party statistic/card services. Native GitHub profile areas—contribution graph, pinned repositories, activity, follower count, repository metadata, languages, stars, forks, and pull requests—are configured and rendered by GitHub, not duplicated as simulated README data.

## Asset order

Build and review in this order: Hero, engineering signals, projects, architecture, timeline, technology ecosystem, open source, footer, README assembly. Freeze each asset after visual, semantic, and size review.

## Performance and semantics

The combined SVG budget is under 750 KB. Every asset must parse as XML, contain `title`, `desc`, and `viewBox`, expose unique IDs, and have no dead definitions or repeated geometry where a symbol is appropriate. Keep the automated SVG quality workflow current with the asset directory.

## Review checklist

- GitHub remains the main character; the README does not read as a landing page.
- Native GitHub signals appear immediately after the hero and remain prominent on the profile.
- All claims can be verified in a local project or GitHub repository.
- Custom SVGs clarify a system rather than decorate the page.
- Markdown scrolls naturally with breathing room.
- Motion is subtle and non-essential.
- The asset budget, XML structure, accessibility metadata, and reference paths pass validation.
