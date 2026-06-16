# Retro Linear™ — AI Design Snack #1: Ruin Linear

> linear.app is peak modern design. Dark, minimal, obsessively refined.
> This is the worse life: same content, three destroyed (or just very dated)
> aesthetics — switchable live with the button in the corner.

**Live site:** https://kalleoksa.github.io/linear/

## What it is
A static reskin of the [Linear](https://linear.app) landing page. The copy and
section order are kept faithfully (hero, customer wall, feature sections, the
Linear Method, testimonial, CTA, footer); only the aesthetic changes.

- `index.html` — the page, semantic HTML shared across every skin
- `style.css` — one CSS-custom-property token set per skin, plus a few
  structural overrides. Pure CSS + emoji, no external assets.

## Skins
Pick a skin with the corner button (it cycles, and your choice is remembered in
`localStorage`). Each is driven by a `data-theme` attribute on `<html>`:

1. **GeoCities** (`geocities`, default) — 1996 web: Comic Sans, tiled
   starfields, rainbow `<hr>`, marquees, `<blink>`, a hit counter, a webring,
   and "Best viewed in Netscape."
2. **Windows 8 / Metro** (`win8`) — flat Live Tiles, edge-to-edge color blocks,
   and a light-weight Segoe UI hierarchy.
3. **Apple 2005** (`apple`) — the Apple Store / Mac OS X Tiger era: a clean
   white canvas with faint Aqua pinstripes, Lucida Grande type, glossy blue
   "aqua" pill buttons, brushed-silver tab bars, and rounded white cards.

## Accessibility (the bonus points)
Semantic landmarks and headings, a skip link, `focus-visible` outlines, alt
text / aria labels on decorative elements, and `prefers-reduced-motion` to
disable blink, marquee, and hue-shift animations.

## Deploy
Published to GitHub Pages via `.github/workflows/deploy-pages.yml` on every push
to `main`.

---
A loving parody. The real thing lives at https://linear.app.
