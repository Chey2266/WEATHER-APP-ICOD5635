# Weather-App-ICOD5635

TITLE: CODTECH IT SOLUTIONS Internship - Task Documentation: "To-Do LIST" Using HTML, CSS and JAVASCRIPT.

INTERN INFORMATION: Name: Chaitanya Mulaka ID: ICOD5635

INTRODUCTION

The Weather App is a web-based application designed to provide users with real-time weather information based on their location input. Developed using HTML, CSS, and JavaScript, the Weather App fetches weather data from the OpenWeatherMap API and displays it in a user-friendly interface. This documentation will cover the various aspects of the Weather App, including its features, functionality, design, and implementation details.

FEATURES

Location Search: Users can enter their location in the search box to retrieve weather information for that specific area.
Dynamic Weather Display: The app dynamically updates the weather information based on the user's input, including temperature, weather condition, humidity, and wind speed.
Responsive Design: The Weather App is designed to be responsive, ensuring optimal user experience across different devices and screen sizes.
Error Handling: In case the entered location is not found or the API request fails, the app displays an error message to alert the user.
Functionality

The Weather App's functionality revolves around fetching weather data from the OpenWeatherMap API and displaying it to the user. Here's how it works:

User Input: 

When a user enters a location in the search box and clicks the search button, the app captures the entered location.
API Request: The app sends a request to the OpenWeatherMap API, passing the user's location as a parameter.
Data Retrieval: Upon receiving a response from the API, the app parses the JSON data containing weather information such as temperature, weather condition, humidity, and wind speed.
Display Update: The app updates the weather display with the retrieved data, including the weather icon, temperature, description, humidity, and wind speed.
Error Handling: If the API response indicates that the location was not found (status code 404), the app displays an error message to notify the user.
Design

The Weather App features a clean and intuitive design aimed at providing users with a seamless weather browsing experience. Here are some design highlights:

Minimalist Interface: 

The app's interface is minimalist, with a focus on essential weather information.
Iconography: Weather icons are used to represent different weather conditions, enhancing visual appeal and aiding user comprehension.
Responsive Layout: The layout is responsive, ensuring that the app adapts to various screen sizes and devices, including desktops, tablets, and mobile phones.
Color Scheme: A soothing color scheme is employed, with subtle contrasts to improve readability and visual aesthetics.
Error Handling: Error messages are displayed prominently to alert users in case of invalid location input or API request failure.
Implementation Details

HTML Structure: 

The app's HTML structure consists of several div elements representing different sections, including the search box, weather display, weather details, and error message.
CSS Styling: CSS stylesheets are used to apply visual styles to the app's elements, including font styles, colors, spacing, and layout.
JavaScript Functionality: JavaScript is responsible for implementing the app's interactive features, such as capturing user input, making API requests, updating the weather display, and handling errors.
API Integration: The app integrates with the OpenWeatherMap API to retrieve weather data, utilizing asynchronous fetch requests to send and receive data.
Error Handling: Error handling is implemented to gracefully handle scenarios where the entered location is not found or the API request fails, ensuring a smooth user experience.

USAGE:

ENTER YOUR LOCATION: Users enter a location in the input field and click 'Search' option to get the weather information about city/town you entered. 
If you entered the incorrect location it shows the error.

CONCLUSION:

The Weather App is a user-friendly and visually appealing web application designed to provide users with accurate and up-to-date weather information. With its intuitive interface, responsive design, and robust functionality, the app offers users a convenient way to check the weather forecast for any location worldwide. Whether on desktop or mobile devices, users can rely on the Weather App to stay informed about current weather conditions wherever they are.

OUTPUT:

![Screenshot 2024-04-03 170353](https://github.com/Chey2266/WEATHER-APP-ICOD5635/assets/153630592/76c075d4-1f6e-487a-a819-33bf9e3e3ee9)

![Screenshot 2024-04-03 170406](https://github.com/Chey2266/WEATHER-APP-ICOD5635/assets/153630592/c0a0466b-4f55-49e2-ac69-a78b9510df7e)




