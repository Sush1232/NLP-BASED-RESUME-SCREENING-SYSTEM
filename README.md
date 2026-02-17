# 🚀 AI-Based ATS Resume Screening System

An AI-powered Applicant Tracking System (ATS) built using Python and NLP techniques to automatically rank resumes based on a Data Science job description.

This system extracts text from multiple PDF resumes, compares them with a predefined job description using TF-IDF and Cosine Similarity, and generates a final weighted ATS score.

---

## 📌 Project Objective

The goal of this project is to simulate a real-world ATS system that:

- Automatically processes multiple resumes
- Evaluates candidate relevance to a job description
- Uses hybrid scoring (semantic + keyword matching)
- Ranks candidates based on overall suitability

---

## 🧠 How It Works

1. Upload ZIP file containing multiple resumes
2. Extract PDF files automatically
3. Extract text from each resume using PDFPlumber
4. Clean and preprocess text data
5. Convert text into TF-IDF vectors
6. Calculate cosine similarity between resume and job description
7. Perform skill-based keyword matching
8. Compute final ATS score using weighted formula
9. Rank candidates in descending order

---

## 📊 Scoring Mechanism

The final ATS score is calculated using:

Final ATS Score =  
(0.6 × TF-IDF Similarity) + (0.4 × Skill Match Score)

Where:

- TF-IDF Similarity measures semantic relevance
- Skill Match Score ensures required technical keywords are present

This hybrid approach improves ranking reliability compared to using cosine similarity alone.

---

## 🛠️ Technologies Used

- Python
- PDFPlumber (PDF text extraction)
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Regular Expressions
- Google Colab

---

## 📂 Features

- Upload multiple resumes in ZIP format
- Automatic folder detection
- Multi-page PDF support
- Text preprocessing
- Hybrid ATS scoring
- Resume ranking system
- Display of matched skills

---

## 📌 Built-in Job Role

This project includes a predefined **Data Scientist** job description with required skills such as:

- Python
- Machine Learning
- Deep Learning
- NLP
- SQL
- Pandas
- NumPy
- Scikit-learn
- Data Analysis
- Model Deployment

---

## 📊 Example Output
🚀 DATA SCIENCE ATS RANKING:

Rank 1: Candidate_Name
TF-IDF Similarity: 52.34%
Skill Match: 80.00%
Final ATS Score: 63.40%
Matched Skills: ['python', 'machine learning', 'sql', 'pandas']



---

## 🚀 Future Improvements

- Implement BERT-based semantic similarity
- Add experience detection (years of experience)
- Detect missing skills automatically
- Export results to CSV
- Convert into Streamlit web application
- Deploy on cloud platform

---

## 👨‍💻 Author

Sushil Suresh Mandhare  
Aspiring Data Scientist | Machine Learning Enthusiast

---

## ⭐ If You Found This Useful

Give this repository a star ⭐

