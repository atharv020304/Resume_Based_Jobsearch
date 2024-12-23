# Resume-Based Job Search Platform

## Overview
The Resume-Based Job Search Platform is a web application built with Python and the Django framework. Unlike traditional job search platforms that rely primarily on job titles, this platform extracts detailed skills and qualifications directly from user resumes. These extracted details are then used to scrape real-time job listings from Indeed.com and match the job descriptions against the user's skills using advanced Natural Language Processing (NLP) techniques. The platform delivers tailored job recommendations, offering a more personalized and efficient job search experience.

## Key Features
- **Resume Parsing**: Extracts skills, qualifications, and relevant details from uploaded resumes.
- **Real-Time Job Scraping**: Scrapes job listings dynamically from Indeed.com based on user-specific criteria.
- **Advanced Matching**: Uses a ML model to analyze and compare job descriptions with extracted skills.
- **Formatted Results**: Presents job recommendations in a user-friendly and structured format.

## Tech Stack
- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MYSQL 
- **Web Scraping**: BeautifulSoup, Requests
- **NLP**: BERT model

## How It Works
1. **User Registration and Resume Upload**: Users sign up and upload their resumes in PDF or DOCX format.
2. **Resume Parsing**: The uploaded resume is parsed to extract key skills and qualifications using NLP techniques.
3. **Job Scraping**: The platform scrapes job listings from Indeed.com based on the extracted skills and location preferences.
4. **Skill Matching**: Each job description is analyzed and matched with the extracted resume skills using a fine-tuned BERT model.
5. **Recommendations**: The system displays a list of jobs ranked by relevance, with key details such as job title, company, location, and a link to apply.

## Installation

### Prerequisites
- Python 3.8+
- Django 3.2+
- MYSQL 
  
## Usage
1. Upload your resume.
2. View your personalized job recommendations.

## Future Enhancements
- Integration with LinkedIn and other job platforms.
- Support for multiple languages in resume parsing and job matching.
- Enhanced filtering options for users.
- Mobile app version for seamless access.

- <img width="960" alt="image" src="https://github.com/user-attachments/assets/7329d6bd-8985-4e0e-b002-2d2c563ce1a2" />

