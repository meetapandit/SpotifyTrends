# SpotifyTrends
The Tableau data visualization aims at finding the top artist by country and determines various characteristics of music like energy vs danceability and time series analysis of acoustics and valence

 1. The dataset is downloaded from Kaggle's spotify_dataset and is refreshed daily with a snapshot of the previous day's top 50 songs by country. Please find the data dictionary 
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
<img width="1246" alt="Screenshot 2023-10-30 at 11 24 50 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/19d788ad-c660-4a02-a815-786c5c67903b">
<img width="636" alt="Screenshot 2023-10-30 at 11 25 31 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/b02c0bd9-3da8-447f-8018-7fd7b5879712">

     c. This drills down into the country and shows unique songs and Top artists from the selected country    
<img width="636" alt="Screenshot 2023-10-30 at 11 25 31 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/11d00d03-f7ab-4feb-bfca-c6f7f317c2c1">

     d. Top artists by popularity shows Top artists from the selected country by popularity score
<img width="589" alt="Screenshot 2023-10-30 at 11 25 46 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/122205a9-ecf9-4bce-86a1-0236b3c090d4">

     e. Acousticness vs valence shows the trend in pattern of the kind of songs popular in the selected country
<img width="636" alt="Screenshot 2023-10-30 at 11 26 00 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/3ad7c13f-d885-4e79-a04f-14bf0fba0102">
    
     f. Correlation of Energy vs danceability shows what kind of songs the people from a given country prefer to listen
<img width="608" alt="Screenshot 2023-10-30 at 11 26 21 PM" src="https://github.com/meetapandit/SpotifyTrends/assets/15186489/027819be-4a7d-4da9-890b-5cb90bc9d1ae">

This dashboard helps determine the top artists, music preferences, and trends in the characteristics of music over time in a selected country of interest.
