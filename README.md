# Movie Recommender System (Content-Based Approach)

This movie recommender system is built using a content-based approach, which suggests movies to users based on the similarities between their preferred movie features and the content of other movies. It analyzes movie characteristics like genre, cast, director, and plot summaries to generate personalized recommendations.

## Workflow

- Utilized the TMDB Dataset from Kaggle consisting of movie_id, genre, cast, director, and plot summaries.
- Extracts features from the dataset and converts it into vectors.
- Calculates similarities between movies using a similarity metric (cosine similarity).
- Recommends movies that are most similar to the user's preferences based on their feature representations.
- Used StreamLit for representing on a website.

## Installation and running the app

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   
2. Install the required dependencies:
    ```bash
      pip install -r requirements.txt
   ```

3. Run the webapp
   ```bash
      streamlit run app.py
   ```

## Future Scope

- Clicking on posters can lead to full information about the movie like overview, cast, director, etc.
- Integrating the collaborative filtering approach, that takes in consideration the user's preferences on the basis of past history.

## Website using StreamLit

![image](https://github.com/sejalapeno/movie-recommender-system/assets/110482301/542409f4-5bbc-45f2-8ca1-2f798456fa7d)

![image](https://github.com/sejalapeno/movie-recommender-system/assets/110482301/a170362a-2182-4b7a-b6dc-22d22b2c3242)

![image](https://github.com/sejalapeno/movie-recommender-system/assets/110482301/cb0b83da-f359-47a7-ba48-ab43e3f90dd9)

