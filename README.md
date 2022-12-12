# Kickstarting with Excel

## Overview of Project
Analyzed Kickstarter data to determine how theater and play fundraising campaigns fared in relation to their launch dates and fundraising goals.

## Analysis and Challenges
#### Outcomes Based on Launch Date 
A pivot table was created to compare the number of successful, failed, and canceled outcomes of Theater fundraising campaigns based on launch dates.  Parent Category and Years were used as filters, with Parent Category being filtered to show only Theater fundraising campaigns; Years were further grouped to show increments by Month.  A line chart titled Outcomes Based on Launch Date was created to visualize this data.
![pivot_table_readme_module1][def]

#### Outcomes Based on Goals
A table was created using COUNTIFS to populate the table with the number of successful, failed, and canceled Play fundraising campaigns based on fundraising goals.  Perctentage successful, percentage failed, and percentage canceled were calculated using the figures collected from COUNTIFS.  Outcome, Goal, and Subcategory were used as filters, with Subcategory being filtered to show only the fundraising campaigns of Plays. A line chart titled Outcomes Based on Goals was created to visualize this data.
COUNTIF used in cell B2:
![Screenshot 2022-12-12 140504](https://user-images.githubusercontent.com/113741694/207132390-69304615-2a1f-4c6d-bd87-cac7ae3e6196.png)



#### Challenges
A challenge I encountered was how to input the COUNTIF functions.  Updating each column was tedious, but I found a way to be more efficent by copying and pasting code used in previous columns.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The best time of year to launch a theater fundraising campaing is in Spring, with May having the most successful theater fundraising campaigns.

A relatively small number of theater fundraising campaigns were canceled.  January had the most cancellations, indicating the challenge of fundraising during the Holdiay Season.

I would recommend launching the theater fundraiser in April, May, or June.
![Outcomes_vs_Launch_Date](https://user-images.githubusercontent.com/113741694/207134556-b2b334e0-7570-4822-9a1f-4deb4be2c40b.png)


- What can you conclude about the Outcomes based on Goals?

The fundraising goals with the highest success rates were the fundraisers with goals under $5000. 76% of fundraisers with a goal of less than $1000 were successful, and 73% of fundraisers with a goal of $1000-$4999 were successful.  

I would recommend a fundraising goal no greater than $5000.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/113741694/207134451-e873776e-0262-4c2d-8ae5-e7d42913dc65.png)

- What are some limitations of this dataset?

A limilation of this dataset is all the fundraising campaigns were launched and completed prior to COVID-19.  I would be very interested to see if the percentage of successful campaigns remains as high post-COVID-19.

- What are some other possible tables and/or graphs that we could create?

Another possible table that could be created would be one that showed the duration in days of each fundraising campaign to study if the length of the campaign had any impact on the percentage of successful fundraising campaigns.


[def]: https://user-images.githubusercontent.com/113741694/207129424-6f25f9f8-3e2a-4420-bb02-1771b20406fd.png
[def2]: https://user-images.githubusercontent.com/113741694/207131964-b5137044-9102-4ec4-9e62-9572afb05138.png