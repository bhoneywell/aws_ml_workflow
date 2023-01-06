# aws_ml_workflow
 
This is a project to deploy an end-to-end ML Workflow on AWS that was created as part as part of the AWS Machine Learning Engineer nanodegree. 

## Overview

This project sought to build an end-to-end ML Workflow on SageMaker, Lamda, and Step Functions. This project focuses on understanding the SageMaker Model Endpoints and Lambda as well as AWS workflow monitoring capabilities with SageMaker Model Monitor and Step Functions. A image classification model was built for Scones Unlimited, a scone-delivery-focused logistic company. The goal of the image classification model was to detect what kind of vehicle delivery drivers have. 

## Methodology

After staging and processing the data the model is trained and deployed using AWS SageMaker. The Lambda functions are chained together using a Step Function to perform image classification and filter out low-confidence inferences. 

## Documents
The documents contained in this repository are below: 

[Analysis](analysis.ipynb) - this file contains the actual code that was ran to train and deploy the machine learning models
[Lambda](lambda_function.py) - this file contains the code used for each of the lambda functions.
