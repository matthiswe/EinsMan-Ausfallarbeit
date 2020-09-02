# EinsMan-Prediction
## Prediction of renewable energy losses based on EinsMan 

# Introduction
Since the modern energy market is a very complex system there is a need for regularization within the system. In order to protect  individual sections of a distribuiton or transmission network from an overload a curtailment of the energy fed in becomes necessary. This overall management of the failure work is called EinsMan. To predict this regulated failure work is the main goal of this project. 

![alt text](https://github.com/matthiswe/EinsMan-Ausfallarbeit/blob/master/ein-windrad-dreht-sich-in.jpg?raw=true)

# Used modules
Python / Pandas / NumPy / Scikit-Learn / Plotly / XGBoost  / Convolutional Neural Networks (Deep Learning) / Ensemble Methods / Transfer Learning / Matplotlib / Random Forest  / SVR / Decision Trees  / K-Nearest-Neighbours / Seaborn / Time Series / Tensorflow

# Conclusion
From every tested model the ARIMA has led to the lowest RMSE. 
The parameters of this model should be tuned regarding the given data

# Future work
- Gridsearch to optimize the parameter for each model
- Test the SARIMA model for a better result
- Get more EinsMan data to predict for other Regions
- Train API models with historical data
- Build a dashboard with Einsman forecast for different Regions

