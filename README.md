# Oysters, Blue Crabs, and Spotted Seatrout (OyBcSt)
***Building Resilience to Environmental Trends and Variability in the Gulf of Mexico***

Oysters, Blue Crab, and Speckled Trout are iconic Gulf species that provide important ecosystem services. Now, they are in decline. To increase resilience, we need to identify stressors and manage stressors, habitats, and populations.
See: [https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout](https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout)

**The Scientific Premise**
- Variations and trends in river discharge drive patterns of primary and secondary production in the bay.
- Multiple stressors are increasing and are overlaid with natural environmental variability.
- Oyster, blue crab, and speckled trout (OyBcSt) populations are being affected by these trends and variability.

**Why focus on OyBcSt?** Active management and restoration efforts towards these species are already underway. Each have different life history strategies and different habitat utilization.  We expect that management activities directed at OyBcSt resilience will improve resilience of *other species* in the estuary as well.

## Climate downscaling
Coarse resolution data sets from general circulation models are downscaled and bias corrected appropriate to the scale of our study area. Our results are being used as forcings for the watershed modeling, physical and biogeochemical modeling. See:
- [Downscaled and bias corrected general circulation model data](https://github.com/OyBcSt/Climate_data)

## Hydrodynamics modeling
A hydrodynamics model calculates sea surface height, water temperature, salinity, and currents. Observations of these physical quantities may only be available for a handful of locations and times, but our model can fill in the gaps, giving us useful data for each point in space and time in the model domain.
- For animations and details about grids, see: [Mobile Bay Hydrodynamics modeling](https://github.com/OyBcSt/oybcst-hydro).
- To compare modeled vs measured salinity and temperature, see our [interactive map of Mobile Bay](https://lisalenorelowe.shinyapps.io/shiny-mb/)

## Ecosystem modeling
CGEM (Coastal General Ecology Model) is an ecosystem model that describes biogeochemical processes regulating carbon, oxygen, nutrients, phytoplankton, and zooplankton. 
- See more about modeling biogeochemical processes with [CGEM (Coastal General Ecology Model)](https://github.com/OyBcSt/cgem-schism)

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
