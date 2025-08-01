# 6.1. Introduction to Elastic Machine Learning

In this lesson, you’ll learn how to detect anomalies in your data with the machine learning capabilities of the Elastic Stack.

<img width="1672" height="852" alt="image" src="https://github.com/user-attachments/assets/e7cec673-e8cf-469e-9255-427b82267c11" />

# Review

- The best way to find anomalies in time series data is to use Machine Learning instead of check all your dashboards every hour.
- Ahead of time, use calendars to configure time ranges during which the model will not be affected by any anomalies. After an event has already happened you can roll back to an earlier snapshot of the model.
- The two mechanisms that can be used to exclude events from anomaly detection analysis are:
  - Calendars
  - Reverting to snapshots
