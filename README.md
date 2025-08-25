# 🧠 AI-Powered Deep Research & Reporting Automation (n8n Workflow)

This repository provides a **production-ready n8n workflow** that automates deep research, professional report generation, and seamless collaboration using **AI + integrations**.

---

## ✨ Key Features

- 🔎 **AI Topic Breakdown** → Expands one query into 5 subtopics
- 📚 **Automated Research** → Queries Tavily API for reliable data
- 📝 **AI Report Writing** → Creates styled HTML reports with clickable references
- 📊 **Google Sheets Sync** → Automatically stores results for collaboration
- ⚡ **Scalable Workflow** → Processes multiple topics in parallel

---

## 🛠️ Tech Stack

- [n8n](https://n8n.io/) – Workflow automation engine
- [LangChain](https://www.langchain.com/) – AI agent integration
- [Tavily API](https://tavily.com/) – Deep web research
- [Google Sheets](https://workspace.google.com/products/sheets/) – Data storage & team collaboration

---

## ⚙️ Workflow Overview

The workflow is designed in **4 main stages**, each represented with its own n8n diagram:

### 1. **Form Submission & Topic Planning**

User submits a topic → AI generates 5 structured subtopics.

<p align="center">
  <img src="/n8n-form-planning.png" alt="n8n Form and Topic Planning Flow" width="850"/>
</p>

---

### 2. **Automated Research Collection**

Each subtopic is processed → Tavily API fetches data + sources.

<p align="center">
  <img src="/n8n-research.png" alt="n8n Research Collection Flow" width="850"/>
</p>

---

### 3. **Report Generation**

AI agents synthesize findings → Format into HTML reports with inline citations.

<p align="center">
  <img src="/n8n-report-writing.png" alt="n8n Report Generation Flow" width="850"/>
</p>

---

### 4. **Storage & Delivery**

Reports and sources are synced to Google Sheets → Delivered to end user.

<p align="center">
  <img src="/n8n-storage-delivery.png" alt="n8n Storage and Delivery Flow" width="850"/>
</p>

---

## 🚀 Getting Started

1. Import the `.json` workflow into n8n
2. Set up credentials for Tavily + Google Sheets
3. Trigger the workflow → Get a professional report in minutes

---

## 📊 Example Use Cases

- Market & Competitor Research
- Business Intelligence Reports
- Blog & Content Drafting
- Academic/Policy Research

---

## 🤝 For Clients

This workflow can be **customized** for your exact needs (industry-specific research, different CRMs, dashboards, PDFs, etc.).  
👉 Contact via GitHub Issues or email for tailored deployment.

---

## 📜 License

Licensed under the **MIT License**.
