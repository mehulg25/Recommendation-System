# Recommendation-System
 
### Introduction

From audio cassettes to vinyl disks, from ipods to itunes, as media products shift from physical goods to bits, the way people explore and perceive new media has also changed through the years.

The amount of data people consume every day makes it a necessity for digital companies to fine tune their selling for each user in order to create a hyper personalised environment for users to be more engaged.

Spotify, an online music streaming platform, puts user personalization at the forefront through recommended playlists. Rather than just listening to a full length album, users are able to control their experience by curating playlists that can reflect their emotions, activities, and memories. Spotify can enhance this personalization experience by assisting users in their music discovery. Discovering new tracks are made easier by offering recommendations relevant to the user.

What sets Spotify apart from other music streaming platforms like Amazon Music, Pandora, Apple Music, and YT Music is precisely the spot on recommendations that it offers users for their playlists. Through this project, we aim to see how any platform can improve its user personalization and its implications for the future of targetted marketing.


### Mission Objectives

For this project we will be building a recommendation system which recommends 20 songs that a user might add to their playlist based on the first song added by the user. This recommendation system can be leveraged by platforms to further refine the precision of their recommendations to users and ensure that customers stay loyal to their platform.

In order to achieve this, we will try to analyze the data in order to find trends in user listening habits. We will also see who are the top artists, what are the top genres, and what sets them apart from the rest. These analysis will not only help us to optimize our recommendation system but can help all the sides of the platform involved in the following ways:

- __Users__ : To get personalized recommendations based on their listening history
- __Artists__ : To include particular attributes to make their song a hit
- __Streaming Platforms__ : To promote in-house curated playlists based on genres people like
- __Record Labels and Music Distributors__ : To sign contracts with artists who are leading the music industry

### Data Sources

The analysis was done on an existing dataset obtained from a Spotify Case Challenge - Million Playlist Dataset Challenge, hosted by AIcrowd in JSON format. This dataset consists of 1 million Spotify playlists and is sampled from over 4 billion public playlists on Spotify. This sampled dataset further consists of over 2 million unique tracks by nearly 300,000 artists and represents the largest public dataset of music playlists in the world. The dataset includes public playlists created by US Spotify users between January 2010 and November 2017. Playlists are sampled with simple randomization, are manually filtered for playlist quality and to remove offensive content and have some dithering and fictitious tracks added to them. As such, the dataset is not representative of the true distribution of playlists on the Spotify platform and must not be interpreted as such in any research or analysis performed on the dataset. The data is anonymized to protect user privacy by Spotify.

However, The analysis was done only on the first 1000 playlists and their respective songs to serve the purpose of this project.

### Data Files

The project consists of two Data files:

- <b> playlist_data </b> <br>
This file is in json format and consists of playlist data and their respective tracks. 

- <b> track_data </b> <br>
This file is in csv format and consists of track meta data.

### Setting Up
To set up this project, you will require the following tools:
1. Anaconda
2. Jupyter Lab
3. Python 3.0.0+
Please make sure that you have installed all the libraries used in this project. 

Once you are done setting up the environment, You can run the Jupyter Notebook on Anaconda. Make sure to change the path of the data as per your convinience. 
You can also check out the presentation report or the HTML report in order to avoid running the Jupyter Notebook.

### Final Thoughts 

This project can be used by any platform who aim to improve its user personalization. 
