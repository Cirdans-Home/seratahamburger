---
layout: presentation
---

## Dove trovarci

{% leaflet_map { "center" : [37.921000,  15.987940],
                 "zoom" : 15,
                 "providerBasemap": "OpenStreetMap.Mapnik" } %}
     {% leaflet_marker { "latitude" : 37.921000,
                    "longitude" : 15.987940,
                    "popupContent" : "Località la Terrazza"} %}
{% endleaflet_map %}
