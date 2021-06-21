# Kickstarting with Excel

## Overview of Project

### Background

>Louise’s play Fever came close to its fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose

An analysis for the different campaigns behaviour is carried out with the available dataset in order to know the outcomes.

There were analyzed two differents variables:

- *`Outcomes based on launch date:`* to determine how successful or not were the plays according the date were released.
- *`Outcomes based on goals:`* to determine the number of success, fail or cancel were got according to the prosposed goals.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis was performed using pivot table for the dataset. In the columns was set the outcomes (**success**, **fail** and **cancel**) and **Date Created Conversion** was set in the rows.

![table1](https://user-images.githubusercontent.com/86028032/122695750-f5c69100-d206-11eb-9366-e265b30a2220.PNG)

It was needed to group the "Row Labels" column to show the months of the year. [Support Microsoft](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us)

Then the data was plotted using line chart to view the behavior of the outcomes throuhout the months.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/86028032/122695777-0840ca80-d207-11eb-960b-6f5f738763b5.png)


### Analysis of Outcomes Based on Goals

This analysis was performed using formulas to get the required data for the different headers. It can be observed the number of success, fail or cancel were got according to the prosposed goals.

Some of Excel formulas that were needed for this analsis were:

```
COUNTIFS()
SUM()
```

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/86028032/122696729-6078cc00-d209-11eb-8215-6118625458b0.png)

### Challenges and Difficulties Encountered

One of the challenge that was encountered, was grouping the "Row Labels" column to show the months of the year, so the microsoft support page was visited to verify the procedure on how to do it.

Also, it was requiered to visit the [Support Microsoft](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us) for understanding how the `COUNTIFS()` function works.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     
  1. Theater success was higher throuhout the years than failures.

  2.  From May to September there is an important drop in success that requires to be analyzed.

- What can you conclude about the Outcomes based on Goals?

   - There were more projects with funding goals below 15,000 and were achieved. It can be cncluded that it's likely more probable that projects with lower goals can succeed.

- What are some limitations of this dataset?
  
  - The dataset is measured for different countries, and the analysis has been done without filtering for a specific country.
  - The goals in the dataset have differents currency
  
- What are some other possible tables and/or graphs that we could create?
  - Getting an analysis for country
  - Using a pie chart to realize the percentage of success, fail, and cancel.
  - Getting an analysis for different currencies
  - Getting an analysis comparing the outcomes for countries.
 
