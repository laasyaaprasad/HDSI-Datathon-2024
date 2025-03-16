# HDSI-Datathon-2024
Harvard Data Science Initiative - Agrithon 2024

The project aims to explore the relationship between farmer age demographics and agricultural production across various regions in the contiguous United States. This investigation will delve into how trends in the average age of farmers, a statistic that has been rising steadily, may impact food production and economic sustainability. By analyzing demographic and land data, the project seeks to understand age-related patterns within states. The analysis involved examining crop sales data and adjusting for inflation to provide a clear picture of economic trends tied to farmer age, potentially highlighting regions where the aging farmer population poses risks to production.

Questions guiding the project include examining variations in farmer age over time and assessing the economic impact of aging within agriculture. By creating visualizations the project aims to display regional differences and spatiotemporal trends and analyze relationships between
avarage farmer age and farm production, before and after inflation, thereby supporting a comprehensive understanding of how farmer demographics could shape the future of U.S. agriculture.

Key Insights : 

* ### Spatiotemporal Trends in Farmer Age
  * How has the average age of farmers evolved over time across states, and nation in the United States, from 1997 onwards?

<img width="1393" alt="Screenshot 2024-10-08 at 12 36 44 AM" src="https://github.com/user-attachments/assets/32979a8d-f740-42ef-9659-5ec61e8a0088">

The national average for each year based on the data is an upward trend (Red Line)

 * 2000: 54.5 Years
 * 2005 : 56.5 Years
 * 2007 : 57.2 Years
 * 2010 : 57.9 Years
 * 2012 : 58.4 Years
 * 2017 : 57.37 Years
 * 2022 : 58.09 Years


Across most states, there is a clear upward trend in the average age of
farmers.

#### Regional Variations

1. States that have a significant percentage of younger farmers.
  * **Rhode Island (FIPS 44)**
  * **Alaska (FIPS 2)**
  * **Maine (FIPS 23)**

2. On the other hand, states that have been consistent in having a higher-than-average farmer age througout the years
  * **Mississippi (FIPS code 28)**
  * **Florida: (FIPS 12)**
  * **California (FIPS 06)**


3. **Arizona (FIPS 4)** seems to have one of the the highest average farmers age 60.1 in 2022
4. D**elaware (FIPS 10)** also seems to have a significant increase in farmers through the years

#### 2012 as a Notable Peak

1. Many states show the darkest shades in 2012, suggesting that the average age peaked around this time. However, in the subsequent years, there’s a slight drop or stabilization in the average age.

#### Aging Trend in Larger Farms

1. From our analysis, it can be found that Larger farms,  tend to be operated by older farmers who have accumulated resources and experience over time.

2. **Texas (FIPS 48)**  which is the state with is the state with the largest farmland in the United States, reflects the increasing trend of an aging agricultural population​.

3. Montana (FIPS 30) is another state that depicts an aging trend among farmers and has a large area of farmland


* ### Regional Variations and Economic Impact
  * At the state level, how does the average age of farmers correlate with the economic scale of farms? 

<img width="1377" alt="Screenshot 2024-10-08 at 12 41 35 AM" src="https://github.com/user-attachments/assets/8e0a8931-e14a-4435-bdb5-3c54b643364b">

#### Correlation Between Average Age of Farmers and Economic Scale of Farms

* **Larger Farms, Older Operators:** Larger farms are more likely to have older operators because older farmers tend to have accumulated more capital and land over their careers. This often results in older farmers running larger, more economically significant farms.

* **Younger Farmers and Smaller Farms:** Younger farmers are more likely to operate smaller farms or be involved in alternative or niche farming enterprises, as they may lack the resources to manage large-scale operations from the start.

#### Trends in the Average Age of Farmers Over the Years

* Steady Increase: The average age of farmers has been increasing steadily over the last few decades, as seen in the provided plot. This trend is largely due to younger generations not entering farming at the same rate as older farmers retire or reduce their activity.

* Delayed Retirement: Many older farmers delay retirement, either due to financial necessity or emotional ties to the land. Additionally, advancements in technology allow them to continue managing their farms despite the physical demands of the profession.

* ### Inflation Adjustment and Sales Analysis
  * Does adjusting for inflation reveal different trends in the relationship between farmer age and farm production?
    
 <img width="988" alt="Screenshot 2024-10-08 at 12 43 19 AM" src="https://github.com/user-attachments/assets/4c9967e4-8acc-4427-bfbc-3a43a0c00f7f">

 The above question can be answered by calculating the correlation between farmer's age and crop types sales in dollars both before and after inflation adjustment.

#### Nominal vs. Inflation-Adjusted Correlations:

The plot shows both nominal and inflation-adjusted correlations between farmer age and various commodity sales.

* Nominal sales correlations are shown in blue, while inflation-adjusted correlations are in red.
Pronounced Correlations:
* Some commodities exhibit a more pronounced correlation with farmer age after adjusting for inflation. These are represented by longer bars in the red section of the plot.


The key insights we can draw from the plot are,

#### Negative Correlations:

* Several commodities, such as rice, corn, cotton show negative correlations with farmer age after inflation adjustment, indicating that as farmers age, production or sales decrease for these commodities.

#### Impact of Inflation Adjustment:

* Adjusting for inflation tends to reveal stronger negative correlations for certain commodities, suggesting that older farmers might be less involved in high-production activities or that their operations may not scale as effectively with age.

This analysis helps identify which commodities are most sensitive to changes in farmer demographics when considering real economic values.

  
