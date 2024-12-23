E-Recruitment
📚 Table of Contents

Description
Features
Technologies Used
Installation
Demo
✨ Description
E-Recruitment is an innovative platform that leverages Natural Language Processing (NLP) to automate the recruitment process. It enables recruiters to create job postings and candidates to submit their resumes. The application calculates the similarity between resumes and job offers, optimizing the selection process and improving the overall efficiency of recruitment.

🔥 Features
For Recruiters
Create Job Postings:
Add details such as job description, salary, and required skills.
For Candidates
Submit Resume:
Candidates can upload their resume to apply directly to job offers.
NLP Analysis
Similarity Calculation:
Method: Uses the BERT model to encode the text of resumes and job offers.
Tool: Cosine similarity calculation with sklearn.
Tests for Candidates:
Method: Generates technical questions based on resumes and job descriptions using the Llama model.
Tool: Groq API to generate questions and evaluate answers.
⚙️ Technologies Used
Frontend: React for the user interface.
Backend: Flask for handling APIs and server-side services.
Database: MongoDB for data storage.
NLP:
Text Encoding: BERT model to process resumes and job descriptions.
Question Generation: Groq API with the Llama model.
Answer Evaluation: Cosine similarity calculation with sklearn.
📦 Installation
Step 1: Clone the repository
bash
Copier le code
git clone https://github.com/your-username/LP-Recruitment.git
cd LP-Recruitment
Step 2: Install dependencies
bash
Copier le code
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
pip install -r requirements.txt
Step 3: Run the application
bash
Copier le code
# Start the backend server
cd backend
flask run

# Start the frontend server
cd frontend
npm start
