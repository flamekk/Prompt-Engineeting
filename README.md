# 📊 Prompt Engineering for Multi-Agent Systems

## 📌 Overview

This project demonstrates how to interact with multiple Large Language Models (LLMs) using Python and apply **Prompt Engineering techniques**.

We explore:

* OpenAI API
* Ollama (local models)
* Groq API

And implement:

* Simple prompting
* Zero-shot prompting
* Few-shot prompting
* Chain-of-Thought (CoT)
* Text-to-Image & Image-to-Image generation
* Real-world use cases with evaluation

---

## 🎯 Objectives

* Understand how to interact with different LLM providers
* Apply prompt engineering techniques
* Build and evaluate NLP pipelines using LLMs
* Compare performance of prompting strategies

---

## 🧠 Technologies Used

* Python 🐍
* LangChain
* OpenAI API
* Ollama (local LLMs)
* Groq API
* HuggingFace Datasets
* Scikit-learn
* Pandas / NumPy
* Matplotlib

---

## ⚙️ Installation

```bash
pip install openai langchain langchain-openai langchain-ollama langchain-groq \
python-dotenv pandas scikit-learn datasets matplotlib pillow
```

---

## 🔐 Environment Setup

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
```

⚠️ **Important:** Never share your API keys publicly.

---

## 🚀 Project Structure

```
📁 project/
│── tp1.ipynb          # Main notebook
│── README.md          # Project documentation
│── .env               # API keys (not shared)
│── images/            # Generated images (optional)
```

---

## 🧪 Prompt Engineering Techniques

### 1. Simple Prompt

Basic interaction with LLMs.

### 2. Zero-Shot Prompt

Model performs task without examples.

### 3. Few-Shot Prompt

Model learns from provided examples.

### 4. Chain-of-Thought (CoT)

Guides reasoning step-by-step before answering.

---

## 🤖 LLM Providers Used

### ✅ OpenAI

* GPT models
* Text + Image generation

### ✅ Ollama

* Local models (e.g., Llama3)
* Runs offline

### ✅ Groq

* Fast inference
* Open-source models

---

## 🖼️ Multi-Modal Capabilities

### Text-to-Image

Generate images from prompts.

### Image-to-Image

Modify existing images using AI.

---

## 📊 Use Case 1: Sentiment Analysis (IMDB)

### Steps:

1. Load dataset (IMDB)
2. Preprocess data
3. Create:

   * Examples (few-shot)
   * Gold examples (evaluation set)
4. Apply:

   * Zero-shot
   * Few-shot
   * CoT prompting
5. Evaluate performance

### 📈 Metrics:

* Accuracy
* Micro-F1 Score

---

## 📊 Use Case 2: SMS Spam Classification

### Objective:

Classify SMS messages as:

* `spam`
* `ham`

### Steps:

* Load dataset
* Apply prompting strategies
* Compare results

---

## 📉 Evaluation

We evaluate prompts using:

* Micro-F1 Score
* Multiple runs for robustness


---

## 💡 Key Learnings

* Few-shot improves accuracy significantly
* CoT helps reasoning tasks
* Prompt design impacts performance heavily
* LLM behavior varies across providers

---

## ⚠️ Notes

* API costs may apply (OpenAI / Groq)
* Ollama requires local installation
* Ensure keys are secured

---

## 📚 References

* OpenAI Documentation
* LangChain Docs
* HuggingFace Datasets
* Course material (Prompt Engineering TP)

---

## 👩‍💻 Author

* Hiba Zbari Big Data & AI Engineering Student

---

## 📄 License

This project is for educational purposes.
