# [Spotify-Songs](#content-table)
The propose of this project is to strengthen my SQL skills and practice with PowerBI.

# [Content Table](#content-table)

- [Spotify-Songs](#spotify-songs)
- [Content Table](#content-table)
- [Introduction](#introduction)
  - [Data Description](#data-description)
  - [Procedure](#procedure)

# [Introduction](#content-table)

For this project, we're going to make a Power BI dashboard. The dashboard will show the most popular songs on Spotify in each country. To develop this project, we're going to upload the dataset to a PostgreSQL database.

## [Data Description](#content-table)

The data proportioned has the following columns of data: 

* `spotify_id`: Unique identifier for the song in Spotify
* `name`: The title of the song
* `artist`: Name(s) of the artist(s) associated with the song
* `daily_rank`: Daily rank of the song in the top 50 list (0 to 50)
* `daily_movement`: Change in rankings compared to the previous day (-49 to 50)
* `weekly_movement`: Change in rankings compared to the previous week (-49 to 50) 
* `country`: ISO code of the country of the TOP 50 Playlist
* `snapshot_date`: Date on which the data was collected from Spotify 
* `popularity`: Measure of the song's current popularity on Spotify (0 to 100)
* `is_explicit`: Whether the song contains explicit lyrics
* `duration_ms`: The duration of the song in milliseconds 
* `album_name`: Name of the album of the song
* `album_release_date`: Date of the release of the album of the song
* `danceability`
* `energy`
* `key`
* `loudness`
* `mode`
* `speechiness`
* `acousticness`
* `instrumentalness`
* `liveness`
* `valence`
* `tempo`
* `time_signature`

## [Procedure](#content-table)

