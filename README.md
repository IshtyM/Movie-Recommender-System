# Movie-Recommender-System

This dataset describes 5-star rating and free-text tagging activity, a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users. All selected users had rated at least 20 movies. Each user is represented by an id, and no other information is provided.
The data are contained in the files `links.csv`, `movies.csv`, `ratings.csv` and `tags.csv`. More details about the contents and use of all these files follows.
Movie information is contained in the file `movies.csv`. Each line of this file after the header row represents one movie, and has the following format:
movieId,title,genres
Genres are a pipe-separated list, and are selected from the following:

* Action
* Adventure
* Animation
* Children's
* Comedy
* Crime
* Documentary
* Drama
* Fantasy
* Film-Noir
* Horror
* Musical
* Mystery
* Romance
* Sci-Fi
* Thriller
* War
* Western

Here, user based collaborative filtering is done by KNN model. 5 movies will be recommended for the selected one. 

### Libraries Used:
Pandas, Numpy, Matplotlib

### Programing Language
Python

### IDE Used
Jupyter Notebook

### Algorthms Used
KNN
