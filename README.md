This script operates on the "MSD.agr" files generated by the diffusion command in cpptraj. Specifically, this script takes in 10 "MSD.agr" files,
one for each replicate simulation containing 20 sugars and your choice of water model. Then, each files contains the averaged MSD across the 20 
sugars within one sim, and the script then averages across all 10 to maximize sampling. Then, an MSD vs time plot is generated and the 
diffusion coefficient is calculated from the slope of this graph and converted into the appropriate units (m^2/s). In this example, a-D-Glucose with the OPC water model is used. I have included the MSD files as well so the user can test the script for themselves. 
