# Kickstarting with Excel

## Overview of Project

This project performs data analysis on Kickstarter crowdfunding projects to discover trends of theater projects.

### Purpose

Louise wants to know the outcome of other campaigns based on their launch dates and funding goals.  I aim to identify the best launch date and funding goal by analyzing the Kickstarter data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To determine when would be the best time to launch a theater crowdfunding project I created a pivot table showing the number of successful, failed, and canceled theater projects by launch month.  This data is visualized below in a line chart.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85706721/124209478-9e9ea700-dab7-11eb-99d2-06f23afe8daa.png)

### Analysis of Outcomes Based on Goals

To determine what funding goal has the best chance of getting funded I tabulated the number of successful, failed, and canceled crowdfunding projects under the "plays" subcategory split out by different funding goal ranges.  I used the COUNTIFS formula (ex. =COUNTIFS(Kickstarter!$D:$D, "<1000", Kickstarter!$F:$F, "successful", Kickstarter!$R:$R, "plays"))  to get the required data into the corresponding cell.  This data is visualized below in a line chart.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85706721/124210323-3781f200-dab9-11eb-8f7e-62804114405a.png)

### Challenges and Difficulties Encountered

I did not encounter any challenges with this particular analysis.  One possible challenge could have been if the outcomes were not definitive.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The clear winner for best launch month is May.
  2. There is a fairly even number of failed and canceled projects throughout the year.

- What can you conclude about the Outcomes based on Goals?
  1. There is a steady decline in success rate the higher the goal amount until the $35k - $45k amount, but the number of projects in this segment is very small and may not be an accurate representation.

- What are some limitations of this dataset?
  1. Kickstarter is just one of many crowdfunding platforms.  To get a more accurate picture, other crowdfunding platforms should be analyzed as well.
  2. This data doesn't include information on any advertising that may have been done about the crowdfunding campaigns.  This could have a significant impact on the success of the campaign.

- What are some other possible tables and/or graphs that we could create?
  1. Vertical bar graphs could have been used instead of line charts.  
  2. For the "Outcomes Based on Goal" chart we could have used a vertical bar graph only showing percentage successful which is an easier to understand representation of what we are trying to portray. (shown below)
  
  ![Outcomes_vs_Goals bargraph](https://user-images.githubusercontent.com/85706721/124212228-9a28bd00-dabc-11eb-8bd9-2cd67e52f45e.png)
