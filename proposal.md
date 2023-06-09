# Data Analysis of Taylor Swift's Eras

## Overview
The proposed visualization project will provide an interactive experience following the career of Taylor Swift. Taylor Swift is one of the most famous pop stars today and is known for experimenting with new music styles, this project will follow her through her career on a timeline,showing key statistics from Spotify. The user will be able to follow her story and compare metrics of her albums, including average duration, number of listeners, popularity, danceability, etc. I intend to have each era display averages for the music she released during that time as well as
include views for her top 3 hits in that era. Additionally, there will be a summary view that looks at her all time averages. I want it to be a fun experience not only for myself but other fans to see where their favorite songs/eras square up. I intend to display this data in a timeline format (innovative) and incorporate reusable components for barcharts and scatter plots to compare eras to one another. 

## Description of the Data
I am using a kaggle dataset that was sourced from the Spotify API. The link for the dataset is https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset. The dataset has the following columns: name, album, release_date, track number, id, uri, acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, tempo, valence, popularity, and duration_ms (duration in milliseconds). Many of the columns are categorical, using an ordinal scale from 0.0 to 1.0 to describe characteristics. 

## Usage scenarios and tasks
While this project is primarily for fun, it will provide detailed information about Taylor Swift's music throughout her career. It can be used to find out what the top song of each of her era's was, as well as the top song of her career. It will also provide analysis comparing her albums and see how these metrics have changed since her debut in 2006. 

## Timeline (Innovative View) 
The first data view will be a timeline starting at Taylor's debut album, Taylor Swift, in 2006 and to the present, her most recent released album, Midnights in 2022, and the albums she has been reproducing as "Taylor's Version": Fearless and Red, also in 2022 and still going. Years should be labeled, using the release date of each album as the stopping point. Above each year, album images will be used to label, with hover links having the album title. The order is as follows: 

* 2006 - Debut/Self-Titled Album 
* 2008 - Fearless 
* 2010 - Speak Now
* 2012 - RED 
* 2014 - 1989 
* 2017 - Reputation 
* 2019 - Lover 
* 2020 - Folklore and Evermore 
* 2021 - Taylor's Version (Ongoing) 
* 2022 - Midnights 

## Second View: Album/Era Profile
Upon clicking on each album, the next view appears, to look at stats on the album/era level. Displays the top three hits from that album, by number of song streams. Then, it looks at the average of several attributes (to be determined) on that album/era level. A picture of Taylor performing will be displayed here, possibly with a good quote on the top before the data. 

## Third View: Overview of Her Career 
After clicking through the albums/eras, an overview will be presented, showing the top songs overall and overall statistics. 

