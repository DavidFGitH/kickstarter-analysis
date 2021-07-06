# Kickstarting with Excel

## Overview of Project

To understand and analyze various factors that could contribute to the outcome of whether a kickstarter project gets funded or not.

### Purpose

The purpose of the analysis was to provide additional context on the successful funding of a kickstarter project by filtering various factors using Kickstarter data, specifically in the theater and play category and subcategory, using factors such as launch date and funding goals.

## Analysis and Challenges

Based on the initial results of the analysis, there is cause to believe that launch date does have an effect on a successful outcome on theater projects. There is consistent data across multiple months, and observable trends that have rational basis. Although analyzing outcomes based on goals seems to have clear results, digging into the data reveals limited data which could skew results and provide misleading results.

### Analysis of Outcomes Based on Launch Date

By isolating all theater projects and dividing projects based on year, we produced data and the below graph. Looking at the graph, it's clear that the best month to start a theater project would be in May, while the worst month to start a kickstarter project would be in December. This can be found by looking at which months have the highest disparity vs months with the lowest disparity in the graph. The trend seems to be a peak in the amound of successful projects around the month of May and decrease until it hits nadir in the month of December.
https://github.com/DavidFGitH/kickstarter-analysis/blob/91f3179a37d1e824ca2dce13738aa6b018780557/resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals

The graph below was created using data created by isolating various ranges of funding goals, and counting the results of kickstarter play projcts in each category and converting the counts as a percentage. The best conclusion that can be made from the data is that for projects with funding goals less than 4999, there is a more than 70% chance of getting a project funded. With higher funding goals, the chance of success drop dramatically to around 50 percent and lower, and although there are ranges with higher percentantages of success those are less reliabe as will be elucidated in challenges. 
https://github.com/DavidFGitH/kickstarter-analysis/blob/91f3179a37d1e824ca2dce13738aa6b018780557/resources/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered

The data for Outcomes Based on Launch Date was consistent but required more context, but there were various issues with the Outcomes Based on Goals data:
-With the Outcomes Based on Launch Date data, overall the data is straightforward with clear outcomes, but more context could be provided. Some things could used more clarification such as in the month of March there is a dip in the number of projects and a large spike in failed projects in October. We could also isolate by year to add more context, as well as account for factors such as the length of a kickstarter project which would allow more time for a project to get more funding.
-For the Outcomes Based on Goals data, there was a significant dropoff in the amount of data for goals above 10000. This dropoff could provide data that would be skewed and produce misleading results, such as goals between 35000 to 49999 being more successful, but when looking at the numbers there are only 9 projects total, too few to be conclusive. If we cutoff to a lower number, we would find projects with goals above 20000 would have an over 60% chance of failure. Some ways around this could be decreasing the ranges of the funding goals, decreasing the cutoff for the largest funding goals, and finding more ways to add context.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclustion that can be made from Outcomes based on Launch Date is that projects that launch in the month of May have the largest chance of success, with an over 65 percent chance of success that would gradually diminish over the course of the next couple of months. The seconde conclusion that can be made is that projects launched in December seems to have the least chance of success, with barely over 50 percent of projects funding. There seems to be an awareness of which months are generally the most desirable to launch because there is a general dropoff in projects launched in the month of March into April, before the largest number of projects overall are launched in the month of May.

- What can you conclude about the Outcomes based on Goals?
There is enough data to conclude that goals below 4999 have a large chance of success, over 70 percent sucess based on the data. After that, the chances of success drop dramatically to the level of a coin flip, up until a range of 10000 to 14999 where there is a significant dropoff in the amount of data to make any conclusions. 

- What are some limitations of this dataset?
As mentioned earlier, the data become very limited in the number of samples once the ranges start increasing over 10000 to 14999. The ranges are also somewhat arbitrary, and could use more analysis with things like a boxplot to see where outliers are and how the data is distributed. Having more sensible ranges and eliminating outliers could help make the data more reliable. Also if someone wants to start a project with higher funding goals, having the chance of success either being around 50 percent or unreliable would be very unsatisfactory and finding more factors that could contribute to success would help as well.

- What are some other possible tables and/or graphs that we could create?
One table that could be created is whether the length of a kickstarter project could have any effect on success. Do projects with a longer period from start to end date have a better chance for funding or does a short period create more interest. There are also factors that could be included into tables such as whether the kickstarter project was chosen in spotlight, or whether it was a staff pick could help contribute to success as well. As mentioned earlier, we could also use boxplots to have a better understanding of the distribution of the outcomes based on goals data. Bar graphs could be used for the Outcomes based on Launch Date to help visual the disparity in number of successful and failed projects in specific months.
