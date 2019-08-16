---
layout: page
title: Location
---

<div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>
<script>
    // create the map object and set the cooridnates of the initial view: 
    var map = L.map('map').setView([50.78027, 6.08096], 14);

    // create the tile layer with correct attribution: 
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { attribution: '© <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors' }).addTo(map);

    L.marker([50.78027, 6.08096]).addTo(map).bindPopup('<a href="https://maps.openrouteservice.org/directions?n1=50.780204&n2=6.081032&n3=17&a=null,null,50.780204,6.081032&b=0&c=0&k1=en-US&k2=km" target="_blank"><b>MESIGA 2019.</b><br> RWTH - Fachgruppe Mathematik.<br>Pontdriesch 14-16<br>52062 Aachen</a>').openPopup();

    L.circle([50.78027, 6.08096], { color: '\#3CA496', fillColor: '\#3CA496', fillOpacity: 0.5, radius: 1500 }).addTo(map);
</script>

## Recommendations

We suggest to plan and to book ahead because the (cheap) city center hotels are often booked by tourist groups.
Also we recommend to take a Hotel in walking distance to the city center (as indicated by the greenish circle) because this is quite compact.
However buses are reliable — a ride is 2.70€ which you may pay on the bus.

## Hotels

- <a href="https://www.aohostels.com/de/aachen/aachen-hauptbahnhof/" target="_blank">a&o Hostel Aachen</a>
- <a href="http://www.hostel-aachen.de/index.html" target="_blank">Hostel Aachen</a>
- <a href="https://www.hotel-aquis-grana.de/index.php/en/" target="_blank">Aquis Grana</a>

### "Big Chains"

- Ibis (about 4 in the City Center: 2 regular, 1 budget, 1 styles)
- Mercure 
- Media 
- Novotel 
- Best Western 
- Hampton by Hilton (a bit far)
- (Extra, for fancy people: Quellenhof)


## <a href="https://www.airbnb.de/s/homes?query=Aachen" target="_blank">Airbnb</a>
A big selection of cozy places available.
