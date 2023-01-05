# Climate-Tweets-Analysis

This project gathers tweets relating to the environment and climate change from the Twitter API v2. Gathered tweets are analyzed sentimentally. After identifying the sentiment disposition of a tweet, tweets are then further analyzed to determine overall sentiment distribution, highest polarity, and highest single word frequency. Results are visualized in numerous ways such as in the form of a pie chart, histograms, and word clouds.

Created with:
- Python
- Juypiter Notebook

Main Python Libraries used:
- pandas
- vaderSentiment
- matplotlib
- tweepy
- wordcloud

## Visualizations
The following are a few examples of the visualizations done within this project.
### Sentiment Classification Distribution
![Sentiment Classification](https://github.com/garlandzhao/Climate-Tweets-Analysis/blob/9f9dbf1958f05455c9b1c85ae72c5e3eb8e2b916/Climate%20Tweets%20Analysis%20Project%20Files/Images/Sentiment%20Classification.png)

The pie chart reveals that most tweets are classified as negative, followed by positive, and then neutral.

### Word Clouds
#### Positive Word Cloud
![Positive Word Cloud](https://github.com/garlandzhao/Climate-Tweets-Analysis/blob/9f9dbf1958f05455c9b1c85ae72c5e3eb8e2b916/Climate%20Tweets%20Analysis%20Project%20Files/Images/Positive%20Wordcloud.png)
#### Negative Word Cloud
![Negative Word Cloud](https://github.com/garlandzhao/Climate-Tweets-Analysis/blob/9f9dbf1958f05455c9b1c85ae72c5e3eb8e2b916/Climate%20Tweets%20Analysis%20Project%20Files/Images/Negative%20Wordcloud.png)

The word clouds reveal that those who are categorized with a positive sentiment often use words that involve working together for a better future while those who are categorized with a negative sentiment often use words that involve their own experiences and what has changed.

### Note
- The keys used for this project has been removed
- New keys must be added to the keys.py file
