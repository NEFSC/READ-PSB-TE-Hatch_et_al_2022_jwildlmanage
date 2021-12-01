# A data compendium for: "Estimating the complex patterns of survey availability for a highly-mobile marine animal"

![gitleaks](https://github.com/jmhatch-NOAA/READ-PSB-TE-Hatch_et_al_2021_jwildlmanage/actions/workflows/secretScan.yml/badge.svg)

Our paper is online here:

> Hatch JM, Haas HL, Sasso CR, Patel SH, Smolowitz RJ. (2021). *Estimating the complex patterns of survey availability for a highly-mobile marine animal*. The Journal of Wildlife Management, Online at <https://doi.org/xxx/xxx>
>

## How to cite

Please cite this data compendium as:

> Hatch JM, Haas HL, Sasso CR, Patel SH, Smolowitz RJ. (2021). *Data compendium for Estimating the complex patterns of survey availability for a highly-mobile marine animal*. Accessed DD MM YYYY. Online at <https://doi.org/xxx/xxx>
> 

## How to use (an example)

After downloading, you can load the data from this compendium into R with:
```r
## load needed libraries
library(dplyr)
library(raster)

## load data
avg_dive_dur = './data/avg_dive_dur/Cc_avg_dive_dur.nc' %>% raster::stack()

## plot
plot(avg_dive_dur)
```

---
This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
