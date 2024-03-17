# CML MLOps Logistics Hands On Lab

This is a Hands On Lab (HOL) of Machine Learning applied to Supply Chain & Logistics optimization in Cloudera Machine Learning (CML).

In this HOL you will use CML to analyze multidimensional time series data at scale and identify similar patterns with Unsupervised Learning techniques made available by Stumpy and the Matrix Profile algorithm invented by the University of California, Riverside.

With Stumpy you will train models capable of identifying patterns in long sequences of time series data matching a particular arbitrary motif, and detect time series sequences that are most similar to others.

Among the many use cases, this allows you to spot anomalous time series patterns from moving devices in real time and discover devices that behave in a similar manner over the span of long time windows potentially across millions of units.

## Content Overview

The HOL is divided in two parts:

1. MLOps with time series and geospatial data
  - [DEV Project](https://github.com/pdefusco/CML_MLOps_Logistics_DEV)
  - [PRD Project](https://github.com/pdefusco/CML_MLOps_Logistics_PRD)

2. MLOps with mlflow
  - [MLOps with MLFlow](https://github.com/pdefusco/CML_MLOps_Logistics_Mlflow)

## Requirements

* A CML Workspace on version 2.0.43 or above with internet access enabled.
* Basic familiarity with git, Python and unix scripting.

## Step by Step Instructions

### DEV Project

The DEV project hosts artifacts for the development of a model to predict on time series sequences.

In this project you will:

  1. 00 Datagen: Run a CML Job to create your own data in Apache Iceberg table format.
  2. 01A Maps: Explore geospatial data interactively with Folium and CML Sessions.
  3. 01B Geospatial: Use Apache Sedona to perform geospatial search on coordinate data.
  4. 02 Model Training: Familiarize yourself with Stumpy for time series machine learning and train your first models.
  5. 03 Model Deployment: Deploy a Stumpy time series classifier in an API endpoint in the Production Environment via CML Models and CML APIv2.
  6. 04 Model Deployment: Deploy a Stumpy time series Unsupervised learning model in an API endpoint in the Production Environment via CML Models and CML APIv2.

##### Project Setup

##### Install Requirements

##### Execute Notebooks

### PRD Project

The PRD project will serve as the production environment for your machine learning models.

In this project you will:

  1. 05 Model Simulation: create synthetic requests and submit them to the CML Models endpoint.
  2. 06 Model Monitoring: monitor model resource consumption in Production.
  3. 07 Model Redeployment: leverage CML APIv2 to redeploy a new model build with additional resources to meet capacity.

##### Project Setup

##### Install Requirements

##### Execute Scripts


### Summary and Next Steps
