# Movie Recommendation System

This project implements a content-based movie recommender using TF-IDF vectorization and cosine similarity.

## Main Features

- Clean text preprocessing for movie plot descriptions
- TF-IDF vectorization for document representation
- Similarity ranking and top-N recommendations

## Dataset

- **Title:** Netflix Movies and TV Shows Dataset  
- **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **License:** CC0 1.0 Universal Public Domain Dedication

## Installation

Install the required packages using pip:

pip install -r requirements.txt


## Usage Example

from recommender import top_ten_sim

# 'df_recommend' is your preprocessed DataFrame, 'cosine_sim' is the similarity matrix
recommendations = top_ten_sim('Inception', df_recommend, cosine_sim)
print(recommendations)

See top_ten_recommend.ipynb for a full walkthrough.


## License

Software: MIT License

Dataset: CC0 1.0 Universal Public Domain Dedication


Feel free to use, modify, and share both code and data!





