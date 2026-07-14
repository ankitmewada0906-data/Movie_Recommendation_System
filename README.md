# 🎬 Movie Recommendation System

## Overview
This project builds a Movie Recommendation System using
Content-Based Filtering and Collaborative Filtering techniques.

## Dataset
- **MovieLens Small Dataset** (GroupLens)
- 9,742 Movies
- 100,836 Ratings
- 610 Users

## Techniques Used

### 1. Content-Based Filtering
- TF-IDF Vectorizer
- Cosine Similarity
- Recommends similar movies based on genres

### 2. Collaborative Filtering
- SVD (Singular Value Decomposition)
- Recommends movies based on user behavior

## Model Results
| Metric | Value |
|--------|-------|
| RMSE | 0.8807 |
| MAE | 0.6766 |

## Steps
1. Data Loading
2. Null & Duplicate Check
3. EDA (Exploratory Data Analysis)
4. Content-Based Filtering
5. Collaborative Filtering (SVD)
6. Model Evaluation

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scikit-surprise

## How to Use
### Content Based
```python
get_recommendations('Toy Story (1995)')
```
### Collaborative
```python
get_svd_recommendations(1)
```