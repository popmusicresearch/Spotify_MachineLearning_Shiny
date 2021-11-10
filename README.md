# Spotify, Machine Learning and Shiny

A workflow that gathers data from the Spotify API, creates a simple Logistic Regression model, and then produces a Shiny app to display results of predictions.

The contents of the repo are as follows:

**1 - Get Spotify Playlist Data**

Retrieves data on ~5,000 songs from the Spotify API. These songs are taken from Spotify's in-house 'Top Hits of {YEAR}' playlists for the years 1970 to 2019.

**2 - Clean Data**

Performs some basic tidying and cleaning of the data set generated in step 1.

**3 - EDA**

A number of exploratory visualsations, looking for the appearance of any linear trends in Spotify metrics over time.

**4 - Build Logistic Regression Model**

Using the TidyModels package, a basic Logstics Regression model is trained on a subset of the data gathered above.

**6 - Evaluate Model **

Predictions generated using the model produced in step 4.

**6 - Create Predictions**

Predictions generated using the model produced in step 4.
