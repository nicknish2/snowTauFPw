# Code for Nicknish and Cronin (2026)

## File descriptions

**imports.ipynb**: A Jupyter notebook containing the necessary inputs to run the code contained in other notebooks (this notebook is executed from within the main analysis and plotting scripts).

**analysisScripts**: Contains Jupyter notebooks that perform the main computations underlying the figures in the paper.

**plottingScripts**: Contains a Jupyter notebook for making all the figures in the paper.

**data**: Folder with SNOTEL station metadata and all the input data needed to make the plots in the plottingScript code.

SNOTEL data can be downloaded from this [link](https://wcc.sc.egov.usda.gov/nwcc/tabget). The filtered version of the dataset (i.e., the variable `allStateDict_filtered` is the analysis scripts) can be loaded with the following line of code if you don't have the SNOTEL data downloaded:
`allStateDict_filtered = np.load('...../data/allStateDict_filtered.npz',allow_pickle=True)['allStateDict_filtered'].item()`

The file allStateDict_filtered.npz is located in the Zenodo repository associated with this work.



For any questions or comments, please contact Paul Nicknish (nicknish@mit.edu).
