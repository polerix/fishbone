# Fishbone Diagram Generator

Interactive web application for creating dynamic Ishikawa (fishbone) diagrams with fillable fields.

## Features

- **6M Framework** — Men, Methods, Materials, Machines, Measurement, Environment
- **Dynamic input fields** — add/remove causes per category
- **Live canvas rendering** — diagram updates as you type
- **Export to PNG** — download your completed diagram
- **Responsive design** — works on desktop and tablet

## Usage

1. Enter your **Problem/Effect** in the header field
2. Add causes under each of the six categories
3. Watch the fishbone diagram update in real-time
4. Download as PNG when complete

## Getting Started

```bash
# Clone the repo
git clone https://github.com/polerix/fishbone.git
cd fishbone

# Open in browser
open index.html
# or
python -m http.server 8000
```

Then navigate to `http://localhost:8000`

## Architecture

- Pure HTML/Canvas (no build step required)
- Vanilla JavaScript state management
- Real-time diagram rendering
- Client-side export via canvas API

## License

MIT
