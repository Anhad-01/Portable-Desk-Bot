# Portable Desk Bot

A smart desk assistant powered by ESP32 with an OLED display that keeps you company while providing useful information.

## Features

### Animated Eyes
- Physics-based eye animation with smooth movement
- Pupils that follow saccade patterns
- Realistic blinking at random intervals
- Breathing animation for a lifelike feel

### Weather Information
- Current temperature and feels-like temperature
- Humidity levels
- Weather condition with animated icons (Clear, Clouds, Rain, etc.)
- 3-day weather forecast

### Mood System
The desk bot's personality changes based on weather conditions:
- **Happy** - Clear skies
- **Sad** - Rainy weather
- **Surprised** - Thunderstorms
- **Excited** - Hot temperatures (>25°C)
- **Sleepy** - Cold temperatures (<5°C)
- **Normal** - Cloudy or mild weather

### Interactive Controls
- **Single tap** - Switch between screens
- **Double tap** - Toggle display brightness (high/low)
- **Long press** - Change mood or skip to specific screens

### Multiple Display Screens
- Eyes screen with animated expressions
- Current weather with detailed information
- Weather forecast for the next 3 days

### Setup Portal
- Built-in web configuration portal for WiFi and API settings
- Configure OpenWeatherMap API key, location, and timezone
- Access via local hotspot when setting up

## Hardware
- ESP32 microcontroller
- 128x64 OLED display (SH1106)
- Touch sensor
- I2C connectivity

## Getting Started
1. Copy `secrets.h.example` to `secrets.h`
2. Fill in your WiFi credentials and OpenWeatherMap API key
3. Upload the sketch to your ESP32
4. The bot will automatically connect and start displaying information

## Future Enhancements
- Web configuration portal for easy setup without code changes
- Additional screens and features
