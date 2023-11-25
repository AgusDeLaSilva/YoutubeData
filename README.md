# YoutubeData

Skills: Python, SQL (DDM (o lo que sea)),  json, API, Pandas, Pyodbc.

In this project, the objective is to request some video metrics from Youtube API and then store them in a database. 

The project has two steps:

First Step. We interact with Youtube API and create a json object in order to obtain the metrics we are looking for (these metrics can be modifed according user preferences/needs reading YoutubeAPI Documentation). Then, we go through the json object in order to store the data we need into variables. 

With a for loop, we apply this proccess to all the videos in a given channel and include that data into a dataframe.

Finally, we create a csv (youtube_vids_2nd_pull.csv) from that dataframe that will be used in the Second Step.

Second Step. We import previous csv into a new data_frame and send it to a database (SQL)..... in progress.
