# Introduction
## Objective
This analysis was carried out so as to understand user listening habits by identifying the most popular tracks, artists and albums, analyzing listening patterns across different platforms and times of the day, and the impact of shuffle mode on listening behavior.
### The data set was collected from over 100,000 users over a period of 12 years, from July 2013 to December 2024. It contains the following variables:
•	spotify_track_uri: Uniquely identifies a track.
•	ts: Timestamp identifying the time the track ended.
•	platform: Identifies the platform on which the track was streamed (android, desktop or web player).
•	ms_played: The duration the track was played in milliseconds.
•	 track_name: The name of the track.
•	artist_name: The name of the artist the track belongs to.
•	album_name: The name of the album the track belongs to. 
•	reason_start: The reason the track started playing.
•	reason_end: The reason the track stopped playing.
•	shuffle: Indicates whether shuffle mode was on or off during playback.
•	skipped: Indicates whether the user manually skipped the track.
## Dataset Link
https://www.kaggle.com/datasets/sgoutami/spotify-streaming-history
## Configuration
For this study, Microsoft Excel 2016 was used to perform all analyses and visualizations.
## Data Preprocessing
Data Cleaning: The data was checked for missing values and a discovery was made that some cells in the reason_start and reason_end field were missing data. Since the data could not be acquired or generated using a formula, the cells were marked as N/A – not available.
The date (ts) was also converted to a “DDD-MMM-YYY” format for easy reading.
## Data Features
After the conversion of the date format, the year and hour was extracted from it to enable for further in-depth analysis.
## Data Analysis
For this study different excel charts were used to visualize the data, so as to draw meaning from them.
1.	Bar charts were used to compare data sets, for example, popular artists.
2.	Column charts were used to compare data side by side.
3.	Pie charts were used to show the breakdown of data into sub parts.
4.	Line charts were used to show the trend of variables over a given period of time.
## Dashboard
![Screenshot (463)](https://github.com/user-attachments/assets/09f74fce-9d69-420f-86df-c07304a939d8)
![Screenshot (464)](https://github.com/user-attachments/assets/79abfdd7-174e-449d-bce2-c4f4d832c4b6)
## Conclusion
The Beatles were the most popular artists as they had a total play count of 13,621. They are followed by The Killers who had a play count of 6878. The great margin emphasizes how much the Beatles were popular. Of the 10 artists, 4 of them are bands. This may suggest that band music is most streamed during that period.  
In Spotify shuffle play, one can rearrange songs in their playlist so as to experience different music every time (SoundGuys, n.d.). Listeners tend to spend more time on the streaming app when they tailor the music to their likes and preferences. 67% of the total time spent on the streaming app was when shuffle mode was on.
Majority of the listeners’ stream on their android devices, with the least using web players to stream. This may also suggest that android devices are the most popular among listeners.
From 2013, the number of streams reduce slightly and then start to increase steadily from 2014 to 2016. A spike in the number of streams is experienced between 2016 and 2017, this is where there are the most number of streams on the platform. From three, there is a massive fall in the number of streams in 2018, followed by an almost stagnant growth through to 2019.The streams then start to increase steadily again from 2019 but then start to plummet from 2020 and continues to fall till 2024.  
Most streams occur during non-working hours (before or after working hours) from 4pm to 6 in the morning.
