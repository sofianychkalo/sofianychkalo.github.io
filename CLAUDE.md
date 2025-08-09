# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub Pages repository containing a single-page portfolio/CV website for Sofia Nychkalo, focusing on medical and aesthetic care expertise. The site is a static HTML page with embedded CSS and is live at https://sofianychkalo.github.io/

## Project Structure

- `index.html` - Main portfolio/CV landing page with:
  - Hero section with professional portrait image
  - About section explaining motivation for BemEstar
  - Experience showcase with treatment categories
  - Features highlighting professional strengths
  - Language capabilities
  - Contact information
- `2025-08-09 16.13.02.jpg` - Professional portrait photo used in hero section

## Development Commands

Since this is a static HTML site with no build process:
- **Preview locally**: Open `index.html` directly in a browser
- **Deploy**: Commit changes to the main branch - GitHub Pages will automatically serve the site at https://sofianychkalo.github.io/

## Architecture Notes

The site uses:
- Pure HTML/CSS with no JavaScript dependencies
- Embedded styles within the HTML file for simplicity
- Google Fonts (Playfair Display and Inter)
- Responsive design with CSS Grid and Flexbox
- Linear gradients and transitions for visual effects
- Mobile-first responsive breakpoints at 768px

## Key Considerations

- The site is designed as a professional portfolio/CV
- All styling is embedded in the HTML file - no external CSS files
- No build process or package management required
- Hero section contains actual portrait image (350x450px with rounded corners)
- Contact information is hardcoded in the HTML

## Recent Changes (2025-08-09)

1. **GitHub Pages Setup**
   - Renamed `sofia_bemestar_landing.html` to `index.html` for proper GitHub Pages deployment
   - Repository now correctly serves at https://sofianychkalo.github.io/

2. **Portrait Image Added**
   - Added professional portrait photo to hero section
   - Replaced placeholder div with actual `<img>` element
   - Updated CSS for proper image display with object-fit: cover