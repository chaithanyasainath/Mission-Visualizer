Project Title
: Mission Visualizer

How to Run ->

npm install
npm start

Runs at http://localhost:3000

Key Design Choices ->

Used React + React-Leaflet for fast MVP delivery and clean UI abstraction.

Reprojected datasets to EPSG:4326 (WGS84) for compatibility with web mapping standards.

Separated mission graph into edges and nodes for clarity and independent styling.

Filtered empty geometries to ensure robust rendering.

Implemented layer toggling using Leaflet’s LayersControl.

Auto-fit map to park boundary for better UX.

Assumptions ->

Infrastructure layer contained empty geometries and was excluded.

Preprocessed CRS offline instead of runtime reprojection for simplicity.


What I Would Improve With More Time ->

Backend service for mission upload & validation.

Real-time robot telemetry integration.

Mission validation logic.

Fleet-level overview dashboard.

OTA update interface simulation.

Better mission styling.

Performance optimization for large datasets.
