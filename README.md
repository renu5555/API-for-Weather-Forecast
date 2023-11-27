# API-for-Weather-Forecast
Weather API with Flask
This project implements a simple weather API using Flask, allowing users to retrieve current weather information for multiple locations. The weather data is fetched from the OpenWeatherMap API.

Prerequisites
Python
Flask
Requests library
Getting Started
Install the required libraries.

bash
Copy code
pip install Flask requests
Get your OpenWeatherMap API key. You can obtain it by signing up here.

Run the application.

bash
Copy code
python app.py
Open Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.

Add a query param location with the value being the city and state (e.g., Bengaluru, KA).

Send the request and check the output.

Note: You can check the accuracy of the retrieved weather data by comparing it with OpenWeatherMap.

Detailed Explanation
Run the Python script in VSCode.

In the terminal, you will see the base URL http://127.0.0.1:5000. Click on this URL, and you will encounter a 404 error.

Open Postman and set the request type to GET.

Enter the URL for your Flask API endpoint: http://127.0.0.1:5000/weather?

Click on the "Params" tab. In the "Key" column, enter location. In the "Value" column, enter the city and state for which you want to retrieve the weather information.

Click the send button to make the request.

To fetch weather data, append the base URL with the API endpoint: http://127.0.0.1:5000/weather?location=city,state (e.g., http://127.0.0.1:5000/weather?location=Bengaluru,Karnataka&location=Mysore,Karnataka).

View the JSON response.
