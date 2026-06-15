# Weather App

A simple and responsive weather application that allows users to search for any city and view real-time weather information, including temperature, humidity, wind speed, and weather conditions. The application fetches live data from a weather API and presents it through a clean and user-friendly interface.

## Features

- Search weather by city name
- View current temperature
- Check humidity levels
- Display wind speed
- Dynamic weather condition icons
- Responsive design for desktop and mobile devices
- Error handling for invalid city names

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap API

## Demo

Add your deployed application link here:

```text
https://your-weather-app-demo-link.com
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/JAHANVI88/weather-app.git
```

2. Navigate to the project directory:

```bash
cd weather-app
```

3. Obtain an API key from OpenWeatherMap.

4. Add your API key in the JavaScript file:

```javascript
const apiKey = "YOUR_API_KEY";
```

5. Open `index.html` in your browser or run the project using a local server.

## Usage

1. Enter the name of a city in the search field.
2. Click the search button.
3. View the current weather details for the selected location.

## Project Structure

```text
weather-app/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── clear.png
│   ├── clouds.png
│   ├── rain.png
│   ├── snow.png
│   └── mist.png
│
└── README.md
```

## API Reference

This project uses the OpenWeatherMap Current Weather API.

Example request:

```http
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

Example response:

```json
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
```

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with REST APIs
- Fetching and handling JSON data
- Using asynchronous JavaScript (Async/Await)
- DOM manipulation
- Event handling
- Responsive web design
- Error handling and user feedback

## Future Enhancements

- Current location weather using Geolocation API
- 5-day weather forecast
- Dark mode support
- Weather alerts
- Search history
- Multiple language support

## Contributing

Contributions are welcome. Feel free to fork the repository, create a new branch, and submit a pull request.

## Author

**Jahanvi Bagjani**

- GitHub: https://github.com/JAHANVI88
- LinkedIn: https://www.linkedin.com/in/jahanvi-bagjani-400390314

## License

This project is licensed under the MIT License.

---

If you found this project useful, consider giving it a star ⭐ on GitHub.
