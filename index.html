<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Weather App</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: "Arial", sans-serif;
        background: linear-gradient(
          45deg,
          #ff7e5f,
          #feb47b,
          #ffcc00,
          #4c6ef5,
          #7a8eeb
        );
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        padding: 20px;
        color: #333;
        text-align: center;
        background-size: 400% 400%;
        animation: gradientAnimation 15s ease infinite;
      }

      @keyframes gradientAnimation {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }

      .weather-container {
        background-color: #ffffff;
        width: 100%;
        max-width: 600px;
        border-radius: 15px;
        box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.1);
        padding: 40px;
        box-sizing: border-box;
      }

      h1 {
        font-size: 2.5rem;
        color: #4c6ef5;
        margin-bottom: 20px;
        font-weight: 700;
      }

      #search-box {
        width: 100%;
        padding: 10px;
        margin-bottom: 20px;
        font-size: 1.2rem;
        border-radius: 5px;
        border: 2px solid #4c6ef5;
      }

      .weather-card {
        background-color: #ffffff;
        border-radius: 15px;
        padding: 20px;
        box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.05);
        text-align: center;
      }

      .weather-card h2 {
        font-size: 1.8rem;
        color: #1e3a8a;
        margin-bottom: 10px;
      }

      .weather-card .temperature {
        font-size: 2.8rem;
        color: #333;
        margin-bottom: 10px;
      }

      .weather-card .description {
        font-size: 1.3rem;
        color: #4b5563;
      }

      .weather-card .wind-speed {
        font-size: 1.2rem;
        margin-top: 10px;
        color: #555;
      }

      .weather-icon {
        width: 60px;
        height: 60px;
        margin-top: 10px;
      }

      .error-message {
        color: red;
        font-size: 1.2rem;
        margin-bottom: 20px;
        display: none;
      }
    </style>
  </head>
  <body>
    <div class="weather-container">
      <h1>Weather App</h1>

      <input type="text" id="search-box" placeholder="Enter city name..." />

      <div id="weather-info"></div>

      <div id="error-message" class="error-message">
        City not found. Please try again.
      </div>
    </div>

    <script>
      const apiKey = "adca9626a1b24ba99e7152524250204"; // Your WeatherAPI key
      const searchBox = document.getElementById("search-box");
      const weatherInfo = document.getElementById("weather-info");
      const errorMessage = document.getElementById("error-message");

      // Fetch weather data based on city name
      async function getWeather(city) {
        const url = `https://api.weatherapi.com/v1/current.json?key=${apiKey}&q=${city}`;

        try {
          const response = await fetch(url);
          const data = await response.json();

          // Handle API error
          if (data.error) {
            errorMessage.style.display = "block";
            weatherInfo.innerHTML = "";
            return;
          }

          // Hide error message if the city is found
          errorMessage.style.display = "none";

          const location = data.location.name;
          const current = data.current;

          // Create HTML to display weather info
          const weatherHTML = `
            <div class="weather-card">
              <h2>${location}</h2>
              <div class="temperature">${current.temp_c}°C</div>
              <div class="description">${current.condition.text}</div>
              <div class="wind-speed">Wind: ${current.wind_kph} kph</div>
              <img src="${current.condition.icon}" alt="${current.condition.text}" class="weather-icon" />
            </div>
          `;

          weatherInfo.innerHTML = weatherHTML;
        } catch (error) {
          console.error(error);
          errorMessage.style.display = "block";
        }
      }

      // Event listener for search input
      searchBox.addEventListener("keyup", (e) => {
        if (e.key === "Enter" && searchBox.value.trim() !== "") {
          getWeather(searchBox.value.trim());
        }
      });
    </script>
  </body>
</html>
