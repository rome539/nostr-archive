# nostr-archive

**Current Version: v2.4** • Open Source • No Tracking

A powerful browser-based app to view, search, filter, and archive your Nostr notes. Built as a single-page HTML app — no backend, no servers, runs entirely in your browser with all data stored locally.

## Features

### Core Functionality
- **Connect with your npub** (public key)
- **Load notes from popular relays** automatically
- **Advanced search & filtering system** with smart query parsing
- **Quick filters**: This Week, This Month, 6 Months, This Year, Images, Videos, Long notes
- **Smart archive-aware filtering**: filters work within archives
- **Engagement stats**: View reactions, zaps, reposts, and quotes for each note
- **Thread view**: See full conversation threads

### Music Player (New in v2.4)
- **Embedded music players** for shared songs
- **Works with all major platforms**:
  - Spotify (tracks, albums, playlists)
  - Apple Music
  - YouTube Music
  - song.link (shows all platforms)
- **Click to play** - players load right inside note cards
- **No new tabs** - everything stays in the app

### Advanced Search Engine
- **Smart keyword search** with natural language processing
- **Boolean operators**: AND, OR, NOT
- **Phrase matching** with quotes: `"exact phrase"`
- **Exclude terms** with minus: `-unwanted`
- **Hashtag search**: `#bitcoin`
- **Media filters**: `has:image`, `has:video`, `has:link`, `has:music`
- **Date range filtering**: Custom date pickers + quick filters
- **Sort by engagement**: Most liked, most zapped, most reposted, most quoted

### Archive System
- **Create unlimited named archives** to organize your notes
- **Bulk add/remove** notes with selection tools
- **Import/export archives** (JSON and CSV formats)
- **Archive context preservation** - filters stay active when viewing archives
- **Quick archive switching** between different collections

### Engagement & Stats
- **Real-time engagement tracking**:
  - Reactions (likes)
  - Zaps (with total sats)
  - Reposts
  - Quote posts
- **Sort by engagement** to find your top-performing notes
- **Visual engagement indicators** on each note

### Storage Management
- **Local browser storage** with IndexedDB
- **Chunked storage system** for handling large archives
- **Storage optimization** tools
- **Usage reports** to monitor space

### Interface & Themes
- **Five beautiful themes**:
  - Default Blue
  - Nostr Purple
  - Dark Nostr
  - Bitcoin Gold
  - Neon Green
- **Lazy-loading media**: Images and videos load on demand
- **YouTube thumbnails** with click-to-play
- **Embedded music players** (new!)
- **Responsive design** works on mobile and desktop

### Keyboard Shortcuts
- `/` or `Ctrl+K` → Focus search
- `Esc` → Clear search/selections/filters
- `A` → Select all visible notes
- `Del` → Remove selected notes

## How to Use

1. **Open the app** (or double-click `index.html`)
2. **Paste your npub** in the input box
3. **Wait for notes to load** from relays (this may take a minute)
4. **Start exploring**:
   - Use the search bar for advanced queries
   - Click quick filters for common views
   - Create archives to organize notes
   - Sort by engagement to see top posts
   - Switch themes to match your style

## Try These Features

- **Search with operators**: `bitcoin AND lightning` or `"exact phrase" -spam`
- **Filter by media**: Use `has:image` to find all notes with images
- **Filter by music**: Use the Music filter to find all shared songs
- **Create themed archives**: Make collections like "Tech Posts" or "Personal Notes"
- **Sort by zaps**: See which of your notes got zapped the most
- **Play shared music**: Click any song link to load the player
- **View threads**: Click thread view to see full conversations
- **Export your data**: Download archives as JSON or Markdown

## Recent Updates

- Embedded music players for Spotify, Apple Music, YouTube Music, and song.link
- Players load directly in note cards
- No more opening new tabs for music
- New "Music" filter to find all notes with music links

- Enhanced engagement tracking system
- Sort by reactions, zaps, reposts, and quotes
- Real-time engagement stats with popup details
- Improved performance for large archives

- Advanced search engine with boolean operators
- Smart filtering with natural language queries
- Media type filters (has:image, has:video, has:link)
- Phrase matching and exclusion operators

- Thread view for conversations
- Storage management and optimization tools
- Improved archive import/export
- Performance optimizations

## Technical Details

- **Single HTML file** - no build process needed
- **No backend or servers** - everything runs in your browser
- **IndexedDB storage** - data persists locally
- **Nostr protocol** - connects directly to relays
- **Privacy-focused** - no tracking, no analytics

## Known Limitations

- Relays are hardcoded; custom relay configuration coming soon
- Import currently supports JSON

## Feedback & Support

Found a bug or have a suggestion? 

- **Report on GitHub**: [github.com/rome539/nostr-archive](https://github.com/rome539/nostr-archive)
- **Share on Nostr**: Tag me with feedback
- **Include details**: What you were doing when the issue occurred

---

**Built with ❤️ for the Nostr community**
