# Bike Components Explained Site

## Overview
This is a simple, static personal website that explains motorcycle (bike) components in three layers:
- **Child‑friendly description** – easy‑to‑understand language as if explaining to a child.
- **Expert description** – a bit more technical, but still without heavy math.
- **Brand note** – how popular motorcycle brands leverage the component for speed and performance.

Each component also displays a picture (you need to supply the image files).

## Project Structure
```
/bike
│   index.html          # Main page – loads component data and renders cards
│   style.css           # Basic styling for the site
│   README.md           # You are reading it!
│
├─ data
│   └─ components.json  # JSON with component information
│
└─ images               # Place component images here (e.g., frame.jpg, engine.jpg)
```

## How to Run locally
1. Open a terminal and `cd` into the `bike` folder.
2. Start a simple static server. For example (Python is usually pre‑installed):
   ```powershell
   python -m http.server 8000
   ```
3. Open a browser and navigate to `http://localhost:8000`. You should see the site with cards for each component.

## Adding/Updating Images
- Save each image in the `images` directory.
- The file name must match the `image` field in `data/components.json` (e.g., `frame.jpg`).
- If an image is missing, the card will simply hide the `<img>` element.

## Extending the Site
- **Add more components**: edit `data/components.json` and add a new object to the `components` array.
- **Change styling**: modify `style.css`.
- **Modify layout**: edit `index.html`.

Feel free to ask for any additional features, such as navigation, search, or animations!
