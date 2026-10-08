# manhwa-recommendation-system
Content-based manhwa recommendation system using NLP, embeddings and machine learning


Manhwa Recommendation System

A content-based recommendation system that recommends similar manhwa (Korean webcomic) titles using Natural Language Processing (NLP), feature engineering, and machine learning techniques.

Project Overview

This project explores how textual descriptions can be used to recommend relevant titles without relying on individual users’ rating histories.

The recommendation pipeline uses metadata obtained from the AniList API, alongside features derived from genres, tags, taxonomies, and descriptions.

Technologies

* Python
* Pandas and NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF
* Sentence Transformers
* Cosine Similarity
* AniList GraphQL API

Methodology

1. Data Collection: Gather title metadata from AniList.
2. Exploratory Data Analysis: Investigate distributions, completeness, and useful recommendation features.
3. Data Preprocessing: Clean and standardise textual and categorical information.
4. Feature Engineering: Extract genres, tags, taxonomy features, and numerical metadata.
5. Recommendation Modelling: Represent titles using text and taxonomy information and calculate similarity scores.
6. Model Exploration: Investigate sentence-embedding representations, including all-MiniLM-L6-v2 and all-mpnet-base-v2, as well as TF-IDF based representations.
7. Evaluation: Analyse recommendation relevance and compare modelling approaches.

How It Works

The system represents titles using their descriptions and metadata. Similarity calculations identify related titles and rank potential recommendations.

This content-based approach makes it possible to generate recommendations without requiring a large history of user interactions.

Future Improvements

* Interactive recommendation interface
* Personalised recommendations from reading history
* Explicit trope and character-preference filtering
* Hybrid system (content-based and collaborative recommendation hybrid including other user sentiments etc.)

Academic Context

Developed as a final-year university project exploring content-based recommendation systems, feature representations, and recommendation relevance.

Author

[Arya] — Computer Science Graduate
