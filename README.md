Leaflet EdgeMarker
==================

Works with Leaflet >= 1.9.4

Leaflet EdgeMarker is a [Leaflet](http://leafletjs.com/) plugin which allows you to indicate Markers, Circles and CircleMarkers that are outside of the current view by displaying CircleMarkers at the edges of the map.

Demo
----

Check out the [demo](http://ubergesundheit.github.io/Leaflet.EdgeMarker)

Usage
-----

  * Download the `Leaflet.EdgeMarker.js`

then

  * Include the file after you included `leaflet.js`
  * copy `images/edge-arrow-marker.png` to the leaflet image directory or specify your own marker icon (see demo).
  * Initialize the EdgeMarkers with `var edgeMarkers = L.edgeMarker().addTo(map)` **after** you initialized your `map` and Markers/Circles/CircleMarkers
  * To remove the EdgeMarkers, call `edgeMarkers.destroy()`

**Or look at the source of `example.html`**
