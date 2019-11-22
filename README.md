# EarlyQCD

This repository contains code and data relating to the paper: [1] arXiv: 1911.01432 (https://arxiv.org/abs/1911.01432)

The code and data herein calculate the possible mixing angles for and current exclusion limits on the benchmarks presented in [1]. Some of the data used is from Figure 5 of [2] arXiv:1711.05722 (https://arxiv.org/abs/1711.05722). The data was extracted using a plot digitizer app [3] https://automeris.io/WebPlotDigitizer/

## Software Versions Used
Mathematica: Version 11.2.0.0

Jupyter: Version 4.4.0

Python: Version 3.6.7

## Brief Description of Files in this Repository
### Directories:

Benchmarks - contains .dat files of parameters for the six benchmarks used in this paper. These .dat files were created by Djuna Croon (dcroon@triumf.ca).

MSsin2Theta - contains .dat files of <img src="https://render.githubusercontent.com/render/math?math=M_S"> vs <img src="https://render.githubusercontent.com/render/math?math=sin^2 \theta (\times BR(S \rightarrow b \bar{b}))"> for the 6 benchmarks.

Constraints - contains .csv files of constraints on <img src="https://render.githubusercontent.com/render/math?math=sin^2 \theta (\times BR(S \rightarrow b \bar{b}))">  as a function of <img src="https://render.githubusercontent.com/render/math?math=M_S"> from LEP and OPAL. These were obtained from Figure 5 of [2] using a plot digitizer app [3].

DiscoveryPotential - contains .csv files for Higgs and Z factory discovery potentials at 95% C.L. _Z5 is a 5 sigma significance, whereas _Z3 is a 3 sigma significance. These were obtained from Figure 5 of [2] using a plot digitizer app [3].

### Files:

MixingAngleLimitPlot.ipynb - This notebook walks through reading in the data and creating Figure 8 of [1]. Note that the plot in the paper was created using Mathematica instead for convenience, but the process is the same.

MSTheta.png - The final plot.

MixingAngleAnalysis_BM1.nb through MixingAngleAnalysis_BM6.nb - The Mathematica notebooks which take the files in Benchmarks/ and create the files in MSsin2Theta/ which are then used in MixingAngleLimitPlot.ipynb to create the final plot.

## Summary of Results


## Notes
