# may 💕

A personal web app built with love for someone special.

**may** is a mobile-first PWA designed as a private safe space — a place to breathe through panic, log emotions, save memories together, and read reassuring words when the world feels too heavy. Built with vanilla HTML/CSS/JS, Supabase for real-time sync, and deployed via Netlify.

## What it does

**may (the app)** lives on May's phone as an installable PWA. It has five sections:

- **SOS** — a guided 4-4-4-4 box breathing exercise that activates when anxiety hits, with rotating reassurance messages and a petal animation that expands and contracts with each breath
- **Ricordi** — a shared memory board for photos, videos, and written moments, synced to the cloud
- **Diario** — an emotional diary where May can log her mood, anxiety level, and a short note
- **Frasi Sicure** — 14 personal messages written by Ema, meant to be read when things get hard
- **Easter egg** — type `15` or tap the nav 15 times to launch fireworks 🎆

**ema (the dashboard)** is a private partner view. It shows May's mood and anxiety in real time, fires an alert banner the moment SOS is activated, and displays a 30-day anxiety trend chart — so Ema always knows how she's doing, even from a distance.

## Stack

- Vanilla HTML · CSS · JavaScript — no framework, no build step
- [Supabase](https://supabase.com) — Postgres database + real-time subscriptions
- [Netlify](https://netlify.com) — static hosting, two separate sites
- PWA — installable on iPhone via Safari, works offline with localStorage sync queue
- Chart.js — anxiety trend graph in the partner dashboard

## Design

Soft glassmorphism aesthetic. Dominant pink palette (`#f9d0e0 → #e8799e`) with green used only as a detail accent. Custom SVG elements throughout: a hand-drawn My Melody character in the hero, rotating flower petals around the breathing orb, falling petals in the background, and animated butterflies on the phrases page.

## Setup

See [`GUIDA_SETUP.md`](./GUIDA_SETUP.md) for the full step-by-step: Supabase tables, credentials, Netlify deploy, and iPhone installation. Takes about 20 minutes, entirely free.

---

*Made with love. For May, always.* 💚
