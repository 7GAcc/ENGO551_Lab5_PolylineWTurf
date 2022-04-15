# ENGO551_Lab5_PolylineWTurf

Hello, this repository contains just one index.html file and a background image. 
In the webpage from the index file, there are two buttons. The first button refreshes the map by removing layers. The second button is used to simplofy polylines that the user can create on the map. 
The map was made in mapbox (same layout as lab 3). Each time a user left clicks on the map, the coordinate of that location that was clicked is stored in an array. When at least 2 points are clicked, we can see a green polyline. To remove this polyline, you simply need to right click. After making a polyline, you can click the simplify button to simplify the polyline using turf.js. This will create a polyline on the map that is blue. The green polyline is still active at this point, which allows for the user to see the difference between the two. To refresh the entire map, you simply select the refresh button. The map will then clear and you can start again. You can also create multiple seperate simplified polylines and have them displayed on the map by drawing a polyline, clicking the simplify button, then right click, and left click to create a new polyline with the previous simplified polylines still on the map.
