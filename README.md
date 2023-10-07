# IMDB-Capstone-Project
DataTrained Capstone Project
Capstone Project IMDB Dataset This capstone is divided into a 4-phase duration. In this document, the entire details of the 4-phase(weekly) duration are given.

# Phase 1

 1) Webscrape the provided URL - IMDB dataset:

https://www.imdb.com/search/title/?genres=action&sort=user_rating,desc&title_type=feature&num_votes=25000,&pf_rd_m=A2FGELUUNOQJNL&pf_rd_p=f11158cc-b50b-4c4d-b0a2-40b32863395b&pf_rd_r=XZ8X52H1R40B7KG5SNZ9&pf_rd_s=right-6&pf_rd_t=15506&pf_rd_i=top&ref_=chttp_gnr_1

 2) Store the entire data in two different CSV files as per the given fields:
The first CSV file data contains :

Sno, Movie Name, Director Name, Duration, year, ratings, Metascore

Bifurcate the Director field into subfields as per the number of directors of the movie belongs to such as Director1, director2

The second CSV file contains the following:

Movie Name, stars, votes, Genre, Gross collection, popularity, Certification

Bifurcate the stars field into 4 subfields as per the number of stars worked in the movie such as star1, star2, star3, star4

Bifurcate the genre into 3 subfields as per the number of genres the movie belongs to such as :

Genre1, genre2, genre3

# Phase 2

Make two tables and corresponding columns provided in the above CSV files in SQLite DBMS. Insert all data of each CSV file in each of the created tables. Now start querying the table(s) in the SQL workbench / SQLite database :

# Phase 3

1) Now make only 1 data frame of two CSV files using the join operation of pandas and start doing EDA.

2) Do the complete EDA in detail to explore the insights of data and write detailed observations of each analysis.

# Phase 4

1) Write the complete Machine learning code to make predictions of votes and gross collection. Use appropriate models on their label basis. Remember you need to make 2 different predictions: vote and gross collection.

2) Apply all the best techniques of scaling, and hyperparameter tuning, and avoid underfitting or overfitting (bias/variance)

3) At the end save the best model and convey on which basis you have chosen that model.
