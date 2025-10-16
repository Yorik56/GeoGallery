# GeoGallery

GeoGallery is a single-file, offline web app that displays your JPEG photos on a map using their EXIF GPS data.  
It runs entirely in your browser — no installation, no upload, no server.

---

## Overview

Open a folder of photos, and GeoGallery automatically extracts GPS coordinates, places the images on an interactive Leaflet map, and connects them in chronological order.  
You can browse your trip visually, navigate photo by photo, or play through your route automatically.

---

## How to Use

1. Download or clone this repository.  
2. Open `geogallery.html` directly in your browser (works best with Chrome or Edge).  
3. Click **“Open folder”** or **“Browse…”** to select a photo directory.  
4. GeoGallery scans all subfolders and shows photos on the map.  

**Available actions:**

- **Navigation:**  
  - Next / Previous photo (buttons or keyboard arrows)  
  - Autoplay mode (Play / Pause button)  
  - Center and zoom on the current photo  
- **Map controls:**  
  - Zoom in / out (bottom-right)  
  - Toggle fullscreen mode  
- **Export:**  
  - CSV (uMap compatible)  
  - GeoJSON (for GIS tools or backup)

All processing is done locally; no data leaves your computer.

---

## Export Formats

- **CSV (uMap)** → `latitude, longitude, name, description` with inline image tag  
- **GeoJSON** → `FeatureCollection` with photo points and route line

---

## License

Released under the MIT License.
