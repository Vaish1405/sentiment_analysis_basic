# Sentiment Analysis on Amazon Fine Food Reviews  

This repository contains a sentiment analysis project focused on the **Amazon Fine Food Reviews dataset**. The goal of this project is to explore classical and modern natural language processing (NLP) techniques for sentiment classification, compare their performance, and visualize insights derived from textual data.  

---

## Overview  
Customer reviews contain valuable information about opinions and satisfaction. Sentiment analysis provides a way to extract these insights at scale. In this project, I:  

- Conducted exploratory data analysis (EDA) to understand the dataset  
- Applied **rule-based NLP techniques** using the VADER sentiment analyzer  
- Implemented **transformer-based deep learning models** (RoBERTa) for more context-aware sentiment detection  
- Compared the performance of traditional and transformer-based approaches  
- Visualized model outputs to highlight relationships between predicted sentiment and Amazon star ratings  

---

## Dataset  
- **Source:** [Amazon Fine Food Reviews (Kaggle)](https://www.kaggle.com/snap/amazon-fine-food-reviews)  
- **Size:** ~500,000 reviews (subset of 500 reviews used here for demonstration and computational efficiency)  

---

## Tools and Libraries  
- **Programming Language:** Python  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **NLP:** NLTK (tokenization, POS tagging, NER, VADER)  
- **Deep Learning:** Hugging Face Transformers (RoBERTa model)  

---

## Methodology  
1. **Exploratory Data Analysis (EDA):** Review distribution by star ratings and initial inspection of text  
2. **Classical NLP (NLTK):** Tokenization, part-of-speech tagging, and named entity recognition  
3. **Rule-based Sentiment Analysis (VADER):** Calculation of compound sentiment scores and comparison with review ratings  
4. **Transformer-based Analysis (RoBERTa):** Contextual sentiment classification using pretrained models  
5. **Model Comparison:** Evaluation of how VADER and RoBERTa differ in sentiment detection across positive, neutral, and negative reviews  
6. **Visualization:** Graphical representations of sentiment distribution and model outputs  

---

## Key Learnings  
Through this project, I strengthened my understanding of:  
- Differences between **rule-based** and **transformer-based** sentiment analysis  
- Preprocessing pipelines for text data, including tokenization, tagging, and named entity recognition  
- Interpreting model predictions through visualization  
- Practical usage of Hugging Face Transformers for downstream NLP tasks  
- The limitations of out-of-the-box models and opportunities for domain-specific fine-tuning  
