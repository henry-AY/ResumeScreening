# ResumeScreening
This project explores the process and development of an Applicant Tracking
System (ATS) for screening and ranking resumes based on their semantic similarity to a job
description and ideal resumes. In this project, we use SBERT for embeddings, cosine similarity
for filtering, and train a Support Vector Machine (SVM) to predict binary classify candidates
based on their resumes. This document shows the results, and how we determined many of
the values/processes for our finished project.

## Installaion & Usage

To install and run this project locally, please follow the written instructions below. Moreover,
this installation guide assumes that you are working in a Python environment.

### 1. Fork the Repository
* Visit the GitHub repository: https://github.com/henry-AY/ResumeScreening
* Fork” the repository to create your own copy.

### 2. Clone the Repository
```
git clone https://github.com/<your-username>/ResumeScreening.git
cd ResumeScreening
jupyter notebook
```

### 3. Open the notebook in a conda environment

This will allow you to run the entire notebook (Note: this might take some time due to many
of the computations and graphs)
