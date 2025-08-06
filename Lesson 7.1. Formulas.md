# 7.1. Formulas

In this lesson, you’ll learn how to use formulas to visualize custom metrics.

In this lab, you will use formulas to visualize the results of math operations on your data.

<img width="1915" height="988" alt="image" src="https://github.com/user-attachments/assets/ede78d37-6c19-4c0b-92e9-ecae444dc187" />

# Summary:

In this lab, you used formulas to visualize the results of math operations on your data.

# Review

- The results of a formula can be filtered with a KQL or Lucene query.
- The results of a formula can be time shifted. Use the "shift" argument.
- This formula finds the percentage of visitors to a webpage that received a not found error: count(kql='response.keyword === 404') / count()

