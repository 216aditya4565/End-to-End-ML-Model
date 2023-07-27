# End-to-End-ML-Model

Let’s consider you have developed a machine learning model with high accuracy by
using the raw data. The next step is to put this highly accurate model into production by
fetching the data in daily batches. But the model in prediction can fail without any
warning. Due to the same keeping, an eye on the model’s prediction power becomes
necessary.

Also, in the real world, data can change due to various factors affecting prediction
accuracy. In production, taking a major to prevent such changing behavior of model and
data is important to serve the business problem over time.
In this project, we will build an end-to-end pipeline to monitor any changes in the
model's predictive power or degradation of data, commonly known as Model and Drift
Monitoring. The model is built to classify whether or not a loan is to be given or rejected
based on data fetched from PostgreSQL. This project also demonstrates the
orchestration of ML pipelines using Docker and Airflow.
