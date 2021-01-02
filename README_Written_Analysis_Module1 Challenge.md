# Written Analysis of the Results for the Kickstarting dataset-Challenge 1 (Theather Outcomes based on Launch date and Goals)

## Overview of Project
We are performing data analysis on several thousand crowdfunding projects data available in form of the Kickstarter Dataset to help an upcoming playwriter-Louise who wants to start a crowdfunding campaign to help fund her play "Fever". Using the Kickstarter dataset we are trying to provide insights to Louise on how different campaigns fared in relation to their launch dates and their funding goals.This analysis will help her visualize campaign outcomes based on their launch dates and their funding goals. 

### Purpose
- Provide Louise with technical analysis and visual results chart of Outcome based on Launch date
- Provide Louise with technical analysis and visual results chart of Outcome based on Goals
- Provide Louise with a written summary report of the data analysis and trends observed 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
- There is more chances for Theather projects to be successful than fail as 61% of Threater projects were succesful and 36% failed
- Cancelation in this category is rare, we saw only 2.7% of Threater projects getting cancelled
- Q2 (April-June) is the peak activity season for threater projects funding with May being the highest month successful projects
- Early months of the year (especially Jan) and ending months (especially Dec) should be avoided for theather projects launch. 
![Theater_Outcomes_vs_Launch] (https://github.com/archinarula/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
- Max successful plays are under $5000 goal amount with lesser failure rates. Higher value plays have more chances of failure.
- Cancellation rate of Plays is zero i.e. No plays get cancelled irrespective of Goal amount. 
![Outcomes_vs_Goals] (https://github.com/archinarula/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
- Making Line chart for Deliverable 2 was not straighforward as table had more columns than required so the quick links to Line charts didn't work. Instead I had to go to the Recommended chart area and then select style of Line chart from there to get the correct Axis for my charts (Percentage on Y and Goal on X axis)
- On Deliverable 2 the line chart for Percentage Cancelled is overlapping with Percentage Failed line if all 3 lines selected. If I show only Percentage successful and Percentage failed then it appears fine. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
- Theather is a strong category and most of Theater projects launched are successful
- Projects launched during first half of year will be successful especially mid year months. End of year and very starting months should be avaoid for Louise play launch.

### What can you conclude about the Outcomes based on Goals?
- Plays is a popular category of theather projects and have more success chances if are under $10000 goal limit or are over $50000 goal
- Failure rate on big goal projects is rare 

### What are some limitations of this dataset?
- Is a small dataset for Threaters on overall , so can't be trusted as a 100% accurate view
- It appears strange how dataset for Plays is skewed either towards >$50000 Goal projects or under $10000 projects. In between Goals have very few samples.

### What are some other possible tables and/or graphs that we could create?
- analysis on Percentage funding trend for Theater plays can give Louise an estimation of expected gap
- analysis on Backers and Country can give Louise idea on kind of Audience for Plays for her customized marketing efforts towards that audience group


