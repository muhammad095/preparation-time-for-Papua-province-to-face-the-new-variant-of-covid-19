# Preparation Time for Papua Province to Face The New Variant of COVID-19

## Objectives
1. To find out when the first cases of COVID-19 detected in DKI Jakarta and Papua Provinces
2. To find out the difference in the timing of the spike in Covid cases between DKI Jakarta and Papua Provinces
3. To give illustration for Provincial Government of Papua how much left time they have to prepare if new variant of COVID-19 or other outbreak have been detected in DKI Jakarta in the future

## Methodology
1. Dataframe manipulation
2. Data visualization

## Benefits
1. Helping Provincial Government of Papua to estimated their time limit to prepare their strategy if new variant of COVID-19 or other outbreak have been detected in DKI Jakarta

## Expected outcome
1. Know when first case detected in DKI Jakarta and Papua Provinces
2. Know when the timing of the spike in COVID cases in Papua and DKI Jakarta Provinces

## Introduction
1. COVID-19 first reported from Wuhan, China, on 31 December 2019.
2. DKI Jakarta province as the entrance of foreign tourist in Indonesia reported first case of COVID-19 on 1 March 2020
3. Since that, other province in Indonesia also reported COVID-19 cases and continued to increased day by day.
4. Papua as the easternmost province and the farthest from DKI Jakarta in Indonesia should have enough time to prepare its region to face the outbreak

## Data Understanding
1. Source data: COVID-19 Indonesia Dataset (Case and Vaccination). https://www.kaggle.com/riqulaziz/case-vaccination-covid19-indonesia-dataset
2. The dataset contain has 17613 rows and 10 columns
3. Data Columns Description:
4. Date: Means the Date of Observation:
5. Province: Means Location/ Province which the data was observed
6. Daily_Case: Means Daily new number of confirmed case in observed province
7. Daily_Death: Means Daily new number of confirmed death in observed province
8. Daily_Recovered: Means Daily new number of confirmed recover in observed province
9. Active_Case: Means Daily new number of active case such as isolated or threated in hospital (still didnt recover nor die)
10. Cumulative_Case: Means total for each day number number of confirmed case of the row's date, for the row's province
11. Cumulative_Recovered: Means total for each day number number of confirmed Recover of the row's date, for the row's province
12. Cumulative_Death: Means total for each day number of confirmed death of the row's date, for the row's province
13. CumulativeActiveCase: Means total for each day number of active case of the row's date, for the row's province

## Data Preparation
1. Python 3.8
2. Packages: Pandas, Numpy, Matplotlib, Seaborn

## Data Cleansing
1. There is no data that contain missing value in dataset. So, we don't need to remove any data row related to missing value
2. There is no duplicate data in dataset. So, we don't need to remove any data row related to duplicated data
3. There are 34 Provinces in dataset, but we will focus only to DKI Jakarta and Papua province

## Analysis of Data Visualization 
1. When the first cases of COVID-19 detected in DKI Jakarta and Papua Provinces?
![image](https://user-images.githubusercontent.com/95937374/155202603-2fa595ee-2cec-481b-ad1b-b9fd21a67170.png)
1 March 2020 was the first COVID-19 case reported in DKI Jakarta, meanwhile in Papua detected on 22 March 2020. There was a difference of two weeks that should be used by the Provincial Government to prepare.

2. What is the difference in the date of the spike in COVID-19 cases between DKI Jakarta and Papua?
Based on the graph above, the spike in COVID-19 cases in DKI Jakarta was detected on August 2 and ended on September 27, 2020; on 1 November 2020 and ended on 30 January 2021; and on May 9 and ended in early July 2021. Meanwhile in Papua Province, spikes were detected throughout September; November 16, 2020; and 27 June to 20 July 2021. Papua Province has two weeks to one month to prepare itself in case of a spike in COVID-19 cases in DKI Jakarta

3. Comparison in cumulative COVID-19 cases graphic between DKI Jakarta and Papua
![image](https://user-images.githubusercontent.com/95937374/155208391-8e649827-b295-4b7d-aa22-b52da7be4ef3.png)
Based on the graph above, we can observe that eventhough DKI Jakarta has more COVID-19 cases and longer spike period of cases than Papua Province, but the gap between cumulative_case's line and cumulative_recovered's are more narrow than in Papua Province subplot graph. That means, average recovery time that needed by people who infected by COVID-19 in DKI Jakarta was faster than in Papua Province. This also can be taken as a note to Provincial Government of Papua Province and also to Central Governent to create strategy how to improve the quality of health services in the province, especially to anticipate if new variant of COVID-19 or other outbreak detected in Indonesia in the futru

## Recommendation
1. Papua Province has about up to two weeks to prepare if an outbreak detected in DKI Jakarta and up to one month to prepare if the outbreak case are spike.
2. Provincial Governments and Central Government should to pay attention to health services in Papua and anything that related and support to it in order to prepare the province to be more ready to face other outbreak in the future. 

