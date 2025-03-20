# Movie Recommendation System ( using machine learning )

# Dataset has been used:

* [Dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv) 

# **Building the Model: Cosine Similarity**

- Cosine Similarity measures the similarity between documents using vectors (NumPy arrays).
- `cosine_similarity()` computes similarity between two vectors, returning a value between **0 (different)** and **1 (identical)**.

## **How to Run the Project**

### **Step 1: Set Up Environment**
```bash
conda create -n movie python=3.7.10 -y  
conda activate movie
```

### **Step 2: Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Step 3: Run the Project**
```bash
# Generate models
Movie Recommender System Data Analysis.ipynb  

# Start the app
streamlit run app.py
```

**Author:** Reshma G.V.S.  
**Email:** gvsreshma2005@gmail.com

