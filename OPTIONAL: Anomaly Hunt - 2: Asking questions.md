# 2: Asking questions

## Objective:

In this lab, you will start asking and answering some questions by adding more visualizations.

    Notice that the blog /blog/welcome-insight-io-to-the-elastic-team had significantly more requests than other blogs.

    "Dashboard"

    Let's learn more about what's happening there. First click on /blog/welcome-insight-io-to-the-elastic-team in the horizontal bar chart in the dashboard Elastic logs.

    "Dashboard with filter"

    This creates a filter for the blog. Now the dashboard has changed to show only the graphs for the documents of visitors to that one blog page. We're able to learn some things about the visitors to that blog page, but not too much. We can see where the visitors are concentrated on the map – US and China - and which status codes are commonly seen – 301 and 200.

    The other charts offer little extra information. Since we're looking at one blog, the donut chart of categories is really just showing us that the blog /blog/welcome-insight-io-to-the-elastic-team is in the category "News".

    Let's create a new dashboard, one that will give us more detailed information about visitors to a specific blog. Let's add some of the visualizations from the Elastic logs dashboard into the new dashboard. Add the date histogram and maps visualizations to a new dashboard called Blog details. The new dashboard should look like the image below.

    "New dashboard Blog details"
    Show answer

    "Copy histogram"


    "Copy map"

    Modify the date histogram. Add a new layer – a line chart displaying the average bytes to the Blog details dashboard. Use the field bytes_sent. The graph should look like the image below.

    "Add a line chart layer"
    Show answer







    "Vertical axis for average bytes"

    Add a horizontal bar chart of the top 10 user agents to the Blog details dashboard. Use the field useragent. The graph should look like the image below.

    "Top 10 user agents"
    Show answer

    "Top 10 user agents"

    "Top values of request"

    Add a document table with the fields geoip.country_name, useragent, bytes_sent, and any other fields you find interesting to the Blog details dashboard.
    Your dashboard should look like the image below.

    "Dashboard with document table"
    Show answer

    "Document Table"

    "Saved search"

    "Add from library"

    Go back to the Elastic Log dashboard.
    Create two drilldowns from the horizontal bar chart of top requests :
        One to the Blog details dashboard with filters applied.
        One to go directly to the blog page URL.

    "Use drilldown"
    Show answer

    "Create drilldown"


    "Go to Blog details"



    "Go to blog page"

    Click on the drilldown for the requst /blog/welcome-insight-io-to-the-elastic-team.

    What is causing those 301 errors for visitors of /blog/welcome-insight-io-to-the-elastic-team ?
    Show answer

    "Filter 301"

    "Windows NT 10 filter"

    "Map with Windows NT 10 filter"

    "Filter on a country"

    "Filter on India"

    "Filter on Sweden"

    "Filter on github-camo"

    "github-camo requests from US"

    "github-camo requests from Kansas"

    "github-camo with 301 response"

    "github-camo with any response"

    Remove all filters on the Blog details dashboard except for the request:/blog/welcome-insight-io-to-the-elastic-team filter.
    Notice there are two spikes in the date histogram when there is higher than usual activity and also less than usual average bytes. That seems counter intuitive. What's going on?

    "What's happening here?"
    Show answer

    "Zoom in"

    "Select filter"

    "Zoom in more"

    "User agent Mozilla for OSX"

    "User agent Mozilla for OSX in Beijing"

    "User agent Mozilla for OSX three visits"

    "No more spike!"

## Summary:

In this lab, you created a second dashboard you can use with Drilldown to get more details about a specific blog you want to investigate. We also asked a few questions and found ways to answer them.
