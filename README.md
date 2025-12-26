# Universal Search - Premium Meta Search Engine

A beautiful, minimalistic, premium single-page search engine that aggregates results from multiple sources. Built with a focus on user retention, privacy, and a premium user experience.

## ✨ Premium Features

### 🔍 **Smart Search**
- **Instant Autocomplete**: Local autocomplete from recent searches, saved topics, and smart suggestions
- **Search Operators**: Quick actions with `!a` (Amazon), `!g` (Google), `!ddg` (DuckDuckGo), `?` (AI/Perplexity)
- **Query Rewriting**: One-click options to make queries shorter, more specific, or shopping-focused
- **Keyboard Shortcuts**: `Cmd/Ctrl+K` to focus search, arrow keys for navigation

### 🎯 **Multi-Mode Search**
- **All**: Blended feed from all sources
- **Web**: Traditional web search (Google, Bing, DuckDuckGo)
- **Shopping**: Amazon product search
- **AI**: Perplexity AI-powered answers
- **Social**: Social media search
- **Saved**: Your saved results

### 📚 **Personal Search Library**
- **Collections**: Organize saved results into custom collections
- **Save Results**: One-click save with ⭐ button
- **Session Timeline**: Track your search history
- **Export to Markdown**: Export your search session

### 🔒 **Privacy First**
- **No Tracking**: All data stored locally in localStorage
- **Privacy Panel**: See what's stored, wipe data anytime
- **Transparent**: Clear visibility into your data

### 🎨 **Premium Design**
- **Minimalistic UI**: Clean, Apple/Perplexity-inspired design
- **Smooth Animations**: Micro-interactions and transitions
- **Responsive**: Perfect on desktop, tablet, and mobile
- **Blended Results**: Beautiful card-based result display

## 🚀 Quick Start

1. Open `index.html` in your browser
2. Start typing to see autocomplete suggestions
3. Use search operators for quick actions:
   - `!a air fryer` - Search Amazon
   - `!g python tutorial` - Search Google
   - `!ddg privacy` - Search DuckDuckGo
   - `? explain AI` - Ask Perplexity
4. Press `Enter` or click search
5. Browse results in tabs or blended view

## 🔑 API Keys (Optional)

The search engine works immediately with DuckDuckGo (no API key needed). To enable other engines, add your API keys in the `CONFIG` object in `index.html`:

```javascript
const CONFIG = {
    GOOGLE_API_KEY: 'your-google-api-key',
    GOOGLE_CSE_ID: 'your-google-cse-id',
    BING_API_KEY: 'your-bing-api-key',
    PERPLEXITY_API_KEY: 'your-perplexity-api-key',
};
```

### Getting API Keys

- **Google**: [Google Cloud Console](https://console.cloud.google.com/) → Custom Search API
- **Bing**: [Azure Portal](https://portal.azure.com/) → Bing Search v7
- **Perplexity**: [Perplexity AI](https://www.perplexity.ai/) → API section

## 📖 Usage Guide

### Search Operators
- `!a query` or `amazon: query` - Search Amazon
- `!g query` or `google: query` - Search Google
- `!ddg query` or `ddg: query` - Search DuckDuckGo
- `? query` or `ask: query` - Ask Perplexity AI

### Keyboard Shortcuts
- `Cmd/Ctrl + K` - Focus search box
- `↑/↓` - Navigate autocomplete
- `Enter` - Search or select autocomplete
- `Esc` - Close autocomplete

### Saving Results
- Click the ⭐ button on any result to save it
- Access saved results via the Library button
- Create collections to organize saved items

### Session Management
- All searches are tracked in the session timeline
- Export your session to Markdown
- Clear session when needed

## 🎯 Features in Detail

### Autocomplete System
- **Recent Searches**: Shows your last 50 searches
- **Saved Topics**: Matches from your saved results
- **Smart Suggestions**: Query variations and improvements
- **Instant Answers**: DuckDuckGo instant answers when available
- **Operator Hints**: Shows available operators as you type

### Blended Results Mode
When in "All" mode, results are displayed in a beautiful blended feed:
- Top results from each engine
- Organized by source with badges
- Clean card-based layout
- Hover effects and smooth transitions

### Privacy & Data
- **Local Storage Only**: All data stays on your device
- **No Cookies**: Except localStorage (required for functionality)
- **No Tracking**: Zero analytics or tracking scripts
- **Transparent**: See exactly what's stored
- **One-Click Wipe**: Delete all data instantly

## 📱 Responsive Design

Fully responsive and optimized for:
- Desktop (1920px+)
- Tablet (768px - 1920px)
- Mobile (320px - 768px)

## 🌐 GitHub Pages Deployment

1. Create a new GitHub repository
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Select your branch (usually `main`)
5. Select `/root` as the source
6. Your site will be live at `https://yourusername.github.io/repository-name/`

## 🛠️ Customization

### Change Search Modes
Edit the mode buttons in the HTML:
```html
<button class="mode-btn" data-mode="web">Web</button>
```

### Add New Engines
1. Add engine to `getEnginesForMode()` function
2. Create search function (e.g., `searchNewEngine()`)
3. Add to `searchWithEngine()` switch statement
4. Update engine names and icons

### Styling
All styles are in the `<style>` section. Key CSS variables:
- `--primary-bg`: Background gradient
- `--primary-text`: Main text color
- `--accent`: Accent color (buttons, highlights)
- `--border-color`: Border colors

## 🔧 Technical Details

- **Single File**: Everything in one HTML file for easy deployment
- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **localStorage**: All data persistence
- **CORS Handling**: Graceful fallbacks for restricted APIs
- **Progressive Enhancement**: Works without JavaScript (basic functionality)

## 📝 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design Philosophy

- **Minimal**: Clean, uncluttered interface
- **Fast**: Instant feedback and smooth animations
- **Private**: Your data stays yours
- **Useful**: Features that actually improve search
- **Beautiful**: Premium feel without bloat

## 🤝 Contributing

Feel free to fork, modify, and improve! This is a personal-use project, but contributions are welcome.

## 📄 License

Open source - use freely for personal projects.

---

**Built with ❤️ for a better search experience**
# Vizoo
