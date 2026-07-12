# 🏛️ European Empires — Historical Simulation (3000 BCE – 2025 CE)

**An interactive map simulation tracing the rise and fall of European empires and civilizations across 5,000 years — from the Minoans on Crete to the modern European Union.**

Built by **H Heuristics** — professional-grade historical cartographic simulation with 25-year increments, empire territory visualization, city founding tracking, key battle markers, and population estimates.

---

## Features

- **Interactive Map** — Leaflet.js-powered map with parchment aesthetic, CARTO light tiles with antique sepia filtering, and color-coded empire territories that appear and disappear through time
- **Timeline Engine** — 25-year increment slider (3000 BCE – 2025 CE) with draggable scrubber, play/pause animation (4 speeds), step controls, and keyboard shortcuts
- **Empire Rise & Fall** — 46 civilizations and empires appear and disappear based on their historical dates, each with distinct heraldic colors and categorized by era
- **Territory Visualization** — Semi-transparent polygon overlays show approximate empire boundaries at each point in time, with hover tooltips and click-to-focus
- **City Founding** — 32 major European cities with founding dates, coordinates, and historical significance — markers appear as the timeline advances
- **Battle & Event Markers** — 21 key battles and turning points appear as contextual markers on the map (Kadesh, Thermopylae, Cannae, Hastings, Waterloo, Stalingrad, D-Day, etc.)
- **Historical Events Panel** — 80+ contextual events (wars, political milestones, cultural achievements, scientific breakthroughs) shown in the sidebar
- **Population Estimates** — Live population counter showing estimated European population across millennia
- **Era Color Coding** — 8 visual eras from Bronze Age to Digital Age with distinct color palettes
- **Responsive Design** — Works on desktop, tablet, and mobile with adaptive layout
- **Keyboard Shortcuts** — Full keyboard navigation for efficient exploration

## Data Coverage

| Category | Count |
|----------|-------|
| Empires & Civilizations | 46 (from Minoan to EU) |
| Major Cities | 32 (with founding dates and significance) |
| Historical Events | 85 (categorized: War, Found, Politics, Culture, Science) |
| Battle/Event Map Markers | 21 (with coordinates and descriptions) |
| Population Data Points | ~100 (3000 BCE – 2025 CE) |
| Timeline Increments | 202 (25-year steps) |

## Era Categories

| Color | Era | Years |
|-------|-----|-------|
| `#8b6914` | Bronze Age | 3000–1200 BCE |
| `#a02030` | Classical Antiquity | 1200 BCE–500 CE |
| `#702080` | Byzantine | 330–1453 CE |
| `#3058a0` | Medieval | 500–1500 CE |
| `#208860` | Islamic Caliphates | 661–1258 CE |
| `#b8963c` | Renaissance & Early Modern | 1400–1700 CE |
| `#2048a0` | Colonial Empires | 1500–1950 CE |
| `#505868` | Modern Nation-States | 1815–2025 CE |

## Empires & Civilizations Included

**Bronze Age**: Minoan, Mycenaean, Hittite, Assyrian, Phoenician

**Classical**: Greek City-States, Achaemenid Persia, Macedonian (Alexander), Carthaginian, Roman Republic, Roman Empire, Parthian, Sassanid

**Medieval**: Byzantine, Umayyad Caliphate, Abbasid Caliphate, Carolingian Empire, Viking Kingdoms, First Bulgarian Empire, Kievan Rus', Holy Roman Empire, Kingdom of England, Kingdom of France, Republic of Venice, Mongol Empire / Golden Horde, Kalmar Union

**Early Modern**: Ottoman Empire, Polish-Lithuanian Commonwealth, Spanish Empire, Portuguese Empire, Habsburg Monarchy, Dutch Republic, Swedish Empire, British Empire, Russian Empire, Prussia, Napoleonic France

**Modern**: German Empire, Austria-Hungary, Soviet Union, Nazi Germany, European Union

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` | Step forward 25 years |
| `←` | Step backward 25 years |
| `Space` | Play / Pause animation |
| `Home` | Jump to 3000 BCE |
| `End` | Jump to 2025 CE |
| `B` | Toggle empire borders |
| `R` | Reset map view |
| `1`–`4` | Set playback speed (0.5× to 4×) |

## Tech Stack

- **Leaflet.js 1.9.4** — Interactive map rendering
- **CARTO Light Basemap** — Minimal tile layer with CSS parchment filter
- **Google Fonts** — Playfair Display, Cormorant Garamond, IM Fell English, Inter
- **Vanilla JavaScript** — Zero framework dependencies, single-file deployment
- **GitHub Pages** — Static hosting deployment

## Historical Aesthetic

The simulation features a warm parchment design system:
- Antique paper tones (`#f4e4c1`, `#e8d5b0`) with deep brown accents
- Vintage serif typography (Playfair Display for headings, Cormorant Garamond for body)
- CARTO light map tiles with CSS sepia/hue-rotate filters for an aged cartographic feel
- Gold and brass border accents throughout the interface
- Dark header bar contrasting with the parchment content area

## Deployment

This is a static site designed for **GitHub Pages**. Simply push to the `main` branch and enable GitHub Pages in the repository settings.

```bash
git clone https://github.com/Hunterhghs/European-Empires-simulation.git
cd European-Empires-simulation
# Open index.html in a browser, or deploy via GitHub Pages
```

## Author

**H Heuristics** — Market research, economic development consulting, and data intelligence.

---

*"Europe is not a continent — it is a palimpsest of empires, each layer written over the last."*
