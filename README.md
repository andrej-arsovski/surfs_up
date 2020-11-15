# Surfs_up
Using SQLite, SQLalchemy, Flask, jupyter notebook, to asses the feasibility of a Surf Shop in Oahu.

## Overview
A client is interested in opening a year-round Surf and Ice Cream shop on the island of Oahu. We have put together a database of weather station information to analyze before finalizing construction plans. Here we dive deeper and look at the temerature trends for the months of June and December in order to determine if the business is sustainable the entire year.

## Results

### June temperatures
The analysis looks at weather station data from 2010 to 2018. We obtained 1700 temperature readings from various weather stations for the month of June in this 8 year period. The mean temperature was just shy of 75 degrees Farhenheit. The minimum was 64 and the maximum 85. The temperature range is pretty tight during this month staying mainly between 73 and 77 degrees.

![june_stats.png](https://github.com/andrej-arsovski/surfs_up/blob/main/june_stats.png)

### December temperatures

During the same period described above, there were 1517 observations for the month of December. The mean temperature for this month was 71.04 degress with a minimum of 56 degrees and a maximum of 83. The majority of days in this month fal between 69 and 74 degrees.

![dec_stats.png](https://github.com/andrej-arsovski/surfs_up/blob/main/dec_stats.png)

### Takeaway
1. Average temperatures are slightly higher in June compared to December in Oahu.
2. The minimum temperatures tend to be lower in December compaared to June.
3. Overall the weather is favorable to surfing and Ice cream consumption in both months.

## Conclusion

From this analysis there does not seem to be a significant difference in tempratures between the 'summer' and 'winter' months on Oahu.

However, before we can recommend proceeding we strongly suggest looking at other weather parameters such as precipitation and chance of tropical storms. This analysis must be done for all months of the year and for a larger time period than just 8 years. Finally, the accelerating rate of climate change will undoubtedly affect the accuracy of weather prediction models based on historical data. The data currently strngly sugests that the probability of historically 'rare' events increases as the climate changes.
