# EDS 223 Homework 2: Exploring Patterns of Environmental Justice

![LA HOLC](./holc-la.jpg) Image credits: [Digital Scholarship Lab, University of Richmond, Mapping Inequality Project](https://dsl.richmond.edu/panorama/redlining/data/CA-LosAngeles)

Author: Ava Robillard

This repository contains a Quarto document with an exploration of environmental justice patterns. The goal of this project is manipulate vector and raster data to build multi-layer maps in R with `tmap`.

The project aims specifically to use EJScreen spatial data at the Census block group level, HOLC grade designations, and bird biodiversity observations to visualize relationships between historical redlining and the present-day environmental justice and biodiversity observations in Los Angeles, California.

## Repository Structure

The **HW2.qmd** file contains the main analysis and visualizations.

The **data** folder contains the ejscreen, HOLC redlining, and biodiversity observation data imported for the analysis.

``` bash
EDS223-HW2
│   README.md
│   HW2.qmd
│   Rmd/Proj files    
│
└───.gitignore
     └───data
         └───ejscreen
         └───gbif-birds-LA
         └───mapping-inequality
```

## Data

The US Environmental Protection Agency's former EJScreen: Environmental Justice Screening and Mapping Tool provides data on environmental and demographic variables for the US at the Census block group level. The data can be found on the [unofficial website.](https://pedp-ejscreen.azurewebsites.net)

The [University of Richmond Digital Scholarship Lab](https://dsl.richmond.edu/) have digitized maps and information from the Home Owner's Loan Corporation (HOLC) as a part of the [Mapping Inequality Project](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58). The maps of HOLC designations for Los Angeles are used for this analysis.

The [Global Biodiversity Information Facility](https://www.gbif.org/) is the largest aggregator of biodiversity observations in the world, and include a location and data that a species was observed. Bird observations from 2021 onward are used for this analysis.

## References

This assignment was created as a part of EDS 223: Geospatial Analysis & Remote Sensing, taught by Annie Adams.

[EJScreen](https://pedp-ejscreen.azurewebsites.net/) [Data File]. Accessed Oct 11, 2025

[Digital Scholarship Lab, Mapping Inequality project: HOLC redlining data](https://dsl.richmond.edu/panorama/redlining/data) [Data File]. Accessed Oct 11, 2025

[Global Biodiversity Information Facility: bird observation data](https://www.gbif.org/) [Data File]. Accessed Oct 11, 2025

-   replace links with ones to data, is data file okay?
