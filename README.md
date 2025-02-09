- This repository contains the core code used in the paper "Establishing an automated heat source calibration framework", Rissaki et al, 2023 DOI:10.3217/978-3-85125-968-1-12
https://diglib.tugraz.at/download.php?id=650c3e202beb7&location=datacite
https://www.researchgate.net/publication/374754787_Establishing_an_automated_heat-source_calibration_framework

- There are two codes in this repository. The 'efficiency.ipynb' code refers to the automatic efficiency determination process. The 'heat_source_parameters.ipynb' code refers to the automatic heat source radii determination.

- In this study (Rissaki et al 2023), the program that was used to run simulations for the heat source calibration was FEAT-WMT. In case of another program used for simulations, the code should be modified according to the format of output files.

- The many simulations of this study were run automatically with a shell script in Manchester University computational shared facility. The core code of the shell script consisted of a for loop and a 'sed' command which replaced a line of a file with another line, so to change a variable value as desired.

- For more information and any question please contact Dimitra Rissaki via email: dimrissaki@gmail.com


Wish you a nice day :)
