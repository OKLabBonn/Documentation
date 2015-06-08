OSM-Datensätze
==============
 * [Apotheken](http://overpass-api.de/api/interpreter?data=[out:json][timeout:90];area[name=%22Bonn%22][admin_level]-%3E.a;%28node%28area.a%29[%22amenity%22=%22pharmacy%22];%29;%28._;%3E;%29;out;)
 * Defibrillator
 * (Park-)Bänke

Information
----------------
Alle OSM-Datensätze beziehen sich auf das Stadtgebiet Bonn.
 
 * http://www.openstreetmap.org/
 * http://overpass-turbo.eu/

Sammlung aller Anfragen
-----------------------
```
http://overpass-api.de/api/interpreter?data=[out:json][timeout:90];area[name="Bonn"][admin_level]->.a;(node(area.a)["amenity"="pharmacy"];);(._;>;);out;
```

