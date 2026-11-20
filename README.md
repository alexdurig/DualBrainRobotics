# Dual Brain Robotics

Website for **Dual Brain Robotics** — a bilateral cognitive architecture for
advanced robotics, developed by Dr. Alexander Durig.

The project explores a new approach to artificial intelligence and robotics
inspired by the cooperative structure of the human brain. A U.S. Utility
Provisional Patent Application has been filed for the Dual Brain Robotics
Architecture (USPTO Application No. 64/181,346).

Live site: <https://dualbrainrobotics.com>

## Technology

- [Astro](https://astro.build) 7 (static site generator)
- Plain HTML / CSS with a small amount of JavaScript
- Node.js >= 22.22

## Project structure

```
/
├── public/                     Static assets (favicon, images, files)
├── src/
│   ├── assets/                 Background and brand artwork
│   ├── components/             Header, Footer, Welcome
│   ├── layouts/                MainLayout, Layout
│   ├── pages/                  One .astro file per route
│   │   ├── index.astro         Home
│   │   ├── about.astro         About / founder
│   │   ├── architecture.astro  The architecture explained
│   │   ├── closer-to-consciousness.astro
│   │   ├── research-foundation.astro
│   │   ├── patent.astro        Patent status
│   │   └── contact.astro       Contact & licensing inquiries
│   └── styles/global.css       Global styles
├── astro.config.mjs
├── package.json
└── AGENTS.md                   Developer notes for coding agents
```

## Commands

Run from the project root:

| Command | Action |
| :-- | :-- |
| `npm install` | Install dependencies |
| `npm run dev` | Start the local dev server at `localhost:4321` |
| `npm run build` | Build the production site into `./dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro ...` | Run Astro CLI commands (`astro add`, `astro check`) |

## Deployment

Pushing to the `main` branch of `alexdurig/DualBrainRobotics` triggers an
automatic deploy of the live site. Build output lives in `dist/`.

## Contact & licensing

Dual Brain Robotics welcomes inquiries about research, collaboration,
licensing, investment, media coverage, and partnerships.

- Email: alex.durig@gmail.com
