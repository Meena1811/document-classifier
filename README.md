# Document Classifier

A text classification model built with scikit-learn that categorizes documents into topics using TF-IDF features and Logistic Regression.

## Dataset
20 Newsgroups dataset (20 categories, ~18,000 documents).

## Approach
1. Text preprocessing and TF-IDF vectorization (unigrams + bigrams)
2. Logistic Regression classifier
3. Train/test split with stratification (80/20)

## Results
- Accuracy: 0.73
- Weighted F1-score: 0.73

## Files
- `Untitled23.ipynb` - notebook with full training, evaluation, and prediction code

## How to Run
Open the notebook in Google Colab and run all cells. Dependencies (scikit-learn, joblib) are installed via the first cell.
