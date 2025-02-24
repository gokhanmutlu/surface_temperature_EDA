# Surface Temperature EDA

## Description

This Dataset contains details of Average Monthly surface temperature (1940-2024). Current climate change is primarily caused by human emissions of greenhouse gases. 
This warming can drive large changes in sea level, sea ice and glacier balances, 
rainfall patterns, and extreme temperatures. This has potentially devastating impacts on human health, farming systems, the stability of societies, and other species.

### Data Understanding

The dataset that you'll be using in this lab contains 198900 rows and 7 columns for the variables listed below. 

**Note:** For more information about the data, refer to its source on [Kaggle](https://www.kaggle.com/datasets/samithsachidanandan/average-monthly-surface-temperature-1940-2024).

|  Column Name         | Description                                      |
|---------------------------------|------------------------------------------------------------|
| **Country Name**                | Country Name.                                            |
| **Country Code**                | Code of Countries.                                            |
| **Year**                        | Year of given data.                                               |
| **Day**                         | Day of given data.                                       |
| **Average surface temperature** | Daily surface temperature.                          |
| **Average surface temperature** | Monthly average surface temperature.                            |

## Analyze (EDA)

<img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Average%20Surface%20Temperature%20by%20Year.png" width="60%">

- The graph indicates a steady increase in average temperatures over the years, likely due to global warming caused by human 
activities like burning fossil fuels and deforestation. This trend highlights the urgent need for climate action to mitigate its impacts.
<br/>

<img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Hottest-Coldest%20Countries.png" width="60%">

- There is little difference in the average temperatures among the top 5 hottest countries.
- There is a significant difference in the average temperatures among the top 5 coldest countries, with Greenland having the coldest average.
<br/>

<img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Hottest-Coldest-Boxplot.png" width="60%">

- Among the top 5 hottest countries, Burkina Faso and Senegal experience little temperature variation throughout the year, while the other countries show more significant fluctuations.
- South Georgia, in particular, has very little temperature variation throughout the year, whereas other countries exhibit more noticeable seasonal changes.
<br/>

<img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Monthly%20Average%20Temperature.png" width="60%">

- When examining the general temperature averages, it is evident that the average temperature during the summer season is higher compared to other seasons.
<br/>


<p float="left">
    <img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Linear%20Regression.png" width="49%">
    <img src="https://github.com/gokhanmutlu/surface_temperature_EDA/blob/main/images/Temperature%20Forecast.png" width="49%">

</p>

<br/>


- If global warming is not curbed and measures to protect nature are not taken in the coming years, we can expect the average temperature to increase by an additional 1 degree.
<br/>

## Summary of EDA

1. Average temperatures have been steadily increasing over the years, primarily due to global warming caused by human activities such as burning fossil fuels and deforestation.
2. There is little variation in average temperatures among the top 5 hottest countries, while significant differences exist among the top 5 coldest countries. Greenland stands out as the country with the coldest average
3. Average temperatures are higher during the summer months compared to other seasons.
4. If global warming is not addressed, average temperatures are expected to rise by an additional 1 degree in the coming years. This underscores the urgent need for measures to mitigate the impacts of climate change.
