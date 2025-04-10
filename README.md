# Data Mine US Counties

This is homework 5 for Applied Machine Learning (Spring 2025) at Columbia University.

This homework requires you to:

- Make a single pull request (PR) against this repository as your submission, this PR should satisfy the following:
  - This PR should be created under a new branch, named after your UNI (i.e. do not push against the main branch).
  - You need to create a new file: `report.md`, `report.ipynb`, OR `report.Rmd` that contains all of the answers to the questions listed below.
  - You will need to make at least **one change** in the existing code either under the `python` or `R` folder. This can be about the logic, the efficiency, or the readability. This should be accompanied with a comment that explains your change.


## Questions your report should answer:

- Give a summary of what you think the project is answering. Limit your answer to one paragraph.
- 




## Fake Report

In this report, we explore the relationships between the [social vulnerability index](https://www.atsdr.cdc.gov/place-health/php/svi/svi-data-documentation-download.html) and changes in the households in different counties in the US.

The social vulnerability index contains metrics on socioeconomic status, household characteristics, racial & ethnic minority status, and housing type & transportation. 

<image src='svi_overview.png'>

The changes in households are inferred from the American Community Survey (5 year), specifically `B11003`. We focus only on the counts for households led by married couples and unmarried singles. One could imagine the trade-off between these households as an indication of changing social structure in the county. 

To capture the different types of counties, we attempt to fit 2 different polynomials to the two household count. We fit a linear line, if the $$R^2$$ value 

{% include lib/mathjax.html %}
