## Udacity's Data Scientist Nanodegree Project: Write a Data Science Blog Post

### Project Overview

The data explored in the present notebook contains detailed information provided by guests about listings and its calendar details for the city of Santiago, Chile, compiled on March 2019. The data was obtained from [Inside AirBnB](http://insideairbnb.com/get-the-data.html).

The Cross-Industry Standard Process for Data Mining (CRISP-DM) will be used to explore the data. The CRISP-DM process encompasses six elements:

    Business Understanding
    Data Understanding
    Data Preparation
    Modeling
    Evaluation
    Deploy

This project is a requirement for Udacity's Data Scientist Nanodegree.

### Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)
4. [Findings](#findings)

### Libraries <a name="libraries"></a>
    
    Pandas
    Matplotlib
    Numpy
    Sklearn

### File descriptions <a name="files"></a>

* write_a_data_science_blog_post.ipynb: Jupyter notebook containing the calculation and visualizations.
* write_a_data_science_blog_post.html: A copy of write_a_data_science_blog_post.ipynb in html format.
* listings.csv: File can be downloaded from [InsideAirBnB](http://insideairbnb.com/get-the-data.html)
* calendar.csv: File can be downloaded from [InsideAirBnB](http://insideairbnb.com/get-the-data.html)

### Contents <a name="contents"></a>

The project is organized along the following sections:

    Project Overview
    Business Understanding
    Data Understanding
    Data Preparation
    Modeling
    Evaluation
    Deploy

### Findings <a name="findings"></a>


1. Which are the neighborhoods with the most listings?

There are a total of 28 neighborhoods listed in AirBnB. The neighborhood with the most listings is Santiago with 3,266 listings, 38.28% of the total. The following neighborhood with the most listings is Providencia, which is east adjacent to Santiago, with 2,159 listings and 25.30% of the total.

2. Which neighborhood is the most expensive and which is the cheapest?

Even though Las Condes is a neighborhood that concentrates just 16.87% of the listings, it is the most expensive neighborhood with a mean price of 208,394 chilean pesos. One explanation is that Las Condes is the main finantial district in Santiago, which leads me to believe that a considerable amount of the listings are business related. Santiago, which is the neighborhood with the most listing, is third and far from Las Condes with a mean listing price of 28,427 chilean pesos

3. What type of properties are more frequently listed?

By far the most frequently listed property are Apartments with 6,381 listings with amounts to 74.79% of the total. Houses and Condominiums follow with 7.25 and 6.09 percent of the total.

4. How does pricing fluctuate in a monthly basis?

The most expensive months run from September to March and the least expensive from April to August. This monthly price fluctuation correlates with the warm and cold seasons. There is a peak in February with a mean price of 58,361 chilean pesos. February is one of the most popular months to have vacations.

5. Can we predict the rating of property using a model?

I got an r-squared value of 0.7759 for the training data and 0.7853 for the test data, which indicates that a considerable amount of variability of the data is explained by the variables. The highest coefficients are related to descriptions of the listing (space, description, neighborhood_overview, summary and interaction), which indicates that the amount of information that the host shares with guest affects the overall rating of the listing.

