📘 Project Title
Smart ATS: AI-Powered Resume Analysis and Job Matching System

🚀 Project Overview
Smart ATS is an AI-driven application that analyzes resumes against job descriptions using NLP and TF-IDF Vectorization. The system evaluates the match percentage, identifies missing keywords, and provides actionable profile summary suggestions to enhance the resume for a better alignment with the job role.

1. Field to put my JD
2. Upload pdf
3. pdf to Image -->  processing --> Google Gemini Pro
4. While converting pdf to image , facing poppler setup issues like pdf not found
5. so, take pdf extrach text and create ats system
6. Prompts Template

🛠 Features
📊 Resume vs JD Match: Calculates a match percentage using TF-IDF Cosine Similarity.

🔎 Missing Keywords Detection: Identifies important keywords from the JD that are absent in the resume.

📝 Profile Summary Suggestions: Offers personalized suggestions to improve the resume content.

📥 PDF Resume Support: Extracts text from PDF resumes using PyPDF2.

🧑‍💻 Tech Stack
Python

Scikit-Learn for TF-IDF Vectorization

Streamlit for UI

PyPDF2 for PDF parsing

Regular Expressions (re) for text cleaning

Google Gemini API

📌 Example Output
json
Copy
Edit
{
  "JD Match": "72.45%",
  "MissingKeywords": ["tensorflow", "kubernetes", "cloud", "microservices"],
  "Profile Summary": "Your profile summary is decent but could be stronger. Quantify your accomplishments and tailor it to mirror the job description's key requirements, using some of the missing keywords."
}
