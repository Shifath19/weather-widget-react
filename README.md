# Weather App

A beautiful weather application built with React and TypeScript. Get real-time weather information with an immersive user interface featuring glassmorphism design.


## Features

- 🌡️ Real-time weather data
- 🔍 City search functionality
- 💨 Wind speed and direction
- 💧 Humidity levels
- 🌡️ "Feels like" temperature
- ☀️ UV index
- 🎨 Glassmorphism UI design
- 📱 Fully responsive

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- WeatherAPI.com
- Axios
- Lucide React

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your WeatherAPI.com API key:
```env
VITE_WEATHER_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

## Project Structure

```
src/
├── components/
│   └── WeatherCard.tsx
├── types/
│   └── weather.ts
├── App.tsx
├── main.tsx
└── index.css
```

## Environment Variables

- `VITE_WEATHER_API_KEY` - Your WeatherAPI.com API key



## Acknowledgments

- Weather data provided by [WeatherAPI.com](https://www.weatherapi.com/)
- Icons by [Lucide](https://lucide.dev/)
- Background image from [Unsplash](https://unsplash.com/)
