# Realtime Transit
Uses [Leaflet Realtime](https://github.com/perliedman/leaflet-realtime) with server-side conversion of Marta train and bus locations to GeoJSON.

<b>To do:</b>
1. Document how to deploy to GitHub or Heroku.
2. Use order_across or order_from_center to position train between stations.
Get [MARTA Train Station Data](https://georgia-transit.carto.com/viz/b22db620-fdfe-11e6-86bd-0e05a8b3e3d7/table)

Icons are currently misplaced because the calculations are using the end-of-the-line rather than the next stop.

# Installation

Clone the Quick Start repository<br>
$ git clone https://github.com/modular-map/realtime-transit

Go into the repository<br>
$ cd realtime-transit
<!--
# Install the dependencies and run
$ npm install && npm start
-->
$ npm install -g electron

$ electron

Drag the docs/index.html file onto the Electron app to view the Leaflet map with train icons.
