# Module 13 Challenge: Mapping Earthquakes 🌎
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

The following figure shows the layers menu and the pop-up window.

![Pop-up](https://user-images.githubusercontent.com/98360572/168451817-28f5ac0b-15b2-44a9-b740-24a96e888a0c.png)

Below is a GIF animation showing the use of the site.  The image is a bit blurred due to filesize limitations on Github 

![ezgif com-gif-maker](https://user-images.githubusercontent.com/98360572/168451364-4cf03a79-5fc2-4f23-8007-88eea6dc8b01.gif)

## :three: View a demonstration in the live site

| [Live Demo](https://peteresis.github.io/earthquake_mapping_demo_site/) of Mapping Earthquakes |
| --- |

The live site contains the API Key which can be publicly accessed but since the key was generated using a non-billable account, there is no financial risk.  For billable accounts, the API keys can be restricted by registering the pages from which they can be called at the moment of generating the API key in the Mapbox site.

[Mapbox says that](https://docs.mapbox.com/accounts/guides/tokens/#:~:text=Contact%20support.-,URL%20restrictions,Tokens%20without%20restrictions%20will%20work%20for%20requests%20originating%20from%20any%20URL.,-403%20errors%20from):

> URL restrictions
> 
> You can make your access tokens more secure by adding URL restrictions from the account dashboard tokens page or with the Tokens API. When you add URL restrictions to a token, that token will only work for requests to billable Mapbox services that originate from the URLs you specify. Requests from unauthorized URLs will return status code 403: Forbidden.
> 
> Tokens without restrictions will work for requests originating from any URL.


## :four: References

**Module 13: Visualizing Earthquake Data**, https://courses.bootcampspot.com/courses/1145/pages/13-dot-0-1-visualizing-earthquake-data, :copyright: 2020-2021 Trilogy Education Services, Web 15 Apr 2022.

**Token management**, https://docs.mapbox.com/accounts/guides/tokens/#url-restrictions

**GeoJSON Summary Format**, https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

**Leaflet Quick Start Guide**, https://leafletjs.com/examples/quick-start/





