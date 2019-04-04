# CvDataSplitter
Gretl package for generating datasets for cross-validation purposess

Learning parameters of a prediction function is a major objective. In order to avoid over-fitting, the model is trained on a different data sample (the 'training set') and evaluated out-of-sample on a so called 'test set'. This approach is known as cross-validation (CV). 

This package comprises different approaches of dividing the raw data set into a training and test set, respectively, depending on the nature of the underlying data. Name the following approaches are supported:
1) k-fold CV
2) Leave-One-Out
3) recursive moving-window (expanding window width)
4) rolling moving-window (fixed window width)

An nice overview can be accessed here: https://scikit-learn.org/stable/modules/cross_validation.html

The separated data sets are stored in array of matrices, which can be read-in for the original model training and evaluation.

Written by: Artur Tarassow (atecon@posteo.de)
Project page: https://github.com/atecon/cv_data_splitter
