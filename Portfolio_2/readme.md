# Files :

- `Data_Preparation.ipynb` - Code for data Preparation for Task-2 in ipynb format
- `Training_With_50000_Games.ipynb` - Code for Model Training with our dataset(50000-Games) in ipynb format.
- `Training_With_9m_1m_Games.ipynb` - Code for Model Training with 9 million and 1 million games in ipynb format.
- `Best_TEST_preds.csv` - Best Test Predictions using the trained model.
- `my_model.pt` - Trained model to predict digits (Task_1 model).
- `Original_Dataset(folder)` - The folder which has our original dataset. This is deleted from Repo because it has more size.
- `Prepared Dataset(folder)` - The folder which has prepared dataset for Task-2.


## Links: 

9M Games Dataset - https://www.kaggle.com/datasets/rohanrao/sudoku/data

1M Games Dataset - https://www.kaggle.com/datasets/bryanpark/sudoku/data

## Notes: 
- To Train the model with 50000 dataset, CNN will take upto 30 minutes and LSTM will take 2 hours in local.
- To Train the model with 1M dataset, CNN will take upto 2 hours and LSTM will take more than 4 hours using GPUP100 in kaggle.
- To Train the model with 9M dataset, CNN will take upto 7 hours and LSTM will take more than 10 hours using GPUP100 in kaggle.
