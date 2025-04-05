# Eco Nexus - Energy Management and Monitoring System

## Map Visualization with Leaflet

The application uses Leaflet for map visualizations, providing a rich and interactive experience for exploring energy data:

- **Open-source mapping:** Leaflet provides a fully-featured open-source alternative to Google Maps, with no API key required
- **Multiple map views:** Switch between street, satellite, topographic, and dark mode views
- **Heat map visualization:** View energy consumption intensity across regions
- **Machine parts analysis:** Locate faulty equipment and get detailed diagnostics
- **Power issue detection:** Identify areas with power outages or high voltage issues
- **3D visualization:** View energy consumption with a 3D perspective
- **Disaster mode:** Special visualization mode to identify critical issues during emergencies

To use the map features, navigate to the Disaster Monitoring page and explore the various visualization options.

## Setting up Google Maps API Key

The heat map feature requires a Google Maps API key to work properly. Follow these steps to set it up:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project (or select an existing one)
3. Navigate to "APIs & Services" > "Library"
4. Enable the following APIs:
   - Maps JavaScript API
   - Places API
   - Geocoding API

5. Go to "APIs & Services" > "Credentials"
6. Click "Create Credentials" > "API Key"
7. Copy your new API key
8. Create a `.env` file in the root directory of the project
9. Add the following line to your `.env` file:
   ```
   VITE_GOOGLE_MAPS_API_KEY=YOUR_GOOGLE_MAPS_API_KEY
   ```
   (Replace `YOUR_GOOGLE_MAPS_API_KEY` with the key you copied)

10. Restart the development server if it's already running

**Important:** For production usage, make sure to restrict your API key to only the domains you'll be using.

## Running the Application

To run the application:

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

## Features

The application includes:

- Real-time energy consumption monitoring
- Heat map visualization of energy usage
- Machine parts fault detection
- Disaster management and power outage tracking
- Equipment health monitoring
- Before/after disaster comparison
# EcoNexus
# Econexusx
