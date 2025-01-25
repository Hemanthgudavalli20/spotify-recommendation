# spotify-recommendation

Dataset source - https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-2023?resource=download&select=spotify_features_data_2023.csv

Description 
A content-based music recommendation system that recommends songs based on features such as tempo, energy, danceability, and more.

Algorithm(s) Used : k-NN cosine similarity , autoencoders

Audio features: tempo, energy, danceability, valence, acousticness, etc.
Metadata: Song name, artist, and other attributes.

Trained the same data with autoencoders and obtained different results but seem more closer to the target song in terms of features.

Expanding Further:
To expand your project with a real streaming environment and Kafka, here’s how you can approach it:

-  Streaming Setup Overview
The real-time recommendation system will work as follows:

Input: A user selects a song.
Process:
The song ID or features are sent to a Kafka topic.
A consumer listens to this topic and retrieves the song's features.
A recommendation engine (running on a server or cloud) generates a list of similar songs.
The results are sent to another Kafka topic or an API.
Output: The recommended songs are displayed to the user.
  


Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or new features.
