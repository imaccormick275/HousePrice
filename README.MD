### Kaggle-titanic

### Dependancies:
See environment.yml for the complete dependency list.

### Environment:
You can create a conda environment with all required dependencies by running conda env create in the root of the repository. Install the environment with:

conda env create -f environment.yml


### Kaggle Competition | Titanic Machine Learning from Disaster
>Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
>With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

From the competition (https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

### Goal for this Notebook:
* regression techniques
* feature creation
* manual outlier removal
* sklearn pipelines for transformation of data and model training
* category encoders for encoding methods
* imbalanced learn for outlier detection and removal (not yet implemented)
* scikit optimization for parameter tuning
* mlxtend for model stacking
* cross-validation