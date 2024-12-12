# AML-blood-glucose-project

Project_EDA.ipynb contains exploratory data analysis pertaining to our predictive task. However, most of the charts found in that file are not the final ones incorporated in our presentation/project report. The file also contains the first step in preprocessing/cleaning the data by rebalancing the number of rows for each patient in the data. The resulting dataframe is passed as a .csv file to the 'Preprocess_data_final.ipynb' notebook, where missing values are handled through imputation and feature removal.

The final processed .csv file is unfortunately too big for GitHub to accept, but we have provided a truncated version (about 10,000 rows) of the preprocessed dataset titled 'New_clean_dataset.csv'.

Blood_Glucose_EDA_Model_Analysis.ipynb contains most of the preliminary models used to predict bg+1:00 before the hybrid model is introduced. Most of the EDA charts included within our presentation/report originate from this file as well. The best performing Random Forest model can be found in that notebook. In addition, other ensemble and regression methods such as XGBoost, CatBoost, and Elastic Net are also contained within the file. 

Final_RNN_and_Transformer_Code.ipynb contains the final hybrid RNN and transformer model trained using the PyTorch library. It utilizes Torch tensors and embeddings within the hybrid model train loop, which is computationally demanding and slow to run. It is recommended not to run it as the output is already in the file for reference. It also serves as the basis for the best model trained and saved for usage in the Anvil web application interface.


The code above represents a collaborative effort of the team consisting of: Andy Ma, Carissa Ing, Sarah Dominguez, Siboney Cardoso, and Utkarsh Garg.


If you are interested in accessing the Anvil application user interface, the link can be found here: https://a3m7qhut2ycixilv.anvil.app/CRZXZOYMBFSHPXQILTMJBXV7

Unfortunately, to use the interface, the backend (server-side) module needs to be running concurrently on a machine somewhere, where the hybrid model and all other necessary preprocessing code is stored to supplement the user interface. You will need to contact Andy Ma, the site's owner, to run the backend to test the user application with the .csv file titled 'Anvil_test.csv' in the Git repository. He can be reached via email through andy.m@utexas.edu.



To Prof. Ghosh and the TA team, thank you for teaching us a great deal about machine/deep learning over the semester!
