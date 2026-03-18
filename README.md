# Playlist vSaaS — Prototype

A fully self-contained interactive prototype. No build step, no dependencies to install.

## Running locally

Just open the file in any modern browser:

```
open concept-v2.html       # macOS
start concept-v2.html      # Windows
xdg-open concept-v2.html   # Linux
```

Or drag `concept-v2.html` into a browser window.

> **Note:** The file loads fonts from Google Fonts (cdn). If you're offline, system fonts will be used as fallback — the prototype still works fully.

## What's inside

| Destination | How to reach it |
|---|---|
| **Home hub** | Click the Playlist logo (top-left sidebar) |
| **Direction 1 — Unified Intelligence** | Home hub → Concept 2 card |
| **Concept 1 — Your AI Team** | Home hub → Concept 1 card |
| **Onboarding** | Home hub → Concept 3 card |
| **Workflow & Pain Analysis** | Home hub → Reference card |
| **Direction 2** | Home hub → Direction 2 (placeholder) |

## Navigation

- All sidebar nav items work within each concept
- Arrow keys `←` `→` advance/rewind the Onboarding chat flow
- Chat FABs are interactive with scripted demo responses
- Client drawer opens by clicking any client name
- Decision cards (cancel/approve) are interactive
- Toggles on the Your AI and Agents pages are interactive

## File structure

Single file: `concept-v2.html`  
Size: ~267 KB  
All assets (logos, icons) are embedded as base64 — no external files needed.
