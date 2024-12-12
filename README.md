# 🎵 Spotify 1 Million Tracks Dataset Analysis 🎧

## 🌟 Project Overview
This project involves an in-depth analysis of the Spotify 1 Million Tracks dataset, exploring various aspects of music tracks including genre distribution, artist contributions, popularity trends, and audio feature characteristics.

## 💿 Dataset
- **Source**: Kaggle (Spotify_1Million_Tracks)
- **Size**: 1 million music track records

## 🔍 Key Analysis Steps

### 🧹 Data Preprocessing
- Read CSV file containing 1 million records
- Data exploration and validation
  - View dataset structure
  - Check column data types
  - Identify and handle null values
- Data cleaning techniques applied

### 📊 Numerical Analysis
Comprehensive statistical analysis including:
- Descriptive statistics (count, mean, standard deviation, min, max)
- Visualization techniques:
  - Histograms
  - Box plots
  - Density plots for key features

### 🕵️ Outlier Detection and Handling
Multiple techniques explored:
- Winzorization
- Interquartile Range (IQR)
- Z-score
- K-Nearest Neighbour (KNN) outlier removal

### 🎼 Feature Analysis
Detailed examination of musical attributes:
- Correlation matrix
- Feature trends over time
- Specific feature analyses:
  - 🥁 Tempo
  - ⚡ Energy
  - 💃 Danceability
  - 🎹 Acousticness
  - ⏱️ Duration
  - 🗣️ Speechiness
  - 🎻 Instrumentalization
  - 📝 Time signature trends

### 🎤 Genre and Artist Insights
- Top genres identification
- Artist contribution analysis
- Popularity trends visualization
- Heatmap of artist popularity

### 🤖 Machine Learning Techniques
- K-means clustering
  - Clustering 82 genres into 10 broader categories
- Recommendation system
  - Cosine similarity for track recommendations
- One-hot encoding of genre names

## 📈 Visualizations
The project includes several key visualizations:
1. 🎨 Artist Track Contribution Chart
   - Tracks by top artists over multiple years
   - Color-coded by year of release
2. 🌈 Artist Popularity Heatmap
   - Average popularity of top artists
3. 📊 Top 10 Genres Bar Chart
   - Genres ranked by track count

## 🔑 Key Observations
- Identification of dominant artists and their contribution patterns
- Genre diversity and distribution
- Popularity trends across different years
- Musical feature variations

## 💻 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
