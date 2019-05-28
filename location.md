---
layout: page
title: Location
---

<div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>
<script>
    // create the map object and set the cooridnates of the initial view: 
    var map = L.map('map').setView([50.78027, 6.08096], 16);
    // create the tile layer with correct attribution: 

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { attribution: '© <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors' }).addTo(map);

    L.marker(\[50.78027, 6.08096\]).addTo(map) .bindPopup('<a href="https://maps.openrouteservice.org/directions?n1=50.780204&n2=6.081032&n3=17&a=null,null,50.780204,6.081032&b=0&c=0&k1=en-US&k2=km" target="_blank"><b>MESIGA 2019.</b><br> RWTH - Fachgruppe Mathematik.<br>Pontdriesch 14-16<br>52062 Aachen</a>') .openPopup();

    L.circle(\[50.78027, 6.08096\], { color: '\#3CA496', fillColor: '\#3CA496', fillOpacity: 0.5, radius: 500 }).addTo(map);
</script>
