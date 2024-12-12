# AML-blood-glucose-project

Project_EDA.ipynb contains exploratory data analysis pertaining to our predictive task. However, most of the charts found in that file are not the final ones incorporated in our presentation/project report. The file also contains the preprocessing/data cleaning code used to modify the original dataset using a variety of imputation methods and feature removal techniques.

Blood_Glucose_EDA_Model_Analysis.ipynb contains most of the preliminary models used to predict bg+1:00 before the hybrid model is introduced. Most of the EDA charts included within our presentation/report originate from this file as well. The best performing Random Forest model can be found in that notebook. In addition, other ensemble and regression methods such as XGBoost, CatBoost, and Elastic Net are also contained within the file. 

Final_RNN_and_Transformer_Code.ipynb contains the final hybrid RNN and transformer model trained using the PyTorch library. It utilizes Torch tensors and embeddings within the hybrid model train loop, which is computationally demanding and slow to run. It is recommended not to run it as the output is already in the file for reference. It also serves as the basis for the best model trained and saved for usage in the Anvil web application interface.


The code represents a collaborative effort of the team consisting of: Andy Ma, Carissa Ing, Sarah Dominguez, Siboney Cardoso, and Utkarsh Garg.


To Prof. Ghosh and the TA team, thank you for teaching us a great deal about machine/deep learning over the semester!
