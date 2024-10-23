Real-Time Tracker
![Screenshot 2024-10-23 124656](https://github.com/user-attachments/assets/b28126f9-fab4-4d35-9a81-8d72757f679a)
Overview
Welcome to the Real-Time Location Tracking project! This web application is designed for real-time location tracking and monitoring. It utilizes WebSocket technology to provide real-time updates, displaying the location of tracked entities on a map. All connected users can view everyone's location on the map in real-time.

Features
Real-time Location Updates: Uses WebSocket technology for instant location updates.
Interactive Map: Displays locations on an interactive map using OpenStreetMap and Leaflet.js.
Multi-user Support: Multiple connected users can view locations simultaneously.
Technologies Used
JavaScript: The programming language used for both client-side and server-side logic.
Node.js: JavaScript runtime built on Chrome's V8 JavaScript engine.
Express.js: A fast, unopinionated, minimalist web framework for Node.js.
Socket.IO: Enables real-time, bidirectional communication between the server and clients.
OpenStreetMap: Provides the map data.
Leaflet.js: An open-source JavaScript library for mobile-friendly interactive maps.
Installation
Clone the repository:
git clone https://github.com/yourusername/realtime-tracker.git
Navigate to the project directory:
cd realtime_location_tracker
Install the dependencies:
npm install
Usage
Start the server:
node app.js
Open your web browser and go to http://localhost:3000 to view the application.
