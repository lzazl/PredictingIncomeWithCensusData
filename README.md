# PredictingIncomeWithCensusData
The objective of this project is to predict whether an individula's income falls below or above $50,000 using US census data. 

The original dataset conains approximately 33,000 records, 25,000 of them were used for traning and validating purposes, while the rest was stored as a separate csv file (to prevent any kind of possible data leakage) for final testing.  

The final Gradient Boosting Classifier model achieves 86.858% overall accuracy, 1.43% lower than best results found on Kaggle. https://www.kaggle.com/uciml/adult-census-income/kernels  

The project uses over 10 different models to test which one is the most approriate for the underlying classification task, and fine tunes the optimal model.

To run the Jupyter Notebook please put everything under a same folder.
