# Biophysics-435-Final-Project

This GitHub repository contains the BaseStacking_and_SASA_Predictive_Models.ipynb file which contains Deep Learning Models trained to predict base-stacking interactions and solvent accessible surface areas for RNA molecules based on 19 chemical shift datapoints. The raw data is contained in the final_training, final_training_sasa, and final_training_sasa_output csv files.

* final_training.csv contains the chemical shift data
* final_training_sasa.csv contains the SASA data
* final_training_sasa_output.csv contains the chemical shift and SASA data together

Two models were trained to predict base-stacking interactions: a Multilayer Perceptron Model and a Random Forest Regression Model.
Three types of models were trained to predict each of the 5 SASA tasks: a Deepchem Multitask Regressor, an MLP, and a Random Forest Regressor.

For further information, please refer to the formal report pdf in this repository.

-- Authors: Kyrillos Abdallah, Andrew Looka, Joseph Mekhael
