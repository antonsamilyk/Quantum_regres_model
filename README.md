# Quantum_regres_model
Scale the data first (data is not normalized).
Try to reduct dimension, by PCA. 2 first components cant explain enough varience, so PCA is useless.
Using LASSO we expect to get the corresponding penalizing value - lambda (alpha in algorithm). lambda is equal 0.99 (close to 1) - bad result, RMSE confirms it.
Let's apply Random Forest Regression (params we choose manually, CV take a long time). 
