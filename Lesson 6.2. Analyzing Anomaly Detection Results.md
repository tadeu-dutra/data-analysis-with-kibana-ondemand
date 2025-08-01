# 6.2. Analyzing Anomaly Detection Results

In this lesson, you’ll learn how to take action when an anomaly occurs in your data.

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/52ab46e1-10ab-4830-8ebd-06c5b740c91e" />
NOTE: Select the Anomalies data view and use the following KQL query: 

```
anomaly_score > 25 and result_type:bucket
```

# Summary

In this lab, you've learned how to use the results of machine learning jobs.

# Review

- Anomalies can be visualized using Kibana Lens like any other data. The results of machine learning jobs are stored in Elasticsearch. You can work with these results like any other data.
- The results of machine learning jobs are stored in Elasticsearch. You can explore that data in Discover, or visualize it on a dashboard. 
