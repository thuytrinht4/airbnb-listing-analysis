
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

## Project Motivation<a name="motivation"></a>

For this project, I was interested in analyzing data from AirBnB homes located in Seattle and Boston.  Specifically, I looked at the following questions:

1. How many rooms available for rent in Seattle and Boston listed in AirBNB on average (per-month, per-year)? 
What type of rooms, what are the average rental rate per type. Which types are most popular?  
2. Are there any area in which many rooms are listed for rent in each city? 
3. Are there seasonality components or price spiking components for how hosts set their home prices? How does this compare from Boston to Seattle?
4. What are the most common words used to describe a listing? Are the same words used for Seattle and Boston homes?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `tobecreated_analysis.ipynb` - a notebook of the analysis performed following the CRISP-DM process

* `calendar_seattle.csv` and `calendar_boston.csv` - csvs containing **home_id**, **date**, **availability**, and **price** for each home

* `listings_seattle.csv` and `listings_boston.csv` - these were not used for this particular analysis, but they were available from the original kaggle link

* `reviews_seattle.csv` and `reviews_boston.csv` - csvs containing the **home_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.

It is worth noting here that the reviews and calendar files did not have overlapping dates, and there were no numeric values associated with reviews.

## Results<a name="results"></a>

The main findings of the code can be found at the [link-to-my-first-medium-blog-post](to-be-written).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  
You can find the Licensing for the data and other descriptive information for the [Boston data on Kaggle](https://www.kaggle.com/airbnb/boston) and for the [Seattle data](https://www.kaggle.com/airbnb/seattle).  