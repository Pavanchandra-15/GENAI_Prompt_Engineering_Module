# AI Resume Screening System

## Overview

This project implements an AI-powered Resume Screening system leveraging Large Language Models (LLMs) and modern NLP pipelines to automate candidate evaluation. The system processes resumes and compares them against job descriptions using semantic understanding, prompt engineering, and LLM-based reasoning.

The core objective is to simulate an intelligent recruitment assistant capable of extracting relevant information, evaluating candidate suitability, and generating structured insights.

---

## Core Concepts Implemented

### 1. Prompt Engineering

* Designed structured prompts to guide LLM responses
* Controlled output format and evaluation criteria
* Improved response consistency and relevance

### 2. LangChain Integration

* Built modular pipelines using LangChain
* Used prompt templates and chaining mechanisms
* Enabled scalable and reusable LLM workflows

### 3. LLM Inference (Groq)

* Integrated Groq API for high-speed inference
* Used chat-based models for contextual reasoning
* Enabled dynamic evaluation of resumes

### 4. Semantic Processing

* Tokenization and text preprocessing
* Context-aware understanding of resumes and job descriptions
* Leveraged transformer-based models for embeddings (if applicable)

### 5. Pipeline Architecture

* Input: Resume + Job Description
* Processing: Prompt construction → LLM invocation
* Output: Structured evaluation (match score, strengths, gaps)

---

## System Workflow

1. **Input Collection**

   * Resume text and job description are provided

2. **Preprocessing**

   * Text normalization and formatting

3. **Prompt Construction**

   * Dynamic prompt created using templates

4. **LLM Invocation**

   * Query sent to Groq-powered model via LangChain

5. **Response Generation**

   * Model returns evaluation and insights

6. **Output Interpretation**

   * Results displayed in structured format

---

## Tech Stack

* **Language:** Python 3.10
* **LLM Framework:** LangChain
* **Model Provider:** Groq API
* **NLP Models:** HuggingFace Transformers
* **Libraries:**

  * pandas
  * numpy
  * scikit-learn
  * sentence-transformers

---

## Project Structure

```
Task-3/
│── Task 3.ipynb        # Main implementation notebook
│── requirements.txt    # Dependency management
│── .env                # Environment variables (ignored)
│── .gitignore          # Git exclusions
```

---

## Environment & Configuration

Sensitive credentials are managed using environment variables:

* GROQ_API_KEY → Used for LLM access
* LANGCHAIN_API_KEY → Used for tracing (optional)

Loaded using `python-dotenv` to ensure secure and modular configuration.

---

## Key Challenges Addressed

* Managing dependency compatibility across LangChain ecosystem
* Handling environment configuration securely
* Designing effective prompts for consistent LLM outputs
* Working within limited computational resources (CPU-based execution)
* Debugging version conflicts in transformers and LangChain

---

## Outcomes

* Successfully built an end-to-end LLM pipeline
* Achieved structured resume evaluation using prompt-based reasoning
* Demonstrated practical application of Generative AI in recruitment
* Ensured reproducibility using controlled environments and fixed dependencies

---

## Future Enhancements

* Add embedding-based similarity scoring
* Integrate vector databases (FAISS / Chroma)
* Build a web interface for real-time usage
* Fine-tune models for domain-specific hiring

---

## Conclusion

This project showcases the practical implementation of Generative AI and LLMs in automating resume screening. It highlights the importance of prompt engineering, system design, and environment management in building reliable AI-powered applications.
