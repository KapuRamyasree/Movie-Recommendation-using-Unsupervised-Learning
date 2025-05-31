# Movie-Recommendation-Using-Unsupervised-Learning

📦 Full Dataset (300MB): [Download from Google Drive](https://drive.google.com/file/d/1jf08yEU-1hQSGpFjjph77R4shUBHRHuF/view?usp=sharing)


## 📌 Introduction

In today’s digital age, users are overwhelmed with the vast array of movie options available across various streaming platforms. As a result, deciding **what to watch next** has become increasingly challenging.

**Movie Recommendation Systems** offer a smart solution by helping users discover films tailored to their preferences. This project focuses on building a **Content-Based Movie Recommendation System** that suggests similar movies to a given title using various metadata features, such as:

- Genre  
- Overview  
- Cast  
- Crew  
- Keywords  

The system leverages similarity between movie attributes to make personalized recommendations — without relying on user ratings or interaction history.

---

## 🛠️ Technologies and Tools Used

This project uses the following tools and libraries:

- **Python** – Core programming language for data processing and modeling  
- **Pandas** – Data cleaning, exploration, and manipulation  
- **NumPy** – Numerical operations and efficient array handling  
- **Scikit-learn** – Feature extraction (e.g., TF-IDF Vectorizer) and cosine similarity computation  
- **Natural Language Processing (NLP)** – To process and vectorize textual metadata like overviews and keywords  
- **Jupyter Notebook** – For interactive development and experimentation  
- **Matplotlib / Seaborn** *(optional)* – Data visualization for pattern recognition and insights  

---

## 📊 Dataset Description

Each feature in the dataset is defined as follows:

- **adult**: Indicates whether the movie is for adults (`True` or `False`)  
- **belongs_to_collection**: Dictionary-like string showing franchise or collection info  
- **budget**: Budget of the movie (in USD)  
- **genres**: List of genres (each as a dictionary with `id` and `name`)  
- **homepage**: Official website URL (if available)  
- **id**: Unique identifier of the movie  
- **imdb_id**: IMDb identifier (e.g., `tt0114709`)  
- **original_language**: Original language code (e.g., `'en'` for English)  
- **original_title**: Original title before translation or localization  
- **overview**: Short synopsis or plot summary  
- **popularity**: Numeric score reflecting popularity  
- **poster_path**: Path to the poster image file  
- **production_companies**: List of involved production companies  
- **production_countries**: List of countries involved in production  
- **release_date**: Official release date (YYYY-MM-DD)  
- **revenue**: Revenue generated (in USD)  
- **runtime**: Duration in minutes  
- **spoken_languages**: List of spoken languages (as dictionaries)  
- **status**: Release status (e.g., Released, Post Production)  
- **tagline**: Marketing tagline or catchphrase  
- **title**: Movie title (localized if applicable)  
- **video**: Indicates whether the entry is a video (`True` or `False`)  
- **vote_average**: Average user rating (typically out of 10)  
- **vote_count**: Number of user ratings or votes  

---

## 📬 Contact

If you have any questions or suggestions, feel free to reach out!
