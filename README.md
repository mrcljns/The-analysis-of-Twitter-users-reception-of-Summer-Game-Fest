# The-analysis-of-Twitter-users-reception-of-Summer-Game-Fest

This is my final project for the University course "Text minining in the Python Language". The full report can be accessed here (unfortunately it's in polish only): https://www.delab.uw.edu.pl/en/dydaktyka-w-delab-uw/

The purpose of this work was to analyze social media with the use of text mining techniques. The study focused on checking the opinions about Summer Game Fest among Twitter users. Summer Game Fest is an exhibition of trailers for the upcoming video games, this year broadcast live from June 9-13. 11,484 tweets were collected containing the hashtag #summergamefest, which were then fed into the pipeline and processed. Using the roBERTa model, the sentiment of posts was classified into one of three classes - negative, neutral or positive. Using the publication date of individual tweets, a time series of their sentiment was created. It was established that the most popular days were the 9th and 12th of June - the dates of the opening live stream and the Xbox + Bethesda Games Showcase. Using the wordnet visualization for tweets with positive and negative sentiment, The researcher was able to highlight well-received game titles and words of criticism about the event. The last stage of the analysis was thematic modeling using the Latent Dirichlet Allocation, where the three most interpretable topics were distinguished. They concern the updates about Callisto Protocol, The Last of Us and Street Fighter 6.

## Wordcloud of positive tweets
<img src="https://github.com/mrcljns/The-analysis-of-Twitter-users-reception-of-Summer-Game-Fest/blob/main/pos_wordcloud.png" data-canonical-src="https://github.com/mrcljns/The-analysis-of-Twitter-users-reception-of-Summer-Game-Fest/blob/main/pos_wordcloud.png" width="720" height="360" />

## Wordcloud of negative tweets
<img src="https://github.com/mrcljns/The-analysis-of-Twitter-users-reception-of-Summer-Game-Fest/blob/main/neg_wordcloud.png" data-canonical-src="https://github.com/mrcljns/The-analysis-of-Twitter-users-reception-of-Summer-Game-Fest/blob/main/neg_wordcloud.png" width="720" height="360" />
