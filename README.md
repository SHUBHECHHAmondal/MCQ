# Question-MCQS-Generator-Using-Machine-learning-NLP

## INTRODUCTION

My project aims to generate multiple-choice questions (MCQs) using machine learning and natural language processing (NLP) techniques. MCQs are widely used in educational assessments to evaluate students' understanding of a given topic. By automating the generation of MCQs, educators can save time and effort while ensuring the quality and relevance of the questions.

## FEATURES

1. Upload PDF or text files for processing.  
2. Automatically generate MCQs from text using spaCy for natural language processing.  
3. Customize the number of MCQs generated.  
4. User-friendly interface built with Flask and Bootstrap.  
5. Generates answer choices with distractors.  

## TECHNOLOGIES USED

Flask: Web framework used to handle routing, file uploads, and rendering templates.
spaCy: NLP library used for text processing, sentence extraction, and noun detection.
PyPDF2: Library used to extract text from PDF files.

## HOW IT WORKS

### Input: 
The user can upload one or more text or PDF files or manually input text.
### Processing:
The uploaded text is processed with spaCy to extract sentences.
Nouns from the sentences are identified as potential answers.
For each question, the most common noun is replaced with a blank and answer choices are generated, including distractors.
### Output:
The app generates a specified number of MCQs and displays them with the correct answer and options shuffled.

## SETUP

To run the project locally, follow these steps:

### Prerequisites
Python 3.x
pip package manager

### INSTALLATION

Clone the repository:
git clone https://github.com/your-username/mcq-generator.git
cd mcq-generator


Install the required dependencies:
pip install Flask
pip install Flask-Bootstrap
pip install spacy
pip install PyPDF2

Download spaCy's English language model:
python -m spacy download en_core_web_sm

Run the Flask application:
python app.py

Open the app in your web browser

## Usage

1.On the homepage, upload your text or PDF files or manually input text.
2.Choose the number of questions you want to generate.
3.Click "Generate MCQs" to create the questions.
4.View the generated MCQs with the correct answers.

## EXAMPLE

<img width="881" alt="mcq1" src="https://github.com/user-attachments/assets/f4c37aee-aafe-4e42-b10b-d0b3226973a1">

<img width="920" alt="mcq2" src="https://github.com/user-attachments/assets/681bf878-77eb-44c1-9690-e709186f7141">







