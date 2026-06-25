# LinkedIn Report System — TeamRocketRush

## Overview
This repository is the master database for the LinkedIn Report automation system.
Claude reads and writes to this repo automatically. Do not edit manually.

## Files
- `clients.json` — live client database (auto-updated by Claude)
- `template.html` — master dashboard template (edit only to change design)
- `SYSTEM.md` — this file (team reference)

## How It Works
1. Rep opens Claude Project → says "Hi"
2. Claude fetches clients.json from this repo
3. Claude greets rep with live client list
4. Rep gives client name + month + uploads Excel
5. Claude builds dashboard, deploys to client repo, updates clients.json

## Client Repos
Each client has their own GitHub repo under teamrocketrush-ui.
GitHub Pages serves each repo as a live URL.

## Adding a New Client
Open the Claude Project and say "New Client".
Claude creates the repo, builds the first dashboard,
enables GitHub Pages, and updates clients.json automatically.

## Support
System built by Claude (Anthropic) for TeamRocketRush.
Last updated: 2026-06-25
