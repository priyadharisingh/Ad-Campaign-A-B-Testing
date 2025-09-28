# Ad-Campaign-A-B-Testing
To understand which platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

# Business Problem
As a marketing agency, our primary objective is to maximize the return on investment (ROI) for our clients advertising campaigns. We have conducted two ad campaigns, one on Facebook and the other on AdWords, and we need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness. By identifying the most effective platform, we can allocate our resources more efficiently and optimize our advertising strategies to deliver better outcomes for our clients.

# Objective:
To understand which platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

# Data Description:
The dataset comprises a collection of data comprising the performance of two separate ad campaigns conducted throughout the year 2019. Specifically, the data covers a Facebook Ad campaign and an AdWords ad campaign. For the year 2021, 2022, 2023, 2024, there is a corresponding row in the dataset, resulting in a total of 1000 days of campaign data for analysis. The dataset includes various performance metrics for each ad campaign, providing insights into their effectiveness and efficiency over time.

# Key Features:
•	Date: The date corresponding to each row of campaign data, ranging from January 1st,2019, to December 31st,2019. <br>
•	Ad Views: The number of times the ad was viewed.<br>
•	Ad Clicks: The number clicks received on the ad.<br>
•	Ad Conversion: The number of conversions resulting from the ad.<br>
•	Cost per Ad: the cost associated with running the Facebook ad campaign.<br>
•	Click Through Rate (CTR): The ratio of clicks to views, indicating the effectiveness of the ad in generating clicks.<br>
•	Conversion Rate: The ratio of conversions to views, reflecting the effectiveness of the ad in driving desired actions.<br>
•	Cost per Click (CPC): The average cost incurred per click on the ad.<br>

# Process:
i.	The dataset and libraries were imported.<br>

ii.	Finding null values:<br>
&nbsp;&nsp;&nsp;The dataset was perfectly clean and did not contain any null values.<br>

iii.	Looking for outliers:<br>
&nbsp;&nbsp;&nbsp; The dataset did contain outliers as on some days the CTR is very high even more than 16 a day. However, we will keep the outliers as they will play an important role in analysis.<br>

iv.	Hypothesis Testing:<br>
&nbsp;&nbsp;&nbsp;Testing was performed to know whether the Advertising on Facebook will result in a greater number of conversions compared to advertising on AdWords or not.<br>

v.	Model creation:<br>
&nbsp;&nbsp;&nbsp;Linear model was created and fit for the facebook_ad_conversion and facebook_ad_clicks which gave an accuracy of 82%.<br>

vi.	Monthly, Weekly and Yearly Conversions of facebook ad:<br>
&nbsp;&nbsp;&nbsp;Since we knew facebook ads performed better than AdWords ads. Hence, detailed analysis was performed on AdWords ads to understand the weekly, montly and yearly analysis.<br>

vii.	Monthly Cost Per Conversion:<br>
&nbsp;&nbsp;&nbsp;This metrics was also calculated for facebook ads to understand which month has the highest cost per conversion.<br>


# Analysis:<br>
•	Facebook ads are performing better than the AdWords ads. <br>
•	More resources should be allocated in the Facebook Ad campaign as it is providing more conversions. <br>
•	Research should be carried out to understand why AdWords ads are not showing more conversions.<br>
•	Further understanding should be developed on the kind of ad created in the month of August as it has the highest CTR and more such ads should be created.
