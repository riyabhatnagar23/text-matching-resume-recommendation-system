# Text Matching Resume Recommendation System

## Overview

The Text Matching Resume Recommendation System is a tool designed to streamline the process of matching job descriptions with resumes. This system utilizes text matching algorithms to assess the similarity between a given job description and a pool of resumes, ultimately recommending the most relevant resumes.

## Features

- **Graphical User Interface (GUI):** A user-friendly interface allows users to input job descriptions, select resumes, and receive recommendations effortlessly.

- **PDF Text Extraction:** The system supports the extraction of text from PDF files, ensuring compatibility with various resume formats.

- **Cosine Similarity Calculation:** Cosine similarity is used to measure the similarity between the content of job descriptions and resumes.

- **CountVectorizer Integration:** The system employs CountVectorizer from scikit-learn for text vectorization, converting text documents into term frequency matrices.

## How to Use

1. **Input Job Description:**
   - Enter the job description into the provided text entry field.

2. **Select Resumes:**
   - Click on the "Select Resume" button to choose multiple resumes using the file dialog.

3. **Find Best Match:**
   - Click on the "Find Best Match" button to initiate the matching process.

4. **View Recommendations:**
   - The system displays the recommended resume and its similarity score.

## Dependencies

- Python 3.x
- Required Python Libraries (install using `pip install library_name`):
  - PyPDF2
  - scikit-learn
  - tkinter (for GUI)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-matching-resume-recommendation.git
