
# TOP SONGS ON SPOTFY: What makes them popular?

![](spotifyimage.png)

Content
1.Introduction:
2.Questions and hypothesis 
3.Workflow

1. Introduction

I am a huge fan of music and it has always been a question if there is any underlying reason taht popular songs get to the top of the charts. Is it by mere luck or is their a certain type of song/genre that will have more chances? In order to furthur investigate this, I found a top tracks spotify datbase that measures some basic types of variables to be able to correlate against success.

3. Questions and hypothesis

The research question is to understand which variables play a role in the popularity of a song in the top ranks of Spotify. This was 

4. Variables

The variables measured and observed:

- Artistfollowers: The number of followers the artist has on Spotify on the 5th of November 2020 
- Explicit: Whether the song is rated as ‘Parental Advisory Explicit Content’ or not
- Popularity: The popularity score calculated taking into account both the number of days a song stayed in the Top200 and the position it stayed in every day, weighting more the top positions
- Danceability: How suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable
- Energy: It is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy
- Key: The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1
- Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db
- Mode Mode: indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0
-Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks
- Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic
- Instrumentalness: Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness: value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0
- Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live
- Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)
- Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration
- Durationms: The duration of the track in milliseconds


4. Dataset

The datasets worked on were created by 7 university students and uploaded to kaggle. The dataset contains songs in Spotify's Daily Top 200 charts in 35+1 (global) countries around the world for a period of over 3 years (2017-2020) obtained from Spotify's API. Due to the dimension of the raw data, a link will be provided instead of including it in the repository. The user will need to download and re-run the jupyter notebook to play with the data. 

The link to the spotify kaggle database: https://www.kaggle.com/pepepython/spotify-huge-database-daily-charts-over-3-years?select=Final+database.csv


5. Workflow

To track and monitor the workflow for this project, a trello board was used. The process started with finding a topic and a database that would be able to answer my questions. This database was based through data cleaning and wrangling with python, to then be firstly explored within python and then passed into tableau. Once trends, questions and possible graphics were identified, the next step was to try to explain the data through a story using a dashboard. 

Link to dashboard: 

6. Links

Introduction:
Questions and hypothesis 
Workflow

Links:

Trello
Slides
Repository
