ATS Tracking System

An AI-powered Applicant Tracking System (ATS) designed to analyze resumes against job descriptions. It provides an overall match percentage, identifies missing keywords, and offers personalized suggestions to optimize resumes for specific roles.

1. Field to put my JD
2. Upload pdf
3. pdf to Image -->  processing --> Google Gemini Pro
4. Prompts Template

🚀 Features

Resume Parsing: Extracts text from PDF resumes using PDFMiner.

Job Description Analysis: Processes job descriptions using NLP techniques.

Keyword Extraction: Identifies missing keywords based on job description analysis.

Profile Improvement Suggestions: Provides actionable recommendations to enhance resumes.

🧑‍💻 Tech Stack

Python: Core language

Streamlit: Web framework

PDFMiner: PDF text extraction

🛠 Installation

Follow these steps to set up the project locally:

# Clone the repository
git clone https://github.com/VukkumJayaGayatri/Smart-ATS-AI-Powered-Resume-Analysis-Using-Google-Gemini-LLM.git

# Navigate to the project directory
cd ATS-Tracking-System

# Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

🧑‍💻 Usage

Run the Application:

streamlit run app.py

Access the Web Interface:

Open a browser and go to http://localhost:5000

Upload Resume and Job Description:

Upload your PDF resume.

Paste the job description.

Get Results:

View the match percentage.

Check missing keywords.

Receive personalized improvement suggestions.

📊 Example Output

Percentage Match: 90%

Missing Keywords: LangChain, OpenAI API, LlamaIndex

Profile Summary Suggestions: Add experience with LangChain and OpenAI API. Emphasize AI-powered business process automation.
