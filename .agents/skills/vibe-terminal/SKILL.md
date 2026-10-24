---
name: vibe-terminal
description: Applies the Terminal visual style (colors, fonts, spacing, layout, motion) to the portfolio site. Use ONLY when the student names the vibe-terminal skill or asks for the Terminal vibe. Never changes the content.
---

# Vibe: Terminal

Status: PLACEHOLDER (delete this line when filled in)

<!--
How to fill this in (delete this comment block when done):
- Keep the name field as vibe-terminal; it must match the folder name.
- Keep every heading below, in this order. The Vibe Studio and the gallery rely on it.
- Design tokens: keep the variable names exactly, change only the values. The site's styles.css copies this block to the top of the file.
- Layout must be one of: single column, grid, editorial, tiles.
- Motion must be one of: none, subtle, lively (then describe it in one line). Whatever the level: animate only transform and opacity, 150 to 300ms, never `transition: all`, nothing moves on page load without a reason, at most two scroll reveals, and everything stops under prefers-reduced-motion.
- Do / Don't: make them specific to this vibe ("no gradients", "sharp corners only"), not general advice. Text contrast must stay at least 4.5:1.
- Do not edit the "Content rule" section.
-->

## Feel
<1 to 2 sentences: the mood and who it suits.> Draft: Hacker, green on black. Signature move: Typed-out whoami intro.

## Design tokens
```css
:root {
  /* Colors (mode: light or dark) */
  --color-bg: #ffffff;
  --color-text: #111111;
  --color-muted: #666666;
  --color-accent: #3366ff;
  --color-border: #e5e5e5;

  /* Fonts */
  --font-heading: "Font Name", sans-serif; /* draft: JetBrains Mono */
  --font-body: "Font Name", sans-serif; /* draft: JetBrains Mono */

  /* Shape and spacing (density: compact, normal or roomy) */
  --radius: 8px;
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 16px;
  --space-4: 32px;
  --space-5: 64px;
  --max-width: 960px;
}
```
Google Fonts link: `<link href="https://fonts.googleapis.com/css2?family=...&display=swap" rel="stylesheet">`

## Layout rules
Layout: <single column | grid | editorial | tiles>
- Hero:
- About:
- Projects:
- Contact:

## Components
- Hero:
- Project card:
- Skill tags:
- Contact block:

## Motion
Motion: <none | subtle | lively>. <one line on what moves, if anything>. Respect `prefers-reduced-motion`.

## Do / Don't
Do:
1.
2.
3.
4.
5.

Don't:
1.
2.
3.
4.
5.

## Content rule
All text and projects come from SPEC.md. Never invent content.
