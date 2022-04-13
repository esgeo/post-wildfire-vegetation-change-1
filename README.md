# ea-2022-post-wildfire-vegetation-change
Earth Lab Capstone Project: Post-Wildfire Vegetation Change

# Purpose
The Chimney Tops 2 Wildfire occurred from November 23 to November 28, 2016 in Great Smoky Mountains National Park and burned approximately 11,000 acres within the park. We are interested in exploring the post-fire vegetation recovery in Great Smoky Mountains National Park by assessing the vegetation type and structure along with burn severity to understand ecosystem recovery and risk assessment for future wildland fires.
# Project Environment
We study the post-wildfire vegetation change for the Chimney Tops 2 Fire using a python environment. We run this environment in a directory called `earth-analytics`. To install and run the python environment for this project, please use the instructions below.
## Installing and Running the Environment
1. Change your directory to `earth-analytics`.
2. Download the file `neon-environment.yml`, which contains instructions on how to install the environment, into this directory. 
3. Create the environment by running: `conda env create -f neon-environment.yml`.
4. Once the environment is installed, activate it by running: `conda activate earth-analytics-neon`. 
# Data Sources
1. NEON LiDAR Ecosystem Structure (https://data.neonscience.org/data-products/DP3.30015.001)
* **Reference**: National Ecological Observatory Network. 2022. Data Product DP3.30015.001, Ecosystem structure. Provisional data downloaded from https://data.neonscience.org on March 31, 2022. Battelle, Boulder, CO, USA NEON. 2022.
2. NEON Spectrometer Reflectance (https://data.neonscience.org/data-products/DP1.30006.001)
* **Reference:** National Ecological Observatory Network. 2022. Data Product DP3.30006.001, Spectrometer orthorectified surface directional reflectance - mosaic. Provisional data downloaded from https://data.neonscience.org on April 3, 2022. Battelle, Boulder, CO, USA NEON. 2022.
3. LandFire Condition Class Grid (https://landfire.gov/fireregime.php)
4. NASA VIIRS Fire Detection (https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/viirs-i-band-active-fire-data)
# Workflow
