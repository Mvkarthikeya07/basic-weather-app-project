# 🌤️ Weather App

A clean, no-nonsense desktop weather app. Type a city, hit a button, get real-time conditions — no clutter, no ads, no fluff.

## Features
- Live weather data via the OpenWeatherMap API
- Temperature, condition, humidity, and wind speed at a glance
- Minimal Tkinter GUI — fast to launch, easy to read
- Graceful error handling for invalid cities or connection issues

## Tech Stack
`Python` · `Tkinter` · `Requests` · `OpenWeatherMap API`

## Run It
```bash
pip install requests
python weather_app.py
```

## Setup
Grab a free API key from [OpenWeatherMap](https://openweathermap.org/api) and set it as an environment variable rather than hardcoding it:
```python
api_key = os.environ.get("OWM_API_KEY")
```

## Roadmap
- [ ] 5-day forecast view
- [ ] Auto-detect location
- [ ] °C / °F toggle

---
*Simple input. Instant answer. That's the whole point.*
