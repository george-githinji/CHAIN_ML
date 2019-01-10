# The CHAIN Machine Learning repository
This repository contains machine learning approaches and code for the CHAIN study. 

## Setup up the appropriate python environment from the command line

Install Anaconda  by downloading the appropriate package from this URL https://www.anaconda.com/download/

Restart the terminal and ensure that Anaconda is in your PATH, Make a new environment for the CHAIN ML work as follows.

```
$ conda update conda
$ conda create -n chain_ml python=3.6
```
Activate this new environment and install the necessary packages

```
$ source activate chain_ml
$ conda install numpy scikit-learn pandas matplotlib seaborn pillow ipython spyder
$ conda install -c conda-forge py-xgboost
$ conda install umap hyperopt
```

The environment is now ready for use.

Load it with ```source activate chain_ml``` every time you wish to use it. 

Happy learning!

