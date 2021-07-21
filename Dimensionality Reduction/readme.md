Q1: Load the load_digit dataset from sklearn.datasets.
This dataset is made up of 1797 8x8 images. Each image, is of a hand-written digit. Therefore, each training example has 64 features (8X8) pixel values. Hence, the size of dataset is 1797X64.
Implement SVD in the following two ways:
(a) Step-by-step
(b) Using inbuilt SVD function in python

Q2: Download the IMDB dataset of movie reviews from the following link
https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
or
https://drive.google.com/drive/folders/19s4vV0GaxFpxkWm4dl2gMinIHNYS0uLl?usp=sharing

IMDB dataset having 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets.
(a) Load the dataset in a dataframe.
(b) Drop the sentiment column and consider the first 1000 reviews.
(c) Make the corpus of first 1000 reviews.
(d) Convert the corpus into binary BOW vector of size mXn, where m=1000 (number of reviews
documents) and n is the number of unique terms obtained from the 1000 documents. Each ij th entry
of the vector is a binary value which is 1 if the jth term is present in ith review else 0.
(e) Compute the co-occurrence matrix of order nXn where each ij th entry of matrix is number of
documents in which both i and j th terms co-occur. (Use binary co-occurrence vector to compute
it).
(f) Using Truncated SVD method of python find the reduced matrix of co-occurrence matrix with
number of coomponents as 100.
(g) The reduced matrix of order nX100 are word embeddings of n words of dimensionality 100.
Explore more about word embeddings to learn more about it

Q3: Implement LDA (step-by-step) on IRIS dataset.
