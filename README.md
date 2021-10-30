# Return-Rate-Researchers---Project-I

October 29, 2021
Emerson College Bootcamp, Data Analytics
Group Name: Return Rates Researchers
Members: Rebecca Melo, Ngoc-Tran Nguyen, Hinley Fung and Stephanie Thurstone 
Project I Analysis: Advertising Content and Consumer Engagement on Social Media
Overview 
The journey of delving into the world of social media targeted marketing campaigns initially began as the group collectively agreed how invasive technological devices and social media platforms are in today’s day and age; “big brother is always watching”. Through discussion, it was determined that there was a common interest to determine why and how we are targeted by so many Ads throughout any given day on our phones and other devices. Therefore, our hypothesis was drafted and we began defining advertisement engagement based on demographics through social media platforms and identifying the highest and lowest return rates and economic effect of targeted marketing. 
_____________________________________________________________________________________________
The Data 
The following are the sources mined for data analysis to support our hypothesis. 
o https://www.kaggle.com/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/data?select=KAG_conversion_data.csv
o https://data.world/ahalps/social-influence-on-shopping
o https://www.wordstream.com/blog/ws/2019/11/12/facebook-ad-benchmarks
o https://www.kaggle.com/mansimeena/facebook-ad-campaigns-analysis-sales-prediction
o https://www.kaggle.com/ryankieswetter/facebook-ad-campaign-analysis
o https://www.developer.twitter.com

Refreshing the Data, Development and Insights
Data exploration with regard to targeted marketing via social media platforms began by mining for data sources on platforms such as Kaggle for reliable data sources as well as diving into the Twitter Developer site to utilize an API. Several CSV files were pulled out of Kaggle, Data World and Word Stream which were then divided amongst group members to begin the cleanup process. Each group member studied and combed thru specific data sources for null/blank values and repetitive or unnecessary data. 
Group members took initiative in cleaning and developing the project through Jupyter Notebook with the intent to provide support to our hypothesis and answer the following research questions: 
I) What are the key targets for specific social media platforms? 
a. What demographics are engaging the most 
i. Age, location, gender, etc. 
II) When are click rates peaking? 
a. Time of year/day
i. relation to current events/pop culture
III) What is average exposure rate per click vs. purchase? 
IV) What social media platforms are most successful in gaining return on investment via click rates? 

Supportive figures were generated as follow: 



Rebecca concentrated on developing visualizations through Twitter’s API and was able to reference a specific time period of activity and engagement on Twitter (9:00-10:00PM).  Most people use Twitter either on the App (phone), actual webpage (Twitter.com), others are far and few in-between. The most engaged are those of the Millennial and Gen-Z generations. 



 
social-influence-on-shopping.csv
Through development, Tran was able to deduce that the majority of social media influence on online shopping was produced via Instagram and Facebook however, the majority of participants in data collection indicated that they were not influenced by target advertisements and submitted their vote as “none”. Additionally, her finding indicated that the majority of individuals included in the data set were white and either middle class or middle/lower class; which was interesting given that the most popular vote for being influenced by targeted Ads was “none,” indicating that perhaps the individuals participating in the survey were primarily focused on saving or household bills. 










KAG_conversion_data.csv
Hinley concentrated on defining the demographics of participants surveyed with regard to Facebook Advertisements and the influence aforementioned had on return of investment.  Via development it was concluded that gender played no influence in terms of Ad engagement or purchases and that the more a company invests into it’s marketing campaigns the larger to return on investment typically is. 

Facebook_Ads_2.csv



Social_Network_Ads(1).csv

Development led Stephanie to conclude that about half those showing activity on Facebook are engaging via clicks on advertisements while the other half are not engaging with ads and that the average amount of time spent on Facebook at a time is 32.92 minutes. Additionally, there was a higher rate of sales based on social media marketing ads for Millennials (ages 35-40) and that gender only had a slight impact on the purchase rates as indicated in the figure above, females are 2% more likely to purchase an item from an advertisement than males.  

Roadblocks
While conducting research we came to the realization that the majority of social media platform data is private to the company and require authorization to receive API of up to two weeks or payment for data utilization. It was concluded that the generation of an API for a public site such as Twitter is far more tedious than initially thought as the JSON file was so large with a vast array of dictionaries. Time constraints held us from developing an additional API due to an authorization hold. Additionally, the Twitter API only allowed for the most recent data to be pulled at once (last 100 instances on specific date/time) and in order to produce larger data quantities the API would have had to have been run for multiple days. 
_____________________________________________________________________________________________
Reflection
Return Rate Researchers were successful in their efforts to develop conclusions to support their hypothesis and answer the majority of presented research questions referenced in Refreshing the Data, Development and Insights. 
The key targets for Facebook and Twitter are mainly Gen-Z and Millennials and gender does not seem to play a large role in return on investment. Click rates peak around 9:37 PM. The average exposure rate per click vs. purchase is 32.92 minutes and Facebook seems to have the largest return on investment based on the data studied. 
_____________________________________________________________________________________________

