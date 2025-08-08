# 
1: Dashboard setup

## Objective:

This lab and the following two parts are optional labs. You will use what you learned during this class to analyze and hunt anomalies from a new dataset. In this first part, you will learn about a new dataset elasticlogs.

    Create a data view for elasticlogs if you don't already have one. Use @timestamp for the time field.

    Use Discover to explore elasticlogs. What date range is the data from?
    Show answer

    "Last 1 year"

    "August 2021"

    Create a new dashboard. Create a date histogram that shows the count of documents grouped by response. Save the dashboard with the time range you found in Step 2 and call it Elastic logs. It should look like the image below.

    "Date histogram"
    Show answer

    "Count of documents"

    "Breakdown by response"

    "Number of values"

    Create a map with two layers:
        One layer has the world countries using EMS boundaries color filled by the count. Use the field geoip.country_iso_code. Add a tooltip for the country name and iso-code-2 fields.
        The other layer is above the first layer. It displays the clusters of the geo locations in the field geoip.location.

    Add the map to the dashboard Elastic logs and save. The dashboard should now look like the image below.

    "Map"
    Show answer

    "EMS Boundaries"

    "World countries"


    "Term joins"

    "Fill by value"

    "Add tooltip"

    "World countries map"

    "Clusters"

    What type of categories are there? Add a donut visualization of the top 5 categories to the dashboard. Use the blog_category field. The graph should look like the image below.

    "Donut chart of categories"
    Show answer

    "Suggestions"

    Which blog had the most visitors? Add a horizontal bar chart of the top 15 most visited blogs. Use the request field for the name of the blog. The graph should look like the image below.

    "Horizontal Bar chart"
    Show answer

    "Flip"

    "Top values of request"

    Feel free to resize and rearrange the visualizations as you like. This dashboard is for you to use so make it convenient for you. If you think of other visualizations you want, you can add them here as well. Don't forget to Save your changes.

## Summary:

In this lab, you set up a dashboard for the Elastic logs. Now you're ready to start asking and answering some questions about this dataset.
