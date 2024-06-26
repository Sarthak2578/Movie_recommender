# Movie_recommender

Recommendation systems are tools designed to predict or filter the items according to the behavior of any user. Movie recommendation systems aim at helping out users by suggesting which movie to watch without having to go through the long process of going through all the available options. <br />
We’ve tried implementing a model which uses a content based approach to provide movie recommendations to any user. Content based approach uses tags to recommend other items similar to what user likes, based on their provided input of previous actions. Since data recommendations are specific to a user, this type of filtering makes it easier to capture the specific interests of a user.

![](Main%20page.png)
*Main Page* <br />

![](Recommendation%20page.png)
*Recommendation Page*

## Key Features:
- **Personalized Recommendations:** Users can discover movies tailored to their tastes, based on genres, keywords, cast, and crew. <br />
- **Data-Driven Insights:** Leverages IMDB 5000 Movie Dataset for rich metadata on movies, including genres, cast, keywords, and overviews. <br />
- **Interactive UI:** Streamlit-powered interface provides a user-friendly platform for movie exploration. <br />
- **Advanced Data Processing:** Utilizes NLP techniques for preprocessing, including tokenization, stop word removal, lemmatization, and vectorization. <br />
- **Similarity-Based Recommendations:** Employs cosine similarity to find movies that closely match the user's preferences. <br />

### Backend Technologies:
- **Pandas** for data manipulation and analysis. <br />
- **Scikit-learn** for feature extraction and similarity computation. <br />
- **NLTK** for natural language processing. <br />
- **Ast** for safely evaluating strings containing Python literal structures. <br />

### Frontend Technologies:
- **Streamlit** for creating the web app. <br />
- **Requests for API calls** to fetch movie posters and additional details. <br />

## Getting Started:
- Clone this repository.
- Install required dependencies: pip install -r requirements.txt.
- Run the Streamlit app: streamlit run app.py.
- Explore movie recommendations by typing in a movie name or selecting from the dropdown.

## How It Works:
The system preprocesses movie metadata to extract meaningful features (genres, keywords, cast, crew, overview). These features are then combined into a single tag for each movie, which undergoes further NLP preprocessing (tokenization, stop word removal, lemmatization) before being vectorized. The cosine similarity between movie vectors is computed to identify the most similar movies for recommendations.

## Explore:
Dive into our movie recommendation system to find your next favorite movie. Contributions, suggestions, and feedback are welcome to improve the system further!
