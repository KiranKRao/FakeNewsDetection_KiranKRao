Fake News Detection

Semantic Classification using NLP & Machine Learning
(Project by: Kiran Kumar Rao)

📌 **Overview**

This project builds a machine learning model to classify news articles as real or fake using natural language processing. It uses semantic embeddings (Word2Vec) and evaluates multiple supervised learning models.

The goal is to create a reliable, scalable pipeline that can support real-world misinformation detection.

🎯 **Objectives**

Develop an end-to-end NLP pipeline for fake news classification

Use Word2Vec semantic embeddings for richer text representation

Train and compare supervised models (Logistic Regression, Decision Tree, Random Forest)

Evaluate model performance using accuracy, precision, recall, and F1-score

🏆 **Achievements**

Built a complete text-processing and classification workflow

Random Forest achieved ~80% accuracy, outperforming other models

Achieved strong precision–recall balance across all classes

Delivered visual insights such as confusion matrices and class-wise performance

🧠 **Project Workflow**
1. Data Preprocessing

Handled missing values

Cleaned text and removed noise

Normalized the corpus for consistent processing

2. Tokenization & Embedding

Used Word2Vec (Google News 300-dim) embeddings for semantic representation

3. Model Development

Logistic Regression

Decision Tree

Random Forest (best performer)

4. Model Evaluation

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Visual analysis of embeddings & word frequencies

📊 **Key Insights**

Ensemble methods outperform single models due to better generalization

Random Forest achieved the best trade-off between precision and recall

Logistic Regression showed moderate performance (~71%)

Decision Trees underperformed compared to the ensemble model

🖼️ **Visual Summary**

A performance comparison chart (from your report) shows Random Forest leading across precision, recall, and F1-scores for different news classes.

(If you'd like, I can embed the image directly into the README.md.)

🚀 **Next Steps**

Integrate deep learning: LSTM, Bi-LSTM, BERT, RoBERTa

Use larger datasets for improved generalization

Apply hyperparameter tuning

Deploy the model as a web app or REST API


📘 **Conclusion**

This project demonstrates how combining semantic embeddings with ensemble learning can create an effective fake news classification system. Random Forest delivered strong performance (~80% accuracy), making it a practical choice for real-world applications.

Future work will focus on deep learning approaches and model deployment.
