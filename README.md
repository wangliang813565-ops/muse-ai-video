# MUSE · AI Video Studio — Capabilities & Product Catalog

A single-page **chromatic-rgb** microsite presenting MUSE's AI video production
capabilities and sellable product catalog. Bilingual (中文 / English), fully static.

**Live:** https://wangliang813565-ops.github.io/muse-ai-video/

## Sections
- **6 capability channels** — Commercial TVC · Repaint & Space · Cinematography & FPV · AI+Live Hybrid · Digital Humans & Drama · Audio & Rights
- **Signal Showcase** — 12 embedded demo reels (click to play, lazy-loaded 720p)
- **Product catalog** — 10 scenario packages (project-based pricing on request)
- **The MUSE Method**, delivery flow, why MUSE, full 49-reel index, contact

## Tech
Pure static HTML/CSS/JS — no build step. Fonts: Space Grotesk / JetBrains Mono / Inter (Google Fonts).
Videos are web-optimized 720p H.264 with `+faststart`, `preload="none"` click-to-play.

## Structure
```
index.html            generated page
assets/video/*.mp4     12 web-optimized demo reels (720p)
assets/poster/*.jpg    poster frames
assets/img/            logo + hero
```

---
MUSE INFORMATION SERVICES L.L.C-FZ · Dubai, UAE · leon@aimuse.ae · www.aimuse.ae
