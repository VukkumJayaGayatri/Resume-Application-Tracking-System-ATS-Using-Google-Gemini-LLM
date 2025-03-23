📘 Project Title
Smart ATS: AI-Powered Resume Analysis and Job Matching System

🚀 Project Overview
Smart ATS is an AI-driven application that analyzes resumes against job descriptions using NLP and TF-IDF Vectorization. The system evaluates the match percentage, identifies missing keywords, and provides actionable profile summary suggestions to enhance the resume for a better alignment with the job role.

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

Google Gemini API (optional for further improvements)

⚙️ Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/VukkumJayaGayatri/smart-ats.git
cd smart-ats
Create a Virtual Environment

bash
Copy
Edit
python -m venv env
source env/bin/activate # For Linux/macOS
env\Scripts\activate    # For Windows
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Download and Install Poppler (Required for PDF Parsing)

Download Poppler

Extract and add the bin folder to your Path in Environment Variables.

🛎 How to Run
bash
Copy
Edit
streamlit run app.py
Upload your resume in PDF format.

Paste the job description.

Click Submit to get insights into the match score, missing keywords, and profile suggestions.

📌 Example Output
json
Copy
Edit
{
  "JD Match": "72.45%",
  "MissingKeywords": ["tensorflow", "kubernetes", "cloud", "microservices"],
  "Profile Summary": "Your profile summary is decent but could be stronger. Quantify your accomplishments and tailor it to mirror the job description's key requirements, using some of the missing keywords."
}
🛡 Troubleshooting
PDFInfoNotInstalledError: Ensure poppler is installed and added to Path.

Google Gemini API Error: Ensure you are using gemini-1.5-flash or a supported model.

ModuleNotFoundError: Run pip install -r requirements.txt to install all dependencies.
