# [iss-tracker](https://iss.alanjc.com)
A website that tracks the location of the ISS in real-time using Javascript and some APIs.

[Link to ISS tracker](https://iss.alanjc.com)

# APIs used
- <a href="https://wheretheiss.at/w/developer">Where the ISS at? API</a>
  - Used for tracking the ISS (latitude, longitude, velocity, altitude, etc).
- <a href="http://open-notify.org/Open-Notify-API/People-In-Space/">Open Notify API</a>
  - Used for getting the names of the people aboard the ISS.
- <a href="https://developers.google.com/maps/documentation/javascript/tutorial">Google Maps API</a>
  - Used for displaying a map with a marker.
  
# Image

Gif
<img src="images/iss-tracker-website.gif" alt="iss-tracker-website.gif">

Static image
<img src="images/iss-tracker.png" alt="iss-tracker.png">

### Note
I hard coded the astronauts aboard the ISS because the Open notify API for the astronauts doesn't serve its requests with HTTPS only HTTP which was causing a mixed-content error.
