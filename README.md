# WEATHER-APP-STEPS-GUIDE

Dependencies

express
hbs
request
api keys
heroku deployment


express
This is a Node.js module available through the npm registry.Before installing, download and install Node.js. Node.js 0.10 or higher is required.

command to install - npm install express

hbs
hbs is a express.js wrapper for the handlebars.js javascript template engine. Handlebars.js is a template engine to make writing html code easier.

command to install - npm install hbs

request
Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.

command to install - npm install request@2.88.2

api keys
I have used two api keys and used them in order to get the final weather.
1)www.weatherstack.com :- register and generate api key from the website and use it in the code(for weather calculation using location cordinates)
2)www.mapbox.com :- register and generate api key  (for getting cordinates by the name of the place)

heroku deployment
I have deployed this application using git and heroku.
You can access the client side of this application via :- https://weather-ysaksham.herokuapp.com/
Type any location and get current weather.


Don't enclose the apikey value within quotes.Just paste the API key only
commands to run
node src/app.js
Go to google. Type localhost:3000
Type any location inside the search bar of weather app
