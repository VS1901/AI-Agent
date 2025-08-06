# 🧠 Multi-Agent AI System with Collaboration and Validation

---

## 📍 Problem Statement

In many real-world applications, complex tasks like summarizing medical documents, validating sensitive content, or collaborating across tasks require **multiple AI agents working together**. This project demonstrates a **Multi-Agent AI System** where each agent specializes in a task such as:

- Medical text summarization  
- Fact validation  
- Translation  
- Text classification  

It is built on **LangChain**, **Ollama**, and **Streamlit**, allowing smooth collaboration between agents using LLMs such as LLaMA 3.

---

## 👨‍🔬 Use Case: Summarize Medical Text

You can enter any medical paragraph, and the AI will summarize the key points using a local LLM model through Ollama. The goal is to assist healthcare professionals, researchers, and analysts by reducing information overload.

---

## 🔧 Architecture

- **Frontend**: Streamlit-based interactive UI  
- **Backend**: Python with LangChain + Ollama  
- **Model**: LLaMA 3 (3.2:3b) – locally served  
- **Agents**: Each tool/agent executes a specific role  
- **Data Flow**: Streamlit Input ➜ LangChain Agent ➜ Local LLM ➜ Output

---

## 📸 Screenshot

![App Screenshot](https://github.com/VS1901/AI-Agent/blob/main/logo.png)

---

## 🛠️ Features

- 🌐 Local LLM using Ollama (no internet dependency)  
- 🩺 Specialized agent for medical summarization  
- 🔄 Retry mechanism if Ollama is unresponsive  
- 🧠 Extensible design – Add more agents for QA, translation, etc.  
- 🖥️ Clean, responsive UI with task selector  

---

## 📜 Steps Followed

1. ✅ Installed and configured **Ollama** and downloaded `llama3:3.2b` model  
2. ✅ Created custom tools using LangChain (Summarizer, Translator, etc.)  
3. ✅ Designed Streamlit UI with dynamic task selection  
4. ✅ Connected frontend to LangChain agent executor  
5. ✅ Implemented multi-agent collaboration pipeline  
6. ✅ Error-handling: retry logic if LLM fails to respond  
7. ✅ Packaged all components into a modular app  

---

## 🧪 Sample Output

**Input**:

> Access to appropriate medications is shown to have substantial impacts on community health and the related economic indicators...

**Summarized Output**:

> Timely access to safe and effective medicines is vital for public health. Global trade challenges regulation, increasing the risk of substandard products. WHO's strategy aims to improve accessibility and reduce falsified medicines.

---

## ⚙️ Tech Stack

- 🐍 Python 3.10+  
- 🧠 LangChain  
- 💬 Ollama (LLaMA 3.2:3b)  
- 🖼️ Streamlit  
- 📦 OpenAI-compatible API (local)

---

