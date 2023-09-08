# EXCEL-CHALLENGE

## Background:
The purpose of this respistory is to organize and analyze a database of 1,000 sample projects to uncover any hidden trends for crowdfunding platforms. In order for these platforms to recieve any type of funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. 

This repository contains the following: 

  - **Crowdfunding.xlsx:** An extensive Excel chart brimming with data, featuring over 1,000 crowdfunding platforms. The chart provides insights into their performance, launch dates, and more. It underwent modifications, including the conversion of timestamps into actual dates, the incorporation of new columns such as average donation, the segregation of parent and sub-categories, and the inclusion of percentage funded.
    
        PIVIOT TABLES&CHARTS
 - ***category_pivot.xlsx:*** This Excel file contains a pivot table that analyzes the crowdfunding data, providing a count of successful, failed, canceled, and currently live campaigns per category. You can also filter the data by country using the table. Additionally, there is a stacked bar graph representing the information in the pivot table.
 - ***subcategory_pivot.xlsx:*** Another curated pivot table within this Excel file examines the crowdfunding data, offering a count of successful, failed, canceled, and currently live campaigns per subcategory. It includes filtering options by country and parent category as well.
 - ***date_created_pivot.xlsx:*** This Excel file features a pivot table with columns for campaign outcomes, rows for Date Created Conversion, and values representing the count of outcomes. You can apply filters based on parent category and years. In addition, there is a line graph that visualizes this new table.
 - ***goal_outcomes.xlsx:***
 - ***backers_count.xlsx:*** A worksheet that consists of the number of backers of successful campaigns and one column for unsuccessful campaigns which is then used to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:

    - The mean number of backers
    - The median number of backers
    - The minimum number of backers
    - The maximum number of backers
    - The variance of the number of backers
    -  The standard deviation of the number of backers


           CROWDFUNDING GOAL ANALYSIS
      Based on the provided data, it appears that crowdfunding campaigns exhibited both successful and failed outcomes. Notably, they achieved their highest levels of success           during the summer months, specifically in June and July, with 55 and 58 campaigns being successful. Among the various categories, plays and theaters stood out as the most          successful.
   
      It's important to note that one limitation of the dataset is the presence of missing data in certain columns. This gap in information leaves us uncertain about whether the         missing values represent a significant number of campaigns that were either successful, failed, or canceled, or if they simply indicate zero occurrences.

      To enhance our analysis, we could consider creating additional graphs or tables to compare different currencies across various countries. Such a comparison would allow us to       discern discrepancies in the actual amounts raised, especially if we were to convert the currencies of European countries into USD, for example.

        STATISTICAL ANALYSIS
      Given that our data is not evenly distributed between the two categories, successful and failed backers' counts. With successful having a length of 566 columns and failed          with a length of 365, it would be more dependable to utilize the median as a summary statistic rather than the mean.

<img width="854" alt="Screenshot 2023-09-07 at 10 53 07 PM" src="https://github.com/sorapmas/excel-challenge/assets/128443029/42825861-a29c-4e49-aff1-0db284e07b15">
