# Geographic_Location_Tracker

web page with the following elements:

1) Display area to show the user's current timezone using their latitude and longitude (obtained using the Geolocation API)
2) Input field for the user to enter an address
3) Button to trigger the timezone retrieval based on the entered address
4) Display area to show the timezone corresponding to the entered address
5) Validate the entered address.
6) Use a geocoding API (e.g., [Geoapify Geocoding API](https://www.geoapify.com/geocoding-api)) to convert the address into latitude and longitude coordinates.
7) If the geocoding API returns valid coordinates, use them to fetch the corresponding timezone using the Geoapify Timezone API.
8) Display the retrieved timezone in the designated area.
