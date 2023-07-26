# AWS-BankML

AWS-BankML is a beginner-friendly project that demonstrates the process of creating, training, and deploying a Machine Learning model on AWS cloud using Amazon S3 and Amazon SageMaker. This project serves as a guide for anyone looking to understand the workflow of building and deploying ML models on AWS infrastructure.

## Project Overview
The primary goal of AWS-BankML is to showcase the step-by-step process of creating an end-to-end ML pipeline. It covers the following key aspects:

- **Initiating an S3 Bucket**: The project demonstrates how to set up an Amazon S3 bucket, which acts as a secure and scalable storage solution for your datasets and model artifacts.

- **Dataset Download**: It guides you through the process of downloading a sample dataset relevant to the banking domain. The dataset serves as the foundation for building the ML model.

- **Data Preprocessing**: Before feeding the data into the ML model, the project shows how to perform necessary preprocessing steps, such as data cleaning, feature engineering, and splitting the data into training and testing sets.

- **Storing Data on S3**: The project teaches you how to store the preprocessed training and testing data on the previously created S3 bucket, ensuring easy access and reproducibility.

- **Model Initialization (XGBoost)**: It walks you through the initialization of a popular ML algorithm, XGBoost, which will be used for building the predictive model.

- **Model Training**: The project illustrates how to train the XGBoost model using the preprocessed data.

- **Model Deployment**: Once the model is trained, you will learn how to deploy it using Amazon SageMaker, making it accessible through an API endpoint.

- **Making Inferences**: The project demonstrates how to use the deployed model to make predictions on new data.

- **Metrics and Evaluation**: It shows how to assess the model's performance by evaluating metrics on the test dataset.

- **Cleanup**: Finally, the project provides guidance on deleting the deployed model endpoint and removing all associated files from the S3 bucket to avoid unnecessary costs.
