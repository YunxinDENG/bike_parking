# Yunxin Deng's Dissertation Data Processing

This repository contains all the code used for data processing in Yunxin Deng's dissertation. The repository is organized to provide transparency and reproducibility of the data analysis.

## Contents

- **Code**: This directory includes all the scripts and programs used for data manipulation and analysis.
  - `data_preprocess.ipynb`: Main script for data processing.
  - `Other Script`: Any additional scripts that were used.

- **Data**: This directory contains the raw data files used in the dissertation.
  - `allPOI2023.csv` : POI data applied from DIGIMAP Data Service.

- **Results**: This directory contains the output files generated from the data processing scripts.
  - `thiesson_all.csv` : Processed data files (replace with the actual file names).

- `data_source.md`: A document summarizing the sources of all data used in the dissertation.

## Usage

Before running the scripts, ensure you have the necessary software and packages installed. The code is written in Python and should be compatible with Python 3.10.5, packaged by conda-forge.

1. Clone the repository:
   
   `git clone https://github.com/[your-username]/yunxin-deng-dissertation.git`
   
3. Navigate into the repository:

   `cd yunxin-deng-dissertation`


## Analysis Steps in External Software

- **MGWR Analysis**: The geographically weighted regression (GWR) analysis was performed using the MGWR2.2 software. This software is specifically designed for conducting local GWR analysis and provides more detailed spatial insights.

- **MCLP Model Site Selection**: The multi-criteria location problem (MCLP) model for site selection was completed within ArcGIS using the Location Solver tool. This tool facilitates the decision-making process by considering multiple factors and criteria.
