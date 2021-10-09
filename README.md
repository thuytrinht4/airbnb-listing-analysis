
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Below is the packages and version used for this project. However, I reckon it will work with Python 3.* and standard data science libraries found in the Anaconda. 
+ Python versions 3.9.7
+ Anaconda3
+ Seaborn 0.11.2

## Project Motivation<a name="motivation"></a>

For this project, I was interested in analyzing data from AirBnB homes located in Seattle and Boston.  
Specifically, I'd like to know the general characteristics for rental market in the two cities, through the following three questions

1. What is the total number of rooms available for rent listed in AirBNB at the time of data collection? 
2. What type of rooms are offered? What are the average rental rate for each type? Which types are most popular? 
3. What are the areas where most rooms are listed for rent in each city?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `AirBNB_Listing_Analysis.ipynb` - a notebook of the analysis performed following the CRISP-DM process

* `data/raw/seattle/calendar.csv` and `data/raw/boston/calendar.csv` - Detailed Calendar Data for listings in Seattle and Boston

* `data/raw/seattle/listings.csv` and `data/raw/boston/listings.csv` - Detailed information and metrics for listings for Seattle and Boston

* `data/raw/seattle/reviews.csv` and `data/raw/boston/reviews.csv` - Review data. These datasets are not used for analysis in this project for now. 

The data used for this project was complied on September 23, 2021. It is downloaded from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), on October 09 2021,

## Results<a name="results"></a>

The main findings of the code can be found at my [Medium Blog Post](https://medium.com/@thuytrinht4/airbnb-listings-in-boston-and-seattle-8e4f7029bb63) or [Kaggle Blog Post](https://www.kaggle.com/thuytrinht4/airbnb-listings-analysis-seattle-vs-boston).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB for the data.  
You can find the Licensing for the data and other descriptive information for the [Behind Inside Airbnb](http://insideairbnb.com/behind.html).  