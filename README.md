# Real Estate Tycoon Project

This repo contains jupyter notebooks for a data science regression project aimed at building a machine learning model that can predict real-estate house properties prices.

The code in the notebooks was executed using python 2.7; the following python libraries were used throughout the project:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn

The pdf file "Data-Dictionary" presents the description for each feature in the real-estate dataset.

## Project Context

Our client is a large Real Estate Investment Trust (REIT).

* They invest in houses, apartments, and condos within a small county in New York state.
* As part of their business, they try to predict the fair transaction price of a property before it's sold.
* They do so to calibrate their internal pricing models and keep a pulse on the market.

## Our Role

The REIT has hired us to find a data-driven approach to valuing properties.

* They currently have an untapped dataset of transaction prices for previous properties on the market.
* Our task is to build a real-estate pricing model using that dataset.
* If we can build a model to predict transaction prices with an average error of under $70,000, then our client can replace inexperienced appraisers with our model.

## Current Solution

The REIT currently uses a third-party appraisal service. Appraisers are professionals who visit a property and estimate a fair price using their own expertise.

* Unfortunately, the skill levels of individual appraisers vary greatly.
* During a trial run, the REIT compared appraiser estimates to actual transaction prices.
* The REIT found that the estimates given by inexperienced appraisers were off by $70,000, on average!


## Problem Specifics

It's always helpful to scope the problem before starting.

```
Deliverable: Trained model file
Machine learning task: Regression
Target variable: Transaction Price
Win condition: Avg. prediction error < $70,000
```
