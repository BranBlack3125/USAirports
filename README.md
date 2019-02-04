# US Airport Location Map

This page displays airport locations throughout the United States. The density of airports found in each state are noted by color (see legend in upper right corner of the page), while the presence (green) or absence (black) of a control tower for each airport is denoted by airport marker. The map is projected in the ESPG 2991, NAD 83 Oregon system. There is also a click-event associated with the airport icons, which displays a "Y" for airports with a control tower, and an "N" for those without. The map is zoomable (controls in upper left), and will also zoom in on clicked points within the map. A scale bar in both km and miles is placed in the lower left corner of the page. 

Leaflet, jQuery, Google font, and chroma libraries were imported to operate the page.

The "Antique" basemap is sourced from CartoDB, and the Google font used is "Acme". The core of the index.html was derived from Prof. Bo Zhao's Geog 571 Lab 3 notes.

An attempt was made to add in Leaflet-based weather reporting to the map, but is not functioning correctly at this time.
