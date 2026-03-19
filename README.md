# Playlist vSaaS — Concept 2: Your AI Assistant

A prototype for the Playlist AI Assistant experience, built as a single-file HTML prototype.

## Getting Started

### Option 1: Open directly
Just open `index.html` in any browser — no build step required.

### Option 2: Serve locally
```bash
# Using Python
python3 -m http.server 8080

# Using Node
npx serve .

# Using VS Code
Install the "Live Server" extension and click "Go Live"
```

Then visit `http://localhost:8080` in your browser.

## What's inside

- **Today** — Daily schedule view with AI-filled appointments
- **Calendar** — Weekly calendar (Mon–Sun, 6AM–9PM) with AI recommendations sidebar
- **Clients** — Client list with health scores and drawer profiles
- **AI Assistant** — Chat tab with shortcut cards + Activity tab with goals and pending approvals
  - Clicking "Maximize My Calendar" opens a slide-in settings panel
- **Analytics, Marketing, Inventory** — Placeholder pages

## Notes

- Single `index.html` file — no dependencies, no build tools
- All fonts loaded from Google Fonts (requires internet connection)
- Prototype only — not connected to a backend
