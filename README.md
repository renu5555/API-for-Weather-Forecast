# API-for-Weather-Forecast
![Uploading weather.jpg…]()

# Weather API with Flask

A weather API based on a simple design with Flask lets its consumers get information on what is the weather now in several cities. Acquiring of the weather data from OpenWeatherMap API.

## Prerequisites

- Python
- Flask
- Requests library

## Getting Started

1. Install the required libraries.

```bash
pip install Flask requests
```

2. Get your OpenWeatherMap API key. You can obtain it by [signing up here](https: //openweathermap.org/api).

3. Run the application.

```bash
python app.py
```

4. Open Postman and create a new request to http: //127.0.0.1:5000/weather with the GET method.

5. Append a query param location with the text city and state (e.g., Bengaluru, KA).

6. Make the request, read the result.

**Note: Comparing it with OpenWeatherMap will help you determine whether this returned data is correct.

## Detailed Explanation

1. In VSCode run Python script.

In the terminal, you will see the base URL http: //127.0.0.1:5000. The error code 404 for a click on this url.

2. Go for Postman and ensure that the request mode is get.

3. Enter the URL for your Flask API endpoint: http://127.0.0.1:5000/weather?

4. Click on the "Params" tab. Into the “Key” box, write `location`. Input the city and state in the “value” field.

5. To do this, simply click “submit”.

6. To fetch weather data, append the base URL with the API endpoint: http://127.0.0.1:5000/weather?location=city,state (e.g., http://127.0.0.1:5000/weather?location=Kunigal,Karnataka&location=Jaipur,Rajasthan&location=Pattaya,Thailand).

7. View the JSON response.

##   Screenshots
![](a)
![](b)
![](c)
![](postman2)
