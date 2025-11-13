# Sentiment Analysis Project Using NLP

## Author
**Fatima Rashid**

## Project Overview
This project focuses on **Sentiment Analysis** using **Natural Language Processing (NLP)** techniques to analyze textual data. The goal is to classify text into **Positive, Negative, and Neutral sentiments** and gain insights into public opinion, customer feedback, or social media trends.

## Dataset
The project uses a text dataset with two main columns:  
- `clean_text`: The text of tweets, reviews, or comments.  
- `category`: Sentiment labels (1 = Positive, 0 = Neutral, -1 = Negative).  

> No external dataset links are included.

## Steps Implemented

1. **Data Loading**  
   Load the CSV dataset into a Pandas DataFrame.

2. **Data Cleaning**  
   - Remove missing values and duplicates.  
   - Clean text by removing special characters, numbers, and unwanted symbols.  

3. **NLP Analysis**  
   - Tokenization: Splitting text into words.  
   - Stopwords Removal: Removing common words that do not carry sentiment.  
   - Lemmatization: Converting words to their root forms.  

4. **Feature Extraction**  
   - Convert text into numerical features using **TF-IDF vectorization**.

5. **Model Training**  
   - Use **Naive Bayes classifier** to classify sentiments.  

6. **Evaluation & Prediction**  
   - Split data into training and testing sets.  
   - Evaluate model performance using accuracy and other metrics.  

7. **Visualization**  
   - Bar charts to show sentiment distribution.  
   - Word clouds for overall and category-specific text visualization.  

## Tools & Libraries Used
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- NLTK (Natural Language Toolkit)  
- Matplotlib, Seaborn  
- WordCloud  

## Conclusion
This project demonstrates the power of **NLP and machine learning** to extract actionable insights from unstructured text data. The analysis can help organizations understand public sentiment, improve customer engagement, and make data-driven decisions.  

---

**Author:** Fatima Rashid
