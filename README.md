Interactive Mapping: A responsive map interface for exploring weather events across different geographic regions.

Data Sources
This application relies on robust government and meteorological APIs to ensure accurate and timely data:

NWS API: National Weather Service API for core meteorological data and alerts.

IEM API: Iowa Environmental Mesonet API for additional specialized weather data and historical archives.

Recent Updates & Troubleshooting
Data Fetching Optimization: Addressed recent data fetching errors by removing specific, deprecated data source parameters from the API calls, ensuring stable and reliable data retrieval from the NWS and IEM services.

Prerequisites
This is a frontend web application leveraging HTML5 and Vanilla JavaScript. To run and modify this project locally, you will need:

Modern Web Browser: To render HTML5 and execute asynchronous JavaScript fetch operations.

Mapping Libraries:

Leaflet.js: For interactive mapping and UI rendering (can be included via CDN).

Turf.js: For complex geographic calculations and handling spatial data (can be included via CDN).

Local Web Server: A basic local development server (e.g., Python's http.server, Node.js http-server, or the VS Code Live Server extension) is recommended to serve the files and prevent CORS (Cross-Origin Resource Sharing) errors when fetching external REST APIs.
