## MUSIC RECOMMENDATION SYSTEM

### Overview:
This project presents a personalized music recommendation system utilizing machine learning algorithms to enhance the music discovery experience. The system suggests tracks, albums, and playlists based on user preferences and listening history, leveraging the power of natural language processing and similarity measures.

### Problem Statement:
The goal is to create a personalized music recommendation system that effectively recommends songs to users based on their past listening behavior. This system aims to improve user engagement by offering a seamless and enjoyable music discovery experience.

### Data Description:
The dataset used for this project consists of song lyrics and metadata. For demonstration purposes, a subset of 1000 songs from the dataset has been utilized. Key columns include:

- Song Title: The name of the song.
- Artist: The name of the artist or band.
- Lyrics: The text of the song lyrics.

### Methodology:
#### Data Preprocessing:
The dataset was cleaned and preprocessed to extract the relevant columns needed for building the recommendation system. The song lyrics were vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) technique to convert the text data into numerical form, which is essential for computing similarities.

#### Vectorization and Similarity Calculation:
TF-IDF was applied to the lyrics to capture the importance of each word in the context of the song. The cosine similarity matrix was then calculated to measure the similarity between different songs based on their lyrics. This similarity matrix serves as the core component of the recommendation algorithm.

#### Recommendation Algorithm:
The system identifies similar songs by comparing the cosine similarity scores. Given a song title, the algorithm retrieves the indices of the top 10 most similar songs and recommends them to the user.

### User Interface:
A user-friendly interface was developed using Streamlit, allowing users to select a song and view the top recommended songs. The GUI includes:
1) A dropdown menu for selecting a song.
2) A button to generate and display recommendations.

### How to Use:
1) Clone the repository.
2) Ensure you have the necessary libraries installed (pandas, scikit-learn, streamlit).
3) Run the Streamlit application using the command: `streamlit run app.py`.
4) Select a song from the dropdown menu and click on the "Show Recommendations" button to view the recommended songs.

### Conclusion:
This project demonstrates the application of machine learning and natural language processing in building a personalized music recommendation system. By leveraging song lyrics and similarity measures, the system provides meaningful and relevant song recommendations, enhancing the overall music discovery experience for users.

For more details, visit the [project repository](https://github.com/prizbot/Music-Recommendation-System.git).

For any inquiries or collaborations, feel free to reach out:
- LinkedIn: [Priyadharshini NRS](www.linkedin.com/in/priyadharshininrs)
- Email: [](mailto:priyadharshininrs@gmail.com)
