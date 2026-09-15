# CODTECH IT SOLUTIONS — Task 3: AI Chatbot with NLP 🤖

An AI-powered chatbot developed as part of my **CODTECH IT SOLUTIONS Internship**.

The project uses **Transformer-based Natural Language Processing (NLP)** to understand the semantic meaning of user queries and provide relevant responses through an interactive web-based interface.

---

## 📌 Project Overview

The objective of this project is to develop an intelligent chatbot capable of understanding different variations of user queries rather than relying only on simple keyword matching.

The chatbot uses **Sentence-BERT (SBERT)** with the **all-MiniLM-L6-v2** model to generate semantic embeddings. It then applies **Cosine Similarity** to compare the user's query with predefined knowledge-base responses and selects the most relevant response.

The application also provides real-time date and time information and handles common conversational interactions such as greetings, gratitude, technical questions, and exit requests.

---

## 🎯 Objectives

- Build an AI chatbot capable of understanding natural language queries.
- Use a pretrained Transformer model for semantic understanding.
- Apply Cosine Similarity for query-response matching.
- Provide real-time date and time information.
- Create an interactive and user-friendly chatbot interface.
- Handle common conversational intents gracefully.

---

## ✨ Key Features

### 🧠 Transformer-Based NLP

Uses **Sentence-BERT (SBERT)** with the `all-MiniLM-L6-v2` pretrained model to convert text into meaningful numerical embeddings.

### 🔍 Semantic Query Matching

Uses **Cosine Similarity** to compare the user's query with predefined knowledge-base queries and identify the most relevant response.

### 💬 Natural Language Interaction

The chatbot can handle different variations of user queries instead of depending only on exact keywords.

### 🕒 Real-Time Awareness

Uses Python's `datetime` module to provide the current system date and time.

### 👋 Conversational Handling

Supports common conversational interactions including:

- Greetings
- Thank-you messages
- Technical questions
- General information
- Goodbye / exit requests

### 🌐 Interactive Web Interface

Uses **Gradio** to provide a clean and responsive chatbot interface that can be accessed through a web browser.

---

## 🛠️ Technology Stack

### Programming Language

- **Python 3.x**

### AI / NLP

- **Sentence-Transformers**
- **Sentence-BERT (SBERT)**
- **all-MiniLM-L6-v2**
- **Cosine Similarity**

### Deep Learning

- **PyTorch**

### User Interface

- **Gradio**

### Standard Library

- **datetime**

---

## 🧠 How the Chatbot Works

The chatbot follows this workflow:

```text
User Query
    ↓
Text Input
    ↓
Sentence-BERT Model
    ↓
Generate Semantic Embedding
    ↓
Compare with Knowledge Base
    ↓
Cosine Similarity
    ↓
Find Most Relevant Query
    ↓
Generate Response
    ↓
Display Response in Gradio
