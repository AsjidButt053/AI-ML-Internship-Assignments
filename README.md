# AI & Machine Learning Internship Assignments

## 👨‍💻 About

This repository contains all assignments and practical work completed during my **6-week AI & Machine Learning Internship**. Throughout the internship, I worked with Python programming, data analysis, machine learning, deep learning, and an end-to-end AI project involving Retrieval-Augmented Generation (RAG) and multiple Large Language Models.

---

# Internship Details

- **Intern:** Muhammad Asjid Butt
- **University:** COMSATS University Islamabad, Sahiwal Campus
- **Degree:** BS Software Engineering
- **Internship Organization:** Zynvex Solutions
- **Internship Domain:** Artificial Intelligence & Machine Learning
- **Duration:** 6 Weeks

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- LangChain
- FAISS
- HuggingFace
- FastAPI
- React
- Vite
- PyMuPDF
- Tesseract OCR
- Google Gemini
- OpenAI
- Ollama
- Docker
- Docker Compose
- Google Colab
- Jupyter Notebook
- GitHub

---

# Weekly Progress

## Week 1 – Data Analysis & EDA

### Topics Covered

- Python Basics
- NumPy
- Pandas
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Outlier Detection

### What I Learned

- Data preprocessing techniques
- Handling missing values and duplicates
- Exploratory Data Analysis (EDA)
- Data transformation and feature engineering
- Data visualization using Matplotlib and Seaborn

### What I Applied

- Cleaned datasets
- Handled missing and duplicate values
- Created new features
- Detected outliers using IQR
- Performed group-by analysis
- Created histograms, box plots, and correlation heatmaps

➡️ Folder: **Week-01**

---

## Week 2 – Machine Learning

### Topics Covered

- Machine Learning Workflow
- Train-Test Split
- Feature Scaling
- StandardScaler
- Regression
- Model Evaluation

### What I Learned

- Data splitting strategies
- Feature scaling using StandardScaler
- Preparing datasets for machine learning
- Training and evaluating machine learning models

### What I Applied

- Performed train-test splitting
- Applied feature scaling
- Trained machine learning models
- Compared model performance
- Evaluated predictions
- Practiced preprocessing workflows

➡️ Folder: **Week-02**

---

## Week 3 – Deep Learning

### Topics Covered

- Artificial Neural Networks
- TensorFlow
- Keras
- Model Training
- Model Evaluation
- Model Optimization

### What I Learned

- ANN architecture
- Deep learning workflow
- Training neural networks
- Model evaluation
- Model optimization and saving

### What I Applied

- Built an ANN
- Trained a neural network
- Evaluated model performance
- Worked with customer churn prediction
- Saved the trained model

➡️ Folder: **Week-03**

---

## Week 4 – AI PDF Chatbot Development

### Objective

Started development of an end-to-end **AI PDF Chatbot** using React, FastAPI, Retrieval-Augmented Generation (RAG), FAISS, and Large Language Models.

### Topics Covered

- Retrieval-Augmented Generation (RAG)
- PDF Processing
- Text Extraction
- OCR
- Text Chunking
- Embeddings
- FAISS Vector Search
- FastAPI REST APIs
- React Frontend
- Docker
- Docker Compose

### What I Learned

- RAG architecture
- Converting documents into searchable vector representations
- Semantic similarity search
- Connecting React frontend with FastAPI backend
- Building REST APIs for AI applications
- Containerizing multi-service applications with Docker

### What I Applied

- Developed PDF upload functionality
- Implemented PDF text extraction
- Added OCR support for scanned PDFs
- Implemented text chunking
- Generated document embeddings
- Created FAISS vector indexes
- Built the initial RAG question-answering pipeline
- Developed the React frontend and FastAPI backend
- Created Docker containers for the application

➡️ Folder: **Week-04**

---

## Week 5 – AI PDF Chatbot Enhancement & Multi-LLM Integration

### Objective

Improved the AI PDF Chatbot's user interface and implemented support for multiple Large Language Model providers.

### Topics Covered

- React UI/UX
- Responsive Design
- Multi-LLM Architecture
- Gemini Integration
- OpenAI Integration
- Ollama Integration
- Docker-based LLM Deployment
- Local LLM Inference
- Error Handling

### What I Learned

- Designing a flexible multi-provider LLM architecture
- Integrating cloud-based and locally hosted models
- Connecting Ollama with a Dockerized FastAPI backend
- Managing model and provider configuration
- Debugging API and Docker dependency issues

### What I Applied

- Finalized the React UI/UX
- Improved sidebar and model settings
- Added Lucide React icons
- Integrated Google Gemini
- Integrated OpenAI GPT
- Integrated Ollama
- Configured Qwen 2.5 0.5B for local inference
- Resolved Docker and Python dependency issues
- Tested frontend, backend, and Ollama containers together

### LLM Providers

- **Google Gemini**
- **OpenAI GPT**
- **Ollama – Qwen 2.5 0.5B**

➡️ Folder: **Week-05**

---

## Week 6 – Testing, UML & Project Documentation

### Objective

Finalize, test, document, and prepare the AI PDF Chatbot for project submission.

### Topics Covered

- Project Testing
- Multi-LLM Testing
- Docker Testing
- UML Modeling
- System Architecture
- Technical Documentation
- Project Reporting
- GitHub Project Management

### What I Learned

- Testing complete AI application workflows
- Identifying and resolving integration issues
- Designing UML diagrams for software systems
- Preparing professional technical documentation
- Documenting system architecture, results, challenges, and future improvements

### What I Applied

- Tested PDF upload and processing
- Tested RAG-based question answering
- Tested Gemini, OpenAI, and Ollama
- Verified source and page references
- Tested chat history and session handling
- Tested Docker containers
- Prepared Use Case Diagram
- Prepared Class Diagram
- Prepared Sequence Diagram
- Prepared Activity Diagram
- Prepared Component Diagram
- Prepared Deployment Diagram
- Prepared complete project report
- Added UI screenshots and project results
- Updated project documentation and GitHub repository

### Final Project Result

Successfully completed and tested the **AI PDF Chatbot**, a RAG-based document question-answering system with support for three LLM providers:

- Google Gemini
- OpenAI GPT
- Ollama with Qwen 2.5 0.5B

➡️ Folder: **Week-06**

---

# Final Project – AI PDF Chatbot

The internship project developed during the final weeks is an **AI-powered PDF Chatbot** based on Retrieval-Augmented Generation.

## Main Features

- PDF upload
- Multiple PDF processing
- PDF text extraction
- OCR for scanned PDFs
- Configurable text chunking
- HuggingFace embeddings
- FAISS vector search
- RAG-based question answering
- Source and page references
- Chat history
- PDF search
- PDF page preview
- Quick actions
- Light and dark themes
- Responsive React UI
- Multiple LLM provider support
- Dockerized application

## Supported LLMs

- Google Gemini
- OpenAI GPT
- Ollama
- Qwen 2.5 0.5B

## Architecture

```text
React / Vite Frontend
          ↓
FastAPI Backend
          ↓
PDF Processing
          ↓
Text Chunking
          ↓
Embeddings
          ↓
FAISS Vector Store
          ↓
RAG Retrieval
          ↓
Selected LLM
    ┌─────┼─────┐
 Gemini OpenAI Ollama
