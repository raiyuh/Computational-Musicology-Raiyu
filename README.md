### Computational-Musicology-Raiyu

# Bowie's *Sellout Period* visualised
Many fans of David Bowie would say that he _sold out_ to the masses in the 1980's, adopting a more radio-friendly sound that would see his hits climbing the charts. 7 of his top 10 chart toppers according to [Billboard] (https://www.billboard.com/music/david-bowie) were all released between 1983 - 1987. In this study I tried to find a parameter that spotify measures that may reflect the change in his music during this specific period, and see if Bowie's *sellout Period* is reflected in the data.

## The corpus
The corpus for this study was a playlist curated by Spotify called "This is David Bowie", which is part of a series of artist focused playlists that spotify creates. The playlsit contains 72 songs that spam his entire career, however there is no information available about how these songs were created, which is a weekness of the corpus.

## Findings
Out of all of the parameters that spotify provides, acousticness reflected an interesting result when plotted against the track release dates. As visible in graph 1, there is a clear drop in acousticness around 1980 - 1990. Unfortunately, due to the aesthetic limitations of the graph (and my lack of coding skills) I was unable to determine the exact period in terms of album.track.release_date, however graph 2 visualises the tracks that had a danceability that was less than 0.006. Here, the corpus is reduced to 15 tracks, 7 of which are tracks that were released between 1980 - 1990 which is the highest concentration per decade. 

# Extra findings
Interestingly, as graph 3 shows, while the songs from the _sellout Period_ are distinguishable by acousticness, when compared with track popularity, they do not stand out of the rest of the corpus. As spotify's popularity is based only since 2018 (which is when the playlist was created) it seems that modern audiences do not listen to his supposedly more radio-friendly songs any more than the rest of his discography
