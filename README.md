# Trail Camera: New Mexico - Interactive Production Map

An interactive web-based map for planning the "Trail Camera: New Mexico - Land of Enchantment" documentary production trip (February 15 - March 31, 2026).

## Live Demo

View the map at: `https://YOUR-USERNAME.github.io/nm-interactive-map/`

## Features

### Location Markers
- **60+ filming locations** across 5 regions
- **Color-coded by category:**
  - Major Towns/Cities (brown)
  - Cultural & Historic Sites (terracotta)
  - Art Community Locations (teal)
  - Natural Features & Landscapes (sage green)
  - O'Keeffe Country (sand)
  - People & Contacts (purple)
  - Resources & Logistics (gray)
- **Regional Overview markers** (gold stars) for area summaries

### Special Designations
Badges on markers indicate:
- 🏛️ UNESCO World Heritage Site
- ⚠️ Production Warning (critical access restrictions)
- 🌸 Seasonal Highlight (best during Feb-March window)
- 🎨 O'Keeffe Connection
- 🚁 Drone flights permitted

### Info Cards
Click any marker to see:
- Location details (region, best shooting time, admission, permits)
- Key features and production notes
- Production warnings highlighted prominently
- Direct links to Google Maps and Google Images search

### Transportation Routes
5 dashed route lines showing travel between:
- ABQ Airport → Santa Fe
- Santa Fe → Taos (via High Road)
- Santa Fe → Ghost Ranch/Abiquiú
- Santa Fe → Los Alamos
- Santa Fe → Ojito Wilderness

Click routes for duration, cost, and logistics notes.

### Interactive Legend
- Click categories to show/hide markers
- Collapsible sidebar for mobile viewing
- Location count statistics

## Technology

- **Leaflet.js** (via CDN) for mapping
- **OpenStreetMap** tiles
- **Single HTML file** - no build process required
- **No API keys** needed

## Local Testing

Simply open `index.html` in a web browser:

```bash
open index.html
```

Or use a local server:

```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Push the files:
   ```bash
   git init
   git add .
   git commit -m "Initial interactive production map"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/nm-interactive-map.git
   git push -u origin main
   ```
3. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: "Deploy from branch"
   - Branch: main, folder: / (root)
4. Access at `https://YOUR-USERNAME.github.io/nm-interactive-map/`

## Map Statistics

| Category | Count |
|----------|-------|
| Total Locations | 60 |
| High Priority | 39 |
| Regional Overviews | 5 |
| Transportation Routes | 5 |
| Production Warnings | 4 |
| Seasonal Highlights | 2 |
| O'Keeffe Connections | 6 |
| Drone-Allowed Sites | 4 |

## Key Production Notes

### Locations with Critical Warnings
1. **Taos Pueblo** - LIKELY CLOSED Feb-March (winter ceremonies)
2. **El Santuario de Chimayó** - Interior filming STRICTLY PROHIBITED
3. **Plaza Blanca** - Verify access 48 hours in advance (policies change)

### Primary Alternatives
- Use **San Francisco de Asís Mission Church** as alternative to Taos Pueblo
- Focus on exterior shots at Chimayó (courtyard, adobe textures, pilgrim arrivals)

### Seasonal Opportunities
- **Velarde Orchards** - Stone fruit blooms late Feb through March
- **Dixon Orchards** - Apple blossoms mid-to-late March
- **March** - Peak lenticular cloud season (599 Relief Route Overlook)

## Project Info

- **Production:** Trail Camera series by PetaPixel
- **Dates:** February 15 - March 31, 2026
- **Base:** Santa Fe, New Mexico
- **Regions:** Santa Fe, Taos, High Road to Taos, O'Keeffe Country, Albuquerque

## License

This map is created for production planning purposes.

---

Generated with Claude Code
