# Movie Recommendation System 🎬

This project is a beginner-friendly **Movie Recommendation System** built using **Natural Language Processing (NLP)** and **Cosine Similarity**.  
It compares movie plots/descriptions and recommends the most similar movies to a given input.

---

## 🔧 Features
- Uses **text vectorization** techniques to convert movie descriptions into numerical vectors.
- Two approaches implemented:
  - **Bag of Words (BoW)**
  - **TF-IDF (Term Frequency – Inverse Document Frequency)**
- Computes similarity between movies using **cosine similarity**.
- Beginner-friendly code with clear examples.

---

## 📂 Project Structure
├── bow_recommender.py # Movie recommender using Bag of Words
├── tfidf_recommender.py # Movie recommender using TF-IDF
├── movies.csv # Dataset of movies with descriptions
└── README.md # Project documentation


---

## 🚀 How It Works

### 1. Bag of Words (BoW)
- Counts the frequency of each word in the movie description.
- Creates a **word count matrix**.
- Uses cosine similarity to find similar movies.

Example Recommendations (BoW):
Titan A.E.
Small Soldiers
Independence Day
Ender's Game
Aliens vs Predator: Requiem


---

### 2. TF-IDF (Term Frequency – Inverse Document Frequency)
- Considers not just word frequency, but also **how unique a word is across all movies**.
- Common words like *“the”*, *“movie”*, *“film”* get lower weight.
- More meaningful words (e.g., *“alien”*, *“space”*, *“robot”*) have higher impact.

Example Recommendations (TF-IDF):
Falcon Rising
Battle: Los Angeles
Apollo 18
Star Trek Into Darkness
Titan A.E.

yaml
Copy
Edit

---

## 📊 Why Two Techniques?
- **Bag of Words** → Simple, works well when dataset is small, but may give noisy results.
- **TF-IDF** → Smarter, reduces importance of common words, usually better for larger datasets.

---

## ⚡ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender.git
   cd movie-recommender
