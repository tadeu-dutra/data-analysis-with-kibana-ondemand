# 3: Answering questions

## Objective:

In this lab, you will build a machine learning job and use its result to ask more questions to answer.

    Create a population job on the elasticlogs index satisfying the following:
        the job is on the whole elasticlogs dataset
        the population is grouped by the request field
        the metric is Count
        the bucket span is 1h.
    Show answer


    "Population job"

    "Use full elasticlogs data"


    "Population job settings"

    "Start job"

    Take a look at the results of the population job.

    "View results"

    The highest severity anomalies are found in /blog/welcome-insight-io-to-the-elastic-team. No surprise there! The anomalies were so severe we had already investigated them. Leave an annotation for the webteam and cyberteam about what we found.
    Show answer

    "Single Metric Viewer"

    "Add annotation"

    Go back to the Anomaly Explorer. Take a look at the request /blog/kibana-10-common-questions-formulas-time-series-maps. What's happening here? What did the population job find that was not obvious to us before?
    Show answer

    "Select row"

    "See graph"

    "View it close up"

    Keep digging around. Use different tools. Create more visualizations in your dashboards. Use Discover. Try to figure out what's causing this strange behavior. Resist the urge to click Show answer until after you've tried to find the solution yourself.
    Show answer

    "Blog table"

## Summary:

In this lab, you created a population job and explored its results. Now you're ready to build your very own custom dashboard for your data!
