# Retro Linear™ — AI Design Snack #1: Ruin Linear

> linear.app is peak modern design. Dark, minimal, obsessively refined.
> This is the worse life: same content, destroyed aesthetic — reskinned as a
> 1996 **GeoCities** page. Comic Sans, tiled starfields, rainbow `<hr>`,
> marquees, `<blink>`, a hit counter, a webring, and "Best viewed in Netscape."

**Live site:** https://kalleoksa.github.io/linear/

## What it is
A static reskin of the [Linear](https://linear.app) landing page. The copy and
section order are kept faithfully (hero, customer wall, feature sections, the
Linear Method, testimonial, CTA, footer); only the aesthetic is ruined.

- `index.html` — the page, semantic HTML under all the chaos
- `style.css` — pure CSS + emoji for every retro effect (no external assets)

## Accessibility (the bonus points)
Semantic landmarks and headings, a skip link, `focus-visible` outlines, alt
text / aria labels on decorative elements, and `prefers-reduced-motion` to
disable blink, marquee, and hue-shift animations.

## Deploy
Published to GitHub Pages via `.github/workflows/deploy-pages.yml` on every push
to `main`.

---
A loving parody. The real thing lives at https://linear.app.
