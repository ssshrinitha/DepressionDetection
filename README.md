# Depression Detection - Sentiment Analysis using tweets.

Depression is one of the major health concerns globally. Each year, millions of people commit suicide due to depression and poor mental health, in order to save the lives of at least a few people, we chose this problem. This would reduce the mental depression of a person by finding his/her state of mind and can offer valuable and accurate insights into one ‘s mental health much earlier than conventional methods.


COLLECT THE DATA

Twitter had provided it's api for developer to access it's data before 2006, so we accessed the tweets to form a dataset for our project.

ANALYZE THE DATA

The dataset contains the following 6 fields:

sentiment: the polarity of the tweet (0 = negative, 4 = positive)
ids: The id of the tweet (2087)
date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
flag: The query (lyx). If there is no query, then this value is NO_QUERY.
user: the user that tweeted (robotickilldozr)
text: the text of the tweet (Lyx is cool)

INFER THE DATA

Importing dataset
Preprocessing Text
Analyzing data
Splitting data
TF-IDF Vectorizer
Transforming Dataset
Creating and Evaluating Models
Saving the Models
Using the Model

INPUT AND OUTPUT FORMAT

Input: The sentiment(contains the polarity of the tweet(0=negative,1=positive)) and text fields(the text of the tweet(Lyx is cool))

Output:        text                sentiment

0         I hate twitter           Negative
1     May the Force be with you    Positive
2       I don't feel so good       Negative



