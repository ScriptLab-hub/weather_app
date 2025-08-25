# Weather Card Web Application

A simple, clean, and dynamic weather card application that displays real-time weather information for any city in the world. The user interface dynamically changes its background and icons based on the current weather conditions.

 <!-- You can replace this with a screenshot of your project -->

## Features

- **Live Weather Data:** Fetches and displays current temperature, high/low temperatures, wind speed, humidity, and rain volume.
- **City Search:** Allows users to search for weather information for any city.
- **Dynamic UI:** The background image and weather icon change according to the weather conditions (e.g., Clear, Clouds, Rain, Snow).
- **Glassmorphism Design:** A modern and visually appealing "frosted glass" effect on the card elements.
- **Real-time Clock:** Displays the current date and time, updated every second.
- **Responsive:** Built with Tailwind CSS, the layout is suitable for various screen sizes.

## Technologies Used

- **HTML5:** For the basic structure of the web page.
- **CSS3:** For custom styles like the glass effect and background transitions.
- **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
- **JavaScript (ES6+):** For application logic, API fetching, and DOM manipulation.
- **OpenWeatherMap API:** To source the real-time weather data.

## How to Use

This is a single-file project, making it very easy to set up and run.

1.  **Get an API Key:**
    - Go to OpenWeatherMap and sign up to get your free API key.

2.  **Update the API Key in the Code:**
    - Open the `card.html` file.
    - Find the `fetchWeather` function in the `<script>` section.
    - Replace the placeholder API key with your own:
      ```javascript
      const apiKey = "YOUR_API_KEY_HERE"; 
      ```

3.  **Run the Application:**
    - Simply open the `card.html` file in your web browser (like Chrome, Firefox, or Edge).

That's it! The application will load with the default weather for London. You can then search for any other city.

## Code Structure

All the code—HTML, CSS, and JavaScript—is contained within the `card.html` file.

- The **HTML** section defines the structure of the header, main weather card, and footer.
- The **CSS** is located in the `<style>` block and uses a combination of custom styles for the background and glass effect, along with Tailwind CSS classes for layout and styling.
- The **JavaScript** is located in the `<script>` block at the end of the body. It handles API calls, updates the UI, manages event listeners for the search functionality, and runs the live clock.

## Credits

This project was created by **Kamran Zafar** as part of the SMIT Assignment.
