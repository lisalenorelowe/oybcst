# Oysters, Blue Crabs, and Spotted Seatrout
***Building Resilience to Environmental Trends and Variability in the Gulf of Mexico***

This project explores how oyster, blue crab, and spotted seatrout populations respond to human and environmental changes with the goal of improving the management of these economically and culturally important species.  
See: [https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout](https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout)

There are mutiple components, including:

## Climate modeling
Coarse resolution data sets from general circulation models are downscaled and bias corrected appropriate to the scale of our study area. These results are being used as forcings for the watershed modeling, physical and biogeochemical modeling. See:
- [Downscaled and bias corrected general circulation model data](https://github.com/OyBcSt/Climate_data)

## Hydrodynamics modeling
A hydrodynamics model calculates sea surface height, water temperature, salinity, and currents. Observations of physical quantities are only available at a handful of locations and times, but our model can fill in the gaps, giving us useful data for each point in space and time for the area of interest.
- For animations and details about grids, see: [Mobile Bay Hydrodynamics modeling](https://github.com/OyBcSt/oybcst-hydro).
- To compare modeled vs measured salinity and temperature, see our [interactive map of Mobile Bay](https://lisalenorelowe.shinyapps.io/shiny-mb/)

## Ecosystem modeling
Phytoplankton and zooplankton dynamics depend on salinity, temperature, and nutrients.  See more about modeling biogeochemical processes with [CGEM (Coastal General Ecology Model)](https://github.com/OyBcSt/cgem-schism)

## Fisheries analysis
Analysis of species data may be improved by using modeling data to fill gaps in measured data.  See:
- [Phenology of Fish and Inverebrates in Mobile Bay, AL](https://github.com/OyBcSt/oybcst-fish)

## Add a Project
New to Notebooks?  Start out with a template:
- [Template for creating an Interactive Notebook in R](https://github.com/OyBcSt/project-template-r)
- [Template for creating an Interactive Notebook with Python](https://github.com/OyBcSt/project-template-python)


## Thank you!
This work is a result of research funded by the National Oceanic and Atmospheric Administration's RESTORE Science Program under award NA19NOS4510194, awarded to University of South Alabama, Mississippi State University, Auburn University, and North Carolina State University.

The hydrodynamics modeling for this project is done on Expanse, at the San Diego Supercomputer Center (SDSC), and the modeling data is being hosted on Open Storage Network (OSN), through allocation EES210015 from the Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support, which is supported by National Science Foundation grants #2138259, #2138286, #2138307, #2137603, and #2138296.

Work at both providers was done under the Extreme Science and Engineering Discovery Environment (XSEDE), which was supported by National Science Foundation grant number #1548562.  We thank Mark W. Van Moer of the National Center for Supercomputing Applications (NCAR) for advanced visualization support, which was made possible through the XSEDE Extended Collaborative Support Service (ECSS) program.
