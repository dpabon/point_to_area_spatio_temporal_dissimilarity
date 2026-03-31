# Point to area comparison using Jensen-Shannon disimilarity index

## OEMC project task: 4.9 Integration and harmonization between in-situ and gridded data

Computing the potential impact of the spatial mismatch between in-situ observations and remote sensing products is a fundamental step to improve the representation of the ecosystem states at a global scale. In this project task, we explore the use of the Jensen-Shannon distance as an indicator of the mismatch between eddy covariance towers and different potential remote sensing areas, that we expect will help to improve the upscaling of Sun-Induced Fluorescence estimates from satellite missions.

The following repository contains three tutorials to compute the Jensen-Shannon distance (dissimilarity metric) using the Copernicus Data Space Ecosystem. Specifically uses the SentinelHub backend through the [xcube](https://xcube.readthedocs.io/en/latest/) package and the plugin [xcube-sh](https://github.com/xcube-dev/xcube-sh)

The notebooks cover several potential use cases: 

1. ```Final_product_1.ipynb```: One point to radius time series.
2. ```Final_product_2.ipynb```: Multiple area sensitivity, based on cloud free composite.
3. ```Final_product_3.ipynb```: Two polygons comparison, using user-defined polygons.

You can run the notebooks locally on your computer or directly in the Copernicus Data Space Ecosystem [Jupyterlab](https://dataspace.copernicus.eu/analyse/jupyterlab) You only need to drag and drop the notebooks in your 
```mystorage``` folder. Be sure to select ```Sentinel Hub``` python kernel before running the notebooks.


## Acknowledgement

This project has received funding from the [Open-Earth-Monitor Cyberinfrastructure](https://earthmonitor.org/) project that is part of European Union's Horizon Europe research and innovation programme under grant [101059548](https://cordis.europa.eu/project/id/101059548).

