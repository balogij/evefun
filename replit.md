# EVE Online Fan Site

## Overview
This is a static HTML website about EVE Online, written in Hungarian. The site features information about the game's factions, ships, and strategies.

## Project Structure
- `index.html` - Main homepage with hero section and carousel
- `frakciok.html` - Factions page (Caldari State, Amarr Empire)
- `hajok.html` - Ships page with accordion layout
- `strategiak.html` - Strategies page with tabbed content
- `server.py` - Python HTTP server for local development
- `.gitignore` - Python gitignore configuration

## Technology Stack
- **Frontend**: HTML5, CSS3, Bootstrap 5.3.3
- **Development Server**: Python 3.11 built-in HTTP server
- **Deployment**: Static site hosting

## Development Setup
The project uses a Python HTTP server to serve static files during development:
- Server runs on port 5000
- Binds to 0.0.0.0 to support Replit's proxy system
- Cache-Control headers disabled for development

## Deployment Configuration
- **Deployment Type**: Static
- **Public Directory**: `.` (root directory)
- All HTML, CSS, and asset files are served directly

## Features
- Responsive design using Bootstrap 5
- Dark space-themed styling with neon cyan accents
- Mobile-first responsive layout
- Navigation menu across all pages
- Bootstrap components: carousel, cards, accordion, tabs/pills

## Recent Changes (November 29, 2025)
- Imported from GitHub
- Completed incomplete HTML files (frakciok.html, hajok.html, strategiak.html)
- Added proper HTML structure (DOCTYPE, head, body tags)
- Created Python HTTP server for development
- Configured workflow for development preview
- Set up static deployment configuration
- Added .gitignore for Python files
- Added space-themed stock images for all pages
- Created shared CSS file (styles.css) for consistent styling
- Improved text contrast and readability across all pages
- Added space nebula background image
- Updated hero section with space battle image
- Added faction-specific images (Caldari, Amarr)
- Added images for ships, mining, and PvP sections

## Assets
Stock images are stored in `attached_assets/stock_images/`:
- `epic_space_battle_wi_*.jpg` - Space battle for hero and PvP sections
- `dark_space_nebula_st_*.jpg` - Background image
- `blue_futuristic_mili_*.jpg` - Caldari faction
- `golden_ornate_spaces_*.jpg` - Amarr faction
- `large_battleship_spa_*.jpg` - Ships page header
- `space_mining_asteroi_*.jpg` - Industry/mining section
- `futuristic_spaceship_*.jpg` - Carousel and exploration sections
