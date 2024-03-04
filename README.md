# CML MLOps Logistics Hands On Lab

This is a Hands On Lab (HOL) of Machine Learning applied to Supply Chain & Logistics optimization in Cloudera Machine Learning (CML).

In this HOL you will use CML to analyze multidimensional time series data at scale and identify similar patterns with Unsupervised Learning techniques made available by Stumpy and the Matrix Profile algorithm invented by the University of California, Riverside.

With Stumpy you will train models capable of identifying patterns in long sequences of time series data matching a particular arbitrary motif, and detect time series sequences that are most similar to others.

Among the many use cases, this allows you to spot anomalous time series patterns from moving devices in real time and discover devices that behave in a similar manner over the span of long time windows potentially across millions of units.

### Content

The HOL is composed of two sections:

1. [DEV Project](https://github.com/pdefusco/CML_MLOps_Logistics_DEV): explore time series data, train and deploy a Stumpy model to a Production Project
2. [PRD Project](https://github.com/pdefusco/CML_MLOps_Logistics_PRD): monitor model performance and redeploy a newer version to better meet model SLA's
