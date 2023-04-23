# Content-Based Music Recommender System

This project is a content-based music recommender system using Spotify's audio features. The recommender system generates personalized playlists by calculating the similarity between tracks using three different algorithms: *Cosine Similarity*, *Euclidean Distance*, and *Manhattan Distance*.

## Libraries Used

- Spotify: Interact with the Spotify Web API
- Skimage: Process and manipulate album cover images
- Pandas: Data manipulation and analysis
- Scikit-learn (sklearn): Machine learning and data mining

## Dataset

The dataset used in this project is the `SpotifyFeatures.csv` file, which can be found on [Kaggle](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db).

## Main File

The main file of this project is `main.ipynb`, which contains the code for importing libraries, loading data, preprocessing, and implementing the recommendation algorithms.

## How to Use

1. Clone this repository.
2. Download the `SpotifyFeatures.csv` dataset from Kaggle and place it in the same folder as the main file.
3. Set up a Spotify Developer account, create an application, and obtain your client ID, client secret, and redirect URI.
4. Replace the placeholders in `main.ipynb` with your actual client ID, client secret, and redirect URI.
5. Replace the playlist name to yours
6. Install the required libraries using `pip` or `conda`.
7. Run the `main.ipynb` file using Jupyter Notebook or any other compatible environment.
