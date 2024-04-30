# Spotify Power BI Dashboard
![Знімок екрана (55)](https://github.com/ViestaBa/dashboard-most-streamed-spotify-songs-2023/assets/145791658/caa1131f-b810-4e5d-b7aa-09f39b83501e)
## Idea 💡 
This Power BI dashboard is structured around several key tasks:
- Filtering songs by artist /track name /date of release
- Displaying streaming statistics: streams per track /streams per date of release /average number of streams /percentage streams difference between average and top-streamed songs
- Highlighting specific characteristics of top-streamed song: track name /artist(s) /# of artists /date of release and speech% / instrumental% /liveliness% /danceability% /energy%
- Displaying track cover of top-streamed song
- Visualizing average energy% and average number of released songs within given time frame

## Steps 🔎
| Step                   | Comment                                                                                   |
| ---------------------- | ----------------------------------------------------------------------------------------- |
| Download Dataset       | https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023?resource=download |
| Enrich Dataset         | add image URL links to track covers using Python                                          |
| Split artist(s)_name   | in separate DataFrame to create effective filtering based on artist                       |
| Create background      | in Power Point                                                                            |
| Download data          | from spotify_dataset.xlsx and track_artist.xlsx                                           |
| Import dates fom BRAVO | time interval is 1930-2023                                                                |
| Configure ER diagram   | screenshot is provided below                                                              |
| Build dashboard        | guide: https://www.youtube.com/watch?v=ZSrVOyKAC4Y&t=42s                                  |

## Key points 🗝️
### ER diagram
- data - spotify dataset with trac covers URLs;
- track_artist - table for Artist slicer;
- data_measures - table with measures used in dashboard;
- Dates - table generated by BRAVO
![Знімок екрана (61)](https://github.com/ViestaBa/dashboard-most-streamed-spotify-songs-2023/assets/145791658/8758204b-2d96-43f7-834d-4e9c6f3a64ef)
