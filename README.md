Introduction

File 1 **Problem Statement** presents the research problem and the partial differential equations (PDEs) used.

File 2 **FDM Simulation and Simulation Data** uses the finite difference method (FDM) to solve the PDEs and obtains simulation results—namely, temperature fields at different depths and times. The temperatures at depths of 0, 1, 2, 3, 4, and 5 m are saved in the file *fdm_observation_data.csv*. These data will be used as observation data for future inversion.

File 3 **Forward Model using PINNs** designs a physics-informed neural network (PINNs) to solve the defined PDEs. Its function is equivalent to that of the FDM and serves as a preparatory step for PINNs-based inversion.

File 4 **Inversion using PINNs** applies PINNs together with the observation data (*fdm_observation_data.csv*) to invert the soil’s thermodynamic parameters.
