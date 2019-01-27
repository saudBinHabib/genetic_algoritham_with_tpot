# Genetic Algoritham


Overview
============
This is the code for Genetic Algorithms. In this code I use the [MAGIC Gamma Telescope dataset](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope) to build a classifer. The classifier will train on the dataset and then be able to classify whether or not some energy is either Gamma Radiation or Hadron Radiation. Instead of guessing and checking the best ML model and hyperparameters to use, I use a genetic programming library called [tpot](https://github.com/rhiever/tpot) to do that for us by trying out a bunch of them.



# Dependencies
============

* Numpy 
* tpot
* scikit-learn
* pandas
