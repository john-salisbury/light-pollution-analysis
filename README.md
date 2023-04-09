# Light Pollution Analysis
A spatiotemporal analysis of light pollution in the city of Boulder, Colorado (2012-2021)

***
### [View Interactive Project Summary](https://john-salisbury.github.io/light-pollution-analysis)
***


This brief analysis explores **how light pollution has changed in the city of Boulder, Colorado** over the past decade or so. 

To explore this topic, **I processed, visualized, and summarized 10 years of nighttime radiance data** collected from NASA's [Visible Infrared Imaging Radiometer Suite (VIIRS)](https://www.earthdata.nasa.gov/learn/find-data/near-real-time/viirs) instrument aboard the NASA/NOAA Joint Polar Satellite System (more specifically, NASA's *VIIRS/NPP Lunar BRDF-Adjusted Nighttime Lights Yearly Composites* product for 2012-2021). This is the same radiance data which powers the popular [lightpollutionmap.info](https://lightpollutionmap.info) web application that allows users to visualize sources of light pollution across the globe.

The data provides annual composite estimates of radiance — the flux of radiation emitted per unit solid angle in a given direction by a unit area of a source — in a rasterized format at a spatial resolution of roughly $500m$. Although it's not a direct measure of sky quality (i.e., darkness), **radiance is a useful way to measure light pollution** and allows us to assess how light pollution has changed in the city of Boulder over the past decade or so.

**In my analysis, I seek answers to the following questions:**
- How has radiance in Boulder, CO changed in the past decade?
- Where within the city is radiance the highest?
- Is it possible to compile some key recommendations for mitigation of nighttime radiance and light pollution within the city?

*Find the geospatial data for this project below:*
* [NASA VIIRS data](https://www.lightpollutionmap.info/help.html)
* [VIIRS documentation](https://viirsland.gsfc.nasa.gov/PDF/BlackMarbleUserGuide_v1.2_20210421.pdf)
* [City of Boulder spatial extent](https://data-boulder.opendata.arcgis.com/datasets/955e7a0f52474b60a9866950daf10acb)
*Note that all TIFs are stored externally and haven't been uploaded to the repository for this project due to size. You can download these TIFs at the helper link above.*