# python-api-challenge
Repo for python api challenge

<p><strong>**NOTE**:</strong> You will need to create a python file called "api_keys" and create 2 vars called "weather_api_key" and "g_key" and store valid api keys for the weather and google api's used in order to run this successfully.

<h3>Part I - WeatherPy</h3>

<h4>Observations</h4>

<p>All observations are inline in the WeatherPy.ipynb file, however here are 3 main observations made:</p> 

<ul>
    <li>The closer to the equator a city is, the higher the max temperature is.</li>
    <li>Humidity and Cloudiness seem to follow a similar trajectory in that they both rise as you move from the southern hemisphere towards the equator, and continue to rise as you move north of the equator. </li>
    <li>Linear regression shows that Wind speed tracks to decrease in cities closer to the equator and increases as cities get further north or south of the equator.</li>
</ul>

<p><strong>*NOTE:</strong> The porcess that requests data via the weather api is throttled with sleep statements to ensure no more than 50 requests/min are made to ensure all requests are serviced and the rules of the free account are respected.  When you run that part, go grab a coffee and a snack as there are ususally around 12 or 13 sets to process...


<h3>Part II - VacationPy</h3>

The following heat map with hotel markers shows 10 or less markers that are clickable and show the templated hotel info:

![](output_data/humidity_heat_map.png)

![](output_data/hotel_humidity_heat_map.png)