---
name: "Peer Review"
about: "Peer review for STA 221 draft report"
title: "Peer Review"
---

### Team doing the review: The BEST Fit

The team members that participated in this review are

Olivia Encarnacion - @Oencarnacion4

Allison Yang - @allison-y-yang

Leo Yang - @Leonard271828

Phillip Lin - @256thFission

### Describe the goal of the project.
To determine the most significant contributions to agriculture-related emissions, as it can help decide which processes would have the greatest impact on total emissions reduction. This would overall improve productivity and efficiency of actions taken to address global climate change.

### Describe the data set used in the project. What are the observations in the data? What is the source of the data? How were the data originally collected?
The data set is obtained from the Food and Agriculture Organization (FAO) from the UN. The FAO collections information by using a variety of different questionnaires. National governments also gather data collected by the FAO by data reporting systems and surveys. Other organizations like the World Bank, WHO, OECD, etc., also provide relevant information. The FAO also conducts the World Census of Agriculture and specific food security surveys which provides annual data from governments and international organizations.

The observations in the data appear to be CO2 emissions from certain agricultural activities of a country/territory per capita, seemingly calculated on an annual basis.

### Consider the exploratory data analysis (EDA). Describe one aspect of the EDA that is effective in helping you understand the data. Provide constructive feedback on how the team might improve the EDA.
The team performed a log transformation on the response variable (agricultural CO2 Emissions), which is helpful in understanding the data as from their initial visualizations, the original response variable was heavily right-skewed. This could aid in normalizing the data and preventing skewing results. It’s easy to follow their line of logic as to why the performed the transformation, and they explained the assumptions they looked at first before doing so. They also created clear univariate and bivariate visualizations, that helped explain why they made modelling decisions later on.

The team might improve the EDA by facet-wrapping certain bivariate visualizations, as this could suggest possible interaction effects they could look into. In terms of general organization, it could also be helpful to just make sure everything on the visualizations is visible.

### Describe the statistical methods, analysis approach, and discussion of model assumptions, diagnostics, model fit.
The group fit a linear regression model, and addressed model fit/regression assumptions by looking at residual plots. From their initial EDA, they picked out key predictors and fit the model as such, also generating a table of the estimated coefficients and their respective p-values and CI’s.

Other diagnostics they viewed included calculating the R-squared and adjusted R-squared to see the predictive power of their models, and acknowledged that certain variables might not add to their model.

### Provide constructive feedback on how the team might improve their analysis. Make sure your feedback includes at least one comment on the statistical modeling aspect of the project, but also feel free to comment on aspects beyond the modeling.
The team might improve their analysis by fitting a new model that only keeps predictors with a p-value less than 0.05. From their table, and conclusion, they acknowledge that the adjusted R-squared compared to the R-squared suggests there may be variables that don’t add much to their model, and so fitting a new model and playing around with removing these predictors could help strengthen their analysis.

They could also consider looking at interaction terms/effects that could strengthen and raise the R-squared of their model.

### Provide constructive feedback on the interpretations and initial conclusion. What is most effective in the presentation of the results? What additional detail can the team provide to make the results and conclusions easier for the reader to understand?
The team is very thorough in discussing what each coefficient and intercept means, alongside what their R-squared and adjusted R-squared terms reveal. However, at times it feels a bit repetitive, and so it may be more effective to just interpret the most important predictors in their model, rather than just listing each one and their given meanings. The team could also discuss possible reasons why they see the results that they do.

### What aspect of this project are you most interested in and think would be interesting to highlight in the written report?
We thought it would be interesting if they focused more on which factors seem to have the greatest significance, as the group includes a lot of different types (such as Economic Indicators, Nutrition, etc.). If the group has time, it could also be interesting to see which countries/territories provide the most data and how this could skew the results that we’re seeing.

### Provide constructive feedback on any issues with file and/or code organization.
The only real issue we see is that sometimes the titles run off of graphs, but in terms of code and file organization, it’s easy to follow and clean.

### (Optional) Any further comments or feedback?
N/A great job!
