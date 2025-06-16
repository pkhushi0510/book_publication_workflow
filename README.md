# 📚 Automated Book Publication Workflow

An intelligent agentic system that automates the fetching, rewriting, reviewing, and versioning of book content using modern AI tools including Google's Gemini LLM, RL-based retrieval, and ChromaDB.

---

## 🚀 Features

- ✅ **Web Scraping**: Fetches book chapters and takes screenshots using Playwright.
- ✍️ **AI Writer**: Uses Gemini (Google Generative AI) to rewrite the content.
- 🔍 **AI Reviewer**: Refines and corrects content using Gemini.
- 🧠 **Human-in-the-Loop**: Allows human editors to review and modify content at each stage.
- 🔁 **Agentic Pipeline**: Seamlessly passes content between AI agents and human reviewers.
- 📦 **Version Management**: Stores final versions in ChromaDB with RL-based retrieval.
- 🔎 **RL Search**: Basic reinforcement learning-based text search to retrieve relevant versions.

---

## 🧰 Tech Stack

- **Python** (core language)
- **Playwright** – Web scraping and screenshots
- **Gemini (Google Generative AI)** – AI writer and reviewer
- **ChromaDB** – Vector database for versioning
- **RL Algorithm** – For intelligent retrieval
- **dotenv** – For managing API keys securely

---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/book_publication_workflow.git
cd book_publication_workflow
pip install -r requirements.txt
