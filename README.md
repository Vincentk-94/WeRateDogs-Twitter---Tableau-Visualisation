# Data Wrangling - WeRateDogs Twitter Archive

In this project I will be gathering data from the WeRateDogs Twitter account. An archive of over 5,000 tweets up to August 1, 2017 has been downloaded to be analysed. Additionally, a file containing the top 3 image predictions for the dog breeds of these tweets using a neural network has been provided. Additional tweet information such as retweet and favourite count will be collected for each tweet in the archive. This will be obtained by querying Twitter's API for each tweet's JSON data using the Tweepy library. This will then be stored into a .txt file and finally read into a Pandas DataFrame. 

I will be using Python with the following libraries: Pandas, Numpy, Matplotlib, Tweepy, JSON and Seaborn. I will also be using Tableau to create a dashboard to display key insights. 

This project will require me to gather the relevant data from Twitter; clean the data by fixing quality and tidiness issues; perform analysis of the clean data then produce a report outlining the wrangling process as well as a report containing insights and visualisations based on findings. The Tableau dashboard will allow users to interact with the data to display trends such as the top dog breeds, top dog names and filtered scatter graphs displaying trends relating to each tweet such as the number of favourites, retweets and also the link to the tweets.

- The wrangle report outlines the steps taken to clean the data gathered from Twitter.  
- The act report outlines the trends found when analysed with Python.  
- The Tableau Dashboard can be found here: https://public.tableau.com/app/profile/vincent5105/viz/WeRateDogsTweetAnalysis/TwitterStatistics


## Summary of insights
- The most common dog rating was 13. Most ratings were at least 10. 1635 out of 2026 tweets have a rating of at least 10. 80.7% of tweets have a rating of at least 10.
- There are a total of four different sources for the tweets made by WeRateDogs. The most common tweet source was iPhone then Vine then Twitter Web Client then TweetDeck.
- The most common dog stage was pupper. There were a few entries that included multiple dog stages, each of which included the dog stage doggo.
- Golden retrievers were the most common dog breed identified by image prediction.
- A total of 113 dog breeds were identified with the neural network.
- Puppos have on average the highest ratings for any single dog stage group. Whilst puppers had the least.
- There is a strong positive correlation between the number of retweets and the number of favourites. These tweets also tend to have higher dog ratings.
- The number of favourites has increased significantly over time. The average dog ratings have also increased over time.
