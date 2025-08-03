# Dynamic Weather Dashboard

![Weather Dashboard Showcase](https://placehold.co/1200x600/6b7280/f9fafb?text=Weather+Dashboard)

A stunning, single-page weather application that provides real-time weather data with a dynamic, theme-changing UI and an interactive 3D globe. This project demonstrates modern front-end development techniques using vanilla JavaScript to create a rich, API-driven user experience.

---

## Features

- **Dynamic Theming:** The entire UI color scheme elegantly transitions to match the current weather conditions (e.g., sunny, rainy, night).
- **Interactive Globe:** An animated globe, built with D3.js, rotates and zooms to the currently selected location, providing a polished and engaging visual centerpiece.
- **Location Search:** Users can search for any city worldwide to get instant weather updates.
- **Geolocation:** Automatically detects the user's location on page load for immediate, relevant weather data.
- **Detailed Forecasts:**
    - Current weather conditions with temperature, humidity, wind speed, UV index, and more.
    - An interactive 24-hour forecast chart powered by Chart.js.
    - A clean 5-day forecast summary.
- **Fully Responsive:** A seamless experience across desktops, tablets, and mobile devices.

---

## Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure for the application. |
| **Tailwind CSS** | For a modern, utility-first, and responsive design. |
| **Vanilla JavaScript** | To handle all logic, API calls, DOM manipulation, and interactivity. |
| **D3.js** | To render the interactive and animated 2D globe projection. |
| **Chart.js** | For the beautiful and responsive hourly forecast line chart. |
| **Open-Meteo API** | Provides free, keyless access to global weather forecast and geocoding data. |

---

## How to Use

This project is a single, self-contained HTML file with no build step required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/weather-dashboard.git](https://github.com/your-username/weather-dashboard.git)
    cd weather-dashboard
    ```
2.  **Open the file:**
    - Simply open the `index.html` file in your favorite web browser.
    - **Note:** Your browser will ask for permission to access your location. Click **"Allow"** for the best initial experience.

---

## License

This project is licensed under the MIT License.
