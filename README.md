# City Explorer Api

**Author**:Leaundrae Mckinney
**Version**:1.0.2

## Overview

This application converts a location entered by the user into a latitude and longitude, then use those values to request weather information for that location.

## Architecture
- Node.js
- Express
- Cors

## Change Log

02-22-2021 2:13pm - Deployed basic express server to Heroku. 

02-22-2021 6:45pm - Installed package.json with express,dotenv and cors dependencies as well as .eslintrc.json and .gitignore. 

02-22-2021 7:30 pm - Created a route with a method of get and a path of /location. The route callback should invoke a function to convert the search query to a latitude and longitude. The function should use the provided JSON data.

 02-22-2021 8:17pm - A constructor function will ensure that each object is created according to the same format when your server receives the external data. Ensure your code base uses a constructor function for this resource.

 02-22-2021 8:30pm - Return an object which contains the necessary information for correct client rendering. See the sample response.

 02-22-2021 9:36pm - Deploy updated express server to Heroku.

 02-22-2021 9:45pm - Confirmed route is responding as expected by entering your deployed backend URL on the City Explorer app's welcome page.  

 02-22-2021 9:51pm - Create route with a method of get and a path of /weather

 02-22-2021 9:58pm - Deployed updated server code to Heroku.

 02-23-2021 6:05pm - Refactored getWeather callback to use .map

02-23-2021 06:15pm - Redeployed App to Heroku

02-23-2021 11:00pm - Implemented the Weather API

02-23-2021 00:02am - Added parks API key

02-24-2021 01:15am - Implemented Park API

02-24-2021 01:19am - Redeployed Park API

02-25-2021 05:18pm - Installed and required NPM PostgreSQL package

02-25-2021 06:30pm - Connected to PostGreSQL Database and created tables using schema.sql

02-25-2021 09:05pm - Connected database to location route 

02-25-2021 09:25pm - Connected database to weather route 






## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->



