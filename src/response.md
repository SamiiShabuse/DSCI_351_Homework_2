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


