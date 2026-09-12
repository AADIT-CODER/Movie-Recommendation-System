# Movie Recommendation System

## 📌 Project Overview

Movie Recommendation System is a machine learning-based project that recommends movies to users based on movie similarity.

The system analyzes movie information such as genres, keywords, cast, crew, and other available features to identify movies that are similar to the movie selected by the user.

This project uses Natural Language Processing, data preprocessing, feature engineering, and cosine similarity to generate personalized movie recommendations.

The project is developed using Python, Pandas, NumPy, and Scikit-learn.

## 🎯 Objectives

* Build a movie recommendation system using machine learning techniques.
* Recommend movies based on similarity between movie features.
* Perform data cleaning and preprocessing on movie datasets.
* Combine relevant movie information such as genres, keywords, cast, and crew.
* Apply text-based feature engineering.
* Calculate similarity between movies using cosine similarity.
* Generate relevant movie recommendations for users.
* Understand the practical implementation of recommendation systems.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Natural Language Processing
* Data Cleaning
* Data Preprocessing
* Feature Engineering
* Cosine Similarity
* Machine Learning

## 📂 Dataset

The project uses movie-related datasets containing information about movies, including:

* Movie titles
* Genres
* Keywords
* Cast
* Crew
* Movie overview and related information

The project uses the following dataset files:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

These datasets are processed and combined to create the final data required for movie recommendations.

## ⚙️ How It Works

1. The movie datasets are loaded using Pandas.
2. The movie data and credits data are merged using the common movie identifier.
3. Relevant columns are selected from the datasets.
4. Missing values and unnecessary data are handled.
5. Movie features such as genres, keywords, cast, crew, and overview are processed.
6. Text data is converted into a suitable format for similarity analysis.
7. Important movie features are combined into a single tags-based representation.
8. Text features are converted into numerical vectors.
9. Cosine similarity is calculated between movie vectors.
10. When a user selects a movie, the system finds similar movies.
11. The system displays recommended movie titles based on similarity scores.

## ✨ Features

* Movie-based recommendation system.
* Content-based filtering approach.
* Uses movie metadata for recommendations.
* Data preprocessing and cleaning.
* Feature extraction from movie information.
* Text-based movie similarity analysis.
* Cosine similarity-based recommendations.
* Recommends movies similar to the selected movie.
* Easy to understand and extend.
* Includes preprocessed movie data and similarity-related files.

## 🧠 Recommendation Methodology

The project follows a content-based recommendation approach.

The system creates a combined feature representation for every movie using information such as:

* Genres
* Keywords
* Cast
* Crew
* Movie overview

These features are converted into numerical vectors using text vectorization techniques.

Cosine similarity is then used to measure the similarity between movies.

A higher similarity score indicates that two movies have more similar content and features.

## 📊 Project Results

The project successfully demonstrates how machine learning and natural language processing techniques can be used to build a movie recommendation system.

The system takes a movie title as input and recommends other movies with similar characteristics.

The recommendation engine generates movie suggestions based on the similarity between movie feature vectors.

### Sample Output

Example:

```text
Input Movie:
Avatar

Recommended Movies:
- Guardians of the Galaxy
- Star Trek
- John Carter
- Star Wars
- The Avengers
```

The output recommendations depend on the movie selected by the user and the similarity calculated from the dataset.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd Movie-Recommendation-System
```

### 3. Install Required Libraries

```bash
pip install numpy pandas scikit-learn jupyter notebook
```

### 4. Check the Project Structure

Make sure the project contains the datasets and Jupyter Notebooks.

```text
Movie-Recommendation-System/
│
├── Movie_Recommendation_System.ipynb
├── 01_Data_Preprocessing.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── movies.pkl
├── movie_dict.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

### 6. Run the Main Notebook

Open:

```text
Movie_Recommendation_System.ipynb
```

Run the notebook cells in sequence to:

1. Load the datasets.
2. Preprocess the movie data.
3. Create movie tags.
4. Generate movie vectors.
5. Calculate cosine similarity.
6. Generate movie recommendations.
7. Save the required output files.

### 7. Generate Recommendation Files

The notebook generates files used by the recommendation system, such as:

* `movies.pkl`
* `movie_dict.pkl`
* `similarity.pkl`

The `similarity.pkl` file may be large and is not included in the GitHub repository.

It can be regenerated by running the main notebook.

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── Movie_Recommendation_System.ipynb
│
├── 01_Data_Preprocessing.ipynb
│
├── tmdb_5000_movies.csv
│
├── tmdb_5000_credits.csv
│
├── movies.pkl
│
├── movie_dict.pkl
│
├── requirements.txt
│
├── .gitignore
│
└── README.md
```

## 📌 Important Files

### `Movie_Recommendation_System.ipynb`

This is the main notebook containing the complete movie recommendation workflow, including:

* Data loading
* Data preprocessing
* Feature engineering
* Movie tags creation
* Vectorization
* Similarity calculation
* Movie recommendation logic
* Pickle file generation

### `01_Data_Preprocessing.ipynb`

This notebook contains the initial data loading, merging, and preprocessing steps used to prepare the movie datasets.

### `movies.pkl`

Stores processed movie-related data used by the recommendation system.

### `movie_dict.pkl`

Stores movie information in dictionary format for accessing movie details.

### `similarity.pkl`

Stores the movie similarity matrix generated using cosine similarity.

Due to its large file size, this file is excluded from the GitHub repository and can be regenerated using the main notebook.

## 💡 Applications

* Movie recommendation platforms.
* Entertainment websites.
* OTT platform recommendation systems.
* Personalized movie discovery.
* Content-based filtering projects.
* Machine learning learning projects.
* Natural Language Processing applications.
* Recommendation system demonstrations.

## 🔮 Future Scope

* Develop a Streamlit-based web application.
* Add an interactive movie search interface.
* Display movie posters and additional movie details.
* Add user-based collaborative filtering.
* Combine content-based and collaborative filtering.
* Improve recommendation accuracy.
* Add movie ratings and review analysis.
* Include user watch history.
* Add personalized recommendations.
* Deploy the system as a web application.
* Integrate a movie database API.
* Add filtering by genre, rating, language, and release year.

## ⚠️ Important Notes

* Python must be installed before running the project.
* Required Python libraries must be installed.
* Both dataset files should be present in the project folder.
* The notebooks should be executed in the correct order.
* The `similarity.pkl`  and tmdb_5000_credits.csv files are large and may need to be generated locally.
* Recommendations depend on the available movie dataset.
* The project currently focuses on content-based movie similarity.
* The recommendation results may vary depending on the selected movie and dataset.

## 🎓 Learning Outcomes

Through this project, the following concepts were implemented:

* Data collection and dataset understanding.
* Data cleaning and preprocessing.
* Data merging using common identifiers.
* Feature selection.
* Feature engineering.
* Natural Language Processing.
* Text vectorization.
* Cosine similarity.
* Recommendation system development.
* Saving and loading processed machine learning data.

## 👨‍💻 Author

**Aditya Chaurasiya**

## 📌 Project Details

**Project Name:** Movie Recommendation System

**Project Type:** Machine Learning / Recommendation System / Natural Language Processing

**Domain:** Artificial Intelligence and Data Science

**Development Tool:** Jupyter Notebook

## ⭐ If You Like This Project

If you find this project useful or interesting, consider giving the repository a star on GitHub.
