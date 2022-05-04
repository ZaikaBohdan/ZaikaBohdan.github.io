# Bohdan Zaika's Data Science Portfolio

Welcome to my Data Science Portfolio. Here you can find brief descriptions of my projects with links to corresponding GitHub repositories.

## [Project 1: Building a car price prediction model for the CarDekho website](https://github.com/ZaikaBohdan/ds_car_price_proj/blob/main/README.md)

<p align="center">
  <img src="https://github.com/ZaikaBohdan/ds_car_price_proj/blob/main/imgs/car_dekho.jpg?raw=true" />
</p>

[CarDekho](https://www.cardekho.com/) is India's leading car search venture that helps users buy cars. Its website and app carry rich automotive content such as expert reviews, detailed specs and prices, comparisons as well as videos and pictures of all car brands and models available in India. 

**The goal of the project** was to build the app for CarDekho users, where they can evaluate the price of put up for sale vehicles or explore data about previous offers on their own. 

In this project, I've:
* cleaned 2 datasets about used cars from the CarDekho website, combined them and splitted into train and validation datasets;
* done Exploratory Data Analysis with visualisations, results of which was later used in Feature Engineering;
* trained the Random Forest Regression model for predicting car prices and evaluated its performance with cross validation and unseen validation dataset;
* build a data preparation and prediction workflow and deployed it in the [web app](https://share.streamlit.io/zaikabohdan/ds_car_price_proj/main/app/app.py).
