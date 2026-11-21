# 🛰️ Who's Watching? — Satellite Pass Tracker

A web-based satellite tracking application that lets users discover which Earth-observation satellites passed over a selected location during the last 7 days and explore publicly available satellite imagery.

## ✨ Features

- 🌍 Search any geographical location.
- 🛰️ Track Earth-observation satellite passes over a 7-day period.
- 📡 Calculate satellite positions using SGP4 orbital propagation.
- 🇮🇳 Identify Indian Earth-observation satellites.
- 🗺️ Visualise searched locations on an interactive map.
- 🖼️ Discover public Sentinel-2 and Landsat imagery.
- 🔎 Match satellite imagery with corresponding satellite passes.
- ⏱️ Display pass timings in local time.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- satellite.js (SGP4)
- Leaflet.js
- CelesTrak TLE data
- Microsoft Planetary Computer STAC API
- OpenStreetMap
- Nominatim Geocoding API

## 🛰️ Data Sources

- CelesTrak — Satellite orbital data.
- Copernicus Sentinel-2 — Earth observation imagery.
- USGS / NASA Landsat — Satellite imagery.
- Microsoft Planetary Computer — Public imagery discovery.
- OpenStreetMap — Maps and geographical search.

## 🚀 How to Run

1. Clone this repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Search for a location.
5. Explore satellite passes and available imagery.

An active internet connection is required to access the external APIs and libraries.

## 📌 Project Note

Satellite passes are calculated using publicly available orbital data. Imagery matching is based on satellite identity and observation timestamps.

Results depend on the availability and freshness of public data sources.

## 👩‍💻 Inspiration

This project was developed as a hands-on learning experience, inspired by an online tutorial/reel.

## 📜 Credits

Data and services are credited to their respective providers, including CelesTrak, Copernicus, USGS/NASA, Microsoft Planetary Computer and OpenStreetMap contributors.
