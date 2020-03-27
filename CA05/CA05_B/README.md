# CA05_A.ipynb

CA05_B.ipynb is a jupyter notebook program for practice on k-nearest-neighbors unsupervised learning.

## Installations

User should have Python3 and Jupyter Notebook installed into their system.

User should also have the following packages installed:
* sklearn
* pandas

## Dataset

The dataset is provided in a .csv file. It can also be retrieved from the following link: https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv

The dataset was obtained from UCI Machine Learning Repository. It is a subset of the IMDB dataset. It contains 30 movie records with the following features:
* Movie ID: number assigned to each movie for identification
* Movie Name
* IMDB Rating
* Biography*
* Drama*
* Thriller*
* Comedy*
* Crime*
* Mystery*
* History*

*These marked features are dummy variables for the genre of each movie. 1 means the movie is in the genre, 0 means the movie is not classified as the genre

## Instructions

User can open CA05_B.ipynb through jupyter notebook or the Google Colab environment. Run all cells as needed.

In order to be able to run the program successfully, please be sure that all the packages listed above are installed in the chosen environment. 

## Usage

The goal of this excercise is to create a recommender system. Given a movie and its features, the program would find 5 most similar movies to the given movie using an unsupervised learner, K-nearest-neighbors model. 

In this case, the given movie was *The Post* with the following features:
* IMDB Rating: 7.2
* Biography: Yes (1)
* Drama: Yes (1)
* Thriller: No (0)
* Comedy: No (0)
* Crime: No (0)
* Mystery: No (0)
* History: Yes (1)

The recommended most similar movies from our dataset are:
1. 12 Years a Slave
2. Hacksaw Ridge
3. Queen of Katwe
4. The Wind Rises
5. A Beautiful Mind
