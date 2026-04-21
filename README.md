# 🎬 Movie Recommender System

Hey! 👋  
This is a simple Movie Recommender System I built using Python and Streamlit.  
You just select a movie, and it suggests 5 similar movies along with their posters.

--
💡 What this project does

- Pick a movie from the dropdown  
- Click **“Show Recommendation”**  
- Get 5 similar movies instantly  
- See their posters (fetched from TMDB API)

--

## 🧠 How it works (in simple words)

Instead of using ratings or user data, this project uses **content-based filtering**.

That means:
- It looks at things like **genres, cast, keywords, and overview**
- Combines all of them into one column called `tags`
- Converts text into numbers using **CountVectorizer**
- Then compares movies using **cosine similarity**

👉 So basically, movies with similar content → get recommended.

---

#🛠️ Tech used

- Python  
- Pandas  
- Scikit-learn  
- Streamlit  
- Pickle  
- Requests (for API)  

---
