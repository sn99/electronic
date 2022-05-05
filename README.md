# Online Ratings for Electronic Gadgets for Commercial Purpose

## Overview

This is the code for our data mining group project. [Scikit learn](http://scikit-learn.org/stable/index.html) is used to developed the code.
Two algorithms are used: <br>

- Multinomial Naive Bayes
- Support Vector Machine

The data are visualized using Matplotlib.

## Dependencies

- python3.8.5
- jupyter notebook
- pandas
- numpy
- nltk
- matplotlib
- sklearn
- beautifulsoup4
- lxml

## Data

Download the data set from [this](https://www.kaggle.com/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones/data) kaggle page and put it in the same directory as Electronic_Rating.ipynb Jupyter Notebook.

## Installation

1. Install the Python libraries required for this project:
```
pip install pandas
pip install numpy
pip install nltk
pip install matplotlib
pip install sklearn
pip install beautifulsoup4
pip install lxml
```
2. The following file must be presented in the same directory before running the Jupyter notebook.
- Amazon_Unlocked_Mobile.csv
- Electronic_Rating.ipynb

## Usage

- Open Jupyter notebook. Go in the settings and make sure the kernel is correct. For this project, we use Python 3.8.5 64-bit kernel but other kernel can be run too in most cases.
- In the notebook, change the destination of Amazon_Unlocked_Mobile.csv (Cell #2) and the destination of putlabel_dataset.csv (Cell #3) to their appropiate destination.
- Now run the code in Jupyter Notebook.