# Movie Recommendation System with GUI

## Project Overview
This project is a web-based movie recommendation system with a graphical user interface (GUI). It leverages Natural Language Processing (NLP) techniques and machine learning algorithms to suggest movies based on a given title. The system uses a dataset of movie details to compute similarity scores and recommend movies that are similar to the input title.

## Key Steps and Achievements

1. **Data Preprocessing:**
   - Loaded the movie dataset using pandas and performed initial data exploration.
   - Created a 'soup' feature by combining relevant textual information for each movie to improve similarity computation.

2. **Feature Extraction:**
   - Utilized `CountVectorizer` to convert the 'soup' feature into a matrix of token counts.
   - Computed cosine similarity scores between all pairs of movies based on the count matrix.

3. **Building the Recommendation Function:**
   - Implemented a function to retrieve movie recommendations based on cosine similarity scores.
   - Sorted movies by similarity and returned the top 10 recommendations.

4. **Web Application Development:**
   - Developed a Flask web application with a graphical user interface to provide an interactive experience.
   - Created routes to handle GET and POST requests, rendering appropriate HTML templates based on user input.
   - Incorporated error handling for cases where the input movie title is not found in the dataset.

## Future Work
Future enhancements for this project could include:
- Expanding the dataset to include more movies and additional metadata.
- Improving the recommendation algorithm by incorporating user ratings and collaborative filtering techniques.
- Integrating a user authentication system to provide personalized recommendations based on user preferences.
- Enhancing the web interface for a more user-friendly experience and adding features such as movie trailers and reviews.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code as long as the original author is credited.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements, bug fixes, or documentation updates.


