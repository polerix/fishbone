# Fishbone Diagram

Interactive Ishikawa diagram builder with dynamic progression feedback.

## Features

- **6-category framework** — People, Methods, Materials, Machines, Measurement, Environment
- **Dynamic text input** — add/remove causes inline
- **Real-time SVG rendering** — diagram updates as you type
- **Fish head progression** — completion meter animates fish head from dead (0%) to radiant (100%)
- **Dark aesthetic** — clean, minimal dark-mode UI aligned with security-adventure theme
- **Export to PNG** — download your diagram at any stage
- **No build required** — vanilla JS, pure SVG

## Usage

1. Enter your **main problem** at the top
2. Add causes under each category
3. Watch the fishbone diagram and fish head evolve in real-time
4. Completion meter tracks % filled
5. Export when ready

## Categories

- **People** — skills, training, communication gaps, motivation
- **Methods** — processes, procedures, documentation, workflows
- **Materials** — supplies, quality, availability, specifications
- **Machines** — equipment, maintenance, age, calibration
- **Measurement** — metrics, data, sensors, standards
- **Environment** — workspace, conditions, culture, external factors

## Getting Started

```bash
git clone https://github.com/polerix/fishbone.git
cd fishbone
open index.html
# or python -m http.server 8000, then visit http://localhost:8000
```

## Fish Head States

6+ progression stages from dead (empty) → radiant (100% complete):
1. Dead fish (X eyes, flat line mouth)
2. Opening eye
3. Clear eye, neutral mouth
4. Slight smile
5. Clear smile, bright eye
6. Big smile, bright eye, sparkles

## Technical Notes

- SVG-based rendering for clean scaling and export
- Client-side completion tracking (no backend)
- Dark theme (`#0b0f19` background, `#7dd3fc` accents)
- Responsive grid layout

## License

MIT

