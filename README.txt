Viloyatga Boramiz — updated project files

Files included: index.html, server.js, package.json, data.json, assets/Car driving on road.svg.

Run locally (Node.js 18 or newer required):
1. Extract the ZIP into a folder.
2. Open a terminal in the extracted Viloyatga_Boramiz_Improved folder.
3. Run: npm start
4. Open: http://localhost:3000

Features in this update:
- Separate passenger and driver experiences. Passengers can select an Uzbekistan region and its listed district/area for both departure and destination.
- Passenger map sizing/location behavior improved. Use the location button and allow browser location permission. Browser geolocation generally requires localhost or HTTPS.
- Driver signup includes a driving-license file picker, years of driving experience, and whether the driver owns a car. For privacy, this prototype saves the selected file name only; it does not upload the license file contents.
- Drivers publish a journey with departure region/area, destination region/area, and price per passenger. Journeys are stored by the local Node server and appear in the driver burger menu under “Mening e’lonlarim”.
- Green rotating globe animation is shown during sign-in for both roles.
- Passenger bookings appear under “Mening bronlarim”.

Notes:
- This is a local prototype, not a publicly hosted service. Other users/devices cannot access it unless you deploy the server to a suitable host.
- Map tiles, geolocation, and the globe libraries require an internet connection. Allow location access for current-location detection.
- District lists are included for the 14 regions/city-level units; official names and administrative boundaries can change.
- Driver announcement defaults to 4 seats and a departure time approximately one day ahead to keep the announcement form short.
