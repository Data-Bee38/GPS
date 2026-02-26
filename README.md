Browser-Based GPS Navigation App
A lightweight, real-time navigation system built with Leaflet and OpenStreetMap, delivering modern GPS functionality directly in the browser — no native app required.

✨ Features
🗺 Interactive Mapping

Dynamic route rendering

Responsive bottom navigation panel

Custom route styling

Recenter map functionality

🚦 Turn-by-Turn Navigation

Step-by-step maneuver instructions

Cleaned & merged routing steps

Active maneuver header

Navigation lifecycle management

📍 Live GPS Tracking

Real-time user location updates

Continuous route progress monitoring

Smart rerouting support

Smooth map recentering

⏱ Live ETA Engine

Remaining distance calculation

Real-time arrival updates

Smart duration formatting (hrs/min)

Miles conversion

Time zone–aware arrival time display

🌎 Time Zone Intelligence

Automatic destination time zone detection

DST-aware ETA formatting

Time zone abbreviation display (PST, MST, etc.)

“X hours ahead/behind” alert system

📱 Mobile-Optimized UX

Keyboard-triggered route search (Enter key)

Auto keyboard dismissal on mobile

Map-centered loading spinner overlay

Responsive UI design

🛠 Built With

Leaflet.js – Interactive maps

OpenStreetMap – Map tile data

OSRM Routing API – Route calculations

Vanilla JavaScript – Core logic

Nominatim – Geocoding service

🚀 How It Works

User enters a starting and destination address.

Addresses are geocoded using Nominatim.

Route data is fetched from the OSRM routing service.

Route polyline is rendered on the map.

Turn-by-turn steps are cleaned and displayed.

ETA and arrival time are calculated (time zone aware).

Live GPS tracking updates distance and progress.

🧠 Technical Highlights

Promise-based geocoding and routing flow

Cleaned maneuver merging logic

Dynamic panel height adjustments

Custom map markers

Overlay-based loading system

Time zone comparison engine

Real-time ETA recalculation loop
