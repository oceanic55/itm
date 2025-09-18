# Technology Stack

## Build System
- **Static HTML/CSS/JavaScript**: No build process required
- **Direct file serving**: Files can be served directly from any web server
- **No dependencies**: Pure vanilla web technologies

## Tech Stack
- **HTML5**: Semantic markup with proper accessibility attributes
- **CSS3**: Custom CSS with responsive design and CSS Grid/Flexbox
- **Vanilla JavaScript**: No frameworks, pure DOM manipulation
- **Google Maps Embed API**: For interactive map functionality

## Fonts & Assets
- **Inter font family**: Multiple weights (400, 500, 600, 700) via TTF files
- **Nebula custom font**: Regular and Hollow variants via OTF files
- **Font loading**: Uses `font-display: swap` for performance
- **Images**: JPG/PNG for photos, SVG for graphics and logos

## Development Commands
Since this is a static site, no build commands are needed:

```bash
# Serve locally (any method works)
python -m http.server 8000
# or
npx serve .
# or use any local web server

# No compilation, bundling, or build steps required
```

## Browser Support
- Modern browsers with CSS Grid and Flexbox support
- Mobile-first responsive design
- Progressive enhancement approach