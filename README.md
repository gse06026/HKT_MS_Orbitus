# HKT_MS_Orbitus

<div align="center">

[![License](https://img.shields.io/github/license/gse06026/HKT_MS_Orbitus.svg)](./LICENSE)
[![Azure](https://img.shields.io/badge/Azure-AI%20Foundry-blue.svg)](https://ai.azure.com/)
[![Hackathon](https://img.shields.io/badge/AI%20Skill%20Fest-2025-green.svg)]()
[![Python](https://img.shields.io/badge/python-%3E%3D3.10-blue.svg)](https://www.python.org/)

**AI Agent built with Azure AI Studio to assist high school teachers**

[Setup](#setup--installation) • [Quick Start](#quick-start) • [Features](#key-features) • [Architecture](#architecture) • [Contributing](#contributing)

</div>

---

## 🧭 Overview

**HKT_MS_Orbitus** is an AI agent designed for high school teachers to simplify administrative and academic workflows.
Built for the **Microsoft AI Skill Fest Hackathon**, the project integrates **Azure AI Foundry** and **Azure OpenAI** services to deliver contextual, domain-specific assistance.

---

## 🎬 Demo Video

Click the thumbnail below to watch a video demonstration of the Orbitus AI agent in action.

[![Demo Video](https://img.youtube.com/vi/XH4HpWa7h_g/0.jpg)](https://youtu.be/XH4HpWa7h_g?feature=shared)

---

## ✨ Key Features

- **Knowledge-Based Q&A (RAG)**
  - Understands school-specific questions using uploaded knowledge documents
  - Supports topics such as:
    - Academic calendar & events
    - Rules & policies (staff/student regulations)
    - Curriculum and assessment guides
    - Equipment & facility procedures
    - Internal system usage (LMS, admin tools)

- **Data Analysis & Calculation (Code Interpreter)**
  - Executes math and data operations on uploaded files (CSV/XLSX/TXT)
  - Generates statistical summaries and visualizations
  - Runs Python code securely in a sandboxed environment

- **Contextual Understanding**
  - Adapts to educational tone and terminology
  - Maintains professionalism and privacy awareness

- **Safety & Compliance**
  - Avoids sensitive or student-identifiable data
  - Rejects inappropriate or out-of-scope queries

---

## ⚙️ Architecture

| Component | Description |
|------------|-------------|
| **Azure AI Foundry** | Core development environment for the agent |
| **Azure OpenAI (gpt-4o-mini)** | Primary language model for reasoning and generation |
| **Azure AI Search** | Backend RAG knowledge retrieval system |
| **Code Interpreter** | Executes user-requested Python analysis |
| **TXT Knowledge Files** | Structured school documents forming the knowledge base |

---
