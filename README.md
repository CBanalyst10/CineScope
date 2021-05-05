# CineScope Movie Recommender

## Introduction
The CineScope movie recommender is an exercise in using movie metadata towards making more precise recommendations for users. The project was designed with the intent to deliver accurate recommendations to new users who want an initial recommendation suited to their preferences, groups of friends trying to agree on a single movie to watch, and established movie watchers who contemplate a change in tastes. 

## Data Sources
The data used in this recommender was sourced across the Internet Movie Database (IMDb), The Movie Database (TMDb), and MovieLens by the Computer Science Department of Massachusetts University (ML). Each of these platforms offer different strengths—IMDb is the fan favorite for movie viewers to rate movies with, TMDb offers extensive metadata options for analysis, and MovieLens offers a dataset of 25 million reviews collected between 1995 and 2019. The collected data was assembled into a new dataset designed to offer an accurate representation of each movie’s popularity amongst users, thus hopefully enabling accurate recommendation.


## Discussion of Data and Functions
The datasets were first blended into an overall movie dataset, then features were chosen based on their relative strengths to other features in user representation, completeness, or significance. The significance of data features was analyzed using Mean Square Error, showing what features should be prioritized over others when further minimizing the data for the model. Once the features for the movie dataset were finalized, the data was linked and merged with the user rating data to create an overall movie rating dataset.


The first draft of my model can give recommendations to users within the model, and rough suggestions of movies to watch for new users.


## Next Steps
My next steps are to finalize my recommendation functions, improve the UI, finalize the form and storage methods for my data, and launch a test with more data via hosting online through Microsoft Azure or Amazon Web Services.
