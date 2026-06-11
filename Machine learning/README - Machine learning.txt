Folder "Baseline ML models" contains all the 6 baseline models made within this thesis, using molecular descriptors from the AQME package. For all baseline models, a ".pkl" file is added that contains the information of the Optuna hyperparameterization study. This is so that the whole Optuna study doesn't need to be repeated over again, and can easilily be loaded into the file.

The folder "Hybrid mechanistic ML" contains the hybrid mechanistic ML file, together with the pkl file for model loading. Data from this model is located in the "Data" folder.

The folder "Appending mechanistic descriptors" contains a script for the general calculation of different mechanistic descriptors. These functions are then called for the specific conditions inside of the Reizman et al. database. The results is that the database is appended with mechanistic descriptors specific for that data points reaction conditions (temperature, ligand, etc.). The result from this, given as a Excel file, is also located in that folder.

