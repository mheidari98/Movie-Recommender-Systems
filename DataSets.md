# DataSets ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ![MIT License](https://wangchujiang.com/sb/license/mit.svg)

## General info
> Movies DataSets for Recommender Systems (RS)

---

## DataSets
* MovieLens [grouplens](https://grouplens.org/datasets/movielens/), [kaggle](https://www.kaggle.com/grouplens/movielens-20m-dataset), [tensorflow](https://www.tensorflow.org/datasets/catalog/movielens)  
    GroupLens Research has collected and made available rating datasets from their movie web site

* [Yahoo Movies (R4)](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)  
    This dataset contains a small sample of the Yahoo! Movies community's preferences for various movies, rated on a scale from A+ to F. Users are represented as meaningless anonymous numbers so that no identifying information is revealed. The dataset also contains a large amount of descriptive information about many movies released prior to November 2003, including cast, crew, synopsis, genre, average ratings, awards, etc. The dataset may be used by researchers to validate recommender systems or collaborative filtering algorithms, including hybrid content and collaborative filtering algorithms. The dataset may serve as a testbed for relational learning and data mining algorithms as well as matrix and graph algorithms including PCA and clustering algorithms. The size of this dataset is 23 MB.

* [CiaoDVD](https://drive.google.com/file/d/1w1FuVSQC9nqxcK5xj0Aw5Oxc1qV7d09A/view?usp=sharing)  
    CiaoDVD is a dataset crawled from the entire category of DVDs from the dvd.ciao.co.uk website in December, 2013
    * File: movie-ratings.txt
        * Columns: userID, movieID, genreID, reviewID, movieRating, date

* [FilmTrust](https://drive.google.com/file/d/1ohQ9oo8aaR7aWlpe56hXx66x-bwXxB56/view?usp=sharing)  
    FilmTrust is a small dataset crawled from the entire FilmTrust website in June, 2011
    * File: ratings.txt
        * Columns: user-id, item-id, rating-value

* [Netflix](http://academictorrents.com/details/9b13183dc4d60676b773c9e2cd6de5e5542cee9a)  
    This is the official data set used in the Netflix Prize competition.

* [MovieTweetings](https://github.com/sidooms/MovieTweetings)  
    A Live Movie Rating Dataset Collected From Twitter 
    * File: ratings.dat
        * Columns: user_id,movie_id,rating,rating_timestamp

---

**Below is the table of some statistics of above datasets.**

|  Data Set	        |  Users	| Items	| Ratings (Scale)	     |
|:-:                |:-:        |:-:    |:-:                     |
|FilmTrust          |1,508	    |2,071	|35,497    --[0.5, 4.0]	 |
|CiaoDVD            |17,615     |16,121 |72,665    --[1, 5]      |
|MovieTweetings     |70,994	    |37,506	|910,396   --[0.0, 10.0] |
|MovieLens 100K     |	943	    |1,682	|100,000   --[1, 5]      |
|MovieLens 1M       |	6,040	|3,706	|1,000,209 --[1, 5]	     |
|MovieLens 10M      |	71,567	|10,681	|10,000,054--[1, 5]	     |


---

## Related Link
* Public Datasets For Recommender Systems ([github](https://github.com/caserec/Datasets-for-Recommender-Systems))
* Recommender System DataSet ([github](https://github.com/daicoolb/RecommenderSystem-DataSet))
* Recommendation and Ratings Public Data Sets For Machine Learning ([gist.github](https://gist.github.com/entaroadun/1653794))