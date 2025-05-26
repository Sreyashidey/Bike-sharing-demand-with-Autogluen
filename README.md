# Predict Bike Sharing Demand with AutoGluon

## Introduction to AWS Machine Learning Final Project

## Overview
In this project, students will apply the knowledge and methods they learned in the Introduction to Machine Learning course to compete in a Kaggle competition using the AutoGluon library.

Students will create a Kaggle account if they do not already have one, download the Bike Sharing Demand dataset, and train a model using AutoGluon. They will then submit their initial results for a ranking.

After they complete the first workflow, they will iterate on the process by trying to improve their score. This will be accomplished by adding more features to the dataset and tuning some of the hyperparameters available with AutoGluon.

Finally they will submit all their work and write a report detailing which methods provided the best score improvement and why.

To meet specifications, the project will require at least these files:
* Jupyter notebook with code run to completion
* HTML export of the jupyter notebbook
* Markdown or PDF file of the report

Images or additional files needed to make your notebook or report complete can be also added.

##  Problem statement- 
Bicycle sharing programs, or bike-sharing systems, offer an efficient and automated way for individuals to rent bikes from a network of kiosks spread across urban areas. These systems allow users to pick up a bike at one location and return it at another, based on their convenience. Currently, there are more than 500 such programs operating globally.

Due to the extensive data they generate—including details like trip duration, start and end locations, and timestamps—bike-sharing systems have become a valuable resource for researchers studying urban mobility patterns. Acting as a large-scale sensor network, they provide deep insights into city-wide transportation trends. The Bike Sharing Demand competition on Kaggle challenges participants to use historical usage and weather data to forecast bike rental demand in Washington D.C.'s Capital Bikeshare program.

## Dataset:
[Bike-Sharing-Demand-Kaggle-Competition-Dataset-Link](https://www.kaggle.com/competitions/bike-sharing-demand/data)

# Used AutoGluon's Tabular Prediction to train and iteratively improve the model through feature engineering, exploratory data analysis, and hyperparameter tuning


## Getting Started (Resources)
* Clone this template repository `git clone git@github.com:udacity/nd009t-c1-intro-to-ml-project-starter.git` into AWS Sagemaker Studio (or local development).

<img src="img/sagemaker-studio-git1.png" alt="sagemaker-studio-git1.png" width="500"/>
<img src="img/sagemaker-studio-git2.png" alt="sagemaker-studio-git2.png" width="500"/>

* Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

### Dependencies

```
Python 3.7
pydantic 1.10.3
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
For this project, it is highly recommended to use Sagemaker Studio from the course provided AWS workspace. This will simplify much of the installation needed to get started.

For local development, you will need to setup a jupyter lab instance.
* Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance.
* If you have a python virtual environment already installed you can just `pip` install it.
```
pip install jupyterlab
```
* There are also docker containers containing jupyter lab from [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).

## Project Instructions

1. Create an account with Kaggle.
2. Download the Kaggle dataset using the kaggle python library.
3. Train a model using AutoGluon’s Tabular Prediction and submit predictions to Kaggle for ranking.
4. Use Pandas to do some exploratory analysis and create a new feature, saving new versions of the train and test dataset.
5. Rerun the model and submit the new predictions for ranking.
6. Tune at least 3 different hyperparameters from AutoGluon and resubmit predictions to rank higher on Kaggle.
7. Write up a report on how improvements (or not) were made by either creating additional features or tuning hyperparameters, and why you think one or the other is the best approach to invest more time in.

## Files present:<br><br>
**1. `project-notebook.ipynb`:** Jupyter notebook with code<br><br>
**2. `project_report.md`:** (Markdown file of the report) A report was generated post-submission that examines the iterations that yielded the most significant improvement in model performance.<br><br>

## Acknowledgements
This dataset was provided by Hadi Fanaee Tork using data from [Capital Bikeshare](https://capitalbikeshare.com/system-data). I would like to thank Kaggle, Hadi Fanaee Tork et al. and the University of California, Irvine (UCI) machine learning repository for [hosting the dataset](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). If you use the problem in publication, please cite:

*Fanaee-T, Hadi, and Gama, Joao, Event labeling combining ensemble detectors and background knowledge, Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg.*


## License
[License](LICENSE.txt)<br><br>

Thank you for taking the time to visit this repository!
