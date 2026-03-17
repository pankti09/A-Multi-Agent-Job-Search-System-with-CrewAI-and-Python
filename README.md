# AI Powered Multi Agent Job Application System

## Overview

The job market is competitive and many employers expect AI skills. This project shows how AI can help automate the job search process using a multi agent system.

The system is built using Python, CrewAI, and Streamlit. It can analyze job descriptions, generate resumes and cover letters, and create LinkedIn outreach messages.

The goal is to save time and demonstrate practical AI skills through a real world project.

---

## Features

* Multi agent system using CrewAI
* Job description analysis
* Resume and cover letter generation
* LinkedIn message creation
* Job listings from USAJobs API
* Streamlit based user interface
* Logging and output storage

---

## Tech Stack

* Python
* CrewAI
* Streamlit
* USAJobs API
* OpenAI or similar LLM provider

---

## Project Structure

```
app.py                  Streamlit application

agents/
  job_analyzer.py
  resume_agent.py
  messaging_agent.py

crew/
  crew_setup.py

utils/
  api.py
  logger.py
  storage.py

outputs/                Generated files
logs/                   Logs

requirements.txt
README.md
```

---

## Getting Started

### Clone the repository

```
git clone https://github.com/your-username/ai-job-agent.git
cd ai-job-agent
```

### Install dependencies

```
pip install -r requirements.txt
```

### Set up environment variables

Create a .env file and add:

```
OPENAI_API_KEY=your_key
USAJOBS_API_KEY=your_key
USAJOBS_USER_EMAIL=your_email
```

### Run the application

```
streamlit run app.py
```

---

## How It Works

Step 1
Fetch job listings from the USAJobs API based on user input.

Step 2
The job analyzer agent extracts skills and requirements from the job description.

Step 3
The resume agent generates a tailored resume and cover letter.

Step 4
The messaging agent creates a LinkedIn outreach message.

Step 5
All agents are orchestrated together using CrewAI.

Step 6
The Streamlit interface allows users to select jobs and generate outputs.

Step 7
Outputs and logs are saved locally.

---

## Project Tasks

Phase 1
Set up the project and API keys

Phase 2
Fetch job listings using the API

Phase 3
Build agents for analysis, resume generation, and messaging

Phase 4
Combine agents into a Crew

Phase 5
Build a Streamlit interface

Phase 6
Add logging and output saving

---

## Use Cases

* Automating job applications
* Learning agent based AI systems
* Building a portfolio project
* Demonstrating LLM skills

---

## Future Improvements

* Add more job sources
* Improve personalization
* Add feedback system
* Deploy to cloud

---

## Author

Pankti Shah
AI Engineer

---

If you want, I can also make a one page architecture diagram or convert this into a strong GitHub portfolio project description.
