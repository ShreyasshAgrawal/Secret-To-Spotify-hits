# 🎵 Secret To Spotify Hits

## 📌 Project Overview
This project explores what makes a song a hit on Spotify using data analysis and clustering techniques.  

The goal is to analyze musical features and engagement metrics to identify hidden patterns behind popular tracks.

---

## 📊 Dataset Features
The dataset includes attributes such as:

- Track Name
- Artist
- Duration
- Release Year
- Decade
- Engagement Metrics
- Audio Features (danceability, energy, etc.)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn
- Missingno
- Pycountry

---

## 📈 Project Workflow

1. Data Cleaning
   - Removed unnecessary columns
   - Handled missing values
   - Standardized formats

2. Exploratory Data Analysis (EDA)
   - Distribution of features
   - Engagement trends over decades
   - Correlation analysis
   - Visual insights using Plotly & Seaborn

3. Feature Engineering
   - Duration conversions
   - Decade extraction
   - Engagement metrics

4. Clustering
   - Standardization using `StandardScaler`
   - Dimensionality reduction using `PCA`
   - K-Means clustering
   - Evaluation using Silhouette Score

---

## 🔍 Key Insights

- Identified distinct clusters of songs based on musical features.
- Observed patterns in engagement trends across decades.
- Certain audio features show a strong correlation with popularity.

---

## ▶️ How to Run This Project

### Option 1: Google Colab
1. Open in Colab
2. Install required libraries:
   ```python
   !pip install pandas numpy seaborn matplotlib plotly missingno scikit-learn pycountry
