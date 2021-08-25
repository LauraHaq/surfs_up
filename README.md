# surfs_up
## Overview
An owner of a soon to be surf and ice cream shop in Hawaii is asking for an analysis of year-round temperatures to determine if his shop would be sustainable in all seasons. Specifically, he requested temperature trends for months of June and December from data recoded from various weather stations over the years.  

### Resources
#### Data
- ![hawaii.sqlite](https://github.com/LauraHaq/surfs_up/blob/main/hawaii.sqlite)
#### Tools
- Python
- SQLAlchemy
- Jupyter Notebook

## Results
![june](https://github.com/LauraHaq/surfs_up/blob/main/june_temp_statistics.png) ![dec](https://github.com/LauraHaq/surfs_up/blob/main/dec_temp_statistics.png)

- Average temperatures during months of June (75&deg;) and December (71&deg;) only show a four degree difference.
- There is a larger standard deviation in December with 3.75 than in June aith 3.26.
- Minimum temperatures recorded for June is 64&deg; and 56&deg; in December.
- Maximum temperatures recorded for June is 86&deg; and 83&deg; in December. 

## Summary
Hawaii is already known as a surfing paradise with a warm tropical climate. It was not a surprise that June proved to be a great month for the shop with average temperature of almost 75&deg;. What was a surprise was that December also proved to be similarly warm on average with 71&deg;. Looking at the average temperatures the shop will do fine selling ice cream throughout the year but will have slightly fewer customers as it is 4&deg; cooler on average in December. Another find is that the maximum temperatures recorded is 86&deg; in June and 83&deg; in December. That is only a 3&deg; difference in six months and also shows that there is very little change of temperature through out the year and the shop will do well. However, with a larger standard deviation for December than in June temperatures, December is more unpredictable. This is also shown in that it has a larger difference between the maximum and minimum temperatures recorded. With only a 56&deg; minimum recorded this unpredictability is not great enough to cause problems for the shop. 

This coding found in the ![SurfsUp_Challenge.ipynb](https://github.com/LauraHaq/surfs_up/blob/main/SurfsUp_Challenge.ipynb) can be refactored for additional months and weather conditions to be analyzed. I would be interested in specifically conditions that would influence the surfing environment such as wind speed and wind direction. Also, ice cream consumption would be influenced on sunny days versus cloudy days. The projected already completed shows that opening a store would be a good business idea. If I were to dig deeper into these additional weather conditions I would be able to show the owner how to prepare season to season and be the most profitable for each month.
