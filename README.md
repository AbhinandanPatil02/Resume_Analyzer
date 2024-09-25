# Resume Analyzer with Google Gemini AI

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://resumeanalyzer-xentcrwz2wbwnfztpcemft.streamlit.app/)

## Overview

This is a Resume Analyzer app powered by **Google Gemini AI**. The app allows users to upload their resumes and paste job descriptions to get detailed feedback on their resume's suitability for a specific job role. It offers various functionalities like:

- **Resume Review**: A detailed evaluation of how well the resume matches the job description.
- **Skill Improvement Suggestions**: Provides recommendations for enhancing both technical and soft skills to better align with job requirements.
- **ATS Compatibility Check**: Simulates how well an Applicant Tracking System (ATS) would score the resume, including missing keywords and a match percentage.

The app has been deployed on Streamlit and can be accessed [here](https://resumeanalyzer-xentcrwz2wbwnfztpcemft.streamlit.app/).

## Features

- **AI-Powered Analysis**: Uses Google Gemini AI to analyze the resume and provide tailored feedback based on the job description.
- **PDF Resume Processing**: Converts PDF resumes into images for further analysis.
- **Interactive Interface**: Provides a smooth and user-friendly interface with custom CSS and glowing mouse effects for an engaging experience.
- **Three Modes of Analysis**:
  - *Resume Feedback* from an experienced HR perspective.
  - *Skill Improvement Suggestions* for better job alignment.
  - *ATS Compatibility* percentage match with a breakdown of missing keywords.

## How It Works

1. **Paste the Job Description**: Copy the job description into the provided text box.
2. **Upload Your Resume (PDF)**: Upload your resume in PDF format.
3. **Select the Analysis**:
   - "Tell Me About the Resume": Get detailed feedback from an HR perspective.
   - "How Can I Improve My Skills": Suggestions on improving your skillset.
   - "Percentage Match": ATS compatibility check and keyword analysis.
4. **Get Results**: View the results instantly on the same page.

## App Interface

- **Job Description**: A text area where users can input job descriptions.
- **Resume Upload**: Upload PDF resumes for processing.
- **Analysis Buttons**: Choose from three types of analysis.
- **Results Display**: AI-generated feedback is displayed below the input sections.

## Technologies Used

- **Streamlit**: Frontend framework for building interactive web apps.
- **Python**: Core backend logic and integrations.
- **Google Gemini AI**: For generating content and analyzing the resume.
- **PDF to Image**: Converts PDF resumes into image format for processing using `PyMuPDF` instead of `pdf2image` to avoid Poppler dependency.

## Installation and Setup

### Clone the repository:

```bash
git clone https://github.com/AbhinandanPatil02/Resume_Analyzer.git
cd resume-analyzer
