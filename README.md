🚤 SAIL PLANNER - Nautical route planner featuring wind, currents, waves, and tactical VMG routing

👉 https://oddandre.github.io/seilrute-pro/ 👈


## ✨ Features

### 🗺 Maps and Navigation
- 6 map layers including official Norwegian Mapping Authority (Kartverket) nautical charts
- Click-based waypoints with drag-and-drop functionality
- Automatic land avoidance based on nautical chart pixels

### 🌬 Weather and Wind
- Time-based wind forecasts from Open-Meteo
- Current effects with color-coded visualization
- Wave heights with safety color-coding
- Tidal data from Kartverket (sehavniva.no)
- Weather window finder (±24 hours)

### ⛵ Sailing Tactics
- ORC database featuring 1969+ Norwegian boats
- VMG routing with correct geometry
- Smart jibe/tack recommendations (only at ≥10% gain)
- Visualization of Z-patterns on the map
- Isochrone routing with land avoidance

### 🛡 Safety
- Detects shallow areas, reefs, and tidal zones
- Utilizes official Kartverket nautical chart pixels
- Warnings for problematic routes

## 🎯 Slik bruker du appen

1. Set waypoints - click on the map
2. Select boat - choose from the list or load ORC data
3. Set departure time - wind data is fetched for the correct time slot
4. Click Calculate - get a complete analysis with ETA

## ⚠ Important Disclaimers

- 🚤 Not a replacement for official nautical charts or GPS
- 📊 Polar data consists of estimates - use an ORC certificate for accuracy
- 🌬 Wind/current data may be delayed or unavailable
- ⚓ Local knowledge and seamanship always come first

  Use this app for decision support, not as an autopilot!

## 💻 Technology

- Frontend: Vanilla JavaScript + HTML5 + CSS3
- Maps: Leaflet.js
- Wind/Currents/Waves: Open-Meteo API
- Tides: Kartverket sehavniva.no
- Nautical Charts: Kartverket WMTS
- ORC: Official ORC database via data.orc.org


## 🛟 Feedback

Suggestions, bugs, or questions? Create an Issue!
(https://github.com/oddandre/seilrute-pro/issues)!
