# How I run my life with two AI agents

A short web deck from Vatsal Mishra's OpenClaw event demo.

It explains a real two-agent personal setup:

- **OpenClaw** — personal concierge for briefings, Home OS, content drafts, research, reminders, files, and local workflows.
- **Hermes** — supervising agent that watches OpenClaw, restarts or alerts on failures, and keeps small failures from becoming silent failures.

The deck is intentionally simple: one static HTML file, one LinkedIn QR image, no backend, no analytics, no build step.

## Run locally

```bash
python3 -m http.server 7003
```

Then open <http://127.0.0.1:7003>.

Keyboard controls:

- `←` / `→` or `Space` to navigate
- `F` for fullscreen
- `Home` to jump to the first slide

## Deploy

This repository is designed for GitHub Pages from the `main` branch root.
