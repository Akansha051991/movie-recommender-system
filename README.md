# 🎬 Movie Recommender System

A sleek, interactive web application that recommends movies based on content similarity. This project uses Machine Learning to find patterns in movie metadata and fetches real-time posters using the TMDB API.

## 🌟 Live Demo
https://movie-recommender-system-i6y33unm4lunqb3eaggmow.streamlit.app/

🧠 Data Science & Machine Learning Workflow
Before the app was built, I performed extensive data processing and model research. 
View the Research & Model Building Notebook (https://github.com/Akansha051991/movie-recommender-system/blob/main/movie_recommender_project.ipynb)
Includes: Data cleaning, exploratory data analysis (EDA), feature engineering, and similarity matrix generation.

🛠️ Tech Stack
Language: Python
Web Framework: Streamlit
ML Libraries: Pandas, Scikit-learn, NLTK
Data Source: TMDB 5000 Movies Dataset

📂 Repository Structure
app.py: The main script for the Streamlit web application.
model/: Contains the pre-trained similarity matrix and movie dictionaries.
movie_recommender_project.ipynb: The Jupyter notebook containing the full ML pipeline.
requirements.txt: List of dependencies needed to run the project.

## 🛠 How it Works
1. **Vectorization:** Movie tags are converted into vectors using `CountVectorizer`.
2. **Similarity:** We calculate the **Cosine Similarity** between movies.
3. **Fetching Posters:** The app calls the **TMDB API** to get high-quality movie posters for a professional look.

## 🚀 Features
- **Smart Search:** Select from over 5,000 movies.
- **Visual Grid:** A 5-column poster layout designed with Streamlit 1.53.1.
- **Fast Performance:** Uses pre-computed similarity matrices for instant results.

## 📦 Installation & Setup
To run this project locally:
1. Clone this repo.
2. Install requirements: `pip install -r requirements.txt`
3. Run the app: `streamlit run app.py`

## 📧 Contact
Akansha Choudhary - [https://www.linkedin.com/in/akansha-choudhary-9a91a0a6/]