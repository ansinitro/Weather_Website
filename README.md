# Weather App

This Weather App provides current weather, 3-hour forecast, 14-day extended forecast and city-related information for cities around the world.
The app defaults to displaying weather information for London on the first visit. Users can then input their preferred city.

### Prerequisites

Before you begin, ensure you have the following installed: 
- Node.js 
-  npm (Node Package Manager)

### Run Website

```bash
git clone https://github.com/AnsiLucky/Weather_Website
cd Weather_Website
npm install
node root.js
```
by default server will start at `http://localhost:3000`

## APIs Used

1.  **OpenWeatherMap API**
    -   Endpoint: `http://api.openweathermap.org/data/2.5/forecast`
    -   Usage: Weahter Info 
2.  **WeatherAPI**
    -   Endpoint: `http://api.weatherapi.com/v1/forecast.json`
    -   Usage: Weahter Info 
3.  **City Info API**
    -   Endpoint: `https://api.api-ninjas.com/v1/city`
    -   Usage: City Info 
    
4.  **Source Unsplash API**
    -   Endpoint: `https://source.unsplash.com/1600x900`
    -   Usage: Random Photos from city
    


