# Udacity-Data-Wrangling
## by Obi-Okonkwo Chisom

## Dataset
This is a project completed in partial fulfillment of the Udacity Data Analysis Nanodegree program.
> Two dataset called [twitter_enhanced.csv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv) and [image_predictions.tsv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv) were be downloaded, with the latter being downloaded programmatically. 
> The third dataset involves querying Twitter's API and getting tweet data using Tweet ID from the first dataset.

## Summary of Data Wrangling
I got 8 quality issues and 2 tidiness issues which I worked
#### Quality Issues
- Dataframe 1: Timestamp column is not of the correct datatype. 
- Dataframe 1: Some rating denominators have wrong values.
- Dataframe 1: Stop words are being wrongly interpreted as dog names. 
- Dataframe 1: Some dogs have 2 dog stages. 
- Dataframe 1: Some observations are retweets and replies. Only tweets are needed. 
- Dataframe 2: Some images are not pictures of dogs.
- Dataframe 2: There is a lower/upper case consistency issue concerning the p1, p2 and p3 columns. 
- Dataframe 3: The id column should be in sync (same spelling) with the tweet_id column in other dataframes 

#### Tidiness Issues
-Dataframe 1: The doggo, fluffer, pupper, poppo should be on one column. 
-Dataframe 2: The p1,p2 and p3 columns are merged to get the most likely breed of dog. 

## Key Insights after Wrangling
-The correlation between number of retweets and number of favorite counts was positive.
-The bar plot for the 10 most common dog breeds were visualized using value_counts, index slicing. Golden_retriever was the most common dog (and by some margin)
