# YoutubeData

Skills: Python, SQL (DDL, DML), json, API, Pandas, Pyodbc.

In this project, the objective is to request some video metrics from Youtube API and then store them in a database. 

First, we interact with Youtube API and create a json object in order to obtain the metrics we are looking for (these metrics can be modifed according user preferences/needs reading YoutubeAPI Documentation). Then, we go through the json object in order to store the data we need into variables, that will be then included in an empty Dataframe. We apply this proccess to all the videos in the selected channel(s).

Once the Dataframe is created, it´s sent to a SQL Server database called YoutubeDataAPI using Pyodbc library.

Also, a csv file (youtube_vids_2nd_pull.csv) from that dataframe just in case it´s more suitable for the end user. It gets pretty useful in different ocassions, for example, when you are interacting with a non-technical area like HR, that is not familiar with SQL databases.
