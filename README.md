# Twitter-Sentiment-Analysis
1. Twitter_credentials.py- As mentioned in pre-requisits you need to create an app @twitter development to get the necessary credentials for execution of this file.

2. Twitter_sentiment_analysis.py- 
      - This py file uses OAuth API to fetch tweets from live twitter application.
      - Used TextBlob one o the concepts of NLP for checking subjectivity and polarity of tweets.
      - Created Scatter Plot using library seaborn to visualize the relationship between "Subjectivity" and "Polarity" of tweets.
      - Created Bar graph using library matplotlib to check the imapct of tweets whether it is positive, negative or Neutral.
      - Built a word chart using library wordcloud to visualize most common words.
      
3. Twitter_app.py- This py file will create an API, using library flask , this will basically accept inputs from the user at runtime and generate an output from Twitter_sentiment_analysis.py.
