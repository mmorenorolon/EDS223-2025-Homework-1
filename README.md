# Environmental Justice in the Puerto Rico Metro Area
*UCSB Masters of Environmental Data Science*

## Purpose  
This repository contains the workflow, data, and outputs for Homework 1 of EDS 223, completed by Melannie Moreno Rolón. The project explores environmental justice in the Metropolitan area of Puerto Rico using the EPA EJScreen (2023) dataset. Specifically, it examines the spatial relationship between low-income communities and estimated cancer risk from air toxics. The analysis was conducted in R using spatial data visualization tools and presented in a Quarto document.

## Repository Contents

- data/ (Contains the ejscreen geodatabase used for the assignment)
- ej_screen.qmd  (Quarto document with the code and interpretation)
- ej_screen.pdf (Rendered PDF output of Quarto document with maps and conclusions)
- README.md (This file)
- LICENSE (MIT License)

## Data Access

- The EJScreen 2023 dataset is sourced from the U.S. EPA.
- The geodatabase used (EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb) is stored locally in the data/ folder.
- To run the code, ensure you have the required R packages installed (sf, tmap, tidyverse, here, tinytex).

## References and Acknowledgements

This project was made possible through publicly accessible geospatial datasets and open-source tools supporting environmental justice research.

EJScreen 2023 data was sourced from the U.S. Environmental Protection Agency (EPA), whose commitment to environmental transparency enables community-level equity assessments across the United States and its territories.

Special thanks to the developers and maintainers of the R packages used in this analysis, including {sf}, {tidyverse}, {tmap}, {here}, and {tinytex},  which supported geospatial data processing, visualization, and reproducible reporting in Quarto. 

This work was completed as part of EDS 223 – Geospatial Analysis & Remote Sensing in the UCSB Master of Environmental Data Science (MEDS) Program at the Bren School of Environmental Science & Management. Guidance and feedback were provided by TA Alessandra Vidal Meza.


## Author  
- [Melannie Moreno Rolón](https://github.com/mmorenorolon)

## License
This repository is distributed under the [MIT License](LICENSE)