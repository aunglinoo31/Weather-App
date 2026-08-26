# 🌤️ Weather App

A sleek, responsive, and real-time weather application that provides up-to-date meteorological data for cities worldwide. Built using vanilla web technologies and powered by the official **OpenWeather API**.

## 🚀 Features

*   **Real-Time Data:** Displays temperature, city name, humidity levels, and wind speeds instantly.
*   **Dynamic Autocomplete:** Fetches live city suggestions via the OpenWeather Geocoding API as you type.
*   **Visual Enhancements:** Features a custom built-in CSS loading spinner during live search queries.
*   **Intuitive UI/UX:** Responsive card layout with adaptive weather icons reflecting real weather conditions (Clouds, Clear, Rain, Drizzle, Mist, Snow).
*   **Multi-Input Support:** Trigger searches seamlessly by either clicking the search icon or pressing the `Enter` key.
*   **Performance Optimized:** Implements debounce functionality (300ms delay) to limit redundant network traffic and save API request quotas.
*   **Graceful Error Handling:** Clearly alerts users if an invalid city name is queried.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3 (Custom Animations & Keyframes)
*   **Scripting:** Vanilla JavaScript (ES6+, Async/Await Fetch API)
*   **External API:** [OpenWeather Map API](https://openweathermap.org/) (Current Weather & Geocoding endpoints)

## 📂 Project Structure

```text
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   ├── snow.png
│   └── wind.png
├── index.html
├── style.css
└── README.md
```

## ⚙️ Setup and Installation

Follow these steps to run the project locally on your machine:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd weather-app
    ```
3.  **Get a Free API Key:**
    *   Sign up at [OpenWeather Map](https://home.openweathermap.org/users/sign_up).
    *   Generate a free API key from your account dashboard.
4.  **Configure your API Key:**
    *   Open `index.html`.
    *   Locate the `apiKey` variable in the `<script>` tag:
        ```javascript
        const apiKey = "YOUR_API_KEY_HERE";
        ```
    *   Replace `"YOUR_API_KEY_HERE"` with your actual unique OpenWeather token.
5.  **Launch the Application:**
    *   Open the `index.html` file directly in any modern web browser, or serve it using an extension like **Live Server** in VS Code.

