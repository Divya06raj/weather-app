  # 🌤️ Weather App - Real-time Weather Information

A beautiful, feature-rich weather application that provides real-time weather data and 5-day forecasts for any location worldwide.

## ✨ Features

- **Real-time Weather Data** - Get current weather conditions instantly
- **5-Day Forecast** - Plan ahead with accurate weather predictions
- **Auto-location Detection** - Automatically detects your location
- **City Search** - Search weather for any city worldwide                                                                                                         
- **Recent Searches** - Quick access to previously searched cities
- **Detailed Weather Info** - Temperature, humidity, wind speed, pressure, visibility, UV index
- **Dynamic Backgrounds** - Background changes based on weather conditions
- **Responsive Design** - Works perfectly on all devices (mobile, tablet, desktop)
- **Beautiful UI** - Modern, clean interface with smooth animations

## 🚀 Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with animations and responsive design
- **Vanilla JavaScript** - No frameworks, pure JS for better performance
- **OpenWeatherMap API** - Weather data provider
- **Geolocation API** - Auto-detect user location
- **LocalStorage** - Save recent searches

## 📦 Setup Instructions

### 1. Get API Key (FREE)

1. Go to [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Go to API Keys section
4. Copy your API key

### 2. Configure the App

1. Open `script.js`
2. Replace `YOUR_API_KEY_HERE` with your actual API key:
   ```javascript
   const API_KEY = 'your_actual_api_key_here';
   ```

### 3. Run Locally

Simply open `index.html` in your browser. That's it!

## 🌐 Deployment Options

### Option 1: Vercel (Recommended)

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   cd "Weather app"
   vercel
   ```

3. Follow the prompts and your app will be live!

### Option 2: Netlify

1. Go to [Netlify](https://www.netlify.com/)
2. Drag and drop your "Weather app" folder
3. Your app is live instantly!

### Option 3: GitHub Pages

1. Create a GitHub repository
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin your-repo-url
   git push -u origin main
   ```
3. Go to Settings → Pages → Select main branch → Save
4. Your app will be live at `https://yourusername.github.io/repo-name`

## 📱 Usage

1. **Auto-location**: Click the location icon to get weather for your current location
2. **Search**: Type any city name and press Enter or click search button
3. **Recent Searches**: Click on any recent city to quickly view its weather
4. **Forecast**: Scroll down to see 5-day weather forecast

## 🎨 Features Breakdown

### Current Weather Display
- City name and country
- Current date
- Temperature (Celsius)
- Weather description with icon
- Feels like temperature
- Humidity percentage
- Wind speed
- Atmospheric pressure
- Visibility distance
- UV index

### 5-Day Forecast
- Daily weather predictions
- Temperature trends
- Weather conditions
- Visual weather icons

### Dynamic Backgrounds
- Clear Sky - Blue gradient
- Clouds - Gray gradient
- Rain/Drizzle - Dark blue gradient
- Thunderstorm - Dark gradient
- Snow - White/gray gradient
- Mist/Fog - Misty gradient

## 🔧 Customization

### Change Temperature Unit
In `script.js`, change `units=metric` to `units=imperial` for Fahrenheit:
```javascript
`${API_BASE}/weather?q=${city}&units=imperial&appid=${API_KEY}`
```

### Modify Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
}
```

## 📊 API Limits

Free OpenWeatherMap API includes:
- 60 calls/minute
- 1,000,000 calls/month
- Current weather data
- 5-day forecast
- UV index

Perfect for personal projects!

## 🐛 Troubleshooting

**Weather not loading?**
- Check if you've added your API key
- Verify API key is active (may take 10 minutes after creation)
- Check browser console for errors

**Location not working?**
- Allow location permission in browser
- Use HTTPS (required for geolocation)

**City not found?**
- Check spelling
- Try with country code: "London, UK"

## 📄 License

Free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to fork, modify, and improve!

## 📞 Support

For issues or questions, check the OpenWeatherMap API documentation or browser console for errors.

---

Made with ❤️ using OpenWeatherMap API
