---
title: "Spotify Trending Song Prediction"
date: 2024-03-01
---

The aim of this project is to create a predictive model to determine the viral potential of songs based on a comprehensive analysis of song statistics. To achieve this, we utilized two primary datasets from Spotify. The first dataset contains detailed information on over 1.2 million songs, including their energy index, danceability, liveness, tempo, and other musical features. The second dataset contains information on the performance of songs across various Spotify charts, detailing their presence and duration within these charts throughout different years.

By analyzing these datasets, we developed a robust predictive model that can forecast the likelihood of a song going viral. This was achieved by examining both the intrinsic qualities of the songs and their historical performance on Spotify charts. Each section of our Jupyter Notebook (added to the GitHub repository linked below) is carefully annotated to explain the rationale behind our analysis, the methodologies employed, and the insights derived from the findings.

The notbook is divided into the following major parts:
1. Data Loading: This done by loading the aforementioned datasets onto an Apache Spark cluster
2. Exploratory Data Analysis: The aim is to analyze various characteristics of songs to forecast their likelihood of becoming popular and making it to the trending charts. We hypothesize that certain song attributes, such as energy, danceability, and tempo, significantly influence their popularity
3. Data Cleaning and Pre-processing: This step is a precursor to making the data ready to be fed into our classification models
4. Classification Models: We compare three types of classification models which are themselves built iteratively. The 3 models are:
    a. Logistic Regression model
    b. Neural Network based models
    c. Decision Tree based models

GitHub Repo: [Spotify-Trending-Song-Prediction](https://github.com/sahilparekh08/Spotify-Trending-Song-Prediction)