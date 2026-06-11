This folder contains all the raw and processed experimental datasets from Reizman et al. and Perera et al., including all curated input files used for model training and
validation. Files for exploratory data analysis on the original datasets are placed in a dedicated folder.

"Reizman database - all cases - raw": Contains the original dataset of 417 datapoints extracted from the SI of the original paper.

"Reizman_database - COMPLETE - BASELINE": Curated dataset, where the duplicates and Xanthphos (bidendate ligand) are removed from the dataset. Molecular descriptors using the AQME package and the script "AQME-APPEND-REIZMAN-FINAL" (given in quantum chemistry file) were used to generate these descriptors. Idem for the Perera dataset.

"Reizman_database - MECH-ML-APPEND - FINAL": Adaptation of the "Reizman_database - COMPLETE - BASELINE", where also mechanistic descriptors from QM calculations and qualitative insights of microkinetic model are adopted. This dataset is used for the hybrid mechanistic ML model developed within this thesis.

"Reizman_database - DATAVIS": Used for the datavisualization.

Note: the KRAKEN base contains ligand descriptors from an online database and was used in an older version of the code. They are non relevant to the whole code and to any other code that is used within the thesis, and never used. They are however, kept in for the stability of the code but could be easily removed to get a cleaner code.

