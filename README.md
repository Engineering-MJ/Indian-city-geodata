# 🇮🇳 Indian City GeoData

📍 A curated JSON dataset of Indian cities with **latitude**, **longitude**, and **state** — perfect for geolocation, mapping, and regional analysis projects.

---

## 📦 Dataset Overview

This dataset contains **100+ Indian cities** in the following format:

```json
{
  "city": "Mumbai",
  "latitude": 18.9667,
  "longitude": 72.8333,
  "state": "Maharashtra"
}
```

| Field      | Type   | Description                  |
|------------|--------|------------------------------|
| `city`     | String | Name of the city             |
| `latitude` | Float  | Latitude coordinate          |
| `longitude`| Float  | Longitude coordinate         |
| `state`    | String | State or union territory     |

---

## 🔍 Use Cases

- 🗺️ Interactive maps (Mapbox, Leaflet, Google Maps)
- 📍 Geolocation-based apps
- 📊 Regional data analysis
- 🧪 Academic projects and research
- 🌐 Location-based filtering or APIs

---

## 📁 Dataset File

- `indian_cities.json` — Main dataset file

---

## 🚀 Usage Examples

### JavaScript

```js
import cities from './indian_cities.json';

cities.forEach(city => {
  console.log(`${city.city}, ${city.state} => ${city.latitude}, ${city.longitude}`);
});
```

### Python

```python
import json

with open('indian_cities.json') as f:
    cities = json.load(f)

for city in cities:
    print(f"{city['city']}, {city['state']} => {city['latitude']}, {city['longitude']}")
```

---

## 🤝 Contributing

Found an issue or want to add more cities?

- 🌟 Star this repo to support it
- 🛠 Submit a pull request with updates
- 🐞 Open an issue for bugs or suggestions
