# Centralized Weather Station Management System — HTML/CSS/JavaScript edition

## Run it
1. Extract the ZIP file.
2. Open `index.html` in a modern browser (Chrome/Edge recommended). No npm, React, Java, Maven, or PostgreSQL is required.

## Included interactions
- Same dashboard layout, summary cards, station registry, search, refresh, add-station form, delete confirmation, status badges, and calibration/sensor attention counts.
- Station data persists in this browser using `localStorage`.
- First launch loads the three demo stations. Add/delete changes are saved locally and remain after refresh in the same browser.

## Important difference from the original full-stack project
This is a browser-only conversion. Because HTML/CSS/JavaScript running as a static page cannot directly replace the Spring Boot API and PostgreSQL database, the original API/database storage has been replaced by browser `localStorage`. Data is local to this browser/device and is not shared across users or devices. The readings are demo values; no physical sensors are connected. The original backend files are intentionally not included in this HTML/CSS/JavaScript-only package.
