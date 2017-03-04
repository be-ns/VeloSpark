# *VEloSpark*

### A Strava Ride/Run Recommender

## Introduction

Strava is a social network for athletes. It allows millions of users to upload there activities and maintains a profile of those activities and any associated achievements, stats, photos, and connections to other athletes.

The VEloSpark app is used to predict rides or runs that a rider/user might enjoy based on their inputs to the web application. The app uses a clustering based approach to label an activity according to it's relative location, total distance and elevation gain. The app then uses collaborative filtering to get recommendations for which activities will most likely correspond with a users input. Future use will allow users to add themselves to the app database and upload their data. This will automatically generate recommendations without the need for manual input.

### Table of Contents
* [Project Scope](#h1)
* [Feature Engineering](#h2)
* [Exploratory Data Analysis](#h3)
* [Model Development](#h4)
* [Web Application](#h5)
* [Dependencies](#h6)
* [Acknowledgements](#h7)

## <a id="h1"></a> Project Scope

#### This project sets out to accomplish two things:
*   Provide users recommendations for rides or runs to do in the state of Colorado.
*   Create a nice stable interface for viewing those recommendations

If I had more time and wasn't limited in resources I might try to create a global recommender to perform the same recommendations at locations world wide. This obviously would require a more powerful cluster of backend servers, a more robust general implementation of my model and a MUCH larger dataset.

## <a id="h2"></a> Feature Engineering

## <a id="h3"></a> Exploratory Data Analysis

*  ### Some Insights

*  ### Digging In

## <a id="h4"></a> Model Development
***this section in progress
* Use k means to cluster activities in colorado according to geographic start/stop, total elevation gain and distance features. This would give a rough label from which i could get ratings to use in the alternating least squares model.
* Start off with 50 clusters on smaller dataset. Might need more or to use an alternate method such as DBscan to find better clusters.

## <a id="h5"></a> Web Application

## <a id="h6"></a> Dependencies

## <a id="h7"></a> Dependencies
