# WaterPotability
Water potability dataset explored. Binary classifier implemented with PyTorch Lightning and Ray Tune. 


## Objective
Several machine learning models are fit to a synthetic dataset of nine features to predict water potability in Kaggle task:

https://www.kaggle.com/adityakadiwal/water-potability

## Notebook Contents
- Feature correlation and distributions are considered.

- Missing data is analyzed and imputed.

- The data is resampled to decrease class imbalance.

- A model spot search is done using scikit-learn.

- A three layer neural network is implemented using PyTorch Lightning.

- Hyperparameters are found using Ray Tune from a user defined search space.

- Hyperparameters and their resulting model’s accuracy are visualized in an interactive parallel coordinates plot.
