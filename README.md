# 🌍 Geo Planner AI Agent Assistant

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Google Maps API](https://img.shields.io/badge/Google%20Maps-API-green.svg)](https://developers.google.com/maps)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![Agent Tool blog: blog]((https://multimodal-geminiai.blogspot.com/2025/11/google-kaggle-ai-agents-intensive.html))](https://multimodal-geminiai.blogspot.com/2025/11/google-kaggle-ai-agents-intensive.html)

A lightweight Python assistant that integrates with **Google Geocoding API** and **Google Places API (v1)** to provide geospatial intelligence.  
It can geocode locations, search nearby places, and return structured results such as names, addresses, and ratings — perfect for AI agents, data pipelines, or location-aware applications.


![Google Maps AI Agent](https://github.com/VijayaJothi24/Google-Kaggle-AI-Agents-Intensive-Project/blob/main/GOOGLEMAPS%20AI%20AGENT.jpeg)


---

## ✨ Features
- 🔎 Convert addresses into latitude/longitude using Geocoding API.
- 📍 Search nearby places with Places API (v1).
- 🍽️ Filter by type (restaurants, cafes, shops, etc.).
- ⭐ Retrieve ratings and formatted addresses.
- ⚡ Simple Python function for easy integration.

---

## 📦 Requirements
- Python 3.8+
- `requests` library
- Google Cloud API key with:
  - Geocoding API enabled
  - Places API enabled

    
🌐 Acknowledgements


Google Maps Geocoding API

Google Places API (New)




[![Agent Tool blog: blog]((https://multimodal-geminiai.blogspot.com/2025/11/google-kaggle-ai-agents-intensive.html))](https://multimodal-geminiai.blogspot.com/2025/11/google-kaggle-ai-agents-intensive.html)



Install dependencies:
```bash

🔑 Setup
1.Create a Google Cloud project and enable Geocoding API and Places API.

2.Generate an API key from the Google Cloud Console.

3.Store your API key securely as an environment variable:

export GOOGLE_API_KEY="your_api_key_here"

flowchart TD
    A[User Input: Query + Location] --> B[Geocoding API]
    B -->|Returns Lat/Lng| C[Places API: searchNearby]
    C -->|Returns Places Data| D[Assistant Processing]
    D --> E[User Output: Name, Address, Rating]
