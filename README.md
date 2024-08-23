This repository contains code and data for Chung et al., "Intersecting memories of immunity and climate: Potential multiyear impacts of the El Niño—Southern Oscillation on infectious disease spread."

The code is in 2 parts:
1. SIRS-ENSO model (seasonal and biennial)
* Runs the SIRS model
* Generates the SIRS model output
* Analyzes and plots the data
2. MERRA-2/SIRS model (HCoV-HKU1, forced by MERRA-2 specific humidity data)
* Analyzes ONI data (ENSO event years)
* Runs the HCoV-HKU1 SIRS model
* Analyzes and plots the disease data

The model output from the SIRS models (#1) output are provided in the data/ folder.

MERRA-2/SIRS model (#2) specific humidity inputs and disease variable outputs are available on tigress-web at Princeton University: https://tigress-web.princeton.edu/~mvchung/ENSO_disease/paper_MERRA2-SIRS-HKU1-data/

MERRA-2 data can be downloaded from NASA here: https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/data_access/
