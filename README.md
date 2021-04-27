# Sentimental Analysis and  AWS SageMaker Deployment Project

## Table of Contents
  - [About](#about)
  - [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installing](#installing)
  - [Acknowledgements](#acknowledgements)

<a name="about"></a>
## About

In this project, I have trained and deployed a ML model on AWS sagemaker. Created one API service to get the prdiction from the deployed ML model using AWS Lambda Function and then can display the predctions on a web App.  

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using ML, should provide enough background.

This project is divided in the following key sections:

1. Train the Machine Learning ML model on the Sagemaker Notebook and store it.
2. Deploy the stored model on Sagemaker and create an endpoint to call the service.
3. Create on API using AWS Lambda function and handle the prediction request coming from the web-app and get the prediction from the deployed ML model endpoint.

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>
### Dependencies
* Python 3.5+, PyTorch, NumPy, Pandas, matplotlib, torchvision, Sagemaker, AWS, Lamb
<a name="acknowledgement"></a>
## Acknowledgements

* [Udacity](https://www.udacity.com/) for providing an amazing Deep Learning Nanodegree Program