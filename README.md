# US_2020_Elections
This repository contains code for sentimental analysis of US 2020 elections held between US president Donald Trump and aspiring candidate Joe Biden. 
The tweets contained on social media are an amalgam of Republic and Democratic sentiments of mass media. 
The code analyzes tweets that are categorized as positive, negative and neutral comments based on wordlist.
The tokenization of words is done using nltk package that contains pre-existing wordlist.
Other packages includes numpy, pandas and matplotlib for plotting graphs between categorized comments.
Columns are as follows:
created_at: Date and time of tweet creation
tweet_id: Unique ID of the tweet
tweet: Full tweet text
likes: Number of likes
retweet_count: Number of retweets
source: Utility used to post tweet
user_id: User ID of tweet creator
user_name: Username of tweet creator
user_screen_name: Screen name of tweet creator
user_description: Description of self by tweet creator
user_join_date: Join date of tweet creator
user_followers_count: Followers count on tweet creator
user_location: Location given on tweet creator's profile
lat: Latitude parsed from user_location
long: Longitude parsed from user_location
city: City parsed from user_location
country: Country parsed from user_location
state: State parsed from user_location
state_code: State code parsed from user_location
collected_at: Date and time tweet data was mined from twitter*


The following predictions were made based on the results of graph:
Which parts of the world are interested (ie: tweet about) in the US elections, apart from the US?
How do the users who tweet about this sort of thing tend to describe themselves?
Is there a correlation between when the user joined Twitter and their political views (this assumes the sentiment analysis is already working well)?
Predict gender from username/screen name and segment tweet count and sentiment by gender.

