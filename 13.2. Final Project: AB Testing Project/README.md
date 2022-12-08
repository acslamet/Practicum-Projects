# Project

- You've received an analytical task from an international online store. Your predecessor failed to complete it: they launched an A/B test and then quit (to start a watermelon farm in Brazil). They left only the technical specifications and the test results.

- Explore the data:
** Do types need to be converted?
** Are there any missing or duplicate values? If so, how would you characterize them?

- Carry out exploratory data analysis:
** Study conversion at different stages of the funnel.
** Is the number of events per user distributed equally among the samples?
** Are there users who are present in both samples?
** How is the number of events distributed among days?
** Are there any peculiarities in the data that you have to take into account before starting the A/B test?

- Evaluate the A/B test results:
** What can you say about the A/B test results?
** Use a z-test to check the statistical difference between the proportions.

- Describe your conclusions regarding the EDA stage and the A/B test results.

## Goals

- To find changes related to the introduction of an improved recommendation system. After the changes, the result expected is that within 14 days of signing up, users will show better conversion into product page views (the product_page event), instances of adding items to the shopping cart (product_cart), and purchases (purchase). At each stage of the funnel product_page → product_cart → purchase, there will be at least a 10% increase.

## Business Value

- 

## Tools

Python:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly
- Math
- Scipy
- Datetime
