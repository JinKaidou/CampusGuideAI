# CampusGuide AI

An AI‑powered university helpdesk chatbot that provides students with instant, accurate, and university‑verified answers to FAQs, campus navigation, event schedules, and administrative processes.

---

## Table of Contents
1. [Overview](#overview)  
2. [Installation](#installation)  
3. [Usage](#usage)  
4. [Technologies Used](#technologies-used)  
5. [Contributing](#contributing)  
6. [License](#license)  

---

## Overview
CampusGuide AI leverages Retrieval‑Augmented Generation (RAG) to pull information from official handbooks, policy documents, and campus maps, then uses an AI chatbot interface to deliver contextually relevant responses to student queries—24/7.

---

## Installation
1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-org/CampusGuideAI.git
   cd CampusGuideAI

## Create & Activate a Virtual Environment
    ```bash
    python -m venv .venv

## Install Dependencies / Packages
    ```bash
    uv sync


Technologies Used
LangChain — Framework for building LLM-driven applications

Ollama — Local inference platform for large language models

Chroma — Vector database for storing and retrieving embeddings

PyPDF2 — Library for reading and manipulating PDF documents

Streamlit — Framework for creating interactive data apps

UV — Fast Python package installer and resolver