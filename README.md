# Personal-Project---Cryptocurrency-trends-prediction
## ABSTRACT
Bitcoin, Etherium, and Litecoin are among the most extensive market capitalized cryptocurrencies in the present era.
With the increased popularity, there is also an increased proclivity of investors towards investing in cryptocurrencies. 
To gain maximum profits and avoid risks, one needs to analyze the trends and history of the cryptocurrency diligently. 
This project tests various machine learning algorithms to scrutinize cryptocurrencies such as Bitcoin, Etherium, and Litecoin based on multiple trading factors such as open price, close price, volume, market price, history, etc.
I have performed various state-of-the-art machine learning to predict the future market value of the cryptocurrencies and derived the performance analysis of the same.

## DATASET
The dataset was taken from the open source webiste Kaggle(https://www.kaggle.com/jessevent/all-crypto-currencies). The CSV file is attached in the repository.

## MODELS

## Elastic Net Regressor
# ALGORITHM
1. Input matrix X.
2. Output y, estimates alpha (u) and lambda (l)
3. Calculating regression estimator (b) and weight coefficients (ws,w)
4. Pre defining (Yi)*= wij(Xij)
5. Finding Lasso (L1) and Ridge penalties (L2) penalized loss functions using objective function.
6. Calculate adaptive elastic net coefficient.
b=(1+l n)b ; where n represents the row size of input matrix.

## Bayesian Ridge Regressor
# ALGORITHM
1. Input matrix X.
2. Output y, estimate
error(ei) ,slope(mi ) , variance(σ ) 2
3. Calculating hyper parameters and weight coefficients (ws,w)
4. Defining Yi = N(c + mi *X , σ ) ,the normalization distribution.
5. configuring likelihood and prior function values. 6.Calculating total error using posterior function and fetching results.

## Ensemble Learning Algorithms

The ensemble regression algorithms were also used for prediction.
1. Random Forest Regressor
2. Extra Trees Regressor
3. Gradient Boosting Regressor

## RESULTS
Calculated MSE and R2 scores for each currency and algorithm to evaluate the efficiency of the suggested models.
Extratrees Regressor outscored the other models in terms of R2 squared score and Mean Square error and helps in predicting the output with greater accuracy.
