# DataFinalGroup-Music

Pipeline for Real-Time Data Processing in Music Applications

Zipotify NEEDS a data analysis tool! Before the middle of January.

Project Overview: The project will stream events that are created by a Eventism and the Million Songs dataset. 
A static demo dataset can be used before you get streaming setup. Apache Kafka and Apache Spark are two examples of streaming technologies that are used for processing data in real-time. 
The Structured Streaming API offered by Spark makes it possible for data to be processed in real-time in mini-batches, which in turn offers low-latency processing capabilities. 
The processed data can be uploaded to something like Google Cloud Storage, where they are then subjected to transformation with the assistance of dbt.
Then make use of this data by consuming it perhaps using PySpark, applying transformations to it, and creating the tables that are needed for our dashboard so that analytics may be generated. 
We are going to try to conduct an analysis of indicators such as the most played songs, active users, user demographics, etc.

You will be able to generate a sample dataset for this project by using Eventism and the Million Songs dataset. Apache Kafka and Apache Spark are two examples of streaming technologies that are used for processing data in real-time. 
The Structured Streaming API offered by Spark makes it possible for data to be processed in real-time in mini-batches, which in turn offers low-latency processing capabilities. The processed data are uploaded to Google Cloud Storage, where they are then subjected to transformation with the assistance of dbt. 
We can clean the data, convert the data, and aggregate the data using dbt so that it is ready for analysis. 
The data could be then sent to BigQuery, which serves as a data warehouse, and Data Studio is used to create a visual representation of the data. 
Apache AirFlow has been used for the purpose of orchestration, whilst Docker is the tool of choice when it comes to containerization.

Use PySpark to create a data pipeline from the song database all the way thru to a Dashboard of some kind.
The tech described above can be swapped out as you decide if an alternative is better for the group.

Each group member should have a series of things to work on, and you'll need to do a serious amount of work to 
draft out the project plan and setup tasks, and keep track of where everyone is over the next 14 days.

All of the above is negotiable, think it thru, discuss amongst yourselves, and on MOnday we can talk.

Do a one-pager, a UX doc, and some data modeling. 
IN this case, the data model will be be a pipeline, with formats described at each stage.
You'll want to use a couple databases, a few analytical processes, and some kind of visual database.

You're excused from a daily stand up for only New Year's Day. 
Whether or not Christmas Day has a standup is based on your decision as a group.

The EventSim software: 
https://github.com/viirya/eventsim/tree/master
