
# Description of Facts and Dimension Tables
<br>
<br>
## Fact Table <br>
**songplays** - records in log data associated with song plays i.e. records with page NextSong
<br>songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent
<br>
## Dimension Tables
**users** - users in the app
<br>user_id, first_name, last_name, gender, level
**songs** - songs in music database
<br>song_id, title, artist_id, year, duration
**artists** - artists in music database
<br>artist_id, name, location, latitude, longitude
**time** - timestamps of records in songplays broken down into specific units
<br>start_time, hour, day, week, month, year, weekday
Project Template
To get started with the project, go to the workspace on the next page, where you'll find the project template files. You can work on your project and submit your work through this workspace. Alternatively, you can download the project template files from the Resources folder if you'd like to develop your project locally.


# Description of Files
**test.ipynb**<br> displays the first few rows of each table to let you check your database.
**create_tables.py**<br> drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.
**etl.ipynb**<br> reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.
**etl.py** <br>reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.
**sql_queries.py**<br> contains all your sql queries, and is imported into the last three files above.
README.md provides discussion on your project.
