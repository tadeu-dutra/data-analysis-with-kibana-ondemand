# 8.3. Managing alerts

In this lesson, you’ll learn how to manage alerts using Kibana.


## 8.3: Managing Alerts

## Objective:

In this lab, you will learn how to manage and monitor existing rules.

    Start by accessing your alerting rules:

        > Stack Management > Alerts and Insights > Rules

    Click My first rule to see its details. "Rule details"

    The History tab shows every time the rule has run and its status. You would expect to have all runs showing Succeeded.

    The Alerts tab shows all occurrences of the condition being detected in the rule.

    Click the switch in the Mute column. It will prevent future actions of the same type to be executed when the rule detect the defined condition. "Switch mute" Toggling Mute will suppress the action indefinitely. If you have multiple actions defined for the rule, each one will have its own Mute button.

    Toggle off the Mute switch to reenable the action.

    There are other ways to prevent notifications from a rule. For instance, you can disable your rule. Click Enabled to see that you could disable the rule if you wanted. "State selector"

    Another option is to snooze your rule. Click the snooze button, shown by the bell icon, to see the available options to change Notify when alerts generated. "Snooze"

    For now, select 1 hour, but note that you can also Snooze indefinitely. Snoozing for a specified time stops any rule actions from running. Snoozing indefinitely stops any action until it is re-enabled. "Snoozed" Snooze your rules if they send out too many notifications. Investigate the cause, make adjustments, and re-enable by clicking Cancel snooze.

    Suppose you have a scheduled maintenance coming, and you know this will cause unnecessary notifications. A maintenance window can be create to allow for this.

    Access Maintenance Windows under Alerts and Insights and click Create a maintenance window. "Create a maintenance window"

    Name it as Montly maintenance window and select a 30-minute timespan of your choice. "Maintenance window time"

    Toggle on Repeat and select how the maintenance window should be repeated. In our example, it is being repeated every first Saturday. "Maintenance window repeat"

    Finally, click Create maintenance window and check its status.

## Congratulations!

You have reached the end of your course lab book, however it is strongly encouraged that you move on to the (optional) Anomaly Hunt exercise. This provides an excellent opportunity to practically apply the concepts and techniques throughout this course.


## Review

- 
