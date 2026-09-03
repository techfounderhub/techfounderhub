# AI Agent Course Landing Page

A modern, responsive landing page for the AI Agent Course. Built with clean HTML and CSS—no build step required. Ready for deployment on Cloudflare Pages.

## Quick Start

### Local Preview

**Option 1: Open directly in browser**
```bash
open index.html
```

**Option 2: Use a local server**
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx serve)
npx serve

# Using Ruby
ruby -run -ehttpd . -p8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment to Cloudflare Pages

### Prerequisites
- GitHub account (for code hosting)
- Cloudflare account (for hosting)
- This repo pushed to GitHub

### Steps

1. **Push this repo to GitHub**
   ```bash
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Connect to Cloudflare Pages**
   - Log in to [Cloudflare Dashboard](https://dash.cloudflare.com)
   - Go to **Pages** → **Create a project**
   - Connect your GitHub account and select this repository
   - Build settings:
     - **Framework preset:** None (Static HTML)
     - **Build command:** (leave empty)
     - **Build output directory:** `/`
   - Deploy!

3. **Your site is live**
   - Cloudflare Pages will serve `index.html` automatically
   - All CSS is inlined, so no separate files needed
   - Your site will be available at `https://<project-name>.pages.dev`

## Project Structure

```
ai-agent-course-site/
├── index.html          # Main landing page (all-in-one)
├── .gitignore          # Git ignore patterns
├── README.md           # This file
└── (no build step needed)
```

## Features

- **Responsive Design** – Works on mobile, tablet, and desktop
- **Fast Loading** – Single static HTML file, no external dependencies
- **Accessible** – Semantic HTML, proper contrast ratios
- **SEO Ready** – Meta tags, proper heading hierarchy
- **No Build Step** – Just deploy `index.html` and go

## Styling Guide

The landing page uses CSS custom properties (variables) for easy theming:

- **Primary Color:** `#FFFFFF` (White)
- **Secondary Color:** `#1B1F6B` (Deep Navy Blue)
- **Accent Color:** `#1A1A6E` (Slightly different navy)
- **Headline Font:** Arial, Helvetica (bold, condensed)
- **Body Font:** System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, etc.)

To customize colors, edit the `:root` selector in the `<style>` tag.

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 AI Agent Course. All rights reserved.
