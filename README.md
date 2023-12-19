-> Weather App for fetching weather details with repect to cities

🚀API Key: The apikey property holds the API key for authentication with the OpenWeatherMap API.

🚀fetchWeather Function: This function is responsible for making an API request to OpenWeatherMap to fetch weather data for a given city. It uses the fetch function to make an HTTP request and handle the response asynchronously using promises.

🚀Handling API Response: The code checks if the response from the API is successful (status code 200). If not, it alerts the user and throws an error. If the response is OK, it parses the JSON data and calls the displayWeather function with the extracted data.

🚀displayWeather Function: This function updates HTML elements on the webpage with the weather information obtained from the API response. It also adjusts the background image of the body based on the city.

🚀Event Listeners: Event listeners are added to the search button and search bar to trigger a weather search when the button is clicked or the Enter key is pressed.

🚀Default Search: The application starts by fetching weather information for the default city, "Hyderabad."

This code demonstrates the basic structure of a web application that interacts with an API to fetch and display data dynamically based on user input. It's a great starting point for understanding asynchronous JavaScript, API interactions, and DOM manipulation.






