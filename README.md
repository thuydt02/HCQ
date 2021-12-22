# HCQ_Tweet_Dataset: FREE to Download. Keywords: HCQ, hydroxychloroquine, tweet, twitter, COVID-19

This dataset is associated with the paper "Understanding Public Opinion on using Hydroxychloroquine for COVID-19 Treatment via Social Media", accepted by 15th International Conference on Health Informatics (HealthInf 2022)

The dataset consists of tweets pulling from Twitter with keyword: Hydroxychloroquine (HCQ), location:  US, Time: Feb - Dec, 2020.
The dataset has 2 files:
+ Full_tweet_to_github.csv.zip includes 164168 raw tweets
+ tweets_manual_classifying.csv includes randomly selected 4850 tweets in March 21, April 06, July 28, October 02. These tweets are manually classified into one of three classes: positive, neutral, and negative, basing on the claim that HCQ is a cure for COVID-19 treatment.

Each file has the following features:
full_text: the content of a tweet
user_location: the location of user who created the tweet
friends_count: the number of friends of the user who created the tweet
followers_count: the number of followers of the user who created the tweet
reply_count: the number of replies of the tweet
retweet_count: how many times the tweet is retweeted
favorite_count: the number of likes (favorites) of the tweet
created_date/created_at: the date when the tweet is created
manual_positivity: in the set of {neu = neutral, neg = negative, pos = positive}
index: the id number of the tweet. It is to linked with the raw tweet file.
hastag: the hastags in the tweet
is_with_url: in the set of {0 = no url in the tweet, 1 = there is some urls in the tweet}
hydroxychloroquine: in the set of {1 = the tweet contains the keyword "hydroxychloroquine", 0 = otherwise}
query_string: the query string to pull the tweet (=hydroxychloroquine)

Please read the paper to see how we manually classify a tweet.
