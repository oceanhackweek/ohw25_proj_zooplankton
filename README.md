## AI Assisted Next Day Predictive Modeling for Zooplankton (ohw25_zooplankton)
Team Members: Syed Usama Imtiaz, Rui Jin, Ismat Jahan, Dafrosa Kataraihya; 
Mentor: Dwight Owens

## Project Summary
Zooplankton Acoustic Profiler (ZAP) systems can be used to monitor abundance and migration patterns of zooplankton in the water column. We wanted to know if a rich ZAP dataset, with accompanying environmental variables, could be used to develop a zooplankton prediction model. Since zooplankton are keystone species in the marine environment, prediction modeling could support aquatic health monitoring systems. 

## Background 
![960px-Haeckel_Copepoda](https://github.com/user-attachments/assets/3aeadd0a-b3b1-4710-9a88-8b87c77751b3)

Zooplankton are keystone species within the marine environment. They are primary consumers, grazing on phytoplankton and acting as a vital link in the food web, transferring energy to higher trophic levels. As such, their abundance and composition could be considered good indicators of overall ecosystem health. Abrupt changes in zooplankton populations can indicate environmental disruptions, which may result from marine heat waves, contamination events or other rapid shifts in environmental conditions. Zooplankton consume phytoplankton. When phytoplankton populations experience rapid growth, we refer to the event as an algal bloom. If these blooms are composed of species that produce toxins, they are termed harmful algal blooms (HABs). Zooplankton grazing can impact the dynamics of these blooms, and in some cases, can even control them by consuming the harmful algae, according to ScienceDirect.com. Given the critical role of zooplankton in the marine food web and their sensitivity to environmental changes, monitoring and predicting zooplankton dynamics can indeed contribute to an early warning system for environmental stressors, possibly including the potential for HABs. By observing trends in zooplankton populations and understanding their interactions with phytoplankton and other environmental factors, scientists can develop models to forecast zooplankton population dyanamics.

## Observing Zooplankton
<img alt="Echosounder Image" src="https://github.com/user-attachments/assets/2fbe2e24-3c04-4ff2-ae57-d63eb8f14029" />

Bioacoustic echosounders are active acoustic instruments that can be used to monitor zooplankton based on backscatter intensities, which correlates with biomass. Many zooplankton ascend to surface waters at night and descend during the day to avoid predators. Echosounders clearly show these vertical movements as shifting “acoustic layers” over 24-hour cycles. For this study, we used data collected by a 200 kHz bioacoustic echosounder manufactured by ASL Environmental Labs (ASL, 2020). 

This instrument was deployed at a depth of 97 metres on Ocean Networks Canada's VENUS Saanich Inlet Instrument Platform, on the southeast coast of Vancouver Island, British Columbia, Canada (see map of Saanich Inlet below). It was co-located with other oceanographic instruments, including a Conductivity-Temperature-Depth instrument, oxygen sensor and others. 
![18056451730_2f98f758ea_b](https://github.com/user-attachments/assets/19e90162-f6ce-4f3a-bf31-176038a8e459)

## Methodology
Our workflow for this study included the following steps:

### Data collection
For this study we combined 2 years of high frequency echosounder data from the Ocean Networks Canada (ONC) observatory, compiled into a dataset by Dr. Mei Sato (Sato et al., 2018) with environmental data from ONC's Saanich Inlet VENUS Instrument Platform (ONC, 2019) and solar irradiance data collected at the nearby Deep Cove Elementary School (School-Based Weather Station Network, 2008-2010). 

### Data Harmonization

### 

## References
ASL Environmental Sciences Zooplankton Acoustic Profiler (ZAP) 200 kHz {Water Column Profiler (WCP)} echosounder. *NERC Vocabulary Server*. British Oceanographic Data Centre / UKRI-NERC, April 17, 2020. Accessed August 21, 2025. http://vocab.nerc.ac.uk/collection/L22/current/TOOL1420/.

Ocean Networks Canada, 2019, "Ten years (2006-2016) of oceanographic temperature, salinity, pressure, density and dissolved oxygen data from the Saanich Inlet cabled observatory", https://doi.org/10.5683/SP2/7UOOVR, Borealis, V1

Sato, Mei; Dower, John F.; Kunze, Eric; Dewey, Richard, 2018, "Second-order seasonal variability in diel vertical migration timing of euphausiids in a coastal inlet (supplemental data)", https://doi.org/10.5683/SP2/KFIH8X, Borealis, V1

School-Based Weather Station Network. “Deep Cove Elementary School.” *Victoria Weather*, Vancouver Island School-Based Weather Station Network, data summary for 2008. Accessed August 21, 2025. [https://www.victoriaweather.ca/data_summary.php?id=62&year=2025](https://www.islandweather.ca/dataavgs.php?field=temperature&interval=60&id=62&year=2008&month=6&showall=1).
