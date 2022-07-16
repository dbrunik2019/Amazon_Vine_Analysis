# Amazon_Vine_Analysis
Amazon_Vine_Analysis
## overview
The purpose of this analysis and project was to learn AWS, BIG data handles, and database systems. We used google collab, which is a little bit like jupyter notebook, to read and write data to SQL and AWS. We hosted a database on AWS and then ran that datbase on our device using postgress sql. (PG ADMIN). By doing this, we were able to read in data from AWS reviews to do an analysis on the reviews and determine the quality of the reviews. I chose to use the music link. url = "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz"

pyspark was used to determine the bias in the reviews and the number of ratings


##resutls
How many Vine reviews and non-Vine reviews were there?
100,000+. 

Imagine is also attached as Capture.png in git files
image.png

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Zero out of the seven Vine reviews had 5 stars, which is 0.0%.
67580 out of the 105979 non-Vine reviews had 5 stars, which is about 63%

### summary 

Overall, people rate music based on a variety of different criteria and there is a lot of different styles, so it is hard to determine the level of bias. its say there might be some level of kurtosis as people rate things positivly on average, and data piles in the middle. More likely it skewed to the right witha  lot of 5 start reviews. Based on the dataset, you can see there is a reasonable amount of positive reviews that could be skewing it. 