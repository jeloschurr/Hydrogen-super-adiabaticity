These are the codes related to the paper "Super adiabatic combustion of H2/air and H2/N2O mixtures" (https://doi.org/10.1016/j.combustflame.2024.113397).
The mechanism used for this simulations are from the paper of Han et al. "An experimental and kinetic modeling study on the laminar burning velocity of NH3+ N2O+ air flames" (https://doi.org/10.1016/j.combustflame.2021.01.027)

The file "0D_Simulations.ipynb" simulates super adiabaticity in a 0D constant volume homogeneous batch reactor.
The file "0D_HRR.ipynb" includes heat release simulations to the 0D batch reactor. The most important reactions are beforehand selected and printed to one graph with the total heat release.
The file "1D_NOx_noNOx.ipynb" is showing the importance of NOx chemistry on the example of 1D flame simulations. Only when including NOx chemistry to the mechanism, super adiabaticity can be observed.
