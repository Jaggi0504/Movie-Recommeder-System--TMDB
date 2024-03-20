Recommendation systems offer numerous benefits for businesses and users alike, contributing to improved satisfaction, revenue, and efficiency. This project is a movie recommender system which will recommend top-5 related movies. I took the dataset from Kaggle (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) which contains credits.csv and movies.csv file.
I performed the following operations on the dataset:
1. Data Preprocessing
2. Feature Engineering
3. NLP techniques: Bag-of-words and TF-IDF
4. Recommend function: will recommend top-5 movies based on cosine similairty
5. For UI, I used streamlit framework (Exported movies dictionary as similarity function through pickle)
6. Created an account on TMDB to use its API (https://www.themoviedb.org/?language=en-CA)
7. To fetch the posters, I used (https://image.tmdb.org/t/p/w500/) + path of movie
<img width="1470" alt="Screenshot 2024-03-20 at 5 44 17 AM" src="https://github.com/Jaggi0504/Movie-Recommeder-System--TMDB/assets/44519331/900844ac-448d-4260-b921-42f374bf4f85">
