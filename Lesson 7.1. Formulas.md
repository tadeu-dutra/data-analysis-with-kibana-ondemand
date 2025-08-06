# 7.1. Formulas

In this lesson, you’ll learn how to use formulas to visualize custom metrics.



# Review

- The results of a formula can be filtered with a KQL or Lucene query.
- The results of a formula can be time shifted. Use the "shift" argument.
- This formula finds the percentage of visitors to a webpage that received a not found error: count(kql='response.keyword === 404') / count()

