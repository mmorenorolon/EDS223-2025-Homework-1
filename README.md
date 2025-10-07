# Homework 1 – EDS 223: Geospatial Analysis & Remote Sensing
*UCSB Masters of Environmental Data Science*

## Purpose  
This repository contains the workflow, data, and outputs for Homework 1 of EDS 223, completed by Melannie Moreno Rolón. The project explores environmental justice in the Metropolitan area of Puerto Rico using the EPA EJScreen (2023) dataset. Specifically, it examines the spatial relationship between low-income communities and estimated cancer risk from air toxics. The analysis was conducted in R using spatial data visualization tools and presented in a Quarto document.

## Repository Contents

- data/ (contains the ejscreen geodatabase used for the assignment)
- ej_screen.qmd  (Quarto document with the code and interpretation)
- ej_screen.pdf (Rendered PDF output of Quarto document with maps and conclusions)
- README.md (this file)
- LICENSE (MIT License)

## Data Access

- The EJScreen 2023 dataset is sourced from the U.S. EPA.
- The geodatabase used (EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb) is stored locally in the data/ folder.
- To run the code, ensure you have the required R packages installed (sf, tmap, tidyverse, here, tinytex).

## Acknowledgements
Data source: https://www.epa.gov/ejscreen

Course: EDS 223 – Geospatial Analysis & Remote Sensing
UCSB MEDS, Bren School of Environment

TA support (Alessandra Vidal Meza) provided throughout the assignment

## Author  
- [Melannie Moreno Rolón](https://github.com/mmorenorolon)

## License
This repository is distributed under the [MIT License](LICENSE)