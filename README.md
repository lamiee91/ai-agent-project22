# ai-agent-project22# AI Agent Framework for Instagram Scraping and Content Filtering

This repository contains an agent-based system designed to scrape Instagram posts using Apify, filter them with LLMs (e.g., OpenAI or Vertex AI), and forward relevant insights to Google Cloud Storage and BigQuery. The architecture is modular, cloud-native, and optimized for rapid experimentation.

---

## 🔍 Use Case

Designed for:
- Filtering fashion-related content (e.g., for Mohito)
- Extracting trends, tone, topics from Instagram posts
- Automating data preparation for GenAI-driven analysis

---

## ⚙️ Tech Stack

- **Python 3.11+**
- **LangChain + LangGraph**
- **LLMs**: OpenAI GPT-4o / Gemini / Claude
- **Apify SDK** (via API)
- **Google Cloud Platform**: 
  - Cloud Storage
  - BigQuery
  - Cloud Run / Functions

---

## 📦 Project Structure

