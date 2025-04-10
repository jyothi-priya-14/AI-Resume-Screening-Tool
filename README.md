# 🧠 AI Resume Screening Tool

## 📌 Description

This is an AI-powered Resume Screening Tool that automates the evaluation of resumes by comparing them against a given job description using Natural Language Processing (NLP) and Machine Learning techniques.

It helps recruiters quickly identify the best candidates by ranking resumes based on similarity scores and keyword matching.

---

## 🚀 Features

- 📄 Upload resumes in `.pdf` and `.docx` formats
- 🔍 Extract text from resumes using `pdfminer` and `docx2txt`
- 🧠 Compare resumes with job descriptions using pre-trained NLP models (`sentence-transformers`)
- 📊 Generate a match score to evaluate candidate-job fit
- 📝 Summarize key content and extract skills, experience, and education
- 🖥️ Web interface built with Streamlit for easy interaction

---

## 🛠️ Tech Stack

- **Python 3**
- **NLP Libraries**:
  - `sentence-transformers`
  - `nltk`
- **Parsing Libraries**:
  - `pdfminer.six`
  - `docx2txt`
- **Web Framework**:
  - `Streamlit`
- **Others**: `Pandas`, `NumPy`, `sklearn`, `os`, `re`

---

## 📷 Sample Output

- ✅ Resume uploaded successfully  
- ✅ Text extracted from document  
- ✅ Job description provided  
- ✅ Match Score: **82.3%**  
- ✅ Candidate suitability: **Strong fit**

---

## 🧪 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/AI_Resume_Screening_Project.git
cd AI_Resume_Screening_Project/resume_screening

# (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate         # On Linux/Mac: source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
 
