# 🤝 Icebreaker Bot — LinkedIn Profile RAG Q&A System

![Language](https://img.shields.io/badge/Language-Python%203.11-3776AB?style=flat-square&logo=python&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-LlamaIndex%20Vector%20DB-FF6B35?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-IBM%20Watsonx-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Source](https://img.shields.io/badge/Source-LinkedIn%20ProxyCurl%20API-0077B5?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Profile%20Intelligence-2E7D32?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

## 📌 Project Overview
RAG-powered LinkedIn profile analyzer that extracts data via ProxyCurl API, stores it in a LlamaIndex vector database, generates ice-breaker facts, and answers Q&A about any person. Modular architecture with data extraction, processing, vector DB, and query engine modules.

**Domain:** RAG — LinkedIn Profile Intelligence  
**LLM:** IBM Watsonx  
**Vector DB:** LlamaIndex  
**Data Source:** LinkedIn (ProxyCurl API + mock mode)

## 🛠️ Tech Stack
| Component | Technology |
|---|---|
| Vector DB | LlamaIndex |
| LLM | IBM Watsonx |
| Profile Data | ProxyCurl API (LinkedIn) |
| Text Splitting | LlamaIndex node parser |
| UI | CLI / Gradio (app.py) |

## 📂 Modules
- `data_extraction.py` — LinkedIn profile via ProxyCurl API
- `data_processing.py` — Split profile + create vector DB
- `query_engine.py` — Generate facts + Q&A
- `llm_interface.py` — IBM Watsonx integration
- Mock mode for testing without API keys

## 🎓 Skills Demonstrated
LlamaIndex RAG · LinkedIn data extraction · IBM Watsonx · Modular Python architecture · Profile intelligence Q&A

## 📛 Suggested Name & Description
**Name:** `icebreaker-bot`  
**Description:** `LinkedIn profile RAG Q&A bot — ProxyCurl extraction + LlamaIndex vector DB + IBM Watsonx generates ice-breaker facts & answers profile questions`  
**Topics:** `rag` `llamaindex` `ibm-watsonx` `linkedin` `python` `vector-database` `profile-intelligence` `nlp`

## 🤝 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Leela%20A-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leela-a)
[![Gmail](https://img.shields.io/badge/Gmail-attotaleelaissak@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:attotaleelaissak@gmail.com)
