# To_The_Bone
One of the many cases when song popularity was affected by Tiktok's trend 
IMPORTANT NOTE: Use external view to view the visualization when opening the script

## Background and Overview
'To the Bone' song by Pamungkas is one of the many viral songs that keep showing up in our social media feed, especially in the first quarter of 2021. Although it has been released since 14th of June 2019, the song continued to gain its popularity and becoming one of the most streamed song in Indonesia.This relatively short project was aimed at observing how the song compared to the other top songs in Indonesia and how Tiktok could be one of the reasons why the song gained so much attention.

## Data
The data is acquired by manually downloading the [spotify chart](https://spotifycharts.com/regional) data in Indonesia region. This only shows the top 200 most listened to in each day so we have 31 separate data in .csv format which will be loaded to one dataframe in [the script](https://github.com/muyassarhafizh/To_The_Bone/blob/main/To_the_Bone_Project.ipynb) . The data consists of five columns, namely : Position','Track Name','Artist','Streams', and 'URL'. 

## Interpretation and Result
The first viral Tiktok which includes 'To the Bone' song could be traced to [a video](https://vt.tiktok.com/ZSed4kh1C/) from an account named 'Hana Wilianto' in which features her euphonious voice when singing the song (Source : [Liputan 6](https://www.liputan6.com/showbiz/read/4512823/lagu-to-the-bone-viral-di-tiktok-ini-profil-singkat-pamungkas)). The singing video, which was uploaded on 7th of March 2021 surged in terms of viewers until it reaches more than 30 million total views and needless to say, it also sparks a huge trend in Tiktok where a person singing or lip syncing to this song/audio. Overall, [the resulting graph](https://github.com/muyassarhafizh/To_The_Bone/blob/main/Visualization/top5_daily_streams.png) highlights the evidence of a strong connection between the Tiktok trend and daily stream numbers in Spotify. This is shown by the fact that the daily streams of the song increase in unusual manners which started since 7th of March, exactly similar to when the viral video was uploaded. This trend lasted for several weeks and the result can also be seen in the graph of daily streams Spotify data.

Additional note : Some of the interpretation is also included in [the python script](https://github.com/muyassarhafizh/To_The_Bone/blob/main/To_the_Bone_Project.ipynb).

## Additional Visualization
Additional visualization such as interactive bar plot and [video chart](https://github.com/muyassarhafizh/To_The_Bone/blob/main/Visualization/bar_chart_race.mp4) has also been included in the script and the visualization folder. 

## Overview of The Code
The main objective of the code is to give a good visualization of the data. In order to do so, we first creted the functions to load the data from several .csv files. Next, we preprocess the data by removing unnecessary duplicated rows and whitespaces though the data is already relatively cleaned. Finally, we use several packages, such as pyplot and bar_chart_race to visualize the results.

## Resources
Enviroment:
-Python 3.7

Software:
-Jupyter Notebook 6.3

## Other Articles
- [The Tiktok trending](https://www.tiktok.com/music/To-the-Bone-full-cover-on-Youtube-Hana-Wilianto-6936672038971017986)
- [Bar Chart Race](https://towardsdatascience.com/creating-bar-chart-race-animation-with-python-cdb01144074e)
