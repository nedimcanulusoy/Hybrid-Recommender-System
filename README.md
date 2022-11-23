<div style="font-style: bold; text-align: center;" markdown="1">

## Hybrid Recommender System

</div>

---

### Problem

It is desired to suggest 10 movies for the user whose ID is given, using the **item-based** and **user-based** recommender
methods.

---

### Dataset

The dataset was provided by MovieLens, a movie recommendation service. It contains the rating scores for these movies
along with the movies. It contains 2,000,0263 ratings across 27,278 movies. This data set was created on October 17, 2016.
Includes 138,493 users and data from 09 January 1995 to 31 March 2015. Users are randomly selected. It is known that all
selected users voted for at least 20 movies.

---

#### movie.csv

There are `3 different variables` and `27278 observations` in the dataset.

    movieId : Movie ID
    title   : Movie title
    genres  : Movie genre

#### rating.csv

There are `4 different variables` and `20000263 observations` in the dataset.
    
    userId  : User ID
    movieId : Movie ID
    rating  : Rating score
    timestamp : Time of rating

The data set can be found under the following [MovieLens](https://grouplens.org/datasets/movielens/) link.

---

### Installation

1. Clone this repository

```
https://github.com/nedimcanulusoy/Hybrid-Recommender-System.git
```

2. Change directory to the cloned repository

```
cd Hybrid-Recommender-System
```

3. Open the notebook and run the cells

---
