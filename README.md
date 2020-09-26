# JS30 Type Ahead
Exercise 06 in WesBos' JavaScript30 tutorials. 

There is quite a bit going on here under the hood from RegEx to inserting html onto the page via JS. Though not covered in the video there is also some neat CSS with the the .suggestions li class. 

I found it extremely helpful that Wes recapped fetch() and explained it from another point of view which really worked for me. 

I took the additional challenge to sort the results by Geo Location distance to the users current position. After about six hours I was able to solve this by using the Geolocation API to ask for permission and then get the users current location, then implement Geolib's orderByDistance() method to re-sort the type ahead matched results by distance (as the crow flies) to the user. I used <a href="https://www.freemaptools.com/how-far-is-it-between.htm" target="_blank"> FreeMapTools.com </a> to verify the list. i.e. Anchorage, Alaska is actually closer to Placerville, CA than Auburn, Alabama. 

<a href="https://nikrowedevjs30-type-ahead.netlify.app/" > Netlify Demo </a>