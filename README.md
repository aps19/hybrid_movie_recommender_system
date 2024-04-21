### Hybrid Movie Recommendation System

**Overview**
- This project uses the MovieLens 25M dataset.
- Functions include data processing, exploratory analysis, and movie recommendations using machine learning.

**Installation**
```bash
pip install pandas numpy scikit-learn surprise plotly matplotlib dask[complete]
```

**Data Setup**
1. Download MovieLens 25M from [MovieLens](https://grouplens.org/datasets/movielens/25m/).
2. Unzip `ml-25m.zip` in the project root. Ensure CSV files are inside.

**Usage**
- Run `rc_final.ipynb`.
- Run a single part at a time.
- Use `factor_of_data` variable to load only a subset of original MovieLens dataset.
- Follow comments in the notebook for guidance.

**Features**
- Data merging and preprocessing.
- Exploratory analysis with basic stats and plots.
- Recommendation models using Surprise and Scikit-Learn.
- Output predictions to CSV.

**Models**
- Models:
1. Popularity based model 
2. Content based model 
3. Collaborative Filtering
4. Matrix Factorization method
5. Combined model (SVD + CF) 
6. Hybrid model

**Similarity Metrics**
1. Cosine similarity
2. Mean square difference-based similarity.
3. Pearson coefficient (mean-centred cosine similarity)
4. Pearson Baseline (uses global baselines for centring instead of means)


**Visualizations**
- Generate plots using matplotlib and plotly (if uncommented).

**License**
- MIT License. See LICENSE file.
