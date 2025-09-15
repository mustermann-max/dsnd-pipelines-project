## README
# DSND Pipelines Project

the project aims to predict whether a product review is a recommendation or not using NLP and classical ML methods

## Getting Started

### Dependencies

conda_environment.txt contains all the dependencies used in this project.

### Installation

replicate the conda environment using: conda create --name dsnd-pipelines-project --file conda_environment.txt
if you want to retrain the spacy model comment in the code in section EXTRA FEATURE: Custom spacy textcat

### Files
- starter.ipynb : contains all the code to preprocess the data, train and evaluate the model
- config.cfg : configuration file for the spacy model
- conda_environment.txt : conda environment file
- model/ : directory where the trained spacy model is saved
- train.spacy, dev.spacy, test.spacy : spacy binary files containing the training, development and test data