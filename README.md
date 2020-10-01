# Using Snapchat Election Data to Predict Number of Ad Impressions in 2020
## Background
The [Social Media Today](https://www.socialmediatoday.com/news/data-shows-snapchat-is-highly-influential-in-getting-younger-people-to-vote/578020/) article discusses how Snapchat has been a very influential platform in getting younger people to vote. Democracy Works revealed that 450,000 Snapchat users registered to vote using TurboVote, which was highly advertised on Snapchat in 2018. Around 57% of these 450,000 registered voters then voted in the US Midterm elections.

Political advertisements on Snapchat use different stickers, filters, and lenses to boost voting sentiment, along with providing an informative list of polling locations on Snap Maps. 
![image](https://user-images.githubusercontent.com/70858878/94759057-e186ef00-036c-11eb-9258-0bb6158e0b4f.png)

I found this topic particularly interesting in times like these, with the presidential debate happening just yesterday, September 29, 2020. I was also interested in exploring which big name firms and organizations pay for political advertising on Snapchat. 

## Business Question
What factors help us increase the number of impressions we receive on our political advertisements? 

## Data Sources
[2020 Snapchat Political Ads Data](https://github.com/vickidecastro/using-snapchat-election-data-to-predict-ad-impressions/blob/master/PoliticalAds.csv): The election data provided by Snapchat includes information on ad impressions, start date, end date, organization name, candidate ballot information, paying advertiser name, region, gender, and age bracket, as well as many other variables. 

[2020 Snapchat Political Ads Readme](https://github.com/vickidecastro/using-snapchat-election-data-to-predict-ad-impressions/blob/master/snapchat%20readme.xlsx): The Snapchat readme file contains descriptive information on each of the variables included in the election data. 

## Data Questions
Which variables have an effect on number of impressions? 
- Ad spend and total time of ad campaign

What are the equations for our simple and linear regressions? 
- Simple: Impressions = -121980.971 + 436.6294095*(Ad Spend)
- Multiple: Impressions= -374937.1815 + 5483.057998*(Total Ad Campaign Time) + 435.3750551*(Ad Spend)

What are the R^2 values of our simple and linear regressions? 
- Simple: 0.700047932 (Ad Spend)
- Multiple: 0.707228264 (Ad Spend and Total Time)

What are the standard errors of our simple and linear regressions? 
- Simple: 2146773.986 (Ad Spend)
- Multiple: 2121130.677 (Ad Spend and Total Time)

<img width="683" alt="Screen Shot 2020-09-30 at 10 37 28 PM" src="https://user-images.githubusercontent.com/70858878/94759301-8a354e80-036d-11eb-932e-2a7904f9fd20.png">

<img width="773" alt="Screen Shot 2020-09-30 at 10 36 29 PM" src="https://user-images.githubusercontent.com/70858878/94759270-696cf900-036d-11eb-9a8c-84be99b74043.png">

## Summary
![image](https://user-images.githubusercontent.com/70858878/94759000-bdc3a900-036c-11eb-8cf7-d18ea5531277.png)




![image](https://user-images.githubusercontent.com/70858878/94759446-eac48b80-036d-11eb-89d7-159d34aa1998.png)
