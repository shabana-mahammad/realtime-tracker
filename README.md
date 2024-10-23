# Real-Time Device Tracker

![Real-Time Device Tracker](https://github.com/user-attachments/assets/b28126f9-fab4-4d35-9a81-8d72757f679a)

## Overview

Welcome to the **Real-Time Device Tracker** project! This web application allows users to monitor and track devices' locations in real-time. Utilizing **WebSocket** technology, it provides instantaneous updates and displays all tracked devices on an interactive map. The map is shared among all users, allowing them to view the location of all connected devices in real-time.

## Features

- **Real-Time Location Updates**: Leverages **WebSocket** technology for instant, real-time updates.
- **Interactive Map**: Displays device locations on an interactive map powered by **OpenStreetMap** and **Leaflet.js**.
- **Multi-User Support**: Multiple users can view real-time location updates on the same map.
  
## Technologies Used

- **JavaScript**: The main programming language for both frontend and backend.
- **Node.js**: The runtime environment for server-side operations.
- **Express.js**: A lightweight web framework for building the backend.
- **Socket.io**: A library that enables real-time, bidirectional communication between the server and clients.
- **OpenStreetMap**: Provides the map data for rendering.
- **Leaflet.js**: A JavaScript library for mobile-friendly, interactive maps.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/realtime-tracker.git
    ```
   
2. **Navigate to the project directory**:
    ```bash
    cd realtime_tracker
    ```

3. **Install the dependencies**:
    ```bash
    npm install
    ```

## Usage

1. **Start the server**:
    ```bash
    node app.js
    ```

2. **Open your web browser** and navigate to:
    ```
    http://localhost:3000
    ```

Once the server is running, the map will be displayed, and real-time device locations will be updated as devices connect.



