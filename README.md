# Top tracks and artists in Vietnam <img src="./screenshots/spotify-logo.png" alt="Spotify logo" width="30px">

# Description

-   A final project in _Data Science Programming_ (University of Science).
-   Finding insight and making decision based on dataset.

# Table of Contents

1. Craw data using APIs
2. Cleaning the data
3. Explore the data
    1. Q1: Which genre has inappropriate lyrics for children?
    2. Q2: Which genres is the most popular one (in terms of quantity and quality)?
    3. Q3: What are the songs that have been released for a long time but are still heard by many people at the present time?
    4. Q4: Question 4: For each song length, what is the average popularity score of the songs?

# Data source

| Column                 | Meaning                                        |
| ---------------------- | ---------------------------------------------- |
| **id**                 | ID of song                                     |
| **name**               | Song name                                      |
| **artist**             | Artist                                         |
| **artist_followers**   | Number of follwers of artist                   |
| **artist_genres**      | Main genres of artist                          |
| **album**              | The album contains the song                    |
| **release_date**       | Release date                                   |
| **album_total_tracks** | Number of songs of the album                   |
| **duration**           | Duration (ms)                                  |
| **explicit**           | Whether the song is inappropriate for children |
| **popularity**         | Popularity on scale from 0 to 100              |

# Usage

Everything has been prepared, just go to these Colab file:

-   [Craw data](https://colab.research.google.com/drive/1bOv9_al3FdaYQh4Luteu9x3iWguxkBIz#scrollTo=nYjHO0p6oWfc "colab")
-   [Cleaning the data](https://colab.research.google.com/drive/1SiyWgEwAyTCxldTgkGWT2IMSblJ9am0-#scrollTo=8NpuAc1C_An3)
-   Understand the data:
    -   [Part 1](https://colab.research.google.com/drive/1ogZBqe-MQmneysn6jHlYwjaQe__cg2DF)
    -   [Part 2](https://colab.research.google.com/drive/1PmP-e8xaa2jFRLcCe_oMjub9Mz84tqFc#scrollTo=djCHS-KQheri)

# Contributors

-   Pham Quoc Hung
-   Tran Tuan Kiet

# References

[Spotify API document](https://developer.spotify.com/documentation/web-api/reference)
