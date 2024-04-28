# Group 1 MIST4610 Group Project 2 (Spring 2024)

## Team Name: 
61608 Group 1

## Team Members:

1) Dylan Palenik: [@DylanPalenik1](https://github.com/dylanpalenik1)
2) Aakash Dholakia: [@AakashDholakia](https://github.com/AakashDholakia)
3) Dan Kerik: [@dan-kerik](https://github.com/dan-kerik)
4) Hayley Daniels: [@hayleydaniels](https://github.com/hayleydaniels)
5) Jordan Beal: [@JordanBeal](https://github.com/jordanbeal1)
6)  Lexie-Anne Rodkey: [@LexieRodkey](https://github.com/lexierodkey)

## The Dataset:

Obtained: https://catalog.data.gov/dataset/youth-tobacco-survey-yts-data

Dimensions: 1,048,576R x 31C

Description: The Youth Tobacco Survey (YTS) dataset is derived from a national survey conducted by the Centers for Disease Control (CDC). The survey collects data on tobacco use among youth in middle and high schools across the US from 1999 to 2017, including the use of cigarettes, e-cigarettes, cigars, and smokeless tobacco. Survey questions cover topics such as tobacco use, attitudes toward smoking, exposure to tobacco advertising, and knowledge of the risks associated with tobacco products.

The goal is for the YTS data to help control strategies and initiatives aimed at reducing youth tobacco use. It helps researchers identify trends and high-risk populations to develop targeted interventions for tobacco use prevention among the American youth.
Specific types of data produced by the Youth Tobacco Survey (YTS) and their meaning.

1. Prevalence of Tobacco Use:
   - Current Use
      - Definition: Students who have used tobacco products (cigarettes, e-cigarettes, cigars, smokeless tobacco) in the past 30 days.
      - Significance: Provides insight into the proportion of students currently using tobacco.
    - Ever Use:
      - Definition: Students who have ever tried or experimented with tobacco products, regardless of whether they are current users.
      - Significance: This data point helps understand initiation rates.
2. Types of Tobacco Products:
    - Cigarettes: Data on cigarette smoking prevalence among youth, including daily and non-daily use.
    - E-cigarettes: Use of electronic nicotine systems (vaping) among students.
    - Cigars: Data on cigar smoking prevalence.
    - Smokeless Tobacco: Use of chewing tobacco among youth.
3. Socio-Demographic Factors: 
    - Age and Grade Level: Use patterns across different age groups and grade levels.
    - Gender: Variations in tobacco use between males and females.
4. Perceptions and Attitudes: 
    - Perceived Harm: Students’ perceptions of the risks associated with tobacco use.
    - Access and Availability: Data on where students obtain tobacco products and their exposure to tobacco use.
5. Trends Over Time: 
    - Yearly Comparisons: Tracking changes in tobacco use prevalence and behaviors over multiple survey cycles.
    - Longitudinal Data: Following students over time to observe the changes in tobacco use from adolescence into young adulthood.
6. Geographic Comparisons: 
    - State-Level Data: Insights into variations in tobacco use, prevalence, policies, and interventions across different states.
    - Urban/Rural Difference: Contrasting tobacco use patterns between urban, suburban, and rural areas.
7. Correlates of Tobacco Use: 
    - Protective Factors: Identifying factors that may reduce the likelihood of tobacco initiation or promote cessation among youth.

By analyzing these data points, researchers can gain a comprehensive understanding of tobacco use among the American youth, identify risk and protective factors, and tailor interventions and policies to address the specific needs of different population groups.

**Glossary**
| TopicDesc  | MeasureDesc | Response | Definition | Data_Value_Footnote |
| ------------- | ------------- | ------------- | -------------  | -------------|
| Cessation | % of Current Smokers Who Want to Quit |   | Percentage of current smokers who want to stop smoking cigarettes. | Data in these cells have been suppressed because of a small sample size |
| Cessation  | Quit Attempt in the Past Year Among Everyday Cigarette Smokers  |   | Percentage of current smokers who quit smoking for one day or more in the past year. | Data in these cells have been suppressed because of a small sample size |
| Cigarette Use  | Smoking Status  | Current | Percentage of students who reported that they had smoked cigarettes on one or more days of the 30 days preceding the survey.  |   |
| Cigarette Use | Smoking Status | Ever | Percentage of students who reported that they had ever tried smoking cigarettes, even one or two puffs. |   |
| Cigarette Use | Smoking Status | Frequent | Percentage of students who reported that they had smoked cigarettes on 20 or more of the 30 days preceding the survey. |  
| Smokeless Tobacco Use | User Status | Current | Percentage of students who reported that they had used smokeless tobacco on one or more days of the 30 days preceding the survey. |   |
| Smokeless Tobacco Use | User Status | Ever | Percentage of students who responded that they had ever used chewing tobacco, snuff, or dip, such as Redman, Levi Garrett, Beechnut, Skoal, Skoal Bandits, or Copenhagen. |   |
| Smokeless Tobacco Use | User Status | Frequent | Percentage of students who reported that they had used smokeless tobacco on 20 or more of the 30 days preceding the survey. |   |
| Cigarette Use | High School (HS) |   | Data are based on a sample of students in grades 9–12. |   |
| Cigarette Use | Middle School (MS) |   | Data are based on a sample of students in grades 6–8. |   |


**Data Dictionary**
| Field Name  | Type | Definition  |
| ------------- | ------------- | ------------- |
| Year | Date | Age of survey participant |
| Location Abbr  | String | Abbreviation for the state in which the survey was conducted |
| Location Desc  | String (Geographic Role - State/Province)  | Full name of the state where the survey was conducted |
| TopicDesc | String | Description of the specific topic being measured (either Smokeless Tobacco Use or Cigarette use) |
| MeasureDesc | String | Description of measures in the survey (Smoking Status, User Status, Quit Attempt in Past Year Among Current Cigarette Smokers, Percent of Current Smokers who want to quit) |
| DataSource | String | The source of the data, in this case, the value is always ‘YTS.’ |
| Response | String | Response category (Ever, Current, or Frequent) |
| DataValueUnit | String | Unit of measure for the data values (%) |
| DataValueType | String | The type of value represented in the dataset |
| DataValue | Number (decimal) | The actual value of the data point |
| DataValueFootnote Symbol | String | Symbol indicating a footnote related to the data value (*) |
| DataValueFootnote | String | Explanation of additional information related to a specific data set |
| DataValueStdErr | Number (decimal) | Standard error associated with the data value, indicating the level of uncertainty or variability |
| LowConfidenceLimit | Number (decimal) | Lower limit of the confidence interval for the data value |
| HighConfidenceLimit | Number (decimal) | Upper limit of the confidence interval for the data value |
| SampleSize | Number (whole) | The size of the sample/number of participants represented in the survey |
| Gender | String | Gender of those who completed the survey (Male or Female) |
| Race | String | Race of the surveyed individuals |
| Age | String | Age of participant |
| Education | String | Grade level of participants categorized into Middle or High School |
| GeoLocation | String | Geographic coordinates of where the participant took the survey for tracking purposes |
| StratificationID1 | String | Stratification identifiers for subgroup analysis - Gender |
| StratificationID2 | String | Stratification identifiers for subgroup analysis - Age |
| StratificationID3 | String | Stratification identifiers for subgroup analysis - Race |
| StratificationID4 | String | Stratification identifiers for subgroup analysis - Education |
| DisplayOrder | Number (whole) | Order for displaying data values in visualizations |



## Questions and Importance:
**Question 1**

1. In the United States, what are the highest and lowest rates of youth tobacco use across different states? For those who are youth tobacco users, what is their status?

This question aims to identify the states in the United States with the highest and lowest rates of youth tobacco use. By examining these rates, we can better understand regional patterns and factors that may influence these differences. Additionally, the question seeks to explore the status of tobacco users among the youth, categorizing them into occasional, regular, or frequent users based on the available data. This segmentation will provide deeper insights into the severity and frequency of tobacco use within these demographics.

Understanding the geographic variation in youth tobacco use is crucial for several reasons:
1) **Policy Development and Implementation:** Regional data can help policymakers tailor interventions and public health campaigns that are more suited to the specific needs and challenges of high-risk areas.
2) **Resource Allocation:** Identifying states with extreme rates of usage can guide resource allocation, ensuring that prevention and cessation programs are directed where they are most needed.
3) **Public Health Education:** This analysis can highlight areas where public health education efforts might be increased to combat youth tobacco use effectively.

This question is tied to the dataset because the dataset retrieved contains information regarding the use, exposure, and knowledge of tobacco among middle school and high school youth. By addressing this question, our analysis will contribute to a more targeted approach in tackling youth tobacco use, potentially leading to more effective public health strategies and better health outcomes.
<br />
<br />
**Question 2**

2. In the United States, how has the average rate of youth tobacco use changed over the years, and are there trends or shifts? Of the youth tobacco users, are there different trends and shifts based on gender?

This question explores how the average rate of youth tobacco use has evolved over the years across the United States. It seeks to identify significant trends or shifts that have occurred, providing a historical perspective on the effectiveness of anti-tobacco measures and changing social attitudes. Additionally, the question delves into whether these trends differ based on gender, offering insights into the demographic-specific behaviors and potentially uncovering unique challenges faced by different groups.

Analyzing the changes in youth tobacco use over time and across genders is vital for several reasons:
1) **Evaluation of Anti-Tobacco Campaigns:** By understanding the trends, we can assess the impact of past public health campaigns and anti-tobacco legislation, determining which strategies have been successful and which have not.
2) **Gender-Specific Interventions:** Identifying gender-specific trends can help in designing more effective, targeted interventions that address the unique challenges faced by both male and female youth.
3) **Future Predictions and Planning:** Understanding historical trends allows for more accurate predictions of future behavior, aiding in the planning of public health strategies and resource allocation to combat youth tobacco use more effectively.

Similar to the first question, this question is also tied to the dataset because the dataset retrieved contains information regarding the use, exposure, and knowledge of tobacco among middle school and high school youth. Through this analysis, we aim to provide a comprehensive overview of the shifts in youth tobacco use, contributing valuable insights for policymakers, educators, and public health officials in their ongoing efforts to reduce tobacco use among young populations.

## Manipulations:
For question 1, “In the United States, what are the highest and lowest rates of youth tobacco use across different states? For those who are youth tobacco users, what is their status?” Here are the manipulations applied to the data set for each visualization.

**Visualization 1**: State-Specific Youth Tobacco Rates

 - Data Preparation: We started by loading the data set into Tableau, and we filtered out data related to “Guam” and “National.” We filtered this data out as we specifically wanted to look at rates across the 50 states.
 - Columns and Rows: The “Location Description” was set as the dimension in rows to separate the data by state. The Data Value was set to measure Average representing the average rate of youth tobacco use and was placed in columns. The Data Value was percentage set to average to better understand overall trends and patterns in youth tobacco use
 - Visual Enhancements: We used “Location Description” for color coding to help visually distinguish between states. Labels were also added to the bars to display the specific averages, improving readability.
 - 
**Visualization 2**: Youth Tobacco Users Status

 - Data Preparation: Similar to the first visualization, we excluded “Guam” and “National” entries to examine rates across the 50 states.
 - Columns and Rows: The “Measure Description” which categories current status of smokers (Percent who want to quit, attempted to quit, currently smoking) was placed in the columns to show the different categories. The average of Data value was again placed in rows to show the rate of use for each category.
 - Visual Enhancements: We color-coded the “Measure Description” to show the different types of status. We also added labels to the average Data Value to show the rates for different statuses.
These visualizations were designed to provide insights into the geographic and categorical aspects of youth tobacco use, helping organizations or governments identify key areas for prevention.

For question 2, “In the United States, how has the average rate of youth tobacco use changed over the years, and are there trends or shifts? Of the youth tobacco users, are there different trends and shifts based on gender?” Here are the manipulations applied to the data set for each visualization.

**Visualization 1**: Historical Trend in Youth Tobacco Use

 Data Preparation: We started by loading the data set into Tableau and filtered out data related to “Guam” and “National.” We filtered this data out because we specifically wanted to look at rates across the 50 states.
 - Columns and Rows: We placed “Year” into columns to show a timeline from the earliest data points in 1999 to the most recent data points in 2017. This represents the rate of youth tobacco use and changes over time.
 - Forecasting: To help understand potential future trends based on historical data, a forecast feature was applied. This helps predict future rates of tobacco use and offers insights into rates if they are expected to fall, rise, or stabilize
Visual Enhancements: The visualization is designed to show fluctuations and progression in youth tobacco use over the years, with the forecast providing a predictive view.

**Visualization 2**: Historical Trend in Youth Tobacco Use By Gender

 - Data Preparation: Similar to the first visualization, we excluded “Guam” and “National” entries to examine rates across the 50 states. We also filtered out data related to “Overall” for gender to focus only on males and females.
- Columns and Rows: We again placed “Year” in the columns to create a timeline. Then, the average of the Data Values was placed in rows to track the youth tobacco use rates across different years for each gender.
 - Forecasting: Forecasting was added for both male and female data sets to help project future trends based on past data. This helps identify if one gender has a sharper increase or decrease in tobacco use rates compared to one another
Visual Enhancements: We put “Gender” as a color mark to differentiate between male and female youth tobacco users. This allows for easier visual comparison of trends for both genders.


## Analysis and Results:

**Question 1 Analysis Overview:**

Using the Youth Tobacco Survey dataset, we analyzed state-specific data collected from 1999 to 2017 to uncover patterns in tobacco usage rates among youth. Two main visualizations were developed: the first detailing average tobacco use by state and the second breaking down the user status within the demographic of current youth tobacco users.


![StateSpecificYouthTobaccoRates](https://github.com/hayleydaniels/MIST-4610-Group-Project-2/assets/150054646/f968acfa-19ce-477d-a162-abd494c7984f)

**State-Specific Tobacco Use:**

Our analysis revealed that Florida has the highest average rate of youth tobacco use at 29.03%, followed by Kentucky at 28.22% and Tennessee at 28.18%. These states showcase rates significantly above the national average, suggesting regional factors may play a significant role in tobacco use prevalence among youth.

On the other end of the spectrum, Vermont reported the lowest rate at 19.31%, with North Carolina and the District of Columbia closely following. These figures are promising and may reflect the successful implementation of tobacco control policies and public health initiatives aimed at reducing youth tobacco consumption.


![YouthTobaccoUsersStatus](https://github.com/hayleydaniels/MIST-4610-Group-Project-2/assets/150054646/aa8a65a2-f249-4135-898a-0935548d05f8)

**Youth Tobacco User Status:**

The breakdown of user status among youth tobacco users provided insight into their consumption patterns. The average percentage of current smokers who want to quit stands at 50.98%, indicating a significant portion of the youth smoking population is interested in cessation. This demonstrates a potential receptive audience for intervention programs.

The data also showed that 55.97% of youth have attempted to quit smoking in the past year, which emphasizes a strong inclination toward smoking cessation among young users. However, it should be noted that this figure represents the complexity of tobacco addiction and the challenges in achieving successful cessation.

In terms of the overall smoking status and user status, our visualization indicates that while there is an evident desire to quit, a large percentage of youth remain engaged in tobacco use, whether experimentally, occasionally, or regularly.

**Implications and Conclusions:**

The implications of these results are twofold. Firstly, the high rates of youth tobacco use in certain states necessitate targeted public health interventions that address local cultural, socioeconomic, and educational factors. Secondly, the evident interest among youth tobacco users in quitting smoking signals an opportunity for public health officials to focus on supportive cessation programs tailored for the younger demographic.

In conclusion, while there is a substantial variation in tobacco use rates across different states, there is also a clear indication that efforts to reduce these rates must be sustained and strategically directed. Our findings underscore the need for continued public health vigilance and the importance of supportive environments that empower youth to engage in healthier behaviors.
<br />
<br />
**Question 2 Analysis Overview:**

This analysis aimed to identify trends in youth tobacco use over time and explore any discernible differences based on gender. Using Tableau, we created two trend visualizations: one depicting the general historical trend in youth tobacco use and the other disaggregating the data by gender.


![HistoricalTrendInYouthTobaccoUse](https://github.com/hayleydaniels/MIST-4610-Group-Project-2/assets/150054646/0e7712c3-343e-45af-b36b-153d8a7a59dd)

**General Historical Trends:**

The general trend of youth tobacco use from 1999 to 2017 shows a statistically significant decrease with an R-squared value of 0.959, indicating that approximately 95.8% of the variability in the average data value can be explained by the year alone. This downward trend has a slope coefficient of -0.0020286 (p < 0.0001), which suggests an annual average decrease in the rate of tobacco use by about 0.20%.

Looking into the future, the forecasted data, shaded in the visualization, estimates this trend will continue. We expected this trend to continue as the overall trend shows a continual decline. However, the forecast has a p-value of 0.0962613, which is insignificant at a significance level of p > 0.05. This means that the forecast does not accurately predict the changes in data value based on year. We believe this is due to the data value standard error and confidence limits as they vary a lot across different entries which show variability which could affect the significance of the trend. We believe this is likely due to the sample size of the data as it was a smaller sample size which typically leads to larger standard error.



![HistoricalTrendInYouthTobaccoUseByGender](https://github.com/hayleydaniels/MIST-4610-Group-Project-2/assets/150054646/57373ddf-4caa-492f-b7c7-f8f265cf3966)


**Trends by Gender:**

The gender-specific analysis revealed a similar downward trend for both males and females. For males, the slope coefficient of the trend line was -0.00232155 (p < 0.0001), and for females, it was -0.002048 (p < 0.0001). Although both genders show a significant decrease, the steeper slope for males indicates that the rate of decline in tobacco use is slightly more pronounced for them compared to females.

The forecast suggests that these declines are expected to continue into the future. The forecast for females, in particular, shows a slightly less steep decline than males, suggesting that the rate of decrease in tobacco use among young females may start to lag behind that of males. This difference is visually represented by the divergence of the estimated trend lines, indicating that if current conditions persist, young males may experience a faster decline in tobacco use rates than females.

However, looking further into the forecast, although we expected both to have a continued downward trend, the male forecast was significant but the female forecast was not significant. The male forecast had a p-value of < 0.0001, which is significant at a significance level of p > 0.05. However, the female forecast had a p-value of 0.119021, which is insignificant at a significance level of p > 0.05. This means that although male tobacco use might have a continued downward trend, the female trend is inconclusive. We believe the insignificance of the female forecast can be explained by the standard error, as the standard errors are higher for females compared to males, which can contribute to a higher p-value. We again believe this is likely due to the sample size of the data as it was a smaller sample size which typically leads to larger standard error.

**Implications and Conclusions:**

The robustness of the downward trend in youth tobacco use, as shown by the high R-squared value and low p-values, suggests that anti-tobacco measures and societal changes are having a sustained impact. The consistent decline over the past two decades reinforces the effectiveness of past public health initiatives.

However, the data also illustrates that the rate of decrease is not uniform across genders, with males showing a marginally faster rate of decline. This gender-specific insight is critical for developing targeted interventions that address the unique societal and psychological factors influencing tobacco use in male and female youths.

In conclusion, our analysis substantiates a positive trajectory in combating youth tobacco use but also calls for continued and possibly differentiated public health strategies to maintain and accelerate this downward trend. Our findings serve as a quantitative foundation for policymakers and public health professionals to refine and focus their strategies moving forward.
