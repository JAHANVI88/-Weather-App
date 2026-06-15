# -Weather-App
A modern and responsive Weather Application that provides real-time weather information for any city worldwide. The app fetches live weather data using a weather API and displays essential weather details in an intuitive user interface.
.

📌 Features
🔍 Search weather by city name
🌡️ Real-time temperature display
💧 Humidity information
🌬️ Wind speed details
☁️ Weather conditions with icons
📱 Fully responsive design
⚡ Fast and user-friendly interface
🌍 Supports weather lookup for cities worldwide
🛠️ Tech Stack
Frontend
HTML5
CSS3
JavaScript (ES6+)
API
OpenWeatherMap API (or your chosen weather API)
📂 Project Structure
Weather-App/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── clear.png
│   ├── clouds.png
│   ├── rain.png
│   ├── snow.png
│   ├── mist.png
│   └── wind.png
│
└── README.md
🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/weather-app.git
2. Navigate to the Project Folder
cd weather-app
3. Get an API Key
Create an account on OpenWeatherMap.
Generate your API key.
Open script.js.
Replace the placeholder API key:
const apiKey = "YOUR_API_KEY";

with:

const apiKey = "YOUR_ACTUAL_API_KEY";
4. Run the Application

Simply open:

index.html

in your browser.

📸 Screenshots
Home Page
Search City → Fetch Weather → Display Results

Add screenshots here:

![Weather App Screenshot](screenshots/weather-app.png)
🔧 How It Works
User enters a city name.
Application sends a request to the weather API.
API returns current weather data.
App extracts relevant information.
Weather details are displayed dynamically on the screen.
📊 Example Response
{
  "name": "London",
  "main": {
    "temp": 18.5,
    "humidity": 72
  },
  "wind": {
    "speed": 4.3
  },
  "weather": [
    {
      "main": "Clouds"
    }
  ]
}
🌟 Future Enhancements
📍 Current location weather
🌅 Sunrise and sunset timings
📅 7-day weather forecast
🌎 Weather maps integration
🌙 Dark/Light mode toggle
🔔 Severe weather alerts
