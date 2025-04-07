# Assignment-on-generative-ai
This is an assignment on Generative ai interviews 

# GenAI Virtual Interviewer

## Overview

The **GenAI Virtual Interviewer** is a Streamlit application designed to simulate a virtual interview experience. It allows candidates to respond to a series of predefined interview questions, receive real-time feedback on their responses, and upload their resumes for context. The app utilizes natural language processing techniques to evaluate candidate responses based on length, sentiment, and keyword relevance.

## Features

- **Multiple Interview Questions**: Candidates are presented with a series of common interview questions.
- **Resume Upload**: Candidates can upload their resumes in PDF format, and the app extracts and displays the text.
- **Real-Time Feedback**: The app evaluates responses based on length, sentiment analysis, and keyword relevance, providing constructive feedback.
- **Timer**: Each question has a countdown timer to simulate a real interview environment.
- **Response Summary**: At the end of the interview, candidates receive a summary of their responses.

## Technologies Used

- **Streamlit**: For building the web application.
- **pdfplumber**: For extracting text from PDF resumes.
- **Camelot**: For potential future enhancements related to table extraction from PDFs.
- **TextBlob**: For sentiment analysis of candidate responses.

