# 🔬 Multi-Agent Research System

A multi-agent AI research system built with **Mistral AI, LangChain, LangGraph, Tavily, BeautifulSoup, and Streamlit**.

The system takes a research topic, searches the web for relevant information, extracts useful content from sources, generates a structured research report, and reviews the report using a critic chain.

## 🚀 Features

* 🔍 **Search Agent** — searches the web using Tavily.
* 📄 **Reader Agent** — extracts information from web pages using BeautifulSoup.
* ✍️ **Writer Chain** — generates a structured research report.
* 🧐 **Critic Chain** — reviews the generated report and provides feedback.
* 🖥️ **Streamlit Interface** — provides an interactive research experience.
* 📥 **Report Download** — allows the final report to be downloaded.

## 🏗️ Architecture

```text
User
  │
  ▼
Research Topic
  │
  ▼
Search Agent ───► Tavily
  │
  ▼
Reader Agent ───► BeautifulSoup
  │
  ▼
Writer Chain ───► Mistral AI
  │
  ▼
Critic Chain ───► Mistral AI
  │
  ▼
Final Research Report
```

## 🛠️ Tech Stack

* Python
* Mistral AI
* LangChain
* LangGraph
* Tavily
* BeautifulSoup
* Requests
* Streamlit

## 📂 Project Structure

```text
Multi-Agent-Research-System/
│
├── agent.py
├── app.py
├── pipline.py
├── tools.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## 🔄 Workflow

### 1. Search Agent

Receives the research topic and searches for recent and relevant information using Tavily.

### 2. Reader Agent

Uses the search results and extracts additional information from selected web pages using BeautifulSoup.

### 3. Writer Chain

Combines the collected information and generates a structured research report.

### 4. Critic Chain

Reviews the generated report and provides a score, strengths, and areas for improvement.

## 💡 Example Research Topics

* Impact of war on stock markets
* Impact of AI on jobs
* Latest developments in quantum computing
* Climate change and agriculture
* Fusion energy progress

## 🎯 Goal

The goal of this project is to demonstrate how **multiple AI agents, external tools, web research, and LangChain chains** can work together to build an automated research system.
