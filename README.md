# ANALYSIS ON TOP SPOTIFY SONGS 2023

We have two files that contains our analysis and one file that contains projet description:

1. Jupyter file
2. Python file
3. Readme file

Both contain the same analysis

## **Description of Dataset**

This dataset contains a comprehensive list of the most famous songs of 2023 as listed on Spotify. The dataset offers a wealth of features beyond what is typically available in similar datasets. It provides insights into each song's attributes, popularity, and presence on various music platforms. The dataset includes information such as **track name**, **artist(s) name**, **release date**, **Spotify playlists** and **charts**, **streaming statistics**, **Apple Music presence**, **Deezer presence**, **Shazam charts**, and various audio features.

## Link of the Dataset

This dataset come from Kaggle. This is the link : [Spotify Songs 2023 Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

## Methods to pull the Dataset

There are several options for getting the dataset into Jupyter :

- Download the CSV manuallly and upload it via Jupyter'GUI
- Use the urlretrieve function from urllib.request to download CSV files from a raw URL

* Use a helper library, e.g opendatasets which contains a collection of curated datasets and provides a helper function for direct download.

  We'll use the opendatasets helper library to download the files.

## **Goal of the project**

In this projet, We'll analyze or explore the Top Spotify Songs 2023 dataset in order to understand and find insights. This dataset contains features of Top Spotify Songs in 2023.

## **Tools used**

- **Pandas** for data manipulation.
- **Numpy** for numeric calculation.
- **Seaborn and Matplotlib** for visualization.

## **About Spotify**

**Spotify** is a popular music streaming service, offering a vast library of tracks and podcasts. Users can listen for free with ads or subscribe for an ad-free experience. It's accessible on various devices, providing convenient music enjoyment.

### Explanation of variables

- **track_name** : Nom de la chanson
- **artist(s)\_name** : nom du ou des artistes de la chanson
- **artist_count** : Nombre d'artistes ayant contribué à la chanson
- **released_year** : Année de sortie de la chanson
- **released_month** : Mois de sortie de la chanson
- **released_day** : Jour du mois où la chanson est sortie
- **in_spotify_playlists** : Nombre de listes de lecture Spotify dans lesquelles la chanson est incluse
- **in_spotify_charts** : Présence et rang de la chanson dans les charts Spotify
  streams : Nombre total de streams sur Spotify
- **in_apple_playlists** : Nombre de listes de lecture Apple Music dans lesquelles la chanson est incluse
- **in_apple_charts** : Présence et rang de la chanson dans les charts d'Apple Music
- **in_deezer_playlists** : Nombre de listes de lecture Deezer dans lesquelles la chanson est incluse
- **in_deezer_charts** : Présence et rang de la chanson dans les charts Deezer
- **in_shazam_charts** : Présence et rang de la chanson dans les charts Shazam
- **bpm** : battements par minute, une mesure du tempo de la chanson
- **key** : Clé de la chanson
- **mode** : Mode de la chanson (majeur ou mineur)
- **danceability\_%** : Pourcentage indiquant dans quelle mesure la chanson se prête à la danse
- **valence\_%** : positivité du contenu musical de la chanson
- **energy\_%** : Niveau d'énergie perçu de la chanson
- **acousticness\_%** : Quantité de sons acoustiques dans la chanson
- **instrumentalness\_%** : Quantité de contenu instrumental dans la chanson
- **liveness\_%** : Présence d'éléments de performance en direct
- **speechiness\_%** : Nombre de mots prononcés dans la chanson
