# Content Based Movie Recommender System using TMDB Dataset

Dataset Used : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

### Overview:
This project implements a content-based movie recommender system using Python, leveraging the TMDB dataset. The recommender system utilizes various attributes such as `movie_id`, `title`, `overview`, `genres`, `keywords`, `cast`, and `crew` to generate recommendations based on the similarity of movie attributes.

### Features:
- **Preprocessing:**
  - Utilized data preprocessing techniques to clean and prepare the dataset for analysis.
  - Extracted relevant information from attributes to create a new column named `tag`, which combines `overview`, `genres`, `keywords`, `cast`, and `crew` information.

- **Model Building:**
  - Employed stemming techniques to process textual data effectively.
  - Implemented cosine similarity to compute the similarity between movies based on their `tag` attributes.

- **Web Application using Streamlit:**
  - Created a user-friendly web application using Streamlit for easy interaction and movie recommendations.

### Steps Involved:

1. **Data Preprocessing:**
   - Cleaned and transformed the dataset.
   - Extracted key information from various attributes.
   
2. **Tag Creation:**
   - Created a new column `tag` that encapsulates essential movie information for recommendation purposes.

3. **Stemming:**
   - Applied stemming to standardize and enhance the effectiveness of textual data analysis.

4. **Cosine Similarity:**
   - Calculated cosine similarity between movies based on their `tag` attributes.

5. **Web Application Development:**
   - Utilized Streamlit to build an interactive web app for users to input preferences and receive movie recommendations.

### How to Use:
1. **Clone the Repository:**
   ```
   git clone https://github.com/rksaarang/movie_recommender_system_.git
   ```

2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```
   streamlit run app.py
   ```
   Access the application via the provided URL.

### Future Improvements:
- Enhance recommendation algorithms for improved accuracy.
- Incorporate user feedback and ratings for personalized recommendations.
- Scale the system to handle larger datasets efficiently.

### Technologies Used:
- Python
- Pandas
- Streamlit
- Cosine Similarity

### Sample Screenshots:
1.Selecting The movie
![image](https://github.com/rksaarang/movie_recommender_system_/assets/105165740/6d991f45-4b4d-4ec6-b8c3-c41f51e71cf0)

2.Recommended Movies
![image](https://github.com/rksaarang/movie_recommender_system_/assets/105165740/48678cdb-c86b-4861-a8ca-80ea1686543a)


