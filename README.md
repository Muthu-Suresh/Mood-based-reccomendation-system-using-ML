# Unified Recommendation System for Personalized Living
This project is an AI-powered recommendation system that uses Natural Language Processing (NLP) and Deep Learning to understand user moods and provide personalized suggestions across multiple categories like Tamil songs, movies, travel destinations, food, and books.

# Features
- 🧠 Predicts user mood using a trained Neural Network.
- 🎬 Recommends Tamil movies and songs.
- 🍲 Suggests food based on your feelings.
- 📖 Book recommendations for every emotion.
- ✈️ Travel location suggestions with famous places and hotel info.

# Technologies Used
- **Python**  
- **Pandas, NumPy**  
- **TensorFlow & Keras** – Deep learning model  
- **NLTK** – Tokenization & stop word removal  
- **TF-IDF Vectorizer** – Text feature extraction  
- **Speech Recognition** *(optionally pluggable)*  
- **Scikit-learn** – Label Encoding, Train-Test Split  

# Dataset Columns
- `Mood`
- `Tamil Song`
- `Tamil Movie`
- `Travel Location`
- `Famous Places`
- `Famous Hotels with Price`
- `Food`
- `Book`

# How It Works
1. User enters a mood as a sentence or phrase.
2. The input is cleaned and vectorized using TF-IDF.
3. A trained deep learning model predicts the mood category.
4. Based on the user's preferred category (song/movie/book/travel/food), a matching recommendation is returned.
