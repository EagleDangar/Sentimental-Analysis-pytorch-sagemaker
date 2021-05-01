# Sentimental Analysis and  AWS SageMaker Deployment Project

## Table of Contents
  - [About](#about)
  - [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installing](#installing)
  - [Acknowledgements](#acknowledgements)

<a name="about"></a>
## About

The project is to get familiar with Sagemaker functionalities and how can we deploy trained Machine learning models on Sagemaker. I have trained and deployed a recurrent neural network performing sentiment analysis on movie reviews using Pytorch on AWS sagemaker. Created one API service to get the prediction from the deployed model using AWS Lambda Function and then can display the outcomes on a web App.

This project is divided in the following key sections:

1. Train the LSTM model on the Sagemaker Notebook and store it as a model.
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