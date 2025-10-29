## Ben Ouaou
Hello! My name is Ben Ouaou (pronounced "whoa") and I am a senior undergraduate studying geography with a GIS track at University of Colorado Boulder. I also have some background in biology/botany/ecology. Through the Earth Analytics Data Science Bootcamp, I'm interested in learning basic data science and programming skills to pair with my GIS knowledge. I am originally from South Florida, and in my free time I love to write, play/see music, ski, and watch sports.

![Me collecting plant specimens as part of an internship with the Santa Fe Botanical Garden, Wheeler Peak, NM](https://visitsfbg.org/wp-content/uploads/Ben-Ouaou-Jankowski-intern.jpg "Collecting plant specimens at Wheeler Peak, NM!")

#### Contact Information
* Email
* LinkedIn
* [GitHub](https://github.com/bwhoa2299)

## Projects

### Map of Baltimore Sports Stadiums
<embed type="text/html" src="bmore.html" width="600" height="600">

### Precipitation Trends in Naples, FL
![Naples, FL Annual Precipitation](naples_precip.png)
Many experts have correlated global climate change to increases in intense precipitation and extreme weather events, particularly as the warming of the Earth allows for the atmosphere to hold more water vapor (Center for Climate and Energy Solutions, 2019). In my hometown of Naples, FL, this change typically manifests as the increase of more intense hurricanes and rainfall events, though not necessarily as an increase in total yearly precipitation. The above linear regression model uses precipitation data taken by the NOAA NCEI, and more specifically at station USC00086078 in Naples, FL. The data was collected daily at this land-based station and was summed to represent total precipitation values for each year between 1943 and 2024. Though it does not account for intensity of precipitation, the plot shows that total precipitation in Naples has in fact increased over time. Whether this total increase in precipitation can be attributed to climate change, or whether it results from a combination of other factors, including surrounding oceanic effects, may require further research.

#### References
Center for Climate and Energy Solutions. (2019, July 12). Extreme Precipitation and Climate Change | Center for Climate and Energy Solutions. Center for Climate and Energy Solutions. https://www.c2es.org/content/extreme-precipitation-and-climate-change/

Climate Indicators - Precipitation - Southeast Florida Regional Climate Compact. (2025, July 23). Southeast Florida Regional Climate Compact. https://southeastfloridaclimatecompact.org/initiative/climate-indicators-precipitation/

‌Menne, Matthew J., Imke Durre, Bryant Korzeniewski, Shelley McNeill, Kristy Thomas, Xungang Yin, Steven Anthony, Ron Ray, Russell S. Vose, Byron E.Gleason, and Tamara G. Houston (2012): Global Historical Climatology Network - Daily (GHCN-Daily), Version 3. Naples, FL station USC00086078 Precipitation Data. NOAA National Climatic Data Center. doi:10.7289/V5D21VHZ Accessed Sept. 23, 2025.
Matthew J. Menne, Imke Durre, Russell S. Vose, Byron E. Gleason, and Tamara G. Houston, 2012: An Overview of the Global Historical Climatology Network-Daily Database. J. Atmos. Oceanic Technol., 29, 897-910. doi:10.1175/JTECH-D-11-00103.1.

### 2023 Migration Patterns of the Cattle Egret (Bubulcus ibis)

#### Species description
The cattle egret is a strongly migratory bird that gets its name from its tendency to associate closely with grazing animals. It also is well-adapted to many diverse habitats, including urban areas, and therefore has become a cosmopolitan species inhabiting parts of almost every continent. Despite its migratory nature, it can be difficult to differentiate between migration and dispersal in cattle egrets because they have a high tendency to wander. However, it is known that cattle egrets generally migrate from North American breeding areas south to Central and South America in the winter and from Australia to areas like Tasmania and New Zealand in the winter as well (Ivory, n.d.).

#### Data description
The data used to plot cattle egret migration patterns comes from ecoregion and GBIF data. The ecoregion dataset was from 2017 and provides the study area for the egret migration data. Generally, ecoregions are areas where ecosystems are similar in terms of their composition of abiotic and biotic phenomena (US EPA, 2019), and they are visible as polygons in the plot. The GBIF dataset comes from the Global Biodiversity Information Facility, and is compiled from 2023 citizen science observations of cattle egret (GBIF.org, 2025). It therefore may not be completely accurate, but enough community observations recorded over time allow it to provide a good estimate of egret migration patterns in relation to ecoregion.

#### Methods description
Ecoregion and GBIF datasets were first downloaded and loaded into Python. Python was then used to convert these datasets to GeoDataFrames, normalize the number of egret occurrences by ecoregion and month, and plot the normalized occurrences according to ecoregion and month.

<embed type="text/html" src="egret-migration.html" width="900" height="900">

#### 2023 Cattle Egret Migration Plot
This plot shows global migration patterns of cattle egret by month in 2023. I was hoping to use this information to discover more specific patterns within the chaotic and widespread migration behavior of the cattle egret, and perhaps even determine where the bird might travel for migration purposes vs wandering or other dispersal. The widespread nature of this species makes such a plot generated from occurrences hard to interpret, however. While migratory patterns are visible, such as a gradual shift of occurrences from central Africa to southern Europe corresponding with the change from winter to summer months, specific drivers of travel patterns remain a mystery and require further research and data analysis.

#### References
GBIF.org (29 October 2025) GBIF Occurrence Download  https://doi.org/10.15468/dl.8awfz7

Ivory, A. (n.d.). Bubulcus ibis (cattle egret). Animal Diversity Web. https://animaldiversity.org/accounts/Bubulcus_ibis/

US EPA. (2019, February 13). Ecoregions | US EPA. US EPA. https://www.epa.gov/eco-research/ecoregions
