# My Home

A customizable personal homepage with bookmarks organized in tabs, sections, and columns. All data is stored locally in your browser with optional cloud sync.

**🔗 Live Demo:** [https://verbeeckorama.github.io/hanshome/](https://verbeeckorama.github.io/hanshome/)

## Features

### 📑 Multi-Tab Organization
- Create multiple tabs for different contexts (Work, Personal, Projects, etc.)
- Rename and delete tabs
- Tabs persist across sessions

### 📁 Sections & Links
- Organize links into named sections
- Drag and drop to reorder links within sections
- Drag links between sections
- Drag sections between columns
- Add, edit, and delete links with custom names
- Section color customization (appears in title background)

### ✏️ Edit Mode
- Toggle global Edit Mode to manage content
- Rename sections inline
- Delete sections with confirmation
- Add new sections to any column

### 🎨 Appearance
- **Dark Mode** - Easy on the eyes
- **Large Icons** - Better visibility for favicons

### ☁️ Free Cloud Backup (GitHub Gist)
- Sync your data across devices using a private GitHub Gist
- Each user can have their own Gist
- Push and pull data manually
- **Auto-backup** option syncs on every change
- Requires a GitHub Personal Access Token with `gist` scope

### 💾 Free Local Backup (JSON File)
- Export all data to a JSON file
- Import from a previously exported file
- **Auto-backup** option downloads a backup on every change

## Getting Started

1. Open `index.html` in your browser
2. Set it as your browser's homepage or new tab page
3. Click **Edit** to start customizing
4. Use **Settings** (⚙️) for appearance and backup options

## Cloud Sync Setup

1. Go to [GitHub Settings > Tokens](https://github.com/settings/tokens)
2. Create a new token with the `gist` scope
3. Open Settings in My Home
4. Paste your token and click **Push to Gist**
5. Your Gist ID will be saved automatically
6. Use the same Gist ID on other devices to sync

## Data Storage

- **Homepage data**: Stored in `localStorage` under `homepageData`
- **Settings**: Stored in `localStorage` under `homepageSettings`
- **Gist credentials**: Stored in `localStorage` (`gistToken`, `gistId`)

All data stays in your browser unless you explicitly push to GitHub Gist.

## License

MIT