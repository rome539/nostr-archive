# nostr-archive

**Build v1.0 — September 2025**

A browser-based app to view, search, filter, and archive your Nostr notes. Built as a single-page HTML app — no backend, runs entirely in your browser.

## Features

**Core Functionality**
• Connect with your npub (public key)
• Load your notes from popular relays
• Search with filters (by date, hashtags, media type)
• Quick filters: This Week, This Month, 6 Months, This Year, Images, Videos, Long notes
• Smart archive-aware filtering: hashtags filter within archives

**Archive System**
• Create multiple named archives
• Bulk add/remove notes
• Import/export archives (JSON, Markdown)
• Archive context preservation during filtering

**Interface & Themes**
• Multiple themes: Default Blue, Nostr Purple, Dark Nostr, Bitcoin Gold, Neon Green
• Media support: images and YouTube thumbnails
• Keyboard shortcuts:
  - `/` or `Ctrl+K` → focus search
  - `Esc` → clear search/selections/filters
  - `A` → select all visible
  - `Del` → remove selected

**Recent Updates (v1.0)**
• Fixed archive hashtag filtering - hashtags now filter within archives instead of exiting
• Added 6 Months quick filter
• Made date filters mutually exclusive (only one active at a time)
• Improved archive navigation and context preservation

## How to Use

1. Open the app (or double-click the `index.html` file)
2. Paste your npub in the input box
3. Wait for notes to load from relays
4. Use filters, archives, and themes to organize your notes
5. Export archives for backup, or import them later

## Try These Features

• Create an archive and filter hashtags within it
• Use the new 6 Months filter to see recent activity
• Combine quick filters (like "Images + This Month")
• Switch themes and test archive functionality
• Export/import archives to save your organization

## Known Limitations

• Relays are hardcoded; custom relay lists not yet supported
• Import currently supports JSON exports from this app only
• Some UI elements still use inline styles

## Feedback

Report bugs or suggestions on Nostr or GitHub. Include what you were doing when the issue occurred.
