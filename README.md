# 🎬 Movie Watch Pattern Clustering

This project applies unsupervised machine learning (KMeans clustering) to group users based on their movie-watching behavior. It aims to uncover patterns from user data such as watch time, genre preference, and rating behavior to enhance user segmentation and personalization.

---

## 📌 Problem Statement

Cluster users based on:
- ⏰ **Time of watching**
- 🎭 **Genre preference**
- ⭐ **Rating behavior**

This clustering can help streaming platforms or entertainment services provide better personalization and targeted recommendations.

---

## 🧪 Features Used
- `watch_time_hour` — hour of the day when the user watched a movie
- `genre_preference` — user’s preferred genre (e.g., Action, Comedy, Drama)
- `avg_rating_given` — average rating the user gave to movies

---

## 🧠 Methodology

1. **Data Upload**: Upload `movie_watch.csv` via Google Colab.
2. **Preprocessing**:
   - `StandardScaler` used for numeric features
   - `OneHotEncoder` used for genre (categorical) encoding
3. **Clustering**:
   - `KMeans` with 3 clusters (can be adjusted)
4. **Dimensionality Reduction**:
   - `PCA` used to reduce features to 2D for visualization
5. **Visualization**:
   - 2D scatter plot shows user clusters
6. **Export**:
   - Clustered data saved as `clustered_movie_watch.csv`

---

## 💻 Technologies Used

- Python
- Google Colab
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `IPython.display`

---

## 📷 Output

Below is a sample output visualization of clustered users:

> *(Insert image or link to screenshot here)*

Each dot represents a user, color-coded by the cluster assigned based on their viewing behavior.

---

## 📁 Files in Repository

| File                        | Description                                |
|----------------------------|--------------------------------------------|
| `movie_watch.csv`          | Sample dataset (not included - upload yours) |
| `cluster_analysis.ipynb`   | Colab notebook with full clustering pipeline |
| `clustered_movie_watch.csv`| Output file with cluster labels             |
| `README.md`                | Project documentation                       |

---

## 📚 References

- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Google Colab](https://colab.research.google.com)
- Dataset: Self-generated or academic sample for clustering demo

---

## 📎 How to Run

1. Open the Colab notebook `cluster_analysis.ipynb`.
2. Upload your `movie_watch.csv` file when prompted.
3. Run all cells.
4. View the scatter plot and download `clustered_movie_watch.csv`.

---

## ✅ Example Use Cases

- Building user profiles in movie recommendation systems
- Segmenting customers for targeted marketing
- Understanding user preferences for content strategy

---

Feel free to fork this repo, improve the clustering logic, or add more interactive features like dynamic cluster selection!
