# Movie Recommendation System using Content-Based Filtering
# Overview
This is a project I built using a content-based method to recommend movies based on user information. The goal of this project was to create a personalized recommendation system that suggests movies to users based on their individual preferences and interests.

# Content-Based Filtering Method
For this project, I used a content-based filtering method. This method works by analyzing the content of movies, such as their title and genre, and matching them to the preferences of users. By identifying movies that are similar in content to movies that a user has enjoyed in the past, the system can recommend those movies to the user.

There are several reasons why I chose to use content-based filtering for this project. Firstly, it is a highly effective method for making personalized recommendations to users. Secondly, it is well-suited to the datasets we were given, which contain information about both movies and users. Finally, this method is relatively simple to implement, which made it a good fit for this project.

# Datasets
This project uses two datasets: movies.csv and users.csv.

movies.csv contains information about individual movies, including their movie_id, title, and genres.

users.csv contains information about individual users, including their index, user_id, gender, age, occupation, zipcode, age_desc, and occ_desc.

# Libraries
This project uses the following libraries:

pandas: for data manipulation and analysis/n
numpy: for numerical operations
warnings: to suppress warnings
cosine_similarity: for computing the similarity between movies
CountVectorizer: for text processing
string: for text processing
re: for text processing
seaborn: for visualization
nltk: for natural language processing

# Conclusion
Overall, this project was a great opportunity to explore content-based filtering and its applications in the field of recommendation systems. By building this system, I gained a deeper understanding of how content-based filtering works and how it can be used to make personalized recommendations to users. I hope this project will be useful to others who are interested in recommendation systems and content-based filtering.

