# TOP SONGS ON SPOTFY: What makes them popular?

![](spotifyimage.png)

Content
1. Introduction
3. Questions and hypothesis 
4. Dataset
5. Variables
6. Workflow


1. Introduction

I am a huge fan of music and it has always been a question if there is any underlying reason taht popular songs get to the top of the charts. Is it by mere luck or is their a certain type of song/genre that will have more chances? In order to furthur investigate this, I found a top tracks spotify datbase that measures some basic types of variables to be able to correlate against success.

2. Questions and hypothesis

The research question is to understand which variables play a role in the popularity of a song in the top ranks of Spotify. This was 

3. Dataset

The datasets worked on were created by 7 university students and uploaded to kaggle. The dataset contains songs in Spotify's Daily Top 200 charts in 35+1 (global) countries around the world for a period of over 3 years (2017-2020) obtained from Spotify's API. Due to the dimension of the raw data, a link will be provided instead of including it in the repository. The user will need to download and re-run the jupyter notebook to play with the data. 

The link to the spotify kaggle database: https://www.kaggle.com/pepepython/spotify-huge-database-daily-charts-over-3-years?select=Final+database.csv

4. Variables

The variables measured and observed:

- Artist followers: The number of followers the artist has on Spotify on the 5th of November 2020 
- Explicit: Whether the song is rated as ‘Parental Advisory Explicit Content’ or not
- Popularity: The popularity score calculated taking into account both the number of days a song stayed in the Top200 and the position it stayed in every day, weighting more the top positions
- Danceability: How suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable
- Energy: It is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy
- Key: The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1
- Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db
- Mode: indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
- Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic
- Instrumentalness: Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness: value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0
-Speechiness: Detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks
- Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live
- Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)
- Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration
- Duration : The duration of the track in seconds


5. Workflow

To track and monitor the workflow for this project, a trello board was used. The process started with finding a topic and a database that would be able to answer my questions. This database was based through data cleaning and wrangling with python, to then be firstly explored within python and then passed into tableau. Once trends, questions and possible graphics were identified, the next step was to try to explain the data through a story using a dashboard.


Link to dashboard: https://public.tableau.com/app/profile/andrea.fought/viz/Spotify_Project_16249173678800/Mode
Link to trello board: https://trello.com/b/VgDCPe6S/data-theives-project-spotify

6. Analysis and Findings

With the use of python and tableau, findings and speculations were infered based on the data. The research question looked into was what variables play a role on the popularity of a song. Imagine you are an up and coming arist and don't have an extensive fan base. If your goals are to one day reach the top charts of Spotify, what type of song must you produce to have the highest chances?

In the exploration phase I wanted to visualize any correlation between the numeric variables, in which we can see that loudness and energy are hughly correlated. This would make sense as with more energy in a song it normally will have an increased volume. The main correlation I wanted to observe was if any of the variables was highly correlated with popularity. This was not the case, but that does not fully mean that it doesn't play a role, but rather the popularity of a song will have countless variables that could play a role. In order to continue with the project, I was determined to find the formula of a song with variables a musician could control.

<img width="917" alt="Screen Shot 2021-07-02 at 9 21 28 PM" src="https://user-images.githubusercontent.com/83591280/124320134-9e67df80-db7b-11eb-8524-18593e0cf4fb.png">

In this analysis we will go over the many variables and try to identify the perfect musical formula to achieve success. In th pie charts below we observe that major and clean songs are amost the most popular. 

<img width="223" alt="Screen_Shot_2021-07-02_at_12 11 58_AM-removebg-preview" src="https://user-images.githubusercontent.com/83591280/124309321-d6b2f200-db6a-11eb-95bf-aff4f3d40720.png">

<img width="297" alt="Screen_Shot_2021-06-30_at_6 36 57_PM-removebg-preview" src="https://user-images.githubusercontent.com/83591280/124309358-e3374a80-db6a-11eb-871f-ff53c348542a.png">

The next bubble chart the most popular data is in C#, but this just might be due to Ed Sheeran being the most popular artist and him majoritly playing in that key. The subseqent chart demonstrates the most popular global artsists from 2017-2020 in Spotify.

<img width="256" alt="Screen_Shot_2021-06-30_at_11 48 18_PM-removebg-preview" src="https://user-images.githubusercontent.com/83591280/124309235-b8e58d00-db6a-11eb-8234-029d9b31f297.png">

<img width="723" alt="Screen Shot 2021-06-30 at 6 28 02 PM" src="https://user-images.githubusercontent.com/83591280/124320716-af652080-db7c-11eb-8be8-e396f463411d.png">

The next couple visuals are based on the the upper 75th quartile of all the global popularity, in which we can observe that most tracks have high danceability and energy. The valence is in the middle, meaning that the users like similarly both positive and negative songs. Acoustics, liveliness and speechiness are low meaning the songs are not recorded in live audiences and the vocals are quite high compared to the instrumentation. The average song is 2075 seconds or 3.4 minutes, the average tempo is 120 bmp and the average loudness is -5.81 db.

<img width="635" alt="Screen Shot 2021-07-01 at 6 39 06 PM" src="https://user-images.githubusercontent.com/83591280/124320610-79c03780-db7c-11eb-8fa9-5be1ba4ceec8.png">

The last graph can also be observed based on genre, as pop and bolero will have differences in their variables. As many artits will not change genre, it is important to have the dimensions for different genres in order to create a formula based on recipe.

<img width="573" alt="Screen Shot 2021-07-01 at 10 02 37 PM" src="https://user-images.githubusercontent.com/83591280/124309282-c864d600-db6a-11eb-97c5-d616976da070.png">

The graph has the accumulated data with the recipe for the perfect song to be placed in the top ranks in spotify.

<img width="502" alt="Screen Shot 2021-07-01 at 10 10 22 PM" src="https://user-images.githubusercontent.com/83591280/124309297-ce5ab700-db6a-11eb-83c6-a2b157082cd2.png">




