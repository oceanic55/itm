# Project Structure

## Root Level
- `index.html` - Main landing page (ITAMI airport content)
- `readme.md` - Project documentation

## Core Directories

### `/src/`
- `styles.css` - Main stylesheet with responsive design
- `styles copy.css` - Backup/alternative stylesheet

### `/h/`
Content pages for different sections:
- `miso.html` - Miso brands and information
- `koji.html` - Koji and fermentation content  
- `food.html` - Supermarket and food retail information
- `other.html` - Additional regional content
- `miso copy.html` - Backup version

### `/fonts/`
- `fonts.css` - Font face declarations
- `inter-*.ttf` - Inter font family (400, 500, 600, 700 weights)
- `/Nebula-Font/` - Custom Nebula font files (Regular.otf, Hollow.otf)

### `/img/`
Content images:
- Product photos (miso.jpg, koji.jpg, etc.)
- People photos (ando.jpg, itami.jpg)
- Food photography (super.jpg)

### `/graphics/`
Design assets:
- `logo.svg`, `nebula.svg` - Vector graphics
- `nebula.pxd` - Design source file
- Various image formats for branding

## File Naming Conventions
- HTML files: lowercase with descriptive names
- CSS files: kebab-case (styles.css)
- Images: lowercase, descriptive (miso.jpg, koji.jpg)
- Fonts: descriptive with weight indicators (inter-400.ttf)

## Navigation Structure
All pages share the same navigation:
- ITAMI (index.html) → MISO → KOJI → SUPERMARKETS → OTHER
- Relative path linking from `/h/` pages back to root