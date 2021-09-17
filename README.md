# amazon_music_reviews_prediction
<h3> Build a recommender system model to make predictions related to Amazon Music Reviews. </h3>
<br>Given a (user, item) pair and associated review data, we want to predict the review’s star rating as accurately as possible. The performance will be measured with MSE. </br>
<h3> Dataset </h3>

**train.csv** 150,000 reviews to be used for training. 

* `reviewerID`: The ID of the user. This is a hashed user identifier from Amazon.
* `itemID`: The ID of the item. This is a hashed product identifier from Amazon.
* `reviewText`: The text of the review.
* `summary`: A short summary of the review.
* `overall`: The star rating of the user’s review from 1 to 5.
* `reviewHash`: Hash of the review (essentially a unique identifier for the review).
* `unixReviewTime`: Time of the review in seconds since 1970.
* `reviewTime`: Plain-text representation of the review time.
* `category`: Category labels of the product being reviewed.

**test.csv** 20,000 reviews to be used for generating the final Kaggle submission. All fields are the same as in train.csv with the exception of the overall rating removed.
