# PyBer_Analysis
## Overview of Project
A visualization and interpretation of total weekly fares for ride-sharing by city type.

### Purpose
Applying Python and Pandas, a summary DataFrame of the ride-sharing data by city type was created. Then, using Pandas and Matplotlib, a multiple-line graph that shows the total weekly fares for each city type was created.  These visualizations summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.

---

## Analysis

Please refer to the following table:

|Type|Total Rides|Total Drivers|Total Fares|Average Fare per Ride|Average Fare per Driver|
|---|---|---|---|---|---|
|Rural|125|78|$4,327.93|$34.62|$55.49|
|Suburban|625|490|$19,356.33|$30.97|$39.50|
|Urban|1625|2405|$39,854.38|$24.53|$16.57|

![PyBer Fare Summary](analysis/PyBer_fare_summary.png.png)

- The gross amount of launches generally ramp up from January through May, and then begin a decline from there.
- Failed launches remain relatively flat with respect to Successful launches.
- Two thirds of the data is culled from the United States alone for Theater Kickstarter campaigns.  The trendlines of just US data matches that of the whole dataset.  One theory as to why Successful launches peak in May is that many small dollar donors receive their IRS tax refund checks in this timeframe, and have more disposable income than at other times of the year.
- One other theory as to why all launches decline in Q4 is that small dollar donors are saving up to purchase gifts for the holidays.
---

## Results

### Outcomes Based on Launch Date
1. Launching a campaign in the April-June timeframe is the most advantageous for garnering funding.
2. The smallest chance to have a failed campaign is in the November-December timeframe.

### Outcomes Based on Goals
1. Significant success can be found in setting a modest goal (less than $15,000) for funding.
2. Failure of funding rises precipitously as goal amount increases.

### Limitations of the dataset
- Clearly, not having more current data may skew the numbers.  Having just come out the other side of a global pandemic, spending habits for small dollar donors may have changed.
- Different genres of plays / musicals / etc. would be helpful, allowing us to drill down even further to reach conclusions about different types of live performances.

### Data or Tables that should be added
- One enhancement to the Outcomes Based on Goals should be a weight given to the amount of data in the lower ranges.  Over 90% of all goals were under $15,000, so making sweeping conclusions about more expensive or ambitious plays is difficult.
