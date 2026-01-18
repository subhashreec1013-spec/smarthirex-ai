# SmartHire AI

Intelligent Resume Screening & HR Automation using NLP

Hackathon Project – SRM Noob Hackfest 2026

## Overview
SmartHire AI is a web-based platform that uses Artificial Intelligence and Natural Language Processing (NLP) to automatically analyze resumes and match them with job descriptions. It helps recruiters shortlist candidates faster, more accurately, and in a bias-free manner.

## Problem Statement
Recruiters receive hundreds of resumes for a single job role, making manual screening slow, inconsistent, and prone to bias. Traditional Applicant Tracking Systems rely mainly on keyword matching and often reject qualified candidates due to formatting or wording differences.

## Our Solution
SmartHire AI extracts skills, education, and experience from resumes, performs semantic matching with job requirements, generates explainable match scores, highlights skill gaps, and ranks candidates based on relevance using AI.

## Key Features
- Resume upload and parsing (PDF)
- NLP-based skill extraction
- Semantic job matching
- Explainable AI scoring
- Skill gap analysis with learning suggestions
- Candidate ranking dashboard
- Bias-free screening mode
- Recruiter-customizable scoring weights

## Technology Stack
- Frontend: HTML, CSS, JavaScript  
- Backend: Python (Flask)  
- AI / NLP: Gemini API or OpenAI API  
- Resume Parsing: PyPDF2 / pdfplumber  
- Database: SQLite / Firebase (optional)

## Impact
- Reduces resume screening time by up to 80%  
- Improves fairness and transparency in hiring  
- Enhances candidate–job matching accuracy  
- Useful for startups, HR teams, and campus placements  

## Team

Team Name: <Hack Nova>

Members:
- Subha Shree C
- Shiyam Shankar
- Sundhares
- Abdul Wahid S
- Mohammed Saad M

## Status
Project under development for SRM Noob Hackfest 2026.

## Demo Prototype (Current)

This repository contains a basic Flask API prototype for resume screening.

### How to run locally:

1. Install dependencies:
   pip install -r requirements.txt

2. Run the server:
   python app.py

3. Test API:

Endpoint: POST /analyze

Sample JSON body:
{
  "resume": "Python SQL Flask",
  "job_description": "Python SQL MachineLearning"
}

Note: This is a placeholder logic. AI/NLP integration will be implemented during the hackathon.
