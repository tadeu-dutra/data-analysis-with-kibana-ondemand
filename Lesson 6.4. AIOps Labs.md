# Lesson 4. AIOps Labs

In this lesson, you’ll learn how to use the different AIOps tools to find insights from your data faster. AIOps tools apply advanced analytics and machine learning to accurately and proactively identify issues that need attention.

## Objective:

In this lab, you will discover how you can use AIOps Labs to quickly understand your data.

    Let's start with the Explain Log Rate Spikes tool. In the machine learning section, click Explain Log Rate Spikes under AIOps Labs.

    Analyze the log rate of the Kibana Sample Data Logs data view.
    Update the time range to use the full data.

    You will notice a spike in the histogram, click on it to start the analysis. "Spike"

    The analysis will automatically start and you'll get results in a few seconds. Which field has the highest impact on this spike?
    Solution

    What clientip is the origin of this log spike? How many docs are from this IP?
    Solution

    Next, let's focus on the Log pattern analysis. Open Discover and select the Kibana Sample Data Logs data view.
    On the left-hand side, click on the message field to see the top values. This will not provide you with useful information. "Message"

    Return to the machine learning section and select Log pattern analysis under AIOps Labs. Choose the Kibana Sample Data Logs data view.

    Under Category field choose message and run the pattern analysis "pa"

    Elasticsearch will create a categorization from the unstructured "message" field. You can further analyze the category by clicking on the + or - icon that will send you to Discover with a new filter.

    Open Discover by clicking on the + icon for the first pattern.
    Notice that on the top a new filter is created. Click on it and choose Edit Filter. You'll find which pattern has been detected. For this pattern, the query should be:

    GET HTTP/1.1 Mozilla/5.0 X11 Linux x86_64 rv Gecko/20110421 Firefox/6.0a1

    Note that this is part of the message among 5632 documents.

    Now, let's explore the Change Point Detection. This tool helps you to quickly detect distribution or trend change in your data.
    Return to the machine learning section and click Change Point Detection under AIOps Labs. Choose the Kibana Sample Data Flights data view. Make sure to:
        Remove any filters from previous steps
        Use full data

    Update the metric field to use the DistanceMiles field (keep the avg) and use DestCountry as the split field. "Change Point Dection"

    You can see that some destinations had a dip in their DistanceMiles distribution. Maybe an incident occurred that day.

## Summary:

In this lab, you learned how to use AIOps labs to quickly get insights from your data.
