# 🎬 Movie Recommendation System

A smart and interactive **Movie Recommendation System** built using modern technologies like FastAPI and Streamlit. This project suggests movies based on user preferences using NLP techniques and similarity algorithms.

---

## 🚀 Features

* 🔍 Search for movies and get instant recommendations
* 🤖 Content-based filtering using **cosine similarity**
* 🧠 NLP preprocessing (stopword removal & lemmatization)
* ⚡ Fast backend powered by FastAPI
* 🎨 Interactive frontend built with Streamlit
* 🎥 Movie data fetched using TMDB API

---

## 🛠️ Tech Stack

* **Backend:** FastAPI
* **Frontend:** Streamlit
* **API:** TMDB (The Movie Database API)
* **Machine Learning:**

  * Cosine Similarity
  * Natural Language Processing (NLP)
* **NLP Techniques:**

  * Stopword Removal
  * Lemmatization

---

## 📂 Project Structure

```
project/
│── app.py                # Streamlit frontend
│── main.py              # FastAPI backend
│── model.pkl            # Trained similarity model
│── data/                # Movie dataset
│── utils.py             # Helper functions
│── requirements.txt     # Dependencies
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

2. Create virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Start FastAPI backend:

```bash
uvicorn main:app --reload
```

### Run Streamlit frontend:

```bash
streamlit run app.py
```

---

## 🔑 API Setup (TMDB)

1. Create an account on TMDB
2. Generate your API key
3. Add it to your project:

```python
API_KEY = "your_tmdb_api_key"
```

---

## 🧠 How It Works

1. Movie metadata is preprocessed using NLP techniques:

   * Removing stopwords
   * Applying lemmatization

2. Text data is converted into vectors.

3. Cosine similarity is calculated between movies.

4. When a user selects a movie:

   * The system finds similar movies
   * Fetches posters/details from TMDB API
   * Displays results via Streamlit

---

## 📸 Screenshots

*Add screenshots of your app here*

---

## 📌 Future Improvements

* Add collaborative filtering
* Improve recommendation accuracy
* Deploy using Docker / Cloud
* Add user authentication

---

## 🤝 Contributing

Feel free to fork this repo and contribute!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 💡 Author

Your Name
GitHub: https://github.com/your-username
