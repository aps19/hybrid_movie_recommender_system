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
2. Unzip to `ml-25m` in the project root. Ensure CSV files are inside.

**Usage**
- Run `rc.ipynb`.
- Follow comments in the notebook for guidance.

**Features**
- Data merging and preprocessing.
- Exploratory analysis with basic stats and plots.
- Recommendation models using Surprise and Scikit-Learn.
- Output predictions to CSV.

**Models**
- Utilizes SVD, SVDpp from Surprise, and TfidfVectorizer from Scikit-Learn.
- Implements a hybrid recommendation model.

**Visualizations**
- Generate plots using matplotlib and plotly (if uncommented).

**License**
- MIT License. See LICENSE file.
