# MyFitBit

With smartwatches and wearable tech becoming more popular, it's becoming easier for consumers to keep track and monitor their activity, heartrate, calories, and even sleep patterns. Fitbit even tracks how long you spend in each stage of sleep and that's what this project is going to look at.

For a few years now, I would occasionally wake up with a migraines which made it hard to concentrate for the whole day. I eventually ended up going to a sleep doctor and they found that I had mild sleep apnea. They recommended getting a CPAP machine to help with the symptoms along with other health issues. At first, it seemed to work but over time, the same migraines started picking up. It wasn't until recently that I switched from sleeping with two pillows to just one and I've noticed a decrease in migraines.

This project takes data pulled from my Fitbit device to see if there's any difference in my heart rate data (or sleep data) from when I was sleeping with two pillows and just one. It's broken up as follows:

- [Data](https://github.com/curtishiga/MyFitBit/tree/master/Data)
  - CurtisHiga/user-site-export
    - This is the raw data files pulled from my Fitbit
  - heartrate.csv
    - This contains my heartrate data for my sleep logs
  - sleep_cleaned.csv
    - This file contains all sleep data recorded by my Fitbit
- [Data_Wrangling](https://github.com/curtishiga/MyFitBit/tree/master/Data_Wrangling)
  - [Data_Wrangling.ipynb](https://github.com/curtishiga/MyFitBit/blob/master/Data_Wrangling/Data_Wrangling.ipynb)
    - Notebook to explore, clean, and consolidate data into single CSV files
- [EDA](https://github.com/curtishiga/MyFitBit/tree/master/EDA)
  - [EDA.ipynb](https://github.com/curtishiga/MyFitBit/blob/master/EDA/EDA.ipynb)
    - Notebook containing analysis and plots of data
  - temp-plot.html
    - Temporary plot created by plotly

If there are any interesting findings to this analysis, it could open up more functionality and opportunities regarding wear-able devices. For example, if it's found that there is a difference in the data, Fitbit/smartwatch manufacturers could implement a warning that the wearer isn't getting the most out of their sleep. Apps could be developed to keep track of the heart rate while sleeping and analyze it if it's atypical for the user or deemed unhealthy. Of course, these are only rudimentary concepts of what could be utilized by this analysis.
