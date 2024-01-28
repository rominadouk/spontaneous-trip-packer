# 3-Day-Trip-Packer
This web application was developed users plan for their spontaneous trips, it provides a three-day forecast and suggestions of what to pack based on the forecast. It also provides a packing list feature to add and delete items. 
Live Link: (https://spontaneous-trip-packer.netlify.app/)

## How it works 
 When users input a destination of a city and state in the destination modal and submit, the code pulls from an Express API that I developed which queries the WeatherAPI and recieves a 3-day forecast in response. It then manipulates the DOM using Vanilla JavaScript using the response data. It also looks at the text forecasts and generates packing list suggestions depending on the type of weather. The packing list also uses the backend where it pings an add or delete route.

## Languages & Frameworks
  * HTML
  * CSS
  * JavaScript
## Technologies Used
 * Weather Api - (https://www.weatherapi.com)
 * Backend - (https://github.com/rominadouk/weekend_packer_backend)

## Challenges
  I spent a little more time on querying the API and setting the default country to the United States. There was a lot of data I got back so this project required a lot of attention to detail. I did not use any frontend frameworks for this project.

## Future Updates
  * UX/UI Changes
  * Make the packing list specific to a session
  * More generated suggestions/Using OpenAI Api Artificial Intelligence to generate suggestions

