# AI-Based Paper Evaluation System

An AI-based paper evaluation system developed to automate the evaluation of student answer papers. The system uses Artificial Intelligence, Optical Character Recognition (OCR), Natural Language Processing (NLP), and Machine Learning techniques to analyze answers, compare them with model answers, and generate evaluation scores.

## Features

- User Registration and Login
- MCQ/Objective Paper Evaluation
- Subjective Answer Evaluation
- OCR-based paper processing
- NLP-based answer analysis
- Comparison with model answers
- Automated score generation
- Web-based evaluation interface
- Reduced manual evaluation effort
- Faster and more consistent evaluation

## Technologies Used

- Python
- Django
- Artificial Intelligence
- Machine Learning
- Natural Language Processing (NLP)
- Optical Character Recognition (OCR)
- SQLite
- HTML/CSS

## How It Works

1. User registers or logs into the system.
2. User selects MCQ or Subjective Paper Evaluation.
3. The answer paper is uploaded.
4. For subjective evaluation, the model/correct answer is provided.
5. The system analyzes the submitted answers.
6. Student answers are compared with the model answers.
7. Marks are assigned automatically.
8. The evaluation result is displayed to the user.

## Project Structure

```text
AI-Paper-Evaluation/
│
├── __pycache__/
├── Evaluate/
├── EvaluateApp/
├── mcq_images/
├── subjective_images/
├── database.txt
├── db.sqlite3
├── manage.py
├── MCQ.py
├── requirements.txt
├── runWebServer.bat
├── SCREENS.docx
└── subjective_Samples.txt
