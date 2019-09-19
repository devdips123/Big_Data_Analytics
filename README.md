# Big_Data_Analytics
Contains projects in Big Data Analytics course during Spring 2019 semester. Projects have been developed using Big Data technologies like Apache Spark, Kafka, python based libraries like NLTK, tweepy, pyspark, spacy. Visualizations are plotted using d3.js with NodeJS backend. Infrastructure hosted on GCP.

Synopsis

Analysis of "Indian General Election" using tweet streams. Following use cases are implemented. Tweets are filtered based on Indian National Election held in April 2019 and the following use cases were implemented
- Sentiment Analysis of the tweets to categorize Positive, Negative and Neutral tweets. Text blob and Google Language API used to classify sentiments. NLTK and spacy is used to pre-process and clean the tweets
- Categorize the tweets based on major political parties and display as a dynamic donut chart showing the tweets per last minute.
- Display the trending Hashtags related to indian elections and display it as a dynamic word cloud refreshing every 30/60 seconds
