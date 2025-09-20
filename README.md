# Team-ROBOLOX.io
online hackathon organised by INNOMATICS RESEARCH LABS 'Code4EdTech'.  

 Automated Resume Relevance Check System
An AI-powered web application designed to automate the process of screening resumes against job descriptions. This tool calculates a relevance score, provides a suitability verdict, and offers personalized, AI-generated feedback to help candidates improve.

This project was built based on a problem statement from Innomatics Research Labs.

✨ Features

Hybrid Scoring System: Combines keyword-based "hard matching" with advanced "semantic matching" using sentence embeddings to understand the context and meaning of the text.



AI-Powered Feedback: Leverages Google's Generative AI (Gemini) to provide personalized, constructive feedback for applicants on how to improve their resumes for a specific role.



Persistent Storage: Automatically saves every analysis report to a local SQLite database for future reference and auditing.




Interactive Dashboard: A built-in dashboard to view, search, and filter all historical analysis results, providing a comprehensive overview for placement teams.



Multi-Format Support: Capable of parsing and analyzing both PDF and DOCX file formats for resumes and job descriptions.

Customizable UI: Features a clean, user-friendly interface with a custom theme that can be easily modified.

📸 Screenshots
Here's a glimpse of the application in action.

Analyzer Page
Upload a Job Description and a Resume to get a detailed analysis report.
Dashboard Page
Review all past analyses in a clean, interactive table.
## 🛠️ Tech Stack

Frontend: Streamlit

Backend & Core Logic: Python

NLP & Analysis: spaCy, Sentence-Transformers (Hugging Face)

Generative AI: Google Generative AI (Gemini)

Database: SQLite, Pandas

File Parsing: PyMuPDF, python-docx

🚀 Getting Started
Follow these instructions to set up and run the project on your local machine.

Prerequisites
Python 3.8+

Access to Google AI Studio to generate an API key.

Steps: 
Clone the repository : git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer 
