# Rust Raid Calculator

Plan your raids. Count your sulfur.

A tool for calculating the exact resources needed to raid structures in Rust. Built with React + Vite.

## Features

- **Structure calculator** — Select doors, walls, floors, external walls, and deployables with quantities
- **Quick calc** — Directly enter explosive counts (C4, rockets, satchels, explo ammo)
- **Method comparison** — See costs for all 4 explosive types side-by-side, with cheapest highlighted
- **Crafting flow** — Satisfactory-style SVG node graph showing the full resource chain from raw ore to final explosives
- **Complete ingredient breakdown** — Every resource including sulfur, charcoal, metal, low grade fuel, cloth, tech trash, pipes, rope
- **Farming estimates** — Sulfur nodes and wood needed

## Data

All crafting data is based on vanilla Rust (April 2026). Gunpowder recipe: 30 charcoal + 20 sulfur → 10 GP. Explo ammo counts assume AK/LR-300.

## Development

```bash
npm install
npm run dev
```

## Deploy

Push to GitHub, connect to Vercel. Done.
