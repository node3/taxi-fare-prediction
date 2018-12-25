# Data Analytics Pipeline for Taxi Fare Prediction

The industry today relies heavily on data analytics to make predictions. These predictions lead to successful business models that incentivise heavily from machine learning. Popular taxi services such as Uber and Lyft provide their users with a prediction of taxi fare before the customer is mapped to a driver. We try to provide a similar solution using the open dataset provided by the NYC Taxi and Limousine Commision (NYC-TLC). The intention is to process voluminous data in streams from NYC-TLC’s public data repository and perform parallel feature engineering and deploy a prediction engine on top of it.

In this project we mplemented a data analytics pipeline to process over 100 million records of NYC-TLC historical data from a public S3 repository and predicted taxi fares. Contributed to parallel data preprocessing on AWS EMR using PySpark and Pandas. Also implemented a Flask web application as an interface for users to query (serving layer).

![AWS Architectures](https://github.com/atambol/taxi-fare-prediction/blob/master/architecture.jpg?raw=true "architecture")
