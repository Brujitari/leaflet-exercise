# Leaflet-exercise 🗺️

In this challenge you'll need to use the map from [leafletjs](https://leafletjs.com/) to print in real time the public transport of Los Angeles.

## Tasks 📝

After have installed and initialized leaflet in your `index.js` you have to:

- Center the map in Los Angeles, here the coordinates: `[34.052235, -118.243683]`.
- Use the [Metro’s Realtime API](https://api.metro.net/agencies/lametro/vehicles/) you have to display the Los Angeles public transport in the map by making petitions to this endpoint `https://api.metro.net/vehicle_positions/bus?output_format=json`. 🚌

## Bonus 🏆
Create a code to refresh each `10` seconds and retrieve the new positions of the public transports and with a popup, display the ID of the vehicle.
