# HealthBot – AI-Powered Patient Education System

An interactive LLM workflow that retrieves trusted medical information, summarizes it in patient-friendly language, and generates comprehension quizzes using LangGraph and LangChain.


## Table of Contents
- [Overview](#overview)
- [Repository-Structure](#repository-structure)
- [Running-This-Project](#running-this-project)


## Overview
HealthBot helps users learn about medical conditions using verified health sources.  
The notebook implements an end-to-end LangGraph workflow that:

- Prompts the user for a medical topic  
- Retrieves information from NIH, Mayo Clinic, CDC, WHO, and MedlinePlus  
- Generates a simplified 8th-grade-level summary  
- Creates an automated multiple-choice quiz  
- Grades answers with citation-based feedback  
- Resets state securely if the user chooses to learn another topic  


## Repository Structure
```bash
├── Code.ipynb          
├── config.env  
├── requirements.txt      
├── .gitignore              
└── README.md
```


## Running This Project
1. Clone the repository
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Create your environment in config.env
```bash
OPENAI_API_KEY=your_openai_key_here
TAVILY_API_KEY=your_tavily_key_here
```