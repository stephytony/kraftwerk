# Assignment 5.1: Will the Customer Accept the Coupon?

## Link to Jupyter Notebook Link -> https://github.com/stephytony/kraftwerk/blob/main/prompt.ipynb 

## Introduction : 

This repository contains the Jupyter Notebook for the Application Assignment 5.1. This takes a sample jupyter notebook to complete the exercise to analyse data in couspons.csv file in the data folder of this repository to determine the features that indicate whether a Driver will accept coupons “right away” or “later before the coupon expires”.

## Project Agenda : 

To identify the factors that contribute more to the coupon acceptance among customers.

## Files explained : 

    1. data/coupons.csv -> Original dataset
    2. images -> plots and visualizations
    3. prompt.ipnyb -> Data analysis - Notebook

## Tools and Libraries : 

    - [pandas](https://pandas.pydata.org/) → data cleaning, preprocessing, grouping  
    - [numpy](https://numpy.org/) → numerical operations  
    - [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/) → visualizations  
    - [jupyter notebook](https://jupyter.org/) → interactive exploration 

## Independent Analysis : 

This analysis is based on the data in coupons.csv and comparing the factors that have influenced the coupon usage.

As per the analysis we determined that the below factors have influenced on coupon usuage

Weather Impact Histogram --> https://github.com/stephytony/kraftwerk/blob/main/images/weather-and-temp-impact.png 
Travelling with friends --> https://github.com/stephytony/kraftwerk/blob/main/images/passanger-impact_point-plot.png
Total observations --> https://github.com/stephytony/kraftwerk/blob/main/images/total_observations.png
Coupons Bar acceptance rate --> https://github.com/stephytony/kraftwerk/blob/main/images/bar-coupons-acceptance.png

    1. Sunny Weather even during a snowy temperature
    2. Travelling with friends
    3. Drivers with college degree
    4. Male drivers travelling alone

## Next Steps and Recommendations :

    1. More Data will provide better analysis. My recommendation is to collect data with users which shows high influence on coupon usage. This will give us more fine tuned analysis as we have the first set ready. The factors that looks no impact can be removed or can be not used in our future pattern analysis.
