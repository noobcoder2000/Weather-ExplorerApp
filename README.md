<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
  <h1>Weather Explorer App</h1>

  <h2>Features</h2>
  <ul>
    <li>Search for weather data of any location by entering the city or place name.</li>
    <li>View real-time weather information, including temperature in Fahrenheit and Celsius, humidity, and wind speed.</li>
    <li>Beautiful background image that changes based on the weather conditions.</li>
    <li>Responsive design that adapts to different screen sizes.</li>
  </ul>

  <h2>How to Use</h2>
  <ol>
    <li>Clone or download this repository to your local machine.</li>
    <li>Open the project in your preferred code editor.</li>
    <li>In the terminal, navigate to the project directory.</li>
    <li>Install the project dependencies by running:<br>
      <code>npm install</code>
    </li>
    <li>Get an API key from OpenWeatherMap by signing up on their website (https://openweathermap.org/) and obtaining
      the API key.</li>
    <li>Create a new file named <code>.env</code> in the root directory of the project and add the following line:<br>
      <code>REACT_APP_API_KEY=your_api_key_here</code></li>
    <li>Replace <code>your_api_key_here</code> with the API key obtained from OpenWeatherMap.</li>
    <li>Save the <code>.env</code> file.</li>
    <li>Start the development server by running:<br>
      <code>npm start</code></li>
    <li>The app will be running at <code>http://localhost:3000</code> in your web browser.</li>
    <li>Enter the name of a city or place in the search bar and press the "Enter" key.</li>
    <li>Weather information for the entered location will be displayed, including temperature, humidity, and wind speed.</li>
  </ol>

  <h2>Technologies Used</h2>
  <ul>
    <li>React: Frontend JavaScript library for building user interfaces.</li>
    <li>Axios: HTTP client used to make API requests to OpenWeatherMap.</li>
    <li>OpenWeatherMap API: Used to fetch real-time weather data based on the user's search.</li>
  </ul>

  <h2>Acknowledgments</h2>
  <p>The background image is sourced from Unsplash (https://unsplash.com/) and is used for illustrative purposes only.</p>

  <h2>Contributing</h2>
  <p>Contributions to this project are welcome. If you find any bugs or want to add new features, feel free to open an
    issue or submit a pull request.</p>

  <h2>License</h2>
  <p>This project is licensed under the MIT License - see the <a href="./LICENSE">LICENSE</a> file for details.</p>
</body>

</html>
