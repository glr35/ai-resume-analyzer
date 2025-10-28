# ai-resume-analyzer
AI-powered Resume Analyzer built with Streamlit and Python
🧠 AI Resume Analyzer

AI-powered resume analysis tool built with Python, Streamlit, and Hugging Face APIs.
This project analyzes CVs and generates intelligent insights, improvement suggestions, and matching internship roles.

🚀 Features

📄 Upload and analyze resumes (PDF/DOCX)

🧠 AI-based feedback generation using NLP

🧩 Skill extraction and categorization

🗂️ Export analysis results as a Word document

🎨 Built with Streamlit for easy use and clean UI

🧰 Tech Stack

Python 3.12+

Streamlit – for the user interface

Hugging Face API – for text analysis

Python-docx / PyMuPDF – for document parsing

Pandas & Requests – for data handling and API integration

⚙️ Installation

Clone the repository:

git clone https://github.com/glr35/ai-resume-analyzer.git
cd ai-resume-analyzer


Create and activate the virtual environment:

python -m venv .venv
.venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run app.py

🔑 Environment Variables

Create a .env file in the project root and add:

HF_API_KEY=hf_xxxxxxxxxxxxxxxxxxxxxxxxxxx
STUDENT_NAME=Güler Göçmen
ROLE_TARGET=AI & Python Developer
UNIVERSITY=Manisa Celal Bayar Üniversitesi
PROGRAM=Computer Engineering
INTERNSHIP_START=2026

🧩 Output Example

AI analyzes your CV and generates feedback.

You can download an improved .docx report automatically.

💡 Author

👩‍💻 Güler Göçmen
🎓 Manisa Celal Bayar University – Computer Engineering
🌍 Erasmus Student – Kosovo
💼 AI & Python Developer | Open to long-term internship opportunities

📫 LinkedIn Profile

💻 GitHub Profile

🌟 Show your support

If you like this project, please ⭐ it on GitHub!

🔮 Next Steps

Integrate with OpenAI GPT for advanced resume scoring

Add dashboard for recruiters

Build a portfolio version on Streamlit Cloud
