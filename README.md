# AI_Hiring_Intelligence
AI Hiring Intelligence System is an end-to-end resume evaluation platform that combines rule-based scoring, NLP-driven skill extraction, and LLM-generated recruiter summaries. Built with FastAPI and Streamlit, the system analyzes candidate skills, experience, and job fit while incorporating evaluation metrics and fairness simulations.

## 🚀 Features

✔ Resume skill extraction  
✔ Experience parsing  
✔ Weighted skill scoring  
✔ Experience scoring  
✔ Final composite score  
✔ Candidate categorization  
✔ Recruiter-style LLM summary  
✔ Bias & fairness evaluation simulation  

## 🧠 Tech Stack

- Python
- FastAPI
- Streamlit
- spaCy
- OpenAI API
- Scikit-learn
- Docker

## 🏗 Architecture

Streamlit UI → FastAPI API → Scoring Engine → Feedback Generator → LLM Summary

## 🐳 Run with Docker

```bash
docker build -t ai-hiring .
docker run -p 8000:8000 ai-hiring
