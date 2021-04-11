# AirBnBBerlinAnalysis2020
Analysis of AirBnB data if and if yes how the Corona pandemic is visible

This repository is part of a project for my data scientist nanodegree from Udacity. The task is to select a dataset or datasets and apply the Cross-Industry Standard Process for Data Mining which was teached in the first lessons of the nanodegree.

### Table of Contents

1. [Installation](#installation)
2. [Data](#data)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>
The analysis is written in a jupyter notebook 5.0.0 with Python version 3 using Anaconda. So with a recent Anaconda distribution of Python there should be no issues.

## Data <a name="data"></a>
I used the listings and review files of Berlin provided by airbnb [here](http://insideairbnb.com/get-the-data.html)
I used these files in particular:

listings:
* [Listings available in November 2019](http://data.insideairbnb.com/germany/be/berlin/2019-11-12/data/listings.csv.gz) (Rename to "listings_Nov2019.csv")
* <a href="http://data.insideairbnb.com/germany/be/berlin/2020-11-10/data/listings.csv.gz">Listings available in November 2020</a> (Rename to "listings_Nov2020.csv")

reviews
* <a href="http://data.insideairbnb.com/germany/be/berlin/2018-11-07/data/reviews.csv.gz">Reviews collected until November 2018</a> (Rename to "reviews_Nov2018.csv")
* <a href="http://data.insideairbnb.com/germany/be/berlin/2019-11-12/data/reviews.csv.gz">Reviews collected until November 2019</a> (Rename to "reviews_Nov2019.csv")
* <a href="http://data.insideairbnb.com/germany/be/berlin/2020-11-10/data/reviews.csv.gz">Reviews collected until November 2020</a> (Rename to "reviews_Nov2020.csv")

After downloading the archives in the same folder like the jupyter notebook they need to be unpacked and renamed because otherwise the listing and review csv would all be called alike and the code would not be processable. So they need to be renamed like written above in brackets.

## Project Motivation<a name="motivation"></a>

Due to the global pandemic I was curious if there are any changes visible in air bnb data of 2020 compared to previous years. 

1. Is the corona pandemic visible in the data of air bnb?
2. Did the preferred booking location change? Did the type of accomondations change because of the pandemic? 
3. What influences the over all scoring of an accomondation? Does that change during the corona pandemic? (like cleanliness get a more important role like before because of hygienic)


## File Descriptions <a name="files"></a>
There is one notebook provided here, which shows my way through the data to answer the questions. Markdowns are used for notes and small explanations of next steps.

## Results<a name="results"></a>

The main findings of the code can be found in the medium post available <a href="https://kasielkest.medium.com/is-the-corona-pandemic-visibel-in-berlin-airbnb-data-9bc280b0f24a">here</a>

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I have to give the credit to airbnb for the data and the preprocessing. You can find the Licensing for the data and other descriptive information [here](http://insideairbnb.com/get-the-data.html). 

Thanks for reading the compelte README ;-)
