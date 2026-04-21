# Step 1

## Construct a rating matrix with dataset provided, each row refers to user id, each column refers to movie id.

- Which movie has the highest number of konwn ratings? Provide movie id, movie title, and the known rating number.

Movie ID: 2858
Movie Title: American Beauty (1999)
Number of Ratings: 3428

# Step 2

## Split the rating matrix into X and Y. Where Y is the column of the movie with the highest number of known ratings in the previous step. X is the resting of the columns in the rating matrix. After the split, for both X and Y, only keep the rows where have known ratings in Y. 

- What is the dimension of X now?

X shape: (3428, 3705)


# Step 3

### Let's perform further cleaning with Y. The known range from 1 to 5. For this model-based movie recommender, we would like to set a threshold, if the rating is higher than (>) the threshold, then we consider the movie can be recommended, otherwises (<=) not recommend. Suppose the threshold is 3, change the value in the Y based on the preference.

- What is the portion of movie to be recommended in Y?

Portion of users that recommended the movie: 0.8322637106184364

- What is the sparsit of X?

Sparsity of X: 0.9437629618431682

- Then imput, 0 for unspecificed ratings in X for modeling. (SAMII: Don't know if this a question, also Idk if i did it in the code Code Lines Up to 39)