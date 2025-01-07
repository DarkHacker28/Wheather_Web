# Weather Web Application

A responsive weather web application that provides real-time weather updates. Built using HTML, CSS, and JavaScript, the application features dynamic UI elements, custom fonts, and weather icons.

# Features

Real-Time Weather Data: Fetches live weather data using an API.
Responsive Design: Optimized for mobile, tablet, and desktop screens.
Custom Fonts and Icons: Uses modern web fonts and weather-specific icons.
User-Friendly Interface: Intuitive design for seamless navigation.


#Tech Stack

HTML: Structure of the web application.
CSS: Styling and responsiveness.
JavaScript: Fetching weather data and updating the UI dynamically.
Icons: Weather icons for different conditions (e.g., sunny, rainy).
Fonts: Custom web fonts for a modern look and feel.


# Setup Instructions

Prerequisites
Ensure you have the following installed on your system:

A modern web browser (e.g., Chrome, Firefox, Edge).
Code editor (e.g., Visual Studio Code).
Internet connection for API calls.

Steps
Clone the repository:

git clone https://github.com/your-username/weather-web-app.git
cd weather-web-app

Open the Project:

Open the index.html file in your preferred browser to preview the app.

Live Server (Optional):

For a better development experience, use a live server (e.g., the Live Server extension in VS Code).

# API Integration

This project uses the OpenWeatherMap API to fetch weather data. To integrate:

Sign up on OpenWeatherMap to get your API key.

Replace YOUR_API_KEY in script.js with your actual API key:

javascript
Copy code
const apiKey = "YOUR_API_KEY";
Fonts and Icons
Fonts
Add your custom fonts in the assets/fonts folder.

Reference the fonts in styles.css:

@font-face {
    font-family: 'CustomFont';
    src: url('./assets/fonts/custom-font.woff2') format('woff2');
}
body {
    font-family: 'CustomFont', sans-serif;
}

Icons
Store weather icons in assets/icons folder.

Dynamically load icons in script.js:
javascript
Copy code
const iconPath = `./assets/icons/${weatherCondition}.svg`;
document.getElementById('weather-icon').src = iconPath;


# Contributing

Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a new branch:

git checkout -b feature-name
Commit your changes:

git commit -m "Add feature description"
Push to the branch:

git push origin feature-name
Create a Pull Request.

Acknowledgments
OpenWeatherMap API
FontAwesome Icons
Google Fonts
Feel free to customize this README to suit your specific project details. Let me know if you need help refining it further!
