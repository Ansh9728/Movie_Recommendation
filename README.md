This code implements a movie recommendation system using Streamlit. Here's a breakdown of its functionality:

<ul>

 <li> Movie Data Retrieval: The system fetches movie data from an external API (The Movie Database - TMDB) using movie IDs. </li>

 <li> Movie Recommendation Logic: The recommendation function recommend(movie) takes a movie title as input, finds the similarity scores between this movie and others in the dataset, and returns the top 5 recommended movie names, their posters, and their homepage URLs.</li>

  <li> Streamlit Interface: The Streamlit app presents a dropdown menu where users can select a movie. Upon selecting a movie and clicking the "Show Recommendation" button, it displays the top 5 recommended movies along with their posters and homepage URLs.</li>

  <li> Loading Indicator: While recommendations are being fetched, a loading spinner is displayed, providing feedback to the user.</li>

  <li> Display of Recommendations: Recommendations are displayed in columns, each containing the movie title, poster image, and homepage URL.</li>

  <li> Implementation Details: The system uses pickle files to store precomputed movie data (movies.pkl) and similarity scores (similarity.pkl), avoiding the need to fetch data from TMDB every time the system is run.</li>

  
</ul>

Overall, this system offers users a simple and interactive way to explore movie recommendations based on their selected preferences.

Demo Url: https://movierecommendation-asv7hc8qday8m6vnheidxc.streamlit.app/
