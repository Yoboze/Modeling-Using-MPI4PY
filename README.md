# Minimization of high computational cost in data preprocessing and modeling using MPI4Py

This project entails application of parallel processing techniques to data preprocessing and modelling.
A popular python library MPI4Py is deployed to speed up the preprocessing of data. For comparative analysis, 
a COVID-19 data is preprocessed with and without MPI. We analyze the results of the two scenarios.

The step by step process to run our code:

1. You can run each cell at time or

2. Go to kernel >> Restart Kernel and Run all

3. Before you run make sure that the following python libraries are imported.
   - numpy
   - pandas
   - matplotlib
   - sklearn for minimax scaling
   - time for checking cpu time




Below is the system design

![System Design](Figures/sys_design.png)




Data can be downloaded from https://www.tn.gov/health/cedep/ncov/data/downloadable-datasets.html

**The link to the Paper Published:** https://www.sciencedirect.com/science/article/pii/S2666827023000361

