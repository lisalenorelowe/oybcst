# Oysters, Blue Crabs, and Spotted Seatrout (OyBcSt)
***Building Resilience to Environmental Trends and Variability in the Gulf of Mexico***

Oysters, Blue Crab, and Speckled Trout are iconic Gulf species that provide important ecosystem services. Now, they are in decline. To increase resilience, we need to identify stressors and manage stressors, habitats, and populations.
See: [https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout](https://restoreactscienceprogram.noaa.gov/projects/oysters-blue-crabs-seatrout)

**The Scientific Premise:** Variations and trends in river discharge drive patterns of primary and secondary production in the bay. Multiple stressors are increasing and are overlaid with natural environmental variability. OyBcSt populations are being affected by these trends and variability.

**Why focus on OyBcSt?** Active management and restoration efforts towards these species are already underway. Each have different life history strategies and different habitat utilization.  We expect that management activities directed at OyBcSt resilience will improve resilience of *other species* in the estuary as well.

## What are the management needs?
Managers want to know
- How are fisheries populations related to bay ecosystem trends and patterns? What are the human drivers?
- What are the underlying causes of fish kills? What are the cumulative stressor effects on fishery populations?
- What are quality trends and patterns? Can we establish a water quality baseline condition?
- How do we improve habitat restoration project success?

**Managers would like access to:** monitoring data and visualization tools, an improved understanding of the changing seascape, targeted analysis and summary of environmental status and trends, and evidence of direct linkage between local watershed management to improvements in bay water quality and habitats. 

## What we plan to provide

**OyBcSt** is a *team of teams* working to answer these questions and provide the resources managers need.  Our efforts include field and lab studies, ecosystem services valuation, numerical modeling, sample processing and data analysis, and historical analysis and data interpretation.

**In a nutshell**, we need to 
- Relate environmental change to change in population productivity and biomass 
- Quantify how change in populations affects living resource ecosystem services and values
- Predict how future human socio-economic pathways will affect this system

## From our Teams
Here are some interactive demos showing results and analysis from some of the teams.  Our work is open and shared with the public, and we will add more demos as they become available.

### Climate Team
Coarse resolution data sets from general circulation models are downscaled and bias corrected appropriate to the scale of our study area. Our results are being used as forcings for the watershed modeling, physical and biogeochemical modeling. See:
- [Downscaled and bias corrected general circulation model data](https://github.com/OyBcSt/Climate_data)

### Hydrodynamics Team
A hydrodynamics model calculates sea surface height, water temperature, salinity, and currents. Observations of these physical quantities may only be available for a handful of locations and times, but our model can fill in the gaps, giving us useful data for each point in space and time in the model domain.
- For details on model runs and a collection of animations, see: [Mobile Bay Hydrodynamics modeling](https://oybcst.github.io).
- To compare modeled vs measured salinity and temperature, see our [interactive map of Mobile Bay](https://lisalenorelowe.shinyapps.io/shiny-mb/)

### Ecosystem Modeling Team
CGEM (Coastal General Ecology Model) is an ecosystem model that describes biogeochemical processes regulating carbon, oxygen, nutrients, phytoplankton, and zooplankton. 
- To run CGEM as a water column with no transport, see our Jupyter Notebook in the [cgem-schism repo](https://github.com/OyBcSt/cgem-schism)
- For updates on coupling CGEM with SCHISM, and details about compiling, running, and visualizing CGEM with SCHISM, see [the CGEM repo](https://github.com/oybcst/CGEM).

### Fisheries Analysis Team
Analysis of species data may be improved by using modeling data to fill gaps in measured data.  See:
- [Phenology of Fish and Inverebrates in Mobile Bay, AL](https://github.com/OyBcSt/oybcst-fish)

### Watershed Modeling Team
The hydrodynamics and water quality in Mobile Bay is affected by water and nutrients flowing in from the Mobile River Basin.  See:
- [Modeled vs Measured streamflow, sediment, nitrate, and phosphate](https://github.com/oybcst/watershed-simulated-vs-observed)

### Add a Project
For OyBcSt, our team of teams: We will continute work on making our results accessible and available.  Add a Notebook for your project here.

New to Notebooks?  Start out with a template:
- [Template for creating an Interactive Notebook with Python](https://github.com/OyBcSt/project-template-python)
- [Template for creating an Interactive Notebook in R](https://github.com/OyBcSt/project-template-r)


## Thank you!
This work is a result of research funded by the National Oceanic and Atmospheric Administration's RESTORE Science Program under award NA19NOS4510194, awarded to University of South Alabama, Mississippi State University, Auburn University, and North Carolina State University.

The hydrodynamics modeling for this project is done on Expanse, at the San Diego Supercomputer Center (SDSC), and the modeling data is being hosted on Open Storage Network (OSN), through allocation EES210015 from the Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support, which is supported by National Science Foundation grants #2138259, #2138286, #2138307, #2137603, and #2138296.

Work at both providers was done under the Extreme Science and Engineering Discovery Environment (XSEDE), which was supported by National Science Foundation grant number #1548562.  We thank Mark W. Van Moer of the National Center for Supercomputing Applications (NCAR) for advanced visualization support, which was made possible through the XSEDE Extended Collaborative Support Service (ECSS) program.
