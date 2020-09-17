# Music_Taste_Analysis
This is the user tastes analysis using Spotify API.
- Learn how to connect the Spotify API
  - Eg. Autheticating from the user with specified scope
- EDA on the songs available in the libary
- Clustering analysis on the songs
- Build personalized recommendation system

The features used for the analysis can be found [here](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)
- `duriation_ms`: The duration of the track in the milliseconds.
- `key`: The estimated overall key of track. Integers map to pitches using the standard `Pitch Class notation`.
- `mode`: Mode indicates the modality(major or minor) of a track, the type of scale from which its medlodic content derived. Major is represented by 1 and minor is 0.
- `time_signature`: An estimated overalltime of a track. The time signature(meter) is a notational convention to specify how many beats in a bar(a measure).
- `acounsticness`: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic. The distribution of values for this feature look like this:
![Optional Text](../main/pic/pc1.png)

