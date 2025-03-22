# AI-resume-screening-system
An advanced AI-driven platform designed to revolutionize recruitment. This system uses NLP, OCR, and BERT embeddings to automate resume parsing, ranking, and bias-free evaluation. With a sleek and intuitive web interface built using Streamlit, it ensures faster and smarter hiring decisions.

cat <<EOF > README.md
# 🤖 AI-Powered Resume Screening and Ranking System  

Transform your recruitment process with this intelligent system designed to streamline resume screening, ensuring efficiency and objectivity in hiring.  

---

## 🌐 Live Demo  
🔗 Experience the system live: [AI Resume Screening System](https://github.com/rushikesh369/AI-resume-screening-system.git)  

---

## 📖 About the Project  
Recruitment can be time-consuming, but this project simplifies the process by:  
1. 🔍 Extracting vital details (Name, Email, Phone, Skills) from resumes.  
2. 📊 Comparing resumes to job descriptions using AI-powered embeddings.  
3. 🏅 Ranking resumes based on relevance to the job description.  
4. ⚖️ Providing unbiased and diversity-focused selection.  

---

## ✨ Features  
- 📤 Resume Upload: Supports PDF and image formats.  
- 📝 Job Description Input: Enter or upload job requirements.  
- 🤖 AI-Powered Ranking: Calculates similarity scores for resumes.  
- 🧾 Detail Extraction: Automatically extracts critical candidate information.  
- 🎯 User-Friendly UI: Built with Streamlit for a smooth experience.  

---

## 🛠️ Tech Stack  
- Frontend: Streamlit  
- Backend: Python  
- Core Libraries:  
  - 📄 PyPDF2 for extracting text from PDFs.  
  - 🖼️ Tesseract OCR for image text recognition.  
  - 🧠 spaCy for Named Entity Recognition (NER).  
  - 🔥 Sentence Transformers for embedding-based similarity.  
  - ⚙️ Torch for deep learning computations.  

---

## 🚀 Installation Guide  

### Prerequisites  
1. Install Python 3.8 or higher.  
2. Install Tesseract OCR:  
   - Linux: `sudo apt install tesseract-ocr`  
   - macOS: `brew install tesseract`  
   - Windows: [Tesseract OCR Download](https://github.com/tesseract-ocr/tesseract)  

### Steps to Set Up  
1. Clone the repository:  
   ```bash
   git clone https://github.com/rushikesh369/AI-resume-screening-system.git
   cd AI-resume-screening-system
