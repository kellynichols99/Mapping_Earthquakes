# Mapping_Earthquakes


<h1>Mapping Earthquakes from the Last 7 Days!</h1>
My goal was to make a multilayer map that shows all the earthquakes tracked in the last 7 days. I used a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes and added the data to a map. I then used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.


<h1>Resources</h1>

- Data Sources: Multiple web based geoJSON data

- Software: VS Code, Web Browser, GitHub

- Programming Languages: JavaScript, HTML, CSS, Leaflet
<body>
<h1>Summary</h1>

<h3> Deliverable 1: Add Tectonic Plate Data</h3>
<p>Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, I added tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.<p>

 <img src="Deliverable 1: Add Tectonic Plate Data.png">
  
<h3>Deliverable 2: Add Major Earthquake Data</h3>
<p>Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add major earthquake data to the map using d3.json(). I also add color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON(). </p>

<img src="Deliverable 2: Add Major Earthquake Data.png">

<h3> Deliverable 3: Add an Additional Map</h3>
<p>Using my knowledge of JavaScript and Leaflet.js add a third map style to your earthquake map.</p>

<img src="Deliverable 3: Add an Additional Map.png">

<body>
  
<h1>Challange Summary</h1>
As you can see our map has multiple layers showing the tectonic plates, a dark layered map, and major earthquakes that have appened in the last 7 days.   
