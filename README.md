UrbanEye 🛰️
AI Urban Intelligence Platform UrbanEye is a powerful, real-time satellite imagery analysis dashboard designed to detect illegal construction, land clearing, and earthworks using Optical Physics Signature Detection.
🌟 Overview
Traditional satellite monitoring requires heavy backend Python servers and delayed data processing. UrbanEye brings the intelligence directly to the browser. By interfacing directly with the Copernicus Sentinel-2 Process API, the platform fetches, super-samples, and mathematically compares historical and present-day satellite data entirely on the client-side.
✨ Features
Optical Signature AI: Goes beyond simple pixel-differencing. It specifically calculates NDVI (Vegetation) loss and NDBI (Luminance) spikes to mathematically confirm human earthworks and concrete structures, ignoring seasonal changes and cloud shadows.
Time Travel Analysis: Dynamically compare today's satellite feed against data from 1 to 6 years ago.
Supersampled Native Resolution: Calculates precise physical bounding boxes to fetch 10m/px optical data and applies crisp-edge CSS scaling to eliminate browser blur.
Global Search & Geocoding: Built-in Nominatim OpenStreetMap search to instantly fly to any city or coordinate pair globally.
100% Responsive Design: A clean, dark-mode dashboard that adapts flawlessly from desktop command centers to mobile screens in the field.
🚀 How to View the Live Site
Because this is a pure frontend application with no required database, it is hosted directly on GitHub Pages!
Go to the Settings tab of this GitHub repository.
Navigate to Pages in the left sidebar.
Look for the message indicating your site is live (e.g., Your site is live at https://yourusername.github.io/urbaneye/).
Click the link to open the dashboard.
Note: If you just forked/cloned this repository, it may take 1-2 minutes for GitHub actions to build and deploy the page for the first time.
🛠️ Usage Instructions
Navigate the Map: Use your mouse or the search bar in the top-left to locate your target area (e.g., a developing suburb or protected forest).
Draw an AOI: Click ⬚ Draw Inspection Area in the bottom left, and drag a rectangle over the map (Max 300km²).
Run AI Analysis: Select your comparison timeframe (e.g., vs 2 Years Ago) and click the Run Signature AI button.
Review Results: The engine will highlight verified construction sites with precise pins, categorizing them as either Land Clearing or New Structure.
📡 Technologies Used
HTML5 / CSS3 / Vanilla JS (No heavy JavaScript frameworks required)
Leaflet.js: Open-source interactive mapping.
Copernicus Sentinel Hub Process API: Real-time satellite imagery fetching and cloud-masking.
Nominatim API: Free geocoding for the global search bar.
⚖️ License
Copyright (c) 2026 UrbanEye. All Rights Reserved.

This project is proprietary and closed-source. You may not copy, clone, distribute, or modify this code without explicit written permission from the owner.
