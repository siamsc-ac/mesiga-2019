---
layout: page
title: Location
---

<div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>
<script>
    // create the map object and set the cooridnates of the initial view: 
    var map = L.map('map').setView([50.78027, 6.08096], 16);
    // create the tile layer with correct attribution: 

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { attribution: '© <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
}).addTo(map);

L.marker([50.78027, 6.08096]).addTo(map)
    .bindPopup('<b>MESIGA 2019.</b><br> RWTH - Fachgruppe Mathematik.<br>Pontdriesch 14-16<br>52062 Aachen')
    .openPopup();
</script>
