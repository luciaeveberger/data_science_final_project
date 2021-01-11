# MILA: Data Science | 6758 Science des données (Universite de Montreal) 

Please see [Project Report](https://github.com/luciaeveberger/data_science_final_project/blob/main/Project_Report.pdf) for more details on the project.

## Team: 
Mo Kleit

AliReza Razaghi

Lucia Eve Berger

# Running the NN code
## Private Score: 1.67770
To generate the submission file, please run all cells of the google-colab or jupyter notebook setup. 

### Data
Data is mounted in a drive. 

# Running the Voting Regressor Code
## Private Score: 1.67191
The pipeline is separated in multiple notebooks.
In order to reproduce the results from start to end, you should
run the following notebooks in that specific order (dependencies are already there for each notebook):
1. [Data preprocessing](https://www.kaggle.com/mokleit/data-exploration-ii)
2. The following two notebooks can be run in parallel:
    * [LightGBM](https://www.kaggle.com/mokleit/lgbm-training)
    * [XGBRegressor](https://www.kaggle.com/mokleit/xgbregressor-training)
3. [VotingRegressor](https://www.kaggle.com/mokleit/voting-training)
4. [Generate submission file](https://www.kaggle.com/mokleit/predict)

##Important notes
* The models are already trained and if you want to simply generate the same submission file, you can run
step 4 above only.
* If you want to rerun the hyperparameter tuning part (it might take some time), please uncomment
the grid search in each notebook of step 2.
