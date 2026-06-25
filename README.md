# Advon & Torch — Consulting Website

Marketing site for Advon & Torch Inc., a veteran-owned (SDVOSB) consultancy
positioned around two practices: **Technology & Digital** and
**Government & Compliance**.

- **Theme:** "Warm Human" — warm neutrals (cream / sand / terracotta), soft
  rounded cards, Fraunces display serif + Inter body. Relationship-first tone.
- **Stack:** a single static `index.html` (no build step). Fonts and icons load
  from CDNs (Google Fonts, Tabler Icons).

## Develop

Open `index.html` in a browser — that's it. No install, no build.

## Deploy (GitHub Pages)

The site is published straight from the repository root on `main`. To turn it
on once:

1. Push this repo to GitHub (the repo must be public, or Pages on a paid plan).
2. **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`.**
3. The site goes live at `https://<user>.github.io/<repo>/`.

Every later push to `main` redeploys automatically.

## To customize

- **Photos:** the hero and about sections use warm placeholder blocks (labeled
  in the markup). Swap them for real photography when available.
- **Testimonial:** the quote section is a placeholder — replace with a real one.
- **Contact form:** currently static. Wire it to a form handler (Formspree,
  Netlify Forms, or an API) to receive submissions.
