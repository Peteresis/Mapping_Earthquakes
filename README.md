# Module 13 Challenge: Mapping Earthquakes
---
This project uses Leaflet and JavaScript to create an interactive map that is displayed on a website

---
## :one: Project Overview

The objective of this challenge was to display GeoJSON seismic data on a map using the Leaflet.js Application Programming Interface (API). Each earthquake is represented by a circle with a different colors and size to show the magnitud of the quake.  The larger the diameter and the darker the color, the more powerful the quake. It is also possible to see the magnitude and position of an earthquake by clicking on any circle and reading the earthquake's pop-up marker.


## :two: Elements of the Site

The site presents several elements using the layers that are shown in the upper-right container.

The bottom layer is the map itself, which offers 3 possible layers for the map of earthquakes around the world:

* `Streets`
* `Satellite`
* `Dark`

There are also three elements plotted on the map:

* The boundaries of the Tectonic Plates
* The location of small earthquakes
* The location of major earthquakes (magnitude above 4.5)

The layers and the additional elements can be toggled `on` or `off` by the user visiting the site.  The map can be `zoomed in` and `zoomed out` or scrolled around.

If the user clicks on any of the circles, a pop-up window is shown indicating the magnitude and the location of the quake.
![Pop-up](https://user-images.githubusercontent.com/98360572/168451817-28f5ac0b-15b2-44a9-b740-24a96e888a0c.png)

Below is a GIF animation showing the 
![ezgif com-gif-maker](https://user-images.githubusercontent.com/98360572/168451364-4cf03a79-5fc2-4f23-8007-88eea6dc8b01.gif)

## View a demonstration in the live site
[Live Demo](https://peteresis.github.io/earthquake_mapping_demo_site/) of Mapping Earthquakes
 
