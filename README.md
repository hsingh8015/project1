# Project # 1 - Global Warming - Fact or Fiction?
Global Warming
Team Members:Danielle Dejean, Kaidon Kennedy, Carolyn Scheese, Harpreet Singh
August 6, 2024
# Global Warming - Fact or Fiction?

## Background information - Synthesis of Contrasting Perspectives on Global Warming
There is a lot of debate about global warming. Global warming presents a complex challenge characterized by rising temperatures and shifting climatic patterns, primarily attributed to increased greenhouse gas concentrations from human activities. Here are some  prevailing scientific viewpoints and critical perspectives, offering a somewhat balanced understanding to guide an effective  discussion and exporation of this topic.
### Key Points:
1.	Role of Greenhouse Gases:
o	Carbon dioxide (CO2) and other greenhouse gases such as methane (CH4) and nitrous oxide (N2O) are central to the enhanced greenhouse effect, driving global temperature increases (IPCC, 2021).
o	Critics argue that the focus on CO2 might overshadow other significant natural and environmental factors, such as solar radiation and volcanic activity, suggesting a need for broader climate modeling (Curry, 2017).
2.	Evidence of Rising Temperatures:
o	Data from the past 50 years indicate the highest global surface temperatures in recorded history, underlining a clear warming trend (NASA, 2020).
o	There is caution against over-reliance on predictive models, which may not capture the full spectrum of natural climate variability, highlighting the necessity for ongoing model refinement (Curry, 2017).
3.	Mitigation and Adaptation Strategies:
o	Current strategies predominantly focus on reducing greenhouse gas emissions through technologies and regulatory measures, including renewable energy adoption and carbon capture (IPCC, 2021).
o	There is a strong case for integrating adaptation strategies to enhance resilience against climate impacts, particularly in vulnerable communities, emphasizing the need for immediate and actionable adaptation measures (Nordhaus, 2013).
4.	Equity and Policy Implications:
o	International efforts, such as the Paris Agreement, aim to reduce global emissions but must consider the differentiated responsibilities of developed and developing countries (UNFCCC, 2015).
o	Policies should acknowledge historical emissions from developed nations and the developmental prerogatives of emerging economies to ensure fairness and effectiveness (Chinweikpe, 2023).
Conclusion: To address global warming comprehensively, it is essential to embrace a multi-faceted approach that combines emission reduction with robust adaptation strategies. This approach should incorporate both scientific consensus and critical insights to foster policies that are not only effective in mitigating climate change but also equitable across different global communities. 
_(Summary generated with the help of ChatGPT 4. All references and materials verified and edited as needed for accuracy.)_
### References:
•	[Intergovernmental Panel on Climate Change ](https://www.ipcc.ch/report/ar6/wg1/) (IPCC). (2021). Climate Change 2021: The Physical Science Basis.
•	[National Aeronautics and Space Administration](https://climate.nasa.gov/vital-signs/global-temperature/?intent=121) (NASA). (2020). Global Climate Change: Vital Signs of the Planet.
•	Curry, J. (2017). [Climate Science and the Uncertainty Monster.](https://journals.ametsoc.org/view/journals/bams/92/12/2011bams3139_1.xml) Bulletin of the American Meteorological Society.
•	Nordhaus, W. (2013). [The Climate Casino: Risk, Uncertainty, and Economics for a Warming World.](https://yalebooks.yale.edu/book/9780300212648/the-climate-casino/) Yale University Press.
•	Chinweikpe, I. E. (2023). [Ethical Paradoxe3s in Global Warming and its Mitigation Strategies.](https://ruor.uottawa.ca/bitstreams/8c31c285-7b10-4ef2-af26-82daa1513905/download) St. Paul Faculty of Philosophy- Research Papers. uOttawa, Canada 
•	United Nations Framework Convention on Climate Change (UNFCCC). (2015). [The Paris Agreement.](https://unfccc.int/process-and-meetings/the-paris-agreement)

# Project Overview 
This project examines 3 environmental data sets for increases in the rise of surface temperature in countries and continents and 
the impact of CO2 for evidence of global warming and possible correlations. 

## Project Goals 
Find and examine various environmental data to see the impact of CO2 and other greenhouse gasses for evidence of global warming and possible correlations
1. Explore the temperature change of different countries and different continents over a 25-year span (1995 – 2020) 
2. Examine CO2 emissions as it relates to increases in surface temperature
3. Explore possible predication models for increases in surface temperature using country data. 

## Project Scope: We created 9 data visualizations to help answer these questions. 

## Data Collection, Clean up, Preparation and Exploration Process
1. Extracted the data from Kaggle; all files were .csv
4 different data sets were seriously considered; settled on 3 data sets. 

2. Explored the data; column, data types, null values, units of measure
One issue with our data set was that we didn't have actual temperature recordings. So, another set of data was found that had temperature recordings so we were able to clean that data set and merge it into the previously cleaned data set.

3. Transformed the data; reshaped dfs, dropped un-useful data, merged, sorted and relabeled
Cleaned the original data set then merged it with the second set according to a specific column. This created one clean data set for us to start working with. 

Set'Country' column to index to isolate and dropped rows with NaN values
Looped through renaming temp/ CO2 columns to differentiate year

4. Loaded; finalized the dataset and exported usable df to .cvs file

## Visualizations 
1. Min/Max Difference in Temp by Country (1995-2020)- Paredo Chart
Cyprus had the highest difference in Temp while Thailand remained consistent in temperatures changes over the years. 
These difference might be explained by the following: 
*Cyprus is located in the Eastern region of the Mediterranean where it can see significant temperature variations between seasons. This can cause climate changes which often lead to hot, dry summers and mild, wet winters, contributing to noticeable seasonal temperature swings.

*Thailand has a tropical climate characterized by relatively stable temperatures throughout the year. Having a consistent Monsoon every year helps as well. 

2. Min/Max Difference in CO2 by Country (1995-2020)- Paredo Chart
The county with the highest CO2 difference over the years is Qatar while the African country of Malawi had the lowest difference of C02 over the same time frame. 
Some factors that might have caused these countries to be at the top and bottom of the chart are:

*Qatar is a small country that has an open desert landscape and their biggest resource is oil and natural gases. 

*Malawi is a small country with mostly rain forests and greenery landscape and their major resource is minerals such as uranium, phosphates, coal, and  limestones.

3. Temperature difference by Contient - Bar graph
From 1995 to 2020 Europe saw the biggest difference temp difference while North America saw the lowest difference in temp over the same period.  

Some reasons for Europe to have the highest difference in temp from 1995-2020:
*Europe has seen more frequent and severe heatwaves leading for faster climate changes compared to other Continents. Europe's size and geography, including both coastal and inland areas, results in different temperature patterns. 

*North Americas’ coastal areas benefit from oceanic moderation, with the Pacific and Atlantic Oceans stabilizing temperatures. North America also has large bodies of water, such as the Great Lakes, which absorb and release heat slowly, reducing temperature variability.

4. Scatter Plot of Average Temp & Average CO2 Increase by Country
There's no direct 1:1 correlation, but higher CO2 levels generally lead to less temperature variability and more predictability.

5. Average Temp Over Time by Country - line chart
6. Average Temperature Over Time by Continent - line chart
7. Average CO2 EmissionsOver Time by Continent - line chart
There is not really a general trend of all temperatures going up like we think there is. This might be caused by our data not being as accurate as we originally thought. If we had more time we would look for another dataset that might provide a more clear distinction of Temperature change over time. Other impacts may be COVID-19 (2020-2021) with the impact of the shutdown

8. Forecasting x 3 
The results predicted that it would be a downward trend with the average temperature of the world. 
We don't know what the impact of COVID-19 (and the decrease in transportation, etc) had on the predications. Additional data points and data beyond 2020 would probably make the predications more accurate. 

9. Coorelation Heat Map
We created this heat map. It shows there is no coorelation and or lag between CO2 and rise in temperature.   

## Next Steps - What we would do if we had more time
-Get additional and better data to forecast temperature & CO2
-Explore CO2 vs Methane
-Explore change in water temperature
-Fit a linear regression line on the scatter plot correlation chart 
-Investigate the lag between the drastic change in CO2 levels and Temp
-Impact of COVID-19 on CO2 over time by continent
-Explore the temp data for inconsistencies/ errors – 2 continents dropped dramatically 
-Explore inequity for which countries are most affected and which have the biggest discrepancies. GDP Explore impact of population density/per capita.
-Explore effect of electric car policies on production & CO2 levels; e.g., country that manufactured vs country that purchased. Did this impact 2020? 

## Results/Summary of the Analysis
Over the past 25+ years the overall surface temperature of the earth has risen. However, the reasons for the rise in temperature are unclear. More research will needed to make any clear correlations with cause and effect. The Scatter Plot is probably the most helpful in visualizing the relationship of CO2 to Temperature. Although there's no direct 1:1 correlation, but higher CO2 levels generally lead to less temperature variability and more predictability. The impact of COVID-19 can't be understated as there are studies from Egypt and other parts of the world that saw a dramatic decrease in greenhouse gasses (traditionally believed to be responsible for the increase in global temperatures) There are many more things to explore, and many factors to consider as we explore Global Warming. Implications of this data analysis include ethical implications of the impact of the use of fossel fuels 

## Detailed Usage and Installation Instructions
All the source data is included in the repo
run 
-get_data.ipynb
-visualizations.ipynb
-continental_avg_temp_change.ipynb 
install the following libraries:
-pandas
-prophet
-numpy
-seaborne
-matplotlib
-datetime

This project is associated with three datasets. Each dataset is provided in .csv format. To prepare the data for analysis, the following steps should be taken:

1. Data Cleaning:
   - Remove any rows with NaN values to ensure data quality.
   - Eliminate unnecessary columns that are not relevant to the analysis.

2. Data Merging:
   - Utilize pandas to combine the first two datasets.
   - After cleaning the third dataset, which is significantly larger, merge it with the previously combined DataFrame to form a single, comprehensive dataset.

3. Data Preparation:
   - Import necessary libraries: pandas for data manipulation, matplotlib and prophet for visualization and forecasting, and datetime for handling date and time data.
   - Load the .csv files using pandas' read_csv function.
   - Verify that the data contains usable values and that there is an overlap in columns/years for a consistent time series.
   - Inspect the columns and their data types to ensure they are appropriate for the intended analysis.
   - Discard any data that is not needed for the analysis.
   - Rename columns for clarity and consistency across the merged dataset.

4. Finalizing the Data:
   - Perform an inner merge to combine the datasets based on common columns.
   - Export the final cleaned and merged dataset to a new .csv file for further use.

## Data Sets
1. [Global Warming Trends (1961-2022)](https://www.kaggle.com/datasets/jawadawan/global-warming-trends-1961-2022)
Country, ISO code, Year and Temperature 
Country wise surface temperature from 1961 to 2022
2. [Countries and their Continents](https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent)
Temperature (1960) to Temperature (2022): annual surface temp (C) from1960 to 2022 
3. [Temperature of all countries from 1995 to 2020](https://www.kaggle.com/datasets/subhamjain/temperature-of-all-countries-19952020) 
Contains data of various major cities of different countries in the world.

## Additional Resources and References 
Mohamed K. Mostafa, Gamil Gamal, A. Wafiq,(2021) The impact of COVID 19 on air pollution levels and other environmental indicators - A case study of Egypt. Journal of Environmental Management. Volume 277, 111496,ISSN 0301-4797,https://doi.org/10.1016/j.jenvman.2020.111496.(https://www.sciencedirect.com/science/article/pii/S0301479720314213)


Team Members: Danielle Dejean, Kaidon Kennedy, Carolyn Scheese, Harpreet Singh
