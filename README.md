# Spotify Analysis
The goal of this code is to show how you can keep tracking of how the music you listen every day evolves and create playlists based in certain parameters personalized by you. The possibilities are almost infinite and this notebook are just an example how analyze data provided by Spotify and some interesting features. 

The libraries used for this project (including data wrangling and visualization libraries) are available at requirements.

## Useful links 
I highly recommend you to check:
  - The official endpoints documentation provided by Spotify: https://developer.spotify.com/documentation/web-api/
  - Python library Spotipy for acess all the endpoints: https://spotipy.readthedocs.io/en/2.22.0/?highlight=playlist#
  - How the Spotify recsys works: https://www.music-tomorrow.com/blog/how-spotify-recommendation-system-works-a-complete-guide-2022
  
## Insights from my data
In the endpoints of top tracks and artists listened by the user, you can choose the time range of the results and the two windows analyzed here were: long term (calculated from several years of data and including all new data as it becomes available) and medium term (approximately last 6 months).

About my top artists, happily the rock and hip hop genre is increasing in the last 6 months compared with the long term data, it reflects in the features of my top tracks when we see that the median of energy and loudness increased significantly. With these values of energy and loudness as reference, the final part of the code requests recommendation of musics in these genres with these profiles of features to discover more and more songs that made my head in the last six months.

![generos](https://user-images.githubusercontent.com/120601240/208439822-9daa7a47-c7fb-41ef-8c89-9dea64ebeb51.png)

![energy](https://user-images.githubusercontent.com/120601240/208441096-acb4676e-0f6a-496c-8421-3b22b64fcba8.png)

![loudness](https://user-images.githubusercontent.com/120601240/208441119-d9b96944-ceff-416a-98ba-2364569fc5dd.png)



 
  
  

