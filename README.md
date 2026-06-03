# Code for Nicknish and Cronin (2026)


## File descriptions

imports.ipynb: a Jupyter notebook containing the necessary inputs to run the code contained in other notebooks (this notebook is executed from within the main analysis and plotting scripts).



SNOTEL data can be downloaded from this link. The filtered version of the dataset (i.e., the variable `allStateDict_filtered` is the analysis scripts can be loaded with the following line of code if you don't have the SNOTEL data downloaded.

np.load('...../data/allStateDict_filtered.npz',allow_pickle=True)['allStateDict_filtered'].item()
