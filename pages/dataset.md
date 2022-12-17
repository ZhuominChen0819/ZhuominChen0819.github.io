---
layout: page-fullwidth
title: "Available Datasets"
permalink: "/dataset/"
header:
   image_fullwidth: "header_datasets.jpg"
---

This data page is a work in progress, and datasets are available upon [request]({{ site.url }}{{ site.baseurl }}/contact/).

### 1. The Cold Pool Index based on ROMS-NWA (1958-2007) and GLORYS12v1 (1993-2021)
* The spatial and temporal characteristics (spatial extents, volume, temperature, salinity, etc.) of the Cold Pool are quantified in the numerical model ([ROMS-NWA](https://doi.org/10.1029/2018JC014148)) and [GLORYS12v1](https://resources.marine.copernicus.eu/?option=com_csw&view=details&product_id=GLOBAL_REANALYSIS_PHY_001_030) reanalysis product.   
* The detailed methodology is documented in [Seasonal Variability of the Cold Pool over the Mid-Atlantic Bight Continental Shelf](https://doi.org/10.1029/2018JC014148) and [Interannual Variability of the Mid-Atlantic Bight Cold Pool](https://doi.org/10.1029/2020JC016445).
<img class="t60" src="{{ site.urlimg }}coldpool_50yr_1d_glorys12v1_combine1.png" alt="">   

### 2. The SSH-based Gulf Stream Index (GSI), 1993-2021 
* The GSI is calculated based on the method presented by [Pérez-Hernández and Joyce (2014)](https://doi.org/10.1175/JPO-D-13-0136.1), which is a simple 16-point GS index constructed by selecting grid points following the maximum Standard deviation of sea level height anomalies every 1.33° longitude between 52° and 72°W and averaging them. The value of 1.33° is based on the resolution of satellite dataset from AVISO. 
* We followed the same method, except using the dataset from CMEMS, which has a 0.25°x0.25° resolution. Therefore we select points every 1° between 52° and 72°W and average them, and there are 21 points in total.
* This GSI has been documented in detail in the published paper [Seasonal Prediction of Bottom Temperature on the Northeast U.S. Continental Shelf](https://doi.org/10.1029/2021JC017187).

### 3. The T200m-based GSI (or GS North Wall Index), 1954-2021 
* This GSI is calculated following [<i>Joyce et al.</i> (2009)](https://doi.org/10.1175/2008JCLI2690.1), but with the temperature data from the [EN4.2.2](https://www.metoffice.gov.uk/hadobs/en4/) dataset. 
* [<i>Joyce et al.</i> (2009)](https://doi.org/10.1175/2008JCLI2690.1) smoothed the WOD with a Gaussian taper temporally (0.5 year) and spatially (1.25° in latitude and 2.5° in longitude), therefore it is on seasonal time scale.
* This GSI using gridded [EN4.2.2](https://www.metoffice.gov.uk/hadobs/en4/) does not require a Gaussian taper for temporal smoothing, thus the resulting index is monthly.
* This GSI has been documented in detail in the published paper [Seasonal Prediction of Bottom Temperature on the Northeast U.S. Continental Shelf](https://doi.org/10.1029/2021JC017187).

<img class="t60" src="{{ site.urlimg }}FigureS3.jpg" alt="">   
<b>Figure.</b> The time series of three Gulf Stream Indices (GSIs). The black line represents the seasonal subsurface T200-based GSI (1954-2017) calculated using the WOD data. The red line is the T200-based monthly GSI using the gridded EN4 data (1954-2018). The cyan line represents the SSH-based monthly GSI (1993-2018). [Figure Source](https://doi.org/10.1029/2021JC017187)

## <a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/contact/">Data Request›</a>
