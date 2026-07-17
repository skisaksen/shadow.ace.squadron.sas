# SHADOW ACE SQUADRON [SAS]

> **SAS INTERNAL // FLEET EYES ONLY**
> *Strike from the dark. Own the night.*

The official website of **Shadow Ace Squadron [SAS]** — a DCS World squadron flying structured, story-driven naval air operations. Carrier launches into contested airspace, strike packages with real objectives, and debriefs that usually end in laughter.

**Live site:** https://skisaksen.github.io/shadow.ace.squadron.sas/

---

## What's on the site

- **Cinematic battlespace background** — animated radar sweep with friendly/hostile contacts, missile trails, range rings, and CRT scanline effects, all rendered on a single `<canvas>`
- **Squadron briefing** — who we are and how we fly
- **Order of battle** — the airframes we operate, from the F-14B to the UH-1H
- **Current tasking** — campaign nights (NAVOPORD 01-26), flight school, and weeknight sorties
- **Recruitment** — open to all skill levels, no gatekeeping

## Tech

One file. No frameworks, no build step, no dependencies.

```
index.html   ← everything: markup, styles, and the radar animation
```

Fonts (Chakra Petch, Share Tech Mono) load from Google Fonts; everything else is self-contained vanilla HTML/CSS/JS.

## Editing

| To change… | Look for… |
|---|---|
| Discord invite link | `#DISCORD_INVITE_PLACEHOLDER` in the Join section |
| Motto / tagline | `.motto` in the hero |
| Status ticker text | `.ticker` block |
| Aircraft cards | `#aircraft` section — copy any `.ac-card` |
| Ops cards | `#operations` section |
| Colors | CSS variables at the top of `<style>` (`--green`, `--cyan`, `--amber`…) |

Open `index.html` in a browser to preview locally — no server needed.

## Deploying

Hosted on **GitHub Pages** from the `main` branch. Any push to `main` redeploys the site automatically within a minute or two.

---

*Shadow Ace Squadron is a DCS World gaming community and is not affiliated with any real-world military organization.*
