# Movies-data-set--R
Introduction: Cinema is one of the most visual influences of the modern age. As cinema has evolved, so have the characteristics that evaluate the cinema. Our model attempts at being a refreshing perspective of analyzing cinema based on genres such as Drama, Comedy, Horror, etc. We also use keywords of a movie as a determining factor in the model.  With the evolution of cinema, the budget of the movies has also gone up. Around 2000’s, we saw a lot of movies made with a budget of 100 million or less. The significance of this is that more people are now involved in the making of the cinema and the industry itself is creating careers for a lot of its people.   

Dataset Description: We begin by analyzing the Full-Movielens metadata consisting of about 45000 movies released on or before July 2017. We also have ratings information of each of these movies from around 270,000 different users, along with 19,900 unique keywords included in the dataset. With this, we also have information around 20 different genres, cast and crew data for 36,000 movies and 42,000 movies respectively. We also filtered keywords based on their frequency (50 occurrences or more) and then performed one-hot encoding on top of 505 keywords and 20 different genres. For dimensionality reduction, we used PCA on some keywords and selected those which had the highest variance. We are implementing classification models to classify movie ratings into buckets/classes based on variables of keywords, genres and release month.  In the dataset, we had several Stringified JSON columns which needed formatting. So, we used sub and gsub functions to format the data and split them into separate columns. 
