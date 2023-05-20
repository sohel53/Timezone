# Timezone

reate a web page with the following elements:

Display area to show the user's current timezone using their latitude and longitude (obtained using the Geolocation API)
Input field for the user to enter an address
Button to trigger the timezone retrieval based on the entered address
Display area to show the timezone corresponding to the entered address
Step 3: Fetch User's Current Timezone
Use the Geolocation API (e.g., HTML5 Geolocation API) to retrieve the user's latitude and longitude automatically when they visit the web page. Use these coordinates to fetch and display their current timezone.

Step 4: Retrieve Timezone by Address
When the user enters an address and clicks the button, perform the following steps:

Validate the entered address.
Use a geocoding API (e.g., [Geoapify Geocoding API](https://www.geoapify.com/geocoding-api)) to convert the address into latitude and longitude coordinates.
If the geocoding API returns valid coordinates, use them to fetch the corresponding timezone using the Geoapify Timezone API.
Display the retrieved timezone in the designated area.
