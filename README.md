# Data Clients And Information Servers

In this project we work with Data Clients and Information Servers that deals primarily with data collection.The main objectives of this project are as follows:

1. Install Jupyter notebook environment and within it R language kernel.
2. Collect data by querying Twitter REST API. This was done via a developer account on twitter.
4. Process data using twitteR library package of R.
5. All the query inputs from the user (for data collection, summarization and visualization) will be specified by Jupyter widgets.
6. Summarize (simple print statement) information extracted as answers for specific queries.
7. Visualize geo spatial information extracted from the tweets using geo-map libraries of R: ggplot2, ggmap, maps,and maptools. Maps and geo codes are supported by Google map API.

We dealt with two separate problems in here:

### Problem 1: Study response to an event

Choose a topic and understand the Search API that we are using for can give you only limited number of tweets per day and also only a sampling of the all the tweets. You will collect at least 20000 tweets. Group them by geo-location as in Google maps API (one more API) and plot them on the map of USA. If you plot the location every tweet then there will be too many points on the map. You can plot all the tweets at a given location (say a city or state) by a single blob, the size of the blob representing the density of tweets. You may need some R programming here.

- Input: Search word or hash tag related to super bowl. Data client processing: Obtain and group tweets by location.

- Output: plot the groups by size on a map of USA for visual understanding of the response to an event. 

### Problem 2: Summarizing trending topics about a location

When we are visiting places (say, for an interview or other official visits) you may want to about topics trending in that place. Instead of reading newspapers and online news, you want just a quick summary. You want to put use your twitter “data client” application development experience. You use the twitteR libraries “trends” function to retrieve 10 top things trending about the place and summarize it appropriately as a complete message (print out).

- Input: Location specified either as geo-location or by its name

- Output: A message listing the topics trending about the place.

Note: Further details are mentioned in the inidivual Jupyter notebooks for the problems.
