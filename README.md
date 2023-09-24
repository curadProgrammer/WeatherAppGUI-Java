<h1>Weather App GUI</h1>
<h2>Introduction</h2>
<p>
    The Weather App is a Java-based application that provides users with real-time weather information for a specified location. It fetches weather data from an external API and displays it in a graphical user interface (GUI). Users can enter a location, and the app retrieves and 
    presents weather details, including temperature, weather condition, humidity, and wind speed. This documentation outlines the project's architecture, technologies used, and the functionality of each class within the application.
</p>

<p>
    You can check out the full tutorial where I will guide and you and explain the steps in this YouTube video: <a href="https://www.youtube.com/watch?v=8ZcEYv2ezWc">link</a>
</p>

<p align="center">
    <img src="https://github.com/curadProgrammer/WeatherAppGUI-Java/blob/main/Screenshot_15.png?raw=true" align="center">
</p>

<h2>Technologies Used</h2>
<p>
    The Weather App utilizes the following technologies and libraries:
</p>
<ul>
  <li>Java 18</li>
  <li><a href="https://code.google.com/archive/p/json-simple/downloads">JSON Simple</a> - Used to parse and read through JSON data</li>
  <li><a href="https://docs.oracle.com/en/java/javase/11/docs/api/java.net/java/net/HttpURLConnection.html">HTTPURLConnection</a>: Java's built-in library for making HTTP requests to fetch data from external APIs.</li>
</ul>

<h2>Class Summaries</h2>

<h3>3.1. AppLauncher</h3>
<p>
    <strong>Description:</strong> The AppLauncher class serves as the entry point for the Weather App. It initializes the GUI and displays the main application window.
</p>

<h3>3.2. WeatherAppGui</h3>
<p>
    <strong>Description:</strong> The WeatherAppGui class represents the graphical user interface (GUI) of the Weather App. It is responsible for displaying weather information for a specified location.
</p>
<p>
    <strong>Summary:</strong> This class handles the layout and display of GUI components, including text fields, labels, buttons, and images. It also implements the user interface for entering a location and updating the weather information based on user input.
</p>

<h3>3.3. WeatherApp</h3>
<p>
    <strong>Description:</strong> The WeatherApp class contains the backend logic for fetching weather data from an external API. It retrieves geographic coordinates for a location, fetches weather data for that location, and provides methods to convert weather codes.
</p>
<p>
    <strong>Summary:</strong> This class encapsulates the core functionality of the Weather App. It includes methods to fetch weather data and location coordinates, convert weather codes into readable weather conditions, and manage API requests. This class acts as the bridge between the GUI and the external weather data source, ensuring that weather information is retrieved and displayed accurately.
</p>
