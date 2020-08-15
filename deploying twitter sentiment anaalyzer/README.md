Twitter Sentiment Analyzer deployed using Flask

Model Building: We will build a Logistic Regression Model pipeline to classify whether the tweet contains hate speech or not. 
Setup Twitter App: We will create a Twitter app on the Twitter developer’s website and get the authentication keys. We will write a Python script to scrape the tweets related to a particular text query
Webpage template: Here, we will design a user interface where the user can submit his query
Get the Tweets: Once we get the query from the user, we will use the twitter API to get the tweets related to the searched query
Predict class and send results: Next, use the saved model to predict the class of the tweets and send the results back to the webpage