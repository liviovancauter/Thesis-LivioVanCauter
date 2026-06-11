Folder "OA pathway" contains files for het processing and analyzation of the OA barriers based on the achieved QM calculations. "OA-DataManipulationMicrokinetic-FINAL" contains functions that calculate the energy barrier of the OA step under 2 different scenarios. Scenario 1 assumes that PdL is the resting state, while scenario 2 assumes PdL2 is the resting state (both monoligated pathway, just different resting states). These functions are evaluates at different temperatures, ligands, aryl halide and boron species. The results of these different conditions is given in the CSV file "MKM-df_OA_barriers". The analysis of these 2 scenarios, discussed within the thesis, are given in the files "OA_barrier_analysis-SC1" and "OA_barrier_analysis-SC2", respsectively. 


Folder "Initial TM pathway" contains the processing and analyzation of the INTIAL TM barriers based on the initial pathway that was assumed. "TM-DataManipulationMicrokinetic-INITIAL" uses a similar structure as for the OA to calculate the reaction barriers under different reaction conditions. Idem for the CSV file and the analysis.


Folder "Revised TM pathway" contains the processing and analyzation of the REVISED TM barriers based on the pathway including dimer intermediates. "TM-ADJUSTED-DIMERS-CORR-FINAL" uses a similar structure as for the OA to calculate the reaction barriers under different reaction conditions. Idem for the CSV file and the analysis.

Folder "Microkinetic model" contains the final microkinetic model named "MicrokineticModel-SweepAnalysis-FINAL". This file contains the full microkinetic model used to predict the reaction yield under certain reaction conditions. The integration of QM data and machanism definition is also present.

"Drawing energy plot - reaction mechanism": contains code to plot energy plot profile in different forms. Used purely for visualization.