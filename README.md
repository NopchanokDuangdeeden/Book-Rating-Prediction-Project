# Book rating prediction project

### Background

Nowadays with so many books available, it can be hard to select the best ones to read. The dataset provided is a curation of Goodreads books based on real user information. It can be
used for many tasks like predicting a book’s rating or recommending new books.
Below is the information you have regarding the dataset attributes:
        1) bookID: A unique identification number for each book.
        2) title: The name under which the book was published.
        3) authors: The names of the authors of the book. Multiple authors are delimited by “/”.
        4) average_rating: The average rating of the book received in total.
        5) isbn: Another unique number to identify the book, known as the International
        Standard Book Number.
        6) isbn13: A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
        7) language_code: Indicates the primary language of the book. For instance, “eng” is
        standard for English.
        8) num_pages: The number of pages the book contains.
        9) ratings_count: The total number of ratings the book received.
        10) text_reviews_count: The total number of written text reviews the book received.
        11) publication_date: The date the book was published.
        12) publisher: The name of the book publisher.

### Objectives

Using the provided dataset coming from Goodreads.com, the objective is to build and train a model that predicts a book’s rating. The project include exploratory analysis of the data, feature engineering and selection, model training and evaluation and finally, deployment.

### Contributors

Nopchanok DUANGDEEDEN
Opeyemi Emmanuel OLATUNJI
Romain ROURE
Céline TAKCHI

### Technologies used

Python
Jupyter

### Data proceesing

The first step for this model is to utilize dataset extracted from Goodreads.com and process it. Data preprocessing is done through a series of steps, namely:

    Data analysis
    Data Cleaning & Feature engineering
    Selection

For this model, Goodreads dataset is used and the steps followed to extract the required data are:

    Read the dataset (Book dataset file provided in Github project's repository)
    Overall analysis of data (features and target)
    Data cleaning and feature engineering to prepare the dataset for the modelling part.


### Modeling

Here we are using Classification Model: XGBoost in order to predict the average rating of a book based on some features:
        * Number of pages
        * Ratings count
        * Author
        * Text review
        * Author productivity (total number of book written by an author)
        * Length of the title



### Files:

        The jupyter notebook for machine learning model is: Book_rating_prediction_model_deployment.ipynb
        The jupyter notebook complete steps (not only the winning model) and additional ressources used to understand dataset but not useful for the model is: Book_rating_prediction_additional codes.ipynb
    
        The dataset used is from the website: https://www.goodreads.com/. 
   