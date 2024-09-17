# niche_overlap
data for the manuscrip> Ecosystem, spatial and trophic dimensions of niche partitioning among freshwater fish predators
Ecosystem, spatial and trophic dimensions of niche partitioning among freshwater fish predators

Description of the data and file structure

Data obtained by telemetery  - description of Material anad methods and the dataset 

Fish telemetry
A total of 90 individuals (15 pike and 15 catfish in each waterbody) were caught and tagged for the study. Individuals were measured and weighed prior to tagging (Table 2). Acoustic transmitters (Lotek Wireless Inc, MM-M-11-28-PM, 65 x 28 mm, weight in air of 13 g), including pressure (all waterbodies), motion (Milada and Most) and temperature (Rimov) sensors, burst rate 25 s (Milada and Most) or 15 s (Rimov) were implanted as described in detail in Říha et al. (2022, 2021). The fish were caught and tagged between 5 and 10 May 2015 in Milada and Most, and between 19 and 20 April 2017 in Rimov.

Three separate MAP positioning systems (Lotek Wireless Inc., Canada) were deployed in all waterbodies to track the tagged fish. Each system consisted of tens of receivers (Lotek Wireless Inc., WHS3250; 44, 47 and 91 receivers in Milada, Most and Rimov, respectively) deployed in arrays (Fig. 1). A detailed description of the design, deployment and accuracy of the arrays can be found for Milada and Most in Říha et al. (2021) and for Rimov in Říha et al. (2022). For the purpose of this study, tracking records of summer period June – September (year 2015 in Milada and Most, 2017 in Rimov) were selected to match data collected for stable isotopes (see below).

The locations of the individual fish were calculated using the proprietary post-processing software UMAP v.1.4.3 (Lotek Wireless Inc., Newmarket, Ontario, Canada). The filtering and further post-processing of the fish locations are described in detail in Říha et al. (2021). The filtered fish locations, which included all three dimensions (latitude, longitude and depth), were then matched with the bathymetry maps of each waterbody (with a grid resolution of 1 x 1 m). The bottom depth was determined at each fish location. Fish depth and bottom depth at the fish location were used as two meaningful niche axes to analyze fish spatial niche. Depth was considered as a vertical axis and bottom depth as a horizontal axis to account for differences between benthic and open water areas (Moraes et al., 2021; Říha et al., 2015).

Files and variables

File: primary_data_telemetry.csv

Description: 

Variables

species: species name, only one species European catfish (Silurus glanis)

lake: lake name 

timestamp_utc: time and date of individual location 

fishid: code of indivudal identity 

depth: depth of fish 

bottom_depth: depth of the bottom at the location of fish 

Code/software

csv format, so any software capable to work with the format
