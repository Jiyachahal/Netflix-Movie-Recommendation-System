# Netflix-Movie-Recommendation-System
The Netflix Movie Recommendation System uses content-based filtering to suggest movies based on user preferences. Features such as genre, cast, and keywords are analyzed to compute similarities using techniques like cosine similarity. This system efficiently personalizes recommendations for enhanced user experience.


## Overview

The system includes:
- **Data Preprocessing**: Cleaning and merging movie and credits datasets.
- **Feature Selection**: Extracting key attributes like genres, cast, and keywords.
- **Recommendation Engine**: Using cosine similarity to find similar movies.

## Dataset

The datasets used in this project are too large to include in the repository but can be downloaded from Kaggle:
- **tmdb_5000_movies.csv**: Contains movie metadata such as genres, budget, and overview.
- **tmdb_5000_credits.csv**: Includes cast and crew details for the movies.

You can download these datasets from Kaggle [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

## Results

The recommendation engine suggests movies based on the input movie, leveraging feature similarities. For example, inputting "Avatar" recommends other action-packed, adventure-based, or sci-fi movies.

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Jiyachahal/Netflix-Movie-Recommendation-System.git
2. **Open and Run the Jupyter Notebook:**
    [View the Jupyter Notebook](./code.ipynb)

## Key Files 
- code.ipynb: Contains the workflow for data preprocessing, modeling, and evaluation.


## Dependencies
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- NLTK (for text preprocessing)

## Contributions 
Contributions are welcome. Fork the repo, make updates, and submit a pull request.


