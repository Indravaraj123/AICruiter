AI Ignite: From Basics to Breakthrough

Overview

AI Ignite is an AI-powered resume screening tool designed to help candidates assess their job suitability before applying. By leveraging AI and automation, it streamlines the initial hiring process, providing feedback and interview scheduling.

Problem Statement

Modern hiring processes rely on AI-based resume screening, often leaving candidates uncertain about their job eligibility. Key issues include:

Lack of Feedback: Candidates apply without knowing their suitability.

Emotional Impact of Rejections: Repeated failures lower confidence.

Limited Access to Screening Tools: No accessible pre-screening resources for candidates.

Solution: AIcruiter

AIcruiter automates the resume screening process using AI to provide candidates with feedback and interview scheduling. It:

Analyzes resumes and job descriptions to determine suitability.

Provides automated feedback via email.

Schedules interviews using Google Calendar if suitable.

Features

Automated Suitability Check: AI compares resumes with job descriptions to determine eligibility.

Personalized Feedback: Candidates receive tailored responses based on AI analysis.

Google Integration: Uses Gmail for communication and Google Calendar for interview scheduling.

Workflow

Upload Resume & Job Description: Users submit documents for assessment.

Text Extraction: AI converts PDFs into readable text.

AI Analysis: Determines match suitability.

Communication:

Sends rejection email if unsuitable.

Schedules interview via Google Calendar if suitable.

Key Functions

Google Authentication: Grants access to Gmail and Calendar.

Resume & Job Description Processing: Extracts text from PDFs.

AI Suitability Assessment: Evaluates job fit using AI models.

Automated Email Updates: Notifies candidates of results.

Interview Scheduling: Sets up Google Calendar events with meeting links.

Packages Required

Python 3.x

PyPDF2

Google API Client

Flask

OpenAI API (for AI-based assessment)

Other Requirements

A Chromium-based browser (e.g., Chrome)

Google Account for API access

Setup Process

Clone the project

git clone https://github.com/Indravaraj123/AICruiter.git

Navigate to the project folder and install dependencies

cd AI-Ignite
pip install -r requirements.txt

Set up Google authentication

Enable Gmail and Calendar APIs in Google Cloud Console.

Generate OAuth credentials and save them as credentials.json.

Run the application

python app.py

Access the web interface

Open the browser and go to http://127.0.0.1:5000

Upload your resume and job description.

View results and schedule interviews.

Contribution

Contributions are welcome! Follow these steps:

Fork the repository.

Create a feature branch:

git checkout -b feature-branch

Commit changes:

git commit -m "Added new AI feature"

Push changes and create a pull request.
