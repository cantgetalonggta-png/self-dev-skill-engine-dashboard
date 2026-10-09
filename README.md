# Self-Dev Skill Engine · Live Dashboard

Production-quality static dashboard for the autonomous skill-tree engine.

## Features
- Overview KPIs (atoms, cycles, insights, upgrades)
- Session enhancements vs base comparison
- Master + Learned skill trees
- Full encyclopedia with search
- Emergent insights
- Self Extractor (line → SkillAtom)
- Self Distiller (merge + version bump + log)
- Autonomous builder checklist
- Verification suite (critical thinking gates)
- Update log

## Run locally
```bash
python3 -m http.server 4173
# open http://localhost:4173
```

## Data
`data/state.json` is the single source of truth (55+ atoms after cycle 2).

## Deploy
Static site root = this directory. Works on Vercel/Netlify/GitHub Pages with zero build step.
