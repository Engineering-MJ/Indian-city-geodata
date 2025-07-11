# Indian-city-geodata
: 📍 A comprehensive JSON dataset of Indian cities with latitude, longitude, and state information — ideal for geolocation, mapping, and regional analysis projects.


# 🇮🇳 Indian Cities Geolocation Dataset

A high-quality, ready-to-use dataset of **Indian cities**, including **latitude**, **longitude**, and **state** — perfect for developers, researchers, data analysts, and geospatial apps.

---

## 📂 What’s Inside?

This JSON dataset includes 100+ Indian cities in the following format:

json
{
  "city": "Mumbai",
  "latitude": 18.9667,
  "longitude": 72.8333,
  "state": "Maharashtra"
}
Field	Type	Description
city	String	City name
latitude	Float	Latitude coordinate
longitude	Float	Longitude coordinate
state	String	State or union territory

📊 Use Cases
🗺️ Map visualizations (Mapbox, Leaflet, Google Maps)

📍 Geolocation services

📊 Data analytics & regional insights

🧪 Research & education

🌐 Location-based filtering & APIs

📁 Dataset File
indian_cities.json — Main dataset file

🚀 Usage Examples
JavaScript
js
Copy
Edit
import cities from './indian_cities.json';

cities.forEach(city => {
  console.log(`${city.city}, ${city.state} => ${city.latitude}, ${city.longitude}`);
});
Python
python
Copy
Edit
import json

with open('indian_cities.json') as f:
    cities = json.load(f)

for city in cities:
    print(f"{city['city']}, {city['state']} => {city['latitude']}, {city['longitude']}")

🤝 Contributing
Spotted an issue or want to add more cities?

🌟 Star this repo

🛠 Submit a pull request

🐞 Open an issue

