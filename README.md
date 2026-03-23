# Playlist vSaaS — Concept 2: Your AI Assistant

A high-fidelity prototype for the Playlist AI Assistant experience, built as a single-file HTML prototype.

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

## Pages

- **Today** — Daily schedule with AI-filled appointments and agent activity feed
- **Calendar** — Weekly view (Mon–Sun, 6AM–9PM) with AI recommendations sidebar
- **Clients** — Client list with health scores and slide-in profile drawer
- **AI Assistant**
  - **Chat tab** — Conversational AI with shortcut cards and suggested prompts
  - **Activity tab** — Active Goals, Pending Approvals, and More Options
    - Click "Maximize My Calendar" to open a detailed settings side panel
- **Analytics, Marketing, Inventory** — Placeholder pages

## Notes

- Single `index.html` — no dependencies, no build tools needed
- Fonts loaded from Google Fonts (requires internet connection for fonts)
- Prototype only — not connected to a backend
- Compatible with GitHub Pages for instant hosting
