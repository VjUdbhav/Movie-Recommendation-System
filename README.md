
# Movie Recommendation System

## Overview
A beginner-friendly content-based Movie Recommendation System using TF-IDF Vectorization and Cosine Similarity.

## Libraries
- NumPy
- Pandas
- difflib
- scikit-learn (TfidfVectorizer, cosine_similarity)

## Dataset
Place `movies.csv` inside the `dataset/` folder.

## Folder Structure
```text
Movie-Recommendation-System/
├── Movie_Recommendation_System.ipynb
├── README.md
├── dataset/
│   └── movies.csv
└── output/
```

## Setup
```bash
pip install numpy pandas scikit-learn jupyter
```

## Run
1. Place `movies.csv` in `dataset/`.
2. Open `Movie_Recommendation_System.ipynb`.
3. Run all cells.
4. Enter a movie title when prompted.

## Sample Output
```
Enter your favourite movie: Avatar

Top 10 Recommended Movies:
1. Guardians of the Galaxy
2. John Carter
...
```

## Future Improvements
- Genre-based recommendations
- Hybrid recommender
- Better text preprocessing
- Web interface using Flask or Streamlit
