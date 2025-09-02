# The Pauper Cube - Draft Guide & Reference

A lightning-fast, mobile-optimized Hugo website for The Pauper Cube draft guide. Perfect for keeping open on your phone during cube drafts!

## Features

- **Mobile-First Design:** Optimized for mobile devices with touch-friendly navigation
- **Lightning Fast:** Built with Hugo and optimized for Cloudflare Pages
- **Complete Draft Guide:** Comprehensive strategy, archetypes, and deck building
- **Full Cube List:** All 540 cards organized by color and type
- **Searchable:** Easy to find cards and strategies while drafting
- **Dark Mode:** Automatic theme switching based on user preference

## Quick Start

### Local Development

```bash
# Clone the repository with submodules
git clone --recursive https://github.com/dunamismax/the-pauper-cube.git

# Or if already cloned, initialize submodules
git submodule update --init --recursive

# Install Hugo (macOS with Homebrew)
brew install hugo

# Start development server
hugo server

# Visit http://localhost:1313
```

### Deploy to Cloudflare Pages

1. **Connect to GitHub:** Link your Cloudflare account to this repository
2. **Build Settings:**
   - **Build command:** `hugo --gc --minify`
   - **Build output directory:** `public`
   - **Node.js version:** Latest LTS
3. **Environment Variables:**
   - `HUGO_VERSION`: `0.148.2`
   - `HUGO_ENV`: `production`

## Project Structure

```
├── content/
│   ├── _index.md           # Homepage
│   └── docs/
│       ├── draft-guide.md   # Complete draft strategy
│       ├── archetypes.md    # 10 color pair guides
│       ├── tips-tricks.md   # Advanced strategies
│       ├── cube-list.md     # Full card list
│       └── credits.md       # Credits and community
├── assets/css/
│   └── custom.css          # Mobile-optimized styling
├── themes/hugo-book/       # Hugo Book theme (submodule)
├── static/
│   ├── robots.txt
│   └── _headers            # Cloudflare headers
├── hugo.toml               # Site configuration
└── .cloudflare-pages.toml  # Cloudflare build config
```

## Design Features

- **Inter Font:** Premium typography on desktop, system fonts on mobile for speed
- **16px Base Font:** Optimal readability on mobile devices
- **Touch-Friendly:** 44px minimum touch targets
- **Performance:** Optimized images, minified CSS/JS, CDN delivery
- **Accessibility:** WCAG compliant with proper focus states and contrast

## Authoritative Cube List

For the always up-to-date, official card list, visit:
**[The Pauper Cube on Cube Cobra](https://cubecobra.com/cube/list/thepaupercube)**

This is the definitive source for the current 540-card list, maintained by Adam Styborski.

## Credits

- **Adam Styborski:** Creator and curator of The Pauper Cube
- **[The Pauper Cube Official Site](https://thepaupercube.com/)**
- **[Cube Cobra](https://cubecobra.com/cube/list/thepaupercube)** 
- **[Discord Community](https://discord.gg/Px2JhHM)**
- **[Hugo Book Theme](https://github.com/alex-shpak/hugo-book)** by Alex Shpak

## About This Guide

**Created by:** dunamismax ([dunamismax@tutamail.com](mailto:dunamismax@tutamail.com))  
**Source Code:** [github.com/dunamismax/the-pauper-cube](https://github.com/dunamismax/the-pauper-cube)

## License

Content is provided with respect and attribution to original creators. The Pauper Cube is curated by Adam Styborski. Magic: The Gathering is © Wizards of the Coast.

---

**Ready to draft?** Visit the live site at [the-pauper-cube.pages.dev](https://the-pauper-cube.pages.dev)