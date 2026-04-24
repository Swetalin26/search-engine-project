# Smart Search Engine using Vector Space Model (VSM):

A Python-based **Search Engine** that retrieves and ranks documents from a local dataset using the **Vector Space Model (VSM) and TF-IDF ranking.

This project demonstrates core concepts of Information Retrieval, Search Algorithms, and Text Processing used in real-world systems.

# Core Features

* Tokenization (splitting text into words)
* Stopword Removal (removing common words like *the, is, a*)
* Stemming (reducing words to root form)
* Inverted Index (fast word → document lookup)
* TF-IDF Ranking (relevance-based scoring)
  
# Advanced enhancements

* Title Boost (title matches weighted higher)
* Category Filter (search within specific categories)
* Boolean Search (`AND`, `OR`, `NOT`)
* Autocomplete suggestions
* Search History tracking

# What is Vector Space Model (VSM)?

The Vector Space Model (VSM) represents documents and queries as vectors in a multi-dimensional space.

# Key Idea

* Each document is converted into a vector
* Each word represents a dimension
* Importance of words is calculated using TF-IDF
  
# How It Works

1. User enters a query
2. Text is processed:

   * Tokenization
   * Stopword removal
   * Stemming
3. Documents are converted into vectors using TF-IDF
4. Query vector is compared with document vectors
5. Similarity is calculated
6. Results are ranked based on relevance
   
# Cosine Similarity

Used to measure similarity between query and documents:
cos(θ) = (A · B) / (||A|| × ||B||)

* A = Query vector
* B = Document vector
* Value ranges from 0 to 1
  
# Tech Stack

* Python
* Jupyter Notebook
* JSON (for dataset storage)


# Project Structure

```
search-engine-project/
│
├── main.ipynb            # Main code
├── database.json         # Dataset
└── README.md             # Documentation
```

# How to Run

1. Clone the repository:

```
git clone https://github.com/Swetalin26/search-engine-project.git
```

2. Go to project folder:

```
cd search-engine-project
```

3. Open Jupyter Notebook:

```
jupyter notebook
```

4. Run `search_engine.ipynb`

---

## 🧪 Example Queries

* machine learning
* climate change
* blockchain AND cryptocurrency
* mental health
* stock market

## Learning Outcomes

* Understanding Vector Space Model
* Implementing TF-IDF
* Building search using inverted index
* Applying Boolean logic in search
* Improving user experience with enhancements

# Future Improvements

* Web interface (React / Next.js)
* Better ranking using NLP
* Voice-based search
* Real-time data integration

  
# Author

**Swetalin Sahoo**
B.Tech Student | Aspiring Developer


# Note

This is a beginner-friendly project that demonstrates how modern search engines rank and retrieve information.
