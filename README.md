# Spam Email Classification

This project builds a **supervised machine learning model** to classify email messages as **spam or ham (not spam)** using text-based features and logistic regression.  
The dataset, derived from the **SpamAssassin public corpus**, was cleaned, vectorized, and modeled to explore practical applications of **natural language processing (NLP)** and text classification.

---

## Project Overview
The goal of this project was to develop an interpretable model that accurately distinguishes spam from legitimate email by:
- Cleaning and preprocessing raw email text.  
- Engineering features such as word frequency, capitalization ratio, punctuation density, and HTML tags.  
- Applying **TF-IDF vectorization** for numerical representation.  
- Training and evaluating multiple models for optimal performance.

---

## Key Features
- **Text Preprocessing:** tokenization, stop-word removal, and TF-IDF feature extraction.  
- **Feature Engineering:** numerical signals for HTML presence, punctuation ratio, and capitalization use.  
- **Modeling:** compared Logistic Regression, Naïve Bayes, and Random Forest classifiers.  
- **Validation:** used 10-fold cross-validation, ROC analysis, and confusion matrices to assess model balance and reliability.  

---

## Tech Stack
**Languages:** Python  
**Libraries:** scikit-learn, Pandas, NumPy, Seaborn, Matplotlib  
**Tools:** Jupyter Notebook  

---

## Results
- Achieved **~87% validation accuracy** and **86–89% consistency across 10-fold CV**.  
- Logistic Regression provided the best generalization and interpretability.  
- Feature analysis revealed strong spam signals in capitalization, HTML content, and specific token frequency.

---

## Future Improvements
- Implement ensemble methods (e.g., XGBoost) for higher accuracy.  
- Experiment with word embeddings (Word2Vec, BERT) for richer semantic representation.  
- Deploy as a Streamlit app for interactive email classification demos.

---

## Dataset
This project uses a publicly available spam dataset from spam assasin https://spamassassin.apache.org/old/publiccorpus/

---

## Author
**Arvin Ayati**  
📍 University of California, Berkeley  
🔗 [LinkedIn](https://linkedin.com/in/arvin-ayati-6b4288265/) | [GitHub](https://github.com/Hire-Arvin)

---
