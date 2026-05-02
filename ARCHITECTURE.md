# Architecture

The README is the manifesto. This is the map.

## Folder Layout

```
lightsaber/
├── README.md        manifesto
├── ARCHITECTURE.md  this file
└── experiments/     half-forged ideas, prototypes, things that glow but don't yet cut
```

That's it for now. The repo grows when something earns a place in it, not before.

## Conventions

- **Conventional folder names for structure.** `experiments/`, `configs/`, `scripts/`, etc. as they emerge.
- **Metaphor names for specific tools, projects, and experiments** when they genuinely fit. A standalone tool can be `kyber-crystal/` if it deserves the name. A folder full of shell configs is just `configs/`.
- **Folders are created when they have content.** No empty scaffolding pretending to be a roadmap.

## What Goes Where

| Folder | Belongs |
|--------|---------|
| `experiments/` | Prototypes, half-baked notions, design candidates, anything I'm trying out |
| `configs/` | (when it exists) Shell, editor, dotfiles, system configs |
| `scripts/` | (when it exists) Workflows, automations, utility scripts |
| `ai/` | (when it exists) Agent profiles, prompts, AI integration patterns |
| `standards/` | (when it exists) Linting configs, commit conventions, ADRs |

The personal infrastructure (style profiles, custom agents, rule-books) lives in `~/.copilot/`, not here. This repo is for things worth sharing.
