# LGCK-LCD
This repository contains the source code for the paper "Controlling the false discovery rate of the Lasso Cox model by a latent Gaussian copula knockoff procedure with application to mixed gene expression data".



The computational implementations of the proposed methods were carried on using R and Python programming languages, employing versions 3.6.3 and 3.9.7, respectively.
The code for running the simulations and the application to a real dataset uses several packages from R and Python. The R packages are the following: dplyr (version 1.0.9), glmnet (version 4.1.4), and survival (version 3.4.0). The Python libraries are the following: numpy (version 1.20.3), pandas (version 1.3.4), joblib (version 1.1.0), matplotlib (version 3.4.3), knockpy (version 1.1.1), gglasso (version 0.1.9), and rpy2 (version 3.5.1).


The folder "Simulations" contains code related to the 5 different scenarios considered in the paper: varying the number of predictors, varying the correlation coefficient of the autoregressive correlation structure, varying the amplitude, varying the censoring rate, and varying the magnitude of the skewness and tailedness of the continuous variables. Each configuration has its own jupyter notebook file, indicating in the name the corresponding scenario (the magnitude of the skewness and tailedness is modulated by the parameter alpha of the skew-t distribution). Some scenarios have two files: one for moderate dimension (p=n), and the other for low dimension (p>n).


The folder "Application" contains code for the application of the proposed methodology to a real dataset of lung cancer.

