🚀 Movie Recommender System  
A modern machine learning-based movie recommendation app built using Python and Streamlit. It uses NLP techniques and cosine similarity to suggest movies similar to a selected title, with real-time poster display via the TMDb API. Designed for simplicity, speed, and a smooth user experience.

📌 Features  
✅ Content-Based Recommendations – Uses overview, cast, crew, keywords, and genres to compute similarity  
✅ Movie Posters – Integrated with TMDb API to show high-quality posters  
✅ Fast Performance – Precomputed similarity matrix ensures instant recommendations  
✅ Clean UI – Interactive Streamlit interface for easy navigation  
✅ Scalable Dataset Support – Easily extendable with new movie data

🏗️ Tech Stack  
📦 Machine Learning 
- Scikit-learn (CountVectorizer, Cosine Similarity)  
- Pandas, NumPy  

🧠 Natural Language Processing (NLP)  
- Text preprocessing of metadata for vectorization  

💻 Frontend 
- Streamlit (Python-based web framework)  

🌐 API Integration  
- TMDb API (for real-time movie posters)

🗂️ Data Source 
- [TMDB 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

⚠️ Note:  
`similarity.pkl` is excluded from this repo due to GitHub’s 100MB limit. You must generate it locally or download it from an external link (e.g., Google Drive) to run the project.


