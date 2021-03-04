# -Recommendation-System-Movie-Recommendation-Engine
Use NLP tfidf technique to analyze large sample of text data on the movie plots and recommend the most similar movies to users

o	Perform data identification, check missing values, remove duplicate values, and data preparation
o	Define a tokenizer function to tokenize each movie plot into sentences then into words, filter non-alphabetic words, and stem tokenized words
o	Create TfidfVectorizer using defined tokenizer, remove stop words, then fit and transform on tokenized movie plot to generate tfidf matrix
o	Introduce linear_kernel instead of cosine similarity to calculate pairwise similarity scores on each movie plot
o	Get input of movie title from user, locate row number in similarity scores matrix, rank elements on the row to get top 10 most similar movies
