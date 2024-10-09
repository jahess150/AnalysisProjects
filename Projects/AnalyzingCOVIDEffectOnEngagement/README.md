# Analyzing COVID-19's Effect on Student Engagement

This project is a thorough analysis of how COVID-19 affected student engagement levels in virtual learning environments during the pandemic. The data is sourced from various school districts in numerous states within the US. However, some states are more represented compared to others, and not all states are included. 

We are given two CSV files containing our data:

- **Districts:** The `districts_info.csv` file contains data on student engagement levels measured over time, as well as what educaitonal products they were using and how much. It includes information about the district's location (state and locale), the student diversity, percent of free/reduced lunches, and other details.

- **Educational Products:** The `products_info.csv` file contains data on all the different educational products used in the school districts within the dataset. It includes the product's name, company, primary function, and other details.

For my analysis, I began by cleaning and engineering the data to address missing values and fix other issues. Then I began an analysis with the goal of answering the following questions:

1. What is the picture of digital connectivity and engagement in 2020?

2. What is the effect of the COVID-19 pandemic on online and distance learning, and how might this also evolve in the future?

3. How does student engagement with different types of educational technology change over the course of the pandemic?

4. How does student engagement with online learning platforms relate to different geography? Demographic content (e.g. race/ethnicity, ESL, learning disability)? Learning context? Socioeconomic status?

Throughout the analysis, I back up my findings with results from both parametric and non-parametric hypothesis testing. At the end of the notebook, I write my conclusions on each of these questions.

A Tableau Public dashboard containing some visualizations of the cleaned dataset from this notebook can be found [here](https://public.tableau.com/views/COVIDEngagementWorkbook/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
