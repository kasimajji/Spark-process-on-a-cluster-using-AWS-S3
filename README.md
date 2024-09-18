# Apache-Spark-process-on-a-cluster-using-AWS-S3
In this project, building robust ELT in a data hosted on Amazon S3. This pipeline should extract raw data hosted in Amazon S3, transform it using Apache Spark into structured and optimized analytics tables, and then load the processed data back into S3 for further use.This involves cleaning, aggregating, and organizing the data into an appropriate structure so that analytics and reporting can be performed on the data. The ELT workflow shall be deployed to an AWS-hosted, scalable Spark cluster for high-performance execution and efficient handling of large datasets. With this solution, decision-making becomes truly data-driven, and preparation of data for analytics purposes becomes seamless and faster.

Step 1 : Read data from S3
Step 2 : Process data using spark
Transforms the raw data into to five different tables :
songplays - records in log data associated with song plays (songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent)

users - users in the app Fields (user_id, first_name, last_name, gender, level)

songs - songs in music database Fields (song_id, title, artist_id, year, duration)

artists - artists in music database Fields (artist_id, name, location, lattitude, longitude)

time - timestamps of records in songplays broken down into specific units Fields (start_time, hour, day, week, month, year, weekday)

Step 3 : Load it back to S3


