# News Classification: Text Mining & Analysis

This repository contains the code and data for a multiclass news article classification project using text mining techniques and machine learning algorithms. The project aims to classify news articles into categories such as politics, sports, business, and entertainment, applying various preprocessing steps and comparing the performance of different machine learning models.

## Project Structure

- `1a. scraped_raw.csv`: Contains the raw, unprocessed news article data scraped from different media sources.
- `1b. scraped_cleaned.csv`: Contains the cleaned and preprocessed news article data after applying steps like tokenization, stemming, and lemmatization.
- `2. TM_UTS_2502042164.ipynb`: Jupyter notebook containing the entire codebase for the project. This includes web scraping, text preprocessing, text representation, and machine learning model implementation.

## Key Features

- **Data Collection**: Web scraping news articles from multiple sources.
- **Text Preprocessing**: Cleaning and preprocessing the text data through techniques like tokenization, stemming, and lemmatization.
- **Text Representation**: Implementing TF-IDF and word vectorization to transform the text into a suitable format for machine learning.
- **Machine Learning Models**: Comparing the performance of Support Vector Machines (SVM) and Random Forest models for multiclass classification.
- **Model Evaluation**: Evaluating the models using metrics such as accuracy, precision, recall, and F1-score.

## Usage

1. Download or clone the repository.
2. Open the `TM_UTS_2502042164.ipynb` notebook.
3. Execute the cells in the notebook to:
   - Load and preprocess the raw data.
   - Train the machine learning models (SVM and Random Forest).
   - Evaluate the model performance.
4. Review the results and compare the models based on performance metrics.

## Results

The project compares the performance of different text representation methods and classification models. Detailed results can be found in the notebook, where the performance of SVM and Random Forest models is summarized using various metrics.
