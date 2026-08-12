# CashCards for Plumbers - Mobile App

An interactive, mobile-friendly web application for browsing and flipping through the CashCards e-deck with 46 sales scripts and objection handling techniques.

## Features

✨ **Complete Card Deck**
- 46 fully-detailed sales cards with scripts, icons, and explanations
- Professional dark theme optimized for readability
- Card flipping animation with smooth transitions

📱 **Mobile-Optimized**
- Fully responsive design for phones, tablets, and desktops
- Touch-friendly swipe controls to navigate between cards
- Tap to flip cards front/back
- Installable as a Progressive Web App (PWA)

🔍 **Search Functionality**
- Search cards by title, script content, or "Why it works" explanation
- Real-time filtering as you type
- Quick access to specific objection handling techniques

⌨️ **Multiple Control Methods**
- **Touch**: Tap to flip, swipe left/right to navigate
- **Keyboard**: Arrow keys for navigation, Space/Up/Down for flipping
- **Buttons**: Click navigation buttons for easy browsing
- **Mouse**: Click card to flip, supports desktop usage

🌐 **Offline Support**
- Works offline after first load (cached)
- Service worker enables PWA functionality
- No internet required after installation

## Quick Start

### Open in Browser
1. Open `index.html` in any modern web browser
2. Start flipping through cards or use the search bar
3. Tap card to flip, swipe/arrow keys to navigate

### Install as Mobile App

**iPhone/iPad (iOS)**
1. Open in Safari
2. Tap Share button → "Add to Home Screen"
3. Open from your home screen

**Android**
1. Open in Chrome
2. Tap menu (⋮) → "Install app"
3. Confirm installation

## Controls

| Action | Result |
|--------|--------|
| Tap/Click Card | Flip between front and back |
| Swipe Left | Next card |
| Swipe Right | Previous card |
| Arrow Right / Page Down | Next card |
| Arrow Left / Page Up | Previous card |
| Space / Arrow Up / Arrow Down | Flip card |
| Type in Search | Filter cards by title, script, or explanation |

## File Structure

```
/
├── index.html          # Main application (complete HTML/CSS/JS)
├── manifest.json       # PWA manifest for installation
├── sw.js              # Service worker for offline support
└── README.md          # This file
```

## Features Breakdown

### 46 Complete Sales Cards
Each card includes:
- **Front**: Objection title with icon
- **Back**: Word-for-word script + "Why It Works" explanation

Topics include:
- Price objections (multiple variations)
- Budget concerns
- Competitor comparison
- Timeline objections
- Decision-making delays
- Trust building
- Quality/value emphasis
- Payment options
- And much more...

### Progressive Web App (PWA)
- Works offline after first load
- Installable on home screen
- Fast loading (~1 second)
- Lightweight (~100KB)
- Full-screen mobile experience

### Search & Filter
Search across:
- Card titles
- Full scripts
- Explanations
- Real-time results

## Deployment Options

### Option 1: Local (No Server Needed)
- Just open `index.html` in any browser
- Perfect for local use or distribution

### Option 2: GitHub Pages
```bash
git push
# Go to Settings → Pages
# Enable GitHub Pages from main branch
```
Live at: `https://yourusername.github.io/VPCASHCARDS`

### Option 3: Any Web Host
Upload these 3 files to your hosting:
- `index.html`
- `manifest.json`
- `sw.js`

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome/Chromium | ✅ Full support |
| Firefox | ✅ Full support |
| Safari | ✅ Full support (iOS 11.3+) |
| Edge | ✅ Full support |
| Opera | ✅ Full support |

## Customization

### Add/Edit Cards
Edit the `deck` array in `index.html`:

```javascript
const deck = [
  {
    title: "YOUR OBJECTION",
    icon: "emoji",
    script: "Your word track script...",
    why: "Why this approach works..."
  }
];
```

### Change Colors
Update CSS variables in `<style>`:
```css
:root {
  --bg-color: #121212;
  --card-bg: #222222;
  --accent-color: #e2b714;
  --text-main: #f0f0f0;
}
```

## Performance

- **Load Time**: < 1 second
- **Offline**: Yes (after first load)
- **Cache Size**: ~50KB
- **No Dependencies**: Pure JavaScript
- **Mobile Optimized**: 100% responsive

## Privacy & Security

- ✅ No external APIs
- ✅ No tracking/analytics
- ✅ No personal data collection
- ✅ Works completely offline
- ✅ All data stored locally

## Tips

1. **Install as app** for best mobile experience
2. **Use search** to quickly find objection handling
3. **Load once** to cache for offline use
4. **Keyboard shortcuts** on desktop for speed
5. **Full screen** mode on mobile for immersion

## License

© STUPAR ENTERPRISES - CashCards for Plumbers

---

**Interactive sales training at your fingertips** 💳