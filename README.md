# Fundamentals of Digital

ACE Training Terminal - Digital Fundamentals Educational Application

This is an interactive educational platform featuring gamification elements for learning digital fundamentals in aviation.

## Features

- Interactive Practice Tests
- Flash Cards
- Jeopardy-style Quiz Game
- Transponder-VSWR Simulator
- Gamification system with XP, levels, and badges
- Progress tracking and score history

## Deployment

This is a static HTML application. To deploy to GitHub Pages:

```bash
npm install
npm run deploy
```

The `npm run deploy` command will:
- Deploy all HTML files and assets to the `gh-pages` branch
- Include dotfiles (like .nojekyll)
- Automatically configure GitHub Pages

After deployment, the site will be available at: `https://00ainick-cmd.github.io/Fundamentals-of-Digital/`

### First-time Setup

After running `npm run deploy` for the first time, you need to enable GitHub Pages:

1. Go to your repository on GitHub
2. Navigate to Settings → Pages
3. Under "Source", select the `gh-pages` branch
4. Click "Save"

The site will be live within a few minutes at the URL above.

## Development

No build process is required. Simply open `index.html` in a web browser to test locally.

## Documentation

See [GAMIFICATION_FIX_DOCUMENTATION.md](GAMIFICATION_FIX_DOCUMENTATION.md) for details about the gamification system implementation.
