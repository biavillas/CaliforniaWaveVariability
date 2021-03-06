[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4127333.svg)](https://doi.org/10.5281/zenodo.4127333)

# Source code for
Villas Bôas, A. B., Gille, S. T., Mazloff, M. R., & Cornuelle, B. D. (2017). Characterization of the deep water surface wave variability in the California Current region. Journal of Geophysical Research: Oceans, 122(11), 8753-8769., doi: https://doi.org/10.1002/2017JC013280

# Abstract
Surface waves are crucial for the dynamics of the upper ocean not only because they mediate exchanges of momentum, heat, energy, and gases between the ocean and the atmosphere, but also because they determine the sea state. The surface wave field in a given region is set by the combination of local and remote forcing. The present work characterizes the seasonal variability of the deep water surface wave field in the California Current region, as retrieved from over two decades of satellite altimetry data combined with wave buoys and wave model hindcast (WaveWatch III). In particular, the extent to which the local wind modulates the variability of the significant wave height, peak period, and peak direction is assessed. During spring/summer, regional-scale wind events of up to 10 m/s are the dominant forcing for waves off the California coast, leading to relatively short-period waves (8–10 s) that come predominantly from the north-northwest. The wave climatology throughout the California Current region shows average significant wave heights exceeding 2 m during most of the year, which may have implications for the planning and retrieval methods of the Surface Water and Ocean Topography (SWOT) satellite mission.
# Authors
* [Bia Villas Boas](https://biavillasboas.github.io/) <<avillasboas@ucsd.edu>>
* [Sarah T. Gille](http://www-pord.ucsd.edu/~sgille/)
* [Matthew R. Mazloff](http://scrippsscholars.ucsd.edu/mmazloff)
* [Bruce D. Cornuelle](http://scrippsscholars.ucsd.edu/bcornuelle)
# Data
This project used three major datasets: Altimetry-based significant wave height, wave-buoy measurements, and 
output from a wave model hindcast. 

Altimetry Data 
-----------
The altimetry data consists of homogeneously validated and calibrated along-track measurements of significant wave height from nine different altimetry missions distributed by the Institut français de recherche pour l'exploitation de la mer (IFREMER). The along-track measurements were daily averaged into 1 degree by 1 degree bins using the code [bin_all_sat.py](https://github.com/biavillas/CaliforniaWaveVariability/blob/master/data/bin_all_sat.py). The original along-track data is available from the IFREMER ftp server <ftp://ftp.ifremer.fr/ifremer/cersat/products/swath/altimeters/waves/data>

Buoy Data 
-----------
Wave-buoy data for this paper were provided by the Coastal Data Information Program [CDIP](http://cdip.ucsd.edu) and are available from their thredds server <http://thredds.cdip.ucsd.edu/thredds/catalog.html>. In particular, we analyzed stations 168, 094, 029, 157, 071, 167, and 191.

WaveWatch III hindcast
-----------
The wave model hindcast used in this paper is based on the WaveWatch III framework forced by reanalisys winds from the Climate Forecast System Reanalysis (CFSR) and it was produced by IFREMER. The full wave hindcast is available for download at <ftp://ftp.ifremer.fr/ifremer/ww3/HINDCAST/GLOBAL>.


# Funding
This project was partlially funded by the SWOT program with NASA grant NNX16AH67G.
Bia Villas Boas was partially funded by NASA grant 80NSSC17K0326.
Bruce Cornuelle was partially funded by the ONR grant N000141512285.

# How to cite this code

If you wish to use the code from this repository, you may cite it as

Villas Bôas, Ana B. (2020, October 25). Source code for: 'Characterization of the Deep Water Surface Wave Variability in the California Current Region' (Version v1.0). Zenodo. https://doi.org/10.5281/zenodo.4127332
