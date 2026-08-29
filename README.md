# Inundation Simulator

Browser-based 2D/3D flood depth visualization using DEM tiles from GSI and rainfall data.

## Quick Start

1. Open [`inundation-simulator-v001.html`](inundation-simulator-v001.html) in a web browser
2. Zoom the map to level 13+ and navigate to your target area → terrain data loads automatically
3. Enter rainfall manually, or click "雨雲データを取得" to fetch JMA radar data
4. Select "簡易水位法" (instant) or "水流シミュレーション" (animated), then click "予測を実行"
5. View results in 2D map and/or 3D visualization

**Note:** Geolocation API requires HTTPS or localhost. For full features, open via GitHub Pages at https://yukix333.github.io/inundation-simulator/

## Features

- Single HTML file, no build or server required
- Manning-based flow calculation with 2D/3D visualization
- Direct watershed-fill solver for instant results
- Water volume conservation tracking
- Responsive mobile/desktop layout
- Real-time JMA radar data integration

## Repository

- **GitHub:** https://github.com/yukix333/inundation-simulator
- **Status:** Public
- **License:** See LICENSE (if present)

