# AI-Recruitment-Classifier
NLP solution to enhance recruitment efficiency by classifying job description sentences and ranking CVs.

# 🚀 AI Recruitment Classifier - Smart Hiring Solution

## 📌 Overview
AI Recruitment Classifier is an **AI-driven recruitment solution** that streamlines job description classification and CV ranking. Using **Natural Language Processing (NLP)** and **Machine Learning**, this project aims to:
- **Structure job descriptions** into key categories.
- **Reduce CV screening time** from **days to minutes**.
- **Improve job-candidate matching** using AI recommendations.

## 🎯 Problem Statement
Recruitment processes often struggle with **unstructured job descriptions** and **lengthy CV screening**, making it difficult to assess candidate-job fit. This project tackles these issues by:
✅ **Classifying job description sentences** into structured categories (Responsibilities, Skills, Experience, etc.).  
✅ **Automating CV screening & ranking** using **Machine Learning & AI**.  
✅ **Speeding up hiring decisions** through AI-powered HR assistance.

## 📊 Dataset & Preprocessing
- **Dataset**: 60,115 job description sentences.
- **Preprocessing**: Text normalization, tokenization, stopword removal, stemming, and lemmatization.
- **Feature Engineering**: TF-IDF vectorization, sentiment scoring, and word count analysis.

## 🏆 Business Impact
📉 **99.73% reduction in CV screening time** (from 5-10 days to minutes).  
📈 **25% increase in candidate placement rate**.  
💡 **STEM-related skills** dominate job descriptions, influencing recruitment trends.

## 🛠️ Technologies Used
- **Python, Pandas, NumPy**  
- **Scikit-learn (Logistic Regression, SVM, Naïve Bayes)**  
- **NLP (TF-IDF, Tokenization, Lemmatization)**  
- **OpenAI API (GPT-3.5 & GPT-4 for job classification & recommendations)**  
- **Streamlit (Web Deployment for CV & Job Matching)**  

## 📌 Model Performance
| Model                     | Train Accuracy | Test Accuracy | Status |
|---------------------------|---------------|--------------|--------|
| **Logistic Regression**   | 81.7%         | 76.5%        | ✅ Best Fit |
| **Support Vector Machine**| 87.7%         | 75.6%        | ⚠ Slight Overfitting |
| **Naïve Bayes**           | 74.0%         | 69.8%        | ⚖ Balanced |
| **OpenAI GPT-3.5**        | 81.0%         | 83.3%        | ⭐ Best for Innovation |

## 🎯 Features
✅ **Job Description Classification**: AI categorizes job descriptions into key areas.  
✅ **AI-powered CV Analysis**: Evaluates and ranks CVs based on job relevance.  
✅ **HR AI Chatbot**: Assists job seekers with CV improvement and job matching.  
✅ **Bigram & Trigram Analysis**: Identifies important skill trends in recruitment.  

## 🚀 Deployment
The system is deployed via **Streamlit** for interactive AI-based recruitment analysis.  
🔗 **Live Demo**:https://finpronautixtech.streamlit.app/
