# IMDb Movie Review Sentiment Analysis using NLP and Machine Learning

## Project Overview

This project was developed as part of the **Horizon TechX Artificial Intelligence & Data Science Internship Program (Task 6: Sentiment Analysis)**.

The objective of this project is to analyze movie reviews and classify them as **Positive** or **Negative** using Natural Language Processing (NLP) and Machine Learning techniques. The project demonstrates text preprocessing, feature extraction, sentiment classification, model evaluation, and visualization of results.

---

## Problem Statement

Online platforms receive thousands of customer reviews every day. Manually analyzing these reviews is time-consuming and inefficient. This project automates sentiment detection by applying machine learning algorithms to classify reviews based on their emotional tone.

---

## Dataset Information

**Dataset:** IMDb 50K Movie Reviews Dataset

Dataset Features:

* Total Reviews: 50,000
* Positive Reviews: 25,000
* Negative Reviews: 25,000
* Columns:

  * Review
  * Sentiment

Due to GitHub file size limitations, the dataset is not included in this repository.

Dataset Source:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Natural Language Processing (NLP)

---

## Project Workflow

### 1. Data Collection

Loaded the IMDb movie review dataset containing labeled positive and negative reviews.

### 2. Data Exploration

* Checked dataset dimensions
* Verified data types
* Identified missing values
* Examined class distribution

### 3. Data Preprocessing

* Converted sentiment labels into numerical values
* Prepared text data for machine learning

### 4. Feature Extraction

Applied **TF-IDF Vectorization** to convert text reviews into numerical feature vectors.

### 5. Model Training

Used **Logistic Regression** for sentiment classification.

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 7. Data Visualization

Created visualizations to understand sentiment distribution and model performance.

---

## Machine Learning Model

### Logistic Regression

Logistic Regression was selected because:

* Efficient for text classification
* High interpretability
* Strong performance on NLP tasks
* Fast training time

---

## Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

Expected Accuracy Range:

**89% – 92%**

---

## Visualizations

### Sentiment Distribution

Displays the number of positive and negative reviews in the dataset.

### Confusion Matrix

Visual representation of classification performance.

---

## Key Findings

* The dataset contains a balanced distribution of positive and negative reviews.
* TF-IDF successfully transformed text data into meaningful numerical features.
* Logistic Regression achieved high classification accuracy.
* Sentiment analysis can be effectively used to understand customer opinions and feedback.

---

## Business Applications

Sentiment Analysis can be applied in:

* Customer Feedback Analysis
* Product Review Monitoring
* Brand Reputation Management
* Social Media Analytics
* Market Research
* Customer Experience Improvement

---

## Skills Demonstrated

* Data Analysis
* Natural Language Processing (NLP)
* Machine Learning
* Text Classification
* Feature Engineering
* Data Visualization
* Model Evaluation
* Python Programming

---

## Repository Structure

HorizonTechX_Sentiment_Analysis/

├── sentiment_analysis.py

├── README.md

├── Project_Report.docx

├── sentiment_distribution.png

├── confusion_matrix.png

└── screenshots/

---

## Future Enhancements

* Implement Deep Learning models such as LSTM
* Use Word Embeddings (Word2Vec, GloVe)
* Build a Streamlit Web Application
* Perform Multi-Class Sentiment Analysis
* Deploy the model using Flask or FastAPI

---

## Conclusion

This project successfully demonstrates the use of Natural Language Processing and Machine Learning for sentiment classification. The developed model can automatically analyze customer reviews and classify them as positive or negative, helping organizations make data-driven decisions based on customer feedback.

---

## Author

Manas Aswal

GitHub: https://github.com/Manas0028

LinkedIn: https://www.linkedin.com/in/manas-aswal-704876288

---

## Internship

Horizon TechX Artificial Intelligence & Data Science Internship Program

Task 6 – Sentiment Analysis
