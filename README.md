# 📘 **README.md**

```markdown
# 🎬 Movie Recommender Demo (AI Workshop)

This project contains a small, educational example showing **how a movie recommendation system works**, similar to the techniques used by platforms like Netflix.

It is designed for **AI workshops, presentations, and hands-on demonstrations**, where participants learn:

- What data powers recommender systems  
- How content-based filtering works  
- How collaborative filtering and matrix factorization work  
- How user and item embeddings are learned  
- How hybrid recommendation systems combine multiple signals  
- How to visualize similarity using heatmaps  

The core demo is implemented as a **Jupyter notebook** and uses a tiny dataset for clarity.

---

## 🚀 Features

- Tiny built-in movie dataset with genres  
- User ratings matrix  
- Popularity-based recommendations  
- Content-based filtering using cosine similarity  
- Collaborative filtering via matrix factorization (implemented from scratch)  
- Hybrid recommender combining both approaches  
- Heatmap visualization of movie similarity  
- Clear markdown explanations for each step  

Perfect for showing *“what’s behind AI”* without overwhelming the audience.

---

## 📁 Project Structure

```

movie-recommender-demo/
│
├─ pyproject.toml          # Project & dependency configuration (uv)
├─ README.md               # You are here
└─ notebooks/
└─ netflix_recommender_demo.ipynb

````

---

## 🧰 Dependencies

Dependencies are managed using **uv**.

Required libraries:

- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- ipykernel  

Everything is already defined inside `pyproject.toml`.

---

## ⚙️ Installation (with uv)

1. Install uv (if you don’t have it already):

```bash
pip install uv
````

2. Sync dependencies and create the virtual environment:

```bash
uv sync
```

3. Register the kernel for Jupyter:

```bash
uv run python -m ipykernel install --user --name movie-recommender-demo
```

---

## 📓 Running the Notebook

Start Jupyter Lab:

```bash
uv run jupyter lab
```

Or classic notebook interface:

```bash
uv run jupyter notebook
```

Then open:

```
notebooks/netflix_recommender_demo.ipynb
```

Select the kernel:

**movie-recommender-demo**

---

## 🎨 What You’ll Learn

Inside the notebook, you will see step-by-step examples of:

### 🔹 1. Content-Based Filtering

* One-hot encoding movie genres
* Computing cosine similarity between movies
* Visualizing similarity using a heatmap

### 🔹 2. Collaborative Filtering

* Constructing a user–item ratings matrix
* Implementing matrix factorization from scratch
* Learning user and movie embeddings

### 🔹 3. Hybrid Recommendations

* Combining collaborative and content scores
* Ranking movies for each user

---

## 🎯 Purpose

This project is meant for:

* AI introductions
* University or company workshops
* Demos showing how neural networks relate to real use cases
* Explaining “how Netflix recommends movies”
* Teaching embeddings and similarity search

The dataset is intentionally tiny so you can focus on **concepts**, not big-data engineering.

---

## 📜 License

This educational project is provided for workshop and teaching purposes.
Feel free to modify, share, or include it in your materials.
