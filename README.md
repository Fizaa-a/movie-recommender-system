# 🎬 Movie Recommender System

A beginner-friendly **Movie Recommendation System** built using **Python** and **Jupyter Notebook**. This project uses **content-based filtering** to suggest similar movies based on a selected title.

---

## 📚 Table of Contents

- [About](#about)
- [Project Files](#project-files)
- [How to Run](#how-to-run)
- [Example Output](#example-output)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Author](#author)

---

## 📖 About

This recommender system takes the name of a movie and returns a list of **5 similar movies** based on their:
- Genres
- Keywords
- Overviews (summaries)

It uses **TF-IDF** vectorization and **cosine similarity** to compute closeness between movies.

---

## 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `Movie_Recommender.ipynb` | Main Jupyter Notebook with the full project code |
| `movies.csv` | Dataset of movies used for generating recommendations |
| `README.md` | Documentation file for the project |

---

## 🚀 How to Run

### 1. Install Dependencies

You’ll need Python and Jupyter Notebook. Then install the required libraries:

```bash
pip install pandas numpy scikit-learn notebook
