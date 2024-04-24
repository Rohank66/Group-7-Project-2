# Group 7 Mist 4610 Group Project 2

## Team Name: 
Sp24_61608_Group 7

## Team Members:

1. Rohan Kothari [@Rohank66](https://github.com/Rohank66)
2. Sedat Akgun [@sedatakgun](https://github.com/sedatakgun)
3. Tharini R.K. [@tr64311](https://github.com/tr64311)
4. Ruhi Shirke [@rushirke](https://github.com/rushirke)
5. Rachel Kim [@rachelkim816](https://github.com/rachelkim816)
6. Danielle LaDuca [@danijlad](https://github.com/danijlad)


## Description of Dataset:

Our dataset captures data on mental health readmissions in New York State from 2014 to 2021. The dataset was sourced from the New York State government’s open data portal (https://catalog.data.gov/dataset/mental-health-readmission-beginning-2014). It specified various dimensions with multiple data types to provide a comprehensive view of mental health readmissions across different groupings and demographics. The metric description identifies the specific metric being recorded, and the grouping level is a numeric identifier for the level of data aggregation (state-wide or more localized). The region or coverage category lists several different coverage types, and their regions. In this case, the unique identifiers are Statewide, FFS (Fee-for-Service), HARP (Health and Recovery Plan), HIV SNP (HIV Special Needs Plan), Mainstream, New York City, and Rest of State. The age inpatient type is a string datatype categorizing patients by age and the type of facility, providing insight into different patient demographics. The year, numerator, denominator, YTD numerator, and YTD denominator data sets provide the year of the data record and quantitative values for calculating readmission rates. They are later used to calculate the rate and YTD rate fields showing the proportion of readmissions relative to the total discharges, based on specific quarters. These various dimensions allow for an analysis on trends, demographic breakdowns, and regional comparisons. This can lead to a better understanding of the dynamics of mental health readmissions, identify areas of concern, and track the effectiveness over time. 

## Question 1:

Question Asked: How have mental health readmission coverage plans evolved over time between New York City and the rest of the state, particularly concerning readmission within 90 days?

Importance:

This question utilizes the Year, Rate, and Age Inpatient Type columns to analyze changes over time and across different age demographics, providing a clear link to the dataset. Considering that nearly half of New York state’s population resides in New York City, it is important to evaluate the various coverage plans available in both the urban and upstate areas of this state and their effectiveness. Based on the results we can determine which coverage plan is the most successful by evaluating which plans decrease the 90-day readmission rate in both New York City and the rest of the state. Four different coverage plans are evaluated for upstate New York: FFS-Rest of State, HARP-Rest of State, HIV SNP-New York City, and MAINSTREAM- Rest of State. While New York City was evaluated on FFS-New York City, HARP-New York City, HIV SNP-New York City, and MAINSTREAM-New York City. The two line graphs depict the peaks and valleys of these four various coverage plans and their effectiveness from 2014 to 2021.


<img width="1699" alt="Screenshot 2024-04-17 at 11 11 49 AM" src="https://github.com/Rohank66/Group-7-Project-2/assets/104539792/ae5ff652-43ac-452b-b0fd-69e975f261e0">

<img width="1698" alt="Screenshot 2024-04-17 at 11 28 13 AM" src="https://github.com/Rohank66/Group-7-Project-2/assets/104539792/03b1fca4-23b1-431c-9c8b-fbeb2e149d0a">

Graph Analysis and Results:

When comparing the readmission rate for the rest of New York, Mainstream-Rest of State and HIV SNP- New York appear to be inversely related. However, when looking specifically at New York City, Mainstream New York City seems to move in unison with HIV-SNP New York. Patients receiving these types of coverage plans seem to be resulting in similar rates of 90-day readmission, proposing that these two plan’s methods are comparable in the aiding patients in the rest of the state.  HARP also hit its peak in the rest of New York in 2017, one year after New York City in 2016. When patients used the Harp coverage category, their 90 day readmission rate significantly increased in both NYC and the rest of the state between the years 2015 and 2017. Two thousand seventeen also marked an increase in successful HIV SNP coverage as readmission rates fell for the entire state of New York to 0.7%. All four plans appear to be effective in 2016 as the readmission rate throughout New York City declined on average. Various factors could have contributed to this decline such as the Chelsea Bombing (local), presidential election (national), and summer Olympics (global). Coverage plans also became for effective in 2020 for New York City, presumably due to the global pandemic, which slightly lowered the 90-day readmission rate.


## Question 2:

Question Asked: How does the mental health readmission rate differ by coverage type, and are there specific coverage types with significantly higher or lower rates?

Importance: 

This question is important because it highlights the differences in mental health readmission rates and enables the public to be aware of the coverage types that are most likely to have adults readmitted for mental health reasons. With this information, insurance plans may decide they need to allocate more mental health coverage plans and resources. 

The heat map depicts the change in mental health readmission rates for each coverage type and highlights the change in rates per coverage type through a color gradient, with a darker hue denoting a higher rate and a lighter hue denoting a lower rate. Between 2015 and 2020, the statewide coverage rate decreased as the heat map shows a lighter color in 2020 in comparison to the color in 2015. 


![PNG image](https://github.com/Rohank66/Group-7-Project-2/assets/104539792/7a6d5743-d8c1-41d3-812a-f25b3d74beec)

This graph shows:

After creating the first heatmap to depict readmission rates in 2015, we decided to delve deeper into what the regional readmission rates would look like in 2020.  Between 2015 and 2020, the statewide coverage rate decreased as the heat map shows a lighter color in 2020 in comparison to the color in 2015. Here we also noticed that HARP-New York City, HARP, and HARP- REST OF STATE had significantly higher rates in 2020 compared to 2015 when it had virtually no usage. 

This phenomenon could be explained by the COVID-19 pandemic, which occurred in late March 2020 and impacted the overall ability for members of the community to gain access to mental health resources in person. As a result, the readmission rate would have been reduced for the year. In 2015, we also noticed HARP-NEW YORK CITY and HARP-REST OF STATE were non-existent. Upon research, the time period between 2015 and 2020 was indicative of the trend in reducing the stigma associated with mental health and gaining resources to help with mental health. As a result, the coverage plans were introduced to include mental health resources and provide members of the community with access to the resources. In addition, the HARP plan existed in 2015, but to increase the usage of the plan and its health and wellness resources, the coverage plan was divided into three small subsections of NEW YORK CITY and REST OF STATE to encourage use of the resources. The data supports this and highlights the increase in the usage of the mental health resources. 


## Manupulations applied to the data set for analysis:

For our project purposes, we did not need to manipulate any data. Our dataset gave us all the information needed to complete our models with having to manipulate or change any information from the dataset.

## Tableau packaged workbook

The packaged workbook containing the visualizations shown above is attached to this repository.






