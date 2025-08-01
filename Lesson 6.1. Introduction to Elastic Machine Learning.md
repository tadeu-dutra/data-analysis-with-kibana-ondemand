# 6.1. Introduction to Elastic Machine Learning

In this lesson, you’ll learn how to detect anomalies in your data with the machine learning capabilities of the Elastic Stack.

<img width="1672" height="852" alt="image" src="https://github.com/user-attachments/assets/e7cec673-e8cf-469e-9255-427b82267c11" />

In this lab, you will learn how to set up single-metric and multi-metric jobs.


## a) single_metric_job

<img width="1917" height="940" alt="image" src="https://github.com/user-attachments/assets/bf4224d3-0c32-4a42-952b-53db305af189" />

## b) multi_metric_job

<img width="1919" height="940" alt="image" src="https://github.com/user-attachments/assets/061df8bb-c40f-4e11-9949-eb2fe1d57ae3" />

<img width="1668" height="764" alt="image" src="https://github.com/user-attachments/assets/e32734d3-7cce-402e-b340-e68543035c62" />

<img width="1667" height="841" alt="image" src="https://github.com/user-attachments/assets/33b04129-55f4-4fd2-90da-237d90f47783" />


# Summary

In this lab, you create single metric and multi-metric jobs to detect anomalies in the web logs data set.

# Review

- The best way to find anomalies in time series data is to use Machine Learning instead of check all your dashboards every hour.
- Ahead of time, use calendars to configure time ranges during which the model will not be affected by any anomalies. After an event has already happened you can roll back to an earlier snapshot of the model.
- The two mechanisms that can be used to exclude events from anomaly detection analysis are:
  - Calendars
  - Reverting to snapshots
