# Autogluon-Bike-Sharing-Demand

This project is a combination of exploratory data analysis, machine learning model implementation with AutoGluon through the prediction of bike sharing demand. Here AWS SageMaker Studio is used as a project platform. Bike sharing data has been downloaded from Kaggle API. This project demonstrates the ability to use AutoGluon to train several iterations of models.

## Project Motivation
AWS SageMaker Studio is a cloud based IDE. It is based on Jupyter Lab. It facilitates to use Amazon S3 where we can easily store and extract big data. AutoGluon library provides the quick machine learning solution focusing on automated stack ensembling. It utilizes the state of the art techniques. Skleran library provides the available built-in machine learning models which support us to analyze different type of model very easily. This project provides the better utilization of these libraries and AWS SageMaker platform.

## Acknowledgement
This project is for Udacity Nanodegree Program (https://www.udacity.com/course/aws-machine-learning-engineer-nanodegree--nd189). Thanks to  Udacity for arranging this project to strengthen our knowledge and thanks to Kaggle (https://www.kaggle.com/) for sharing Data.

## Installation
This project platform has been taken from Udacity Workspace, where there was the access in AWS SageMaker Studio.
If we want to use our own computer, then the following items are needed to be installed:
- Python 3.7 or above
- Jupyter Lab installed in Python environment via: pip install jupyterlab
- MXNet 1.8 installed via: pip install "mxnet<2.0.0"
- AutoGluon installed via: pip install autogluon
- Start jupyter Lab instance in the same directory as the project files: jupyter notebook

## File Description
The sequence of Data files are as follows:
- Bike_sharing_demand.ipynb
- Bike_sharing_demand.html

## Discussion
Many companies such as Uber, Lyft, and DoorDash face the difficulties in the bike-sharing demand. Proper predictions can slove their high demand problem and provide a reliable and comfortable service to the customers.
