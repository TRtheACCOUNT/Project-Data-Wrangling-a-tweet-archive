# General
This project will start by gathering three pieces of data:
- Downloading the file “ twitter_archive_master.csv “ manually from the Udacity’s classroom.
- Downloading the file “ image_predictions.tsv “ programmatically from the Udacity's servers using the Requests library.
- Gather each tweet's retweet count and favorite ("like") count from the “tweet_json.txt” file.

After that this project will show an analysis of a dataset formed by merging the pieces wich is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs 
with a humorous comment about the dog. The enhanced data set countain these informations :
- ‘tweet_id’ : Contains the id of the tweet . 
- ‘text’ : The text of the tweet 
- ‘rating_numerator ‘: The numerator of the rathing. 
- ‘rating_denominator‘: The denominator of the rathing. 
- ‘name’: The name of the dog. 
- ‘dog_name’: The type of the dog. 
- ‘jpg_url’: The URL of the image. 
- ‘img_num’: The number of images. 
- ‘p1’: Prediction number 1. 
- ‘p1_conf’ : Prediction percentage. 
- ‘p1_dog’ : Prediction true or false. 
- ‘P2’: Prediction number 2. 
- ‘p2_conf’ : Prediction percentage. 
- ‘p2_dog’ : Prediction true or false. 
- ‘P3’: Prediction number 3. 
- ‘p3_conf’: Prediction percentage. 
- ‘ p3_dog ‘: Prediction true or false 
- ‘retweet_count’ : The number of retweets of a tweet. 
- ‘favorite_count’ : The number of favorites of a tweet.

# packages :
Python is the language used in this project, the packages used were:
- pandas
- NumPy
- requests
- tweepy
- json
