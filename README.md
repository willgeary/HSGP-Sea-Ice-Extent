# HSGP Sea Ice Extent

Experimenting with modeling monthly sea ice extent over time for the Arctic and Antarctic separately using through an approximation of Gaussian Processes known as Hilbert Space Gaussian Processes (HSGP) with the Bambi library, following this [tutorial](https://bambinos.github.io/bambi/notebooks/hsgp_1d.html).

Sea Ice Extent (SIE) is defined as the area covered by a significant amount of sea ice, that is the area of ocean covered with more than 15% Sea Ice Concentration (SIC).
The SIE data used in `notebook.ipynb` comes from The European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT) Ocean and Sea Ice Satellite Application Facility (OSISAF) available for download [here](https://osisaf-hl.met.no/v2p1-sea-ice-index).

![alt text](https://raw.githubusercontent.com/willgeary/HSGP-Sea-Ice-Extent/main/charts/North_chart.png)

![alt text](https://raw.githubusercontent.com/willgeary/HSGP-Sea-Ice-Extent/main/charts/South_chart.png)

