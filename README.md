Real-Time Device Tracker
![Screenshot 2024-10-23 124656](https://github.com/user-attachments/assets/cb2792fd-1217-4f7c-812b-9c89a66b39f8)

Overview
Welcome to the Real-Time Device Tracker project! This web application allows users to monitor and track devices' locations in real-time. Utilizing WebSocket technology, it provides instantaneous updates and displays all tracked devices on an interactive map. The map is shared among all users, allowing them to view the location of all connected devices in real time.

Features
Real-Time Location Updates: Leverages WebSocket technology for instant, real-time updates.
Interactive Map: Displays device locations on an interactive map powered by OpenStreetMap and Leaflet.js.
Multi-User Support: Multiple users can view real-time location updates on the same map.

Technologies Used
JavaScript: The main programming language for both frontend and backend.
Node.js: The runtime environment for server-side operations.
Express.js: A lightweight web framework for building the backend.
Socket.io: A library that enables real-time, bidirectional communication between the server and clients.
OpenStreetMap: Provides the map data for rendering.
Leaflet.js: A JavaScript library for mobile-friendly, interactive maps.

Installation
To run this project locally, follow these steps:
Clone the repository:
git clone https://github.com/yourusername/realtime-tracker.git
Navigate to the project directory:
cd realtime_tracker
Install the dependencies:
npm install

Usage
Start the server:
node app.js
Open your web browser and navigate to:
http://localhost:3000
Once the server is running, the map will be displayed, and real-time device locations will be updated as devices connect.
