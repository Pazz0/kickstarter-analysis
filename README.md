# Kickstarting with Excel

## Analyzing Raw Data of Multiple Kickstarter projects to find trends for a client

### Filtering data to find Outcomes on other Kickstarters based on their Launch dates and Goals

## Our client wanted to compare her succesful play to other campaigns to see how they fared. Applying filters to the raw excel data to narrow our options and creating new columns of data that will be later used. Using a pivot table I was able to narrow "theatre" type kickstarter campaigns as well as their outcomes.

### Analysis of Outcomes Based on Launch Date.
Using the afformentioned pivot table we were able to narrow down which Months whad the most succesful theatre outcomes. This tells us when the best time to launch a play would be. May being the month with the most success shows us that late spring into summer is the most ideal time to launch a theatre kickstarter.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/18335464/206360920-ef2af1c1-8cdf-4c83-a1fd-fc762a088d66.png)


### Analysis of Outcomes Based on Goals
While analyzing data it was noticed that a projects goal had a major impact on the success of the campaign. To showcae this, I created ranges of Goals in excel and used COUNTIFS functions to determine the number of successful, failed and canceled campaigns in each Goal range. I then showcased the percentages of these outcomes in this line graph:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/18335464/206361488-f093ddac-b4fd-4e3d-984c-a746cbd9313b.png)


### Challenges and Difficulties Encountered
Outliers and incomplete data may skew our findings. In this case our results were generally clean and straightforward. Creating Goal ranges can cause errors if incorrect formulas are entered during the process. In this case the formula works as intended

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- May is the month that launches the most succesful thetre campaigns with June and July not far behind. These 3 months are ideal. In terms of failed campaigns, October sees a small peak as well as December. December would be the least ideal time to launch a campaign.

- What can you conclude about the Outcomes based on Goals?
- The succes and failed charts are an inverse of each other! As the goal range increases to the 30000-35999 goal range we see an increase of failed campaings. Generally the hogher the goal the more chance of failure. Although, something interesting happens in the 35000 - 44999 goal ranges, the amount of successes increase! This goal range is an exception to the previous statement.

- What are some limitations of this dataset?
- There are only so many campaigns here to work with. Because of this there may be other variables that could affect the data of these campaigns that aren't present for us to decipher. Working with the data we had we provided the best results and created our own new columns using existing data.

- What are some other possible tables and/or graphs that we could create?
- If we wanted to know how Currency would affect the success or failure we could create a table showing which currencies were most successful as well as which ones had the most amount of money pledged. We could also create a table to visualize if staff picked kickstarters contributed to their success.
