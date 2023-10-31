# SpotifyTrends
The Tableau data visualization aims at finding the top artist by country and determines various characteristics of music like energy vs danceability and time series analysis of acoustics and valence

 1. The dataset is downloaded from Kaggle's spotify_dataset and is refreshed daily with a snapshot of the previous day's top 50 songs by country Please find the data dictionary 
     explaining various fields used in the visualization
     spotify_id - unique ID of a song
     name - song name
     artists -  song artists (one or more as comma separated string)
     daily rank - daily rank of a song by country
     popularity - A measure of the song's current popularity on Spotify. (type: int)
     acousticness - A measure of the acoustic quality of the song. (type: float)
     valence - A measure of the musical positiveness conveyed by the song. (type: float)
     energy - A measure of the intensity and activity level of the song. (type: float)
     danceability - A measure of how suitable the song is for dancing based on various musical elements. (type: float)
 
 3. The dataset is uploaded to Google Cloud storage and read as dataframe into Jupyter notebook
 4. Please find Jupyter notebook uploaded in the code section for a detailed walkthrough
 5. The data visualization is created in Tableau. Please find below guidance to navigate the dashboard:
     a. The dashboard is refreshed on 10/27/2023 and a new snapshot of top 50 songs from each country is updated everyday
     b. Please select Country dropdown from the filter or Select one of the countries from the map
     c. This drills down into the country and shows unique songs and Top artists from the selected country
     d. Top artists by popularity shows Top artists from the selected country by popularity score 
     e. Acousticness vs valence shows the trend in pattern of the kind of songs popular in the selected country
     f. Correlation of Energy vs danceability shows what kind of songs the people from a given country prefer to listen

This dashboard helps determine the top artists, music preferences, and trends in characteristics of music over time in a selected country of interest.
