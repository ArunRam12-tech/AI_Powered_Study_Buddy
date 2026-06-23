# 🎓 AI Powered Study Buddy

## Overview

AI Powered Study Buddy is an AI-driven learning assistant designed to help students improve their study efficiency, understanding, and productivity. Built using Streamlit and powered by the Groq API with the Llama 3.1 model, the application provides intelligent study support through topic explanations, note summarization, quiz generation, flashcards, writing assistance, study planning, and document-based question answering.

The platform combines Generative AI and interactive learning tools to create a personalized and engaging study experience.

---

## Features

### 📝 Study Tools

#### Explain Complex Topics

* Simplifies difficult concepts into easy-to-understand explanations.
* Suitable for quick learning and revision.

#### Note Summarization

* Converts lengthy notes into concise summaries.
* Highlights key concepts and important points.

#### Quiz Generator

* Generates multiple-choice quizzes from study notes.
* Supports adjustable difficulty levels.

#### Flashcard Generator

* Creates AI-generated flashcards from educational content.
* Interactive review mode for self-assessment.

---

### ✍️ Writing Assistant

#### Essay & Paragraph Helper

* Generates structured essay outlines.
* Drafts paragraphs on selected topics.
* Suggests writing improvements and refinements.

---

### 🗓️ Planner & Visualizer

#### Study Schedule Planner

* Creates personalized study schedules.
* Considers subjects, exam dates, and available study hours.

#### Concept Visualizer

* Generates mind-map style outlines.
* Helps visualize relationships between concepts.

---

### 💬 Chat with Documents

#### PDF Question Answering

* Upload PDF documents.
* Ask questions directly from document content.

#### Quiz from Documents

* Automatically generates quizzes from uploaded PDFs.

---

### 📜 Activity History

* Stores previous activities locally.
* Review past summaries, quizzes, flashcards, and explanations.
* Delete unwanted records when needed.

---

## Technologies Used

### Programming Language

* Python 3.11+

### Framework

* Streamlit

### AI & Generative AI

* Groq API
* Llama 3.1 (llama-3.1-8b-instant)

### Libraries

* PyPDF2
* JSON
* Datetime
* OS

---

## System Architecture

```text
User Input
     │
     ▼
 Streamlit Interface
     │
     ▼
 Groq API (Llama 3.1)
     │
     ▼
 AI Processing
     │
 ┌───┼───────────────┐
 │   │               │
 ▼   ▼               ▼
Summaries   Quizzes   Flashcards
 │
 ▼
 Results Display
```

---

## Project Features at a Glance

✅ Topic Explanation

✅ Note Summarization

✅ Quiz Generation

✅ Flashcard Creation

✅ Writing Assistance

✅ Study Planning

✅ Concept Visualization

✅ PDF Question Answering

✅ Activity History Tracking

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Powered-Study-Buddy.git
cd AI-Powered-Study-Buddy
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure API Key

Create:

```text
.streamlit/secrets.toml
```

Add:

```toml
GROQ_API_KEY="your_api_key_here"
```

### Run Application

```bash
python -m streamlit run app.py
```

---

## Learning Outcomes

This project helped develop practical skills in:

* Generative AI
* Prompt Engineering
* Large Language Models (LLMs)
* Streamlit Development
* API Integration
* Natural Language Processing
* Educational Technology Solutions
* User Interface Design

---

## Future Enhancements

* User Authentication
* Cloud Deployment
* Voice-Based Learning Assistant
* Personalized Learning Analytics
* Multi-Language Support
* Progress Tracking Dashboard

---

## Author

**Arun H**

B.E. Computer Science Engineering
ACS College of Engineering

### Skills Demonstrated

* Python
* Generative AI
* Prompt Engineering
* LLM Integration
* Streamlit
* Groq API
* NLP
* PDF Processing
* AI Application Development

---

⭐ If you found this project useful, consider giving it a star.
