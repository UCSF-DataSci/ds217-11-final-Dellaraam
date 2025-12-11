###Summary 

The dataset analyized in this project is called "Weather Sensors Dataset". The goal of this analysis is to contend with the data's discrepencies and the challanges they present and find key take away's about Real Time Weather sensor reading's from Lake Michigan's beachs. For the purposes of this analysis we only focused on patterns and correlations relating to rain volume. The biggest take awats being Total Rain was often the highest in the winter months between the end of the year and the begining of the year and Humidity and Maximum Wind Speed did not have a strong correlation with Total Rain while Air Temperature has a moderate correlation. The XGBoost model proformed best with the data with a test R²: 0.6046, RMSE: 130.95 demonstrating that Total Rain can be predicted with good accuracy from temporal features, rolling windows of predictor variables, and weather variables.

###Phase 1&2

The data started with many missing peices of data and the timestamp was not recorded in datetime yet. 

###Phase 3

All the rows with missing data were dropped as that was the most conveintant way od dealing with that large amount of data without potentially skewing any visualizations. The outliers seen in the Solier Raditation section was removed using "Q - 3 * IQR". 

###Phase 4

The Temporal features seen in Total Rain Total Rain, Air Temp, Humidity, and Max Wind Speed 

`![Figure 1-3: A. Avarege Total Rain, Air Temp, Humidity, and Max Wind Speed over the years, B. Avarege Monthly,Daily,Yearly Seasonal Patterns in Total Rain, C. Correlation Matrix Total Rain, Air Temp, Humidity, and Max Wind Speed ](output/q5_patterns.png)`


##Visualizations

![Figure 1: Initial Data Exploration](output/q1_visualizations.png)
