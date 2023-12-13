# data_analysis_proj

This is the repository for Aidan, Caley, and Aya's Data Analysis Project for JOUR472/772.

We have chosen to analyze House Office Expenditure Data.

To see full clean and join of the initial data, run "clean_only.Rmd"

For analysis of the data, run "team_notebook_cleaned.Rmd" 

In addition to reviewing the data for cleanliness, summary/high-level statistics, and any unexpected or unusual values, we wanted to answer the following questions:

1) Do US reps from DC, Maryland and Virginia spend less on average than their colleagues? It seems logical that they would spend significantly less at least on travel, but is that the case? If so, does that mean they spend less overall, or do they outspend their peers in other categories?
2) Which political party does the most spending, and does that change with whether or not that party holds the majority in the House?
3) Did the most common categories of spending change during COVID? For example, were members spending less on office equipment while everyone was working remotely? Or did they perhaps spend more on franked mail to communicate with constituents during isolation?
4) Which offices in the House are spending the least annually? There may be an interesting story behind lawmakers who have shown restraint in spending their budgets compared to colleagues.
5) Has staff pay kept on pace with wage growth nation-wide? The Federal Times has reported on this question, but we think it would be well-suited for data visualization.

Partway through the project, we also added the following questions to further explore the data for newsworthy findings:

- We excluded Intern Allowances very early in our analysis to only look at regular member expenses. So we decided to go back and take a look to see what patterns we could observe about intern pay.
- At least one office seems to have gone over its max budget for intern pay -- why is that?
- Are any offices spending significantly LESS than their allotted budget for interns?
- We saw in Q5 that personnel expenses are outpacing wage growth. Are there any offices whose growth in spending on personnel expenses lag(s) far behind the national trend?
- Printing and reproduction costs skyrocketed between 2021-2022. Is that being driven by a handful of offices or is it a congress-wide trend?

Quarterly expenditure data was downloaded from https://projects.propublica.org/represent/expenditures

House member data originates from ProPublica's Congress API https://projects.propublica.org/api-docs/congress-api/ which requires an API key. 
Request an API key here: https://www.propublica.org/datastore/api/propublica-congress-api

National Average Wage Index data was extacted from a pdf copy of https://www.ssa.gov/oact/cola/AWI.html#Series using tabula

To see full clean and join, run "clean_only.rmd_"

For analysis, run "team_notebook_cleaned" 
