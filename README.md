# fake_currency_detection

Fake Currency Detection is a task of binary classification in machine learning. If we have enough data on real and fake banknotes, we can use that data to train a model that can classify the new banknotes as real or fake. The dataset contains these four input characteristics:


1. The variance of the image transformed into wavelets
2. The asymmetry of the image transformed into wavelets
3. Kurtosis of the image transformed into wavelets
4. Image entropy


The target value is simply 0 for real banknotes and 1 for fake banknotes.

There are four main tasks- Importing libraries and data, Data exploration, Data preprocessing and Logistic Regression for training our model. The libraries used in this project are: Numpy, Pandas, Matplotlib, Scikit-learn and Seaborn.
