# Global-temperature-analysis
Using R programming to analyze avg. global temperature 
---
🌍🌍🌍


## Introduction
Climate change has become one of the most critical global challenges, affecting ecosystems, weather patterns, and human livelihoods. Analyzing historical temperature data provides insights into how the Earth's climate has evolved over time. This project examines global temperature trends over the last century to identify patterns, seasonal variations, and long-term changes. These findings contribute to our understanding of global warming and its potential consequences, supporting decision-making in climate policy and awareness.

## Dataset description
The dataset contains global average temperature records spanning from 1889 to 2023, providing a comprehensive overview of long-term climate behavior. It captures detailed monthly, seasonal, and annual temperature data, making it a good resource for analyzing trends and variations over time. This dataset is particularly valuable for studying patterns of climate change, as it highlights how temperatures have fluctuated across months, seasons, and years. Below are the key variables included:

- **Year**: Represents the range of years from 1889 to 2023, serving as the timeline for the dataset
- **J-D**: The annual average global temperature calculated across all months of a calendar year, offering a complete yearly summary.
- **DJF**: Represents the average temperature of the winter season, spanning December of one year to February of the next. This metric is critical for understanding winter climate patterns.
- **JJA**: Records the average temperature of the summer season, highlighting trends during the warmest months of the year.


## Plan and Techniques  

1. **Data Cleaning**:🧹
 
-Handle missing values and ensure the dataset is not having any missing values which will hinder the analysis.Data Cleaning ensures accuracy by addressing incomplete or inconsistent entries.

2. **Data visualization**: 👓
 
-Create visualizations to uncover temperature trends over months, years, and seasons.Data visualization is crucial for visualizing patterns and understanding seasonal/annual variations in the data to gain some valuable insights seen over periods of time which will be best represented by using geom_line under ggplot2 library and we can use legend of seasonal to depict rising temperature in graphs.

3. **Global Annual Temperature Trends**:📈
 
-This visualization will provide us with trend of global temperature throughout the year since 1889 to 2023.

4. **Global Annual Temperature Trends of winters(Dec-FEB)**:❄

  -This visualization will provide us with trend of global temperature during winters that is December to February.
  
5. **Global Annual Temperature Trends of summers(June-August)**:☀
  -This visualization will provide us with trend of global temperature during summers that is June to August.
![image](https://github.com/user-attachments/assets/e6971ac7-2997-42cf-a6ad-5507ad377f3b)


## Conclusion

This analysis highlights an undeniable upward trend in global temperatures, affirming the evidence of climate change.A consistent rise in **annual average temperatures**, particularly after the 1970s.
**Winters** have warmed significantly, reducing the seasonal contrast between winter and summer which cause risk of ice caps melting and not freezing during winter which is rising issue in northern west territories of Canada increasing cases of permafrost.
Seasonal variability is becoming more pronounced, which may have ecological and economic implications. **Summers** have also drastically gotten warmer after 1980s which actively contribute in ice cap melting and environmental issues like frequent heat waves and irregular climate vents.
Future analyses could  further improvement can be made by analyzing **carbon emissions analysis** which will help to analyse which factor is contributing most in carbon emissions throughout the globe and what actions can be taken to prevent it. This study shows the urgency for global initiatives to mitigate climate change and adapt to its impacts.

